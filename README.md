# parcial.1_micros
comportamiento de mi programa:
Switch 1 → Alterna LED 1 (intermitencia)
Switch 2 → Alterna LED 2. (intermitencia)
Switch 3 → Activa la secuencia especial de LEDs. (#8. los LEDs se encienden en secuencia descendente, mayor a menor numero de pin)
La secuencia se ejecuta cada 150 ms (controlado con millis()).
se usa delay(200) para evitar rebotes en los switches.
updateLEDs() mantiene el estado de los LEDs actualizado.
