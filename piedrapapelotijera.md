Main
    int rondas, ganapc, ganahumano
    string[] = piedra, papel, tijera
    string jugada, jugadaPC

    rondas = ganapc = ganahumano = 0

    for(rondas = 0; rondas < 3; rondas++)
        mostrar "Elige piedra, papel o tijera"
        leer jugada
        jugadaPC = string[Random(0,2)]
        mostrar "La pc elige" + jugadaPC

        if(jugada == jugadaPC)
            mostrar "Empate"
        else if((jugada == "piedra" && jugadaPC == "tijera") ||
                (jugada == "papel" && jugadaPC == "piedra") ||
                (jugada == "tijera" && jugadaPC == "papel"))
            mostrar "Ganaste"
            ganahumano++
        else
            mostrar "Perdiste"
            ganapc++
        finif
    finfor

    mostrar "Humano: " + ganahumano + " - Computadora: " + ganapc
    if(ganahumano > ganapc)
        mostrar "¡Ganaste el juego!"
    else if(ganapc > ganahumano)
        mostrar "Perdiste xd."
    else
        mostrar "Empate"
    finif
FinMain
Main
    int rondas, ganapc, ganahumano
    string[] = piedra, papel, tijera
    string jugada, jugadaPC

    rondas = ganapc = ganahumano = 0

    for(rondas = 0; rondas < 3; rondas++)
        mostrar "Elige piedra, papel o tijera"
        leer jugada
        jugadaPC = string[Random(0,2)]
        mostrar "La computadora eligió: " + jugadaPC

        if(jugada == jugadaPC)
            mostrar "Empate"
        else if((jugada == "piedra" && jugadaPC == "tijera") ||
                (jugada == "papel" && jugadaPC == "piedra") ||
                (jugada == "tijera" && jugadaPC == "papel"))
            mostrar "Ganaste"
            ganahumano++
        else
            mostrar "Perdiste"
            ganapc++
        finif
    finfor

    mostrar "Humano: " + ganahumano + " - Computadora: " + ganapc
    if(ganahumano > ganapc)
        mostrar "¡Ganaste el juego!"
    else if(ganapc > ganahumano)
        mostrar "Perdiste xd"
    else
        mostrar "Empate"
    finif
FinMain
