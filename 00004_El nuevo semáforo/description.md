Ya que en Gobstones tenemos un tablero y bolitas de colores, ¿por qué no creamos nuestro propio semáforo? :vertical_traffic_light:

La diferencia es que nuestro semáforo se va a ver así:

<gs-board>
  GBB/1.0
    size 1 3
    cell 0 0 Negro 1
    cell 0 1 Verde 1
    cell 0 2 Azul 1
    head 0 3
<gs-board>

> Definí el procedimiento `CrearSemaforo` e invocalo en el programa. Tené en cuenta que el cabezal comienza en el casillero del `Sur`.