Main
    int numJugador
    int intentos = 7
    bool adivinado = FALSO
    int numeroSecreto = Random(0, 101)

    while (intentos > 0 && !adivinado)
        lee numJugador

        if (numJugador == numeroSecreto)
            adivinado = VERDADERO
            mostrar "Has Ganado"
        sino
            if (numJugador > numeroSecreto)
                mostrar "Demasiado alto"
            sino
                mostrar "Demasiado bajo"
            finIf
            --intentos
        finIf
    finWhile

    if (!adivinado)
        mostrar "Has perdido. El número secreto era " + numeroSecreto
    finIf
FinMain
