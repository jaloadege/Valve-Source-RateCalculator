# Valve - Source Engine - Rate Calculator
Calculatora de consumo de un servidor hosteado en el motor Source de Valve.

## Calculadora de consumo extremo del servidor
Consumo de ancho de banda total (según max. jugadores) y consumo por cada jugador.

Consumo variable, teniendo en cuenta mínimo/máximo tickrate y mínimo/máximo packet_size (rate)



## Consumo del jugador (cliente)
Consumo variable según las opciones min/máx establecidas en el servidor.
Sliders para encontrar la configuración que mejor se adapte al jugador.
- Tick rate (límitado por min/max del servidor)
- Rate (límitado por min/max del servidor)

Muestra el consumo esperado con las opciones establecidas.
> Copiá los comandos generados a partir de las opciones.

## Calculadora variable (limit testing)
- Tick rate variable
- Rate (packet size) variable
- Jugadores variables.

Muestra el consumo esperado con las opciones establecidas.

> Copiá los comandos generados a partir de las opciones.

> La configuración variable siempre establece los máximos,
> 
> los valores mínimos siempre serán {valor máximo / 2}
