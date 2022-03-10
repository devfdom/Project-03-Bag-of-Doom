Mars Rover
==========

> La Kata Mars Rover es una de las más conocidas en el mundo del desarrollo, y normalmente se utiliza para 
practicar testing, TDD y diseño orientado a objetos. En esta versión simplificada de la kata practicaremos algunas de las cosas que hemos visto hasta ahora en Javascript.


!['Mars Rover'](https://upload.wikimedia.org/wikipedia/commons/d/d8/NASA_Mars_Rover.jpg)

## Objetivo

> _You’re part of the team that explores Mars by sending remotely controlled vehicles to the surface of the planet. Develop an API that translates the commands sent from earth to instructions that are understood by the rover._ (descripción de la kata Mars Rover original)

En este ejercicio vamos a controlar el movimiento de nuestro Mars Rover en la superficie del planeta rojo.

El Rover empieza en las coordenadas (100,100) de la superficie de Marte. Las coordenadas indican la posición en los ejes Norte-Sur y Este-Oeste, respectivamente.

Por ejemplo:

```
( 50,  20) --> 50 km norte, 20 km este
(-10,  10) --> 10 km sur, 10 km este
( 10, -10) --> 10 km norte, 10 km oeste
```

Le indicaremos los movimientos que debe realizar mediante los símbolos N (Norte), S (Sur), E (Este) y W (Oeste). Por ejemplo `['N', 'W', 'N']` hace que el Rover se mueva un kilómetro al Norte, luego un kilómetro al Oeste y otro kilómetro al Norte.

Nuestro objetivo es obtener la posición final del Rover después de recibir y ejecutar las instrucciones.

Para completar la kata, debes hacer pasar todos los tests (`tests.js`).

