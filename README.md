# Regularizacion_4
Este es el proyecto necesario para la regularización del cuarto parcial de Análisis y Procesamiento de Imágenes

## **INSTRUCCIONES**

Programar un juego donde una pelota deba llegar a un área ganadora. El juego consiste en detectar una pelota por medio de la cámara de computadora. En una ventana de opencv dibujar el pasillo verde con la forma que se adjunta. Este pasillo consiste en un embudo que comienza en forma de triángulo y después pasa por un pasillo estrecho. Al acabar el pasillo estrecho llegar a un área rectangular, denominada zona ganadora. Las reglas del juego son:

1. Mover con la mano la pelota a través de la cámara. 
2. Se debe comenzar por la zona de inicio y trasladar pelota a lo largo de la pantalla hasta llegar a la zona ganadora. 
3. Si en el transcurso del movimiento, la pelota pega con con alguna de las paredes verdes, el jugador perderá.
4. El programa debe retroalimentar al jugador por medio de cuatro mensajes: Sin pelota, Jugando, Colisión, Ganaste.
- 4.1 "Sin pelota": mientras no se detecte la pelota o la pelota se encuentre fuera del pasillo o la zona ganadora.
- 4.2 "Jugando": cuando se detecte pelota y vaya por el pasillo.
- 4.3 "Colisión": cuando la pelota esté en juego y choque contra alguna pared.
- 4.4 "Ganaste": si la pelota se detecta dentro de la zona ganadora.
Los mensajes se pueden mostrar en la ventana  de juego por medio de opencv o en la terminal. El mensaje se debe estar refrescando cada cierto tiempo para que el jugar siempre conozca su estado.


Entregables:
- El programa de python utilizado.
- Un video sin cortes con tres pruebas. Cada prueba tendrá diferentes estados y se deben ir comentando los estados verbalmente en el video. Esto implica que la pelota se debe mover lentamente para que se alcance a comentar y a leer en pantalla el estado actual: 
1. Que no se detecte pelota (estado 1), luego que detecte jugando (estado 2), luego que colisione contra la pared superior (estado 3), y por último, que sin salir de pantalla, salga del pasillo para marcar "sin pelota" (estado 4). Después sacar la pelota de pantalla.
2. Que no se detecte pelota (estado 1), luego que detecte jugando (estado 2), luego que colisione contra la pared inferior (estado 3), y por último, que sin salir de pantalla, salga del pasillo para marcar "sin pelota" (estado 4). Después sacar la pelota de pantalla.
3. Que no se detecte pelota (estado 1), luego que detecte jugando (estado 2), por último que llegue a la zona ganadora y te avise que ganaste (estado 3).
