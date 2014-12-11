juego-spiran
============
Requiere de Unity 4.6+ (usa el nuevo GUI)

Basicamente solo son las piezas, el tablero y un botón. (No he hecho nada de scripting porque no se ni por donde empezar)

El tablero está hecho de tal manera que cada cuadrado está alineada con las coordenadas vector3 de Unity.
Osea que una ficha puede cambiar de posición en el tablero simplemente cambiando sus coordenadas a un vector3 en X,Y,Z 
(aunque Z siempre es 0 porque es 2d). Por ejemplo una ficha en vector3(0,0,0) va a estar en la esquina inferior derecha 
del tablero.
