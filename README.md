# Drag---Words
An experimental drag and drop minigame for kids

## Que es esto, nen?

Pues na, que un finde me dió por probar una librera drag and drop muy chula llamada interact.js, y tuve una idea aparentemente fácil de poner en practica de una miniapp para que jugara mi hijo de 5 años. Como su maestra comentó algo de que las palabras en catalán le costaban, pues aproveché y le puse un poco de vocabulario catalán, bueno con algunos superhéroes de por medio, para que se motive (es algo vago).

Es tán simple como un scrabble drag and drop, donde le doy unas letras mezcladas al niño, y tiene que arrastrar las correctas que corresponden a la palabra del dibujo.

Así de simple. Empecé a hacerme ollas de cómo debía preparar cada juego, y al final opté por insertar manualmente cada palabra en un json, pero también es manual la elección de letras ofrecidas.

La ilustración la pillo de un directorio, y corresponde a la palabra usada.

No he vuelto a hacer nada más, pero para ser un experimento quedó chulo, y además le puse algunas opciones interesantes, como una navegación de palabras, y la opción de poder usar mayúsculas o minúsculas.

La verdad es que fueron saliéndome complicaciones, y algunas ideas interesantes de "features" que podría ir poniendo...

Pero claro, voy justo de tiempo, y ya veremos. De todos modos, si algún día quisiera publicar el juego, tanto de manera comercial como educativa, ya veis que las imágenes tienen copyright, así que o contrato el servicio de un ilustrador o me las hago yo... yo que sé, ya veramos.

Se podrían usar varias tipografías, o incluso "lletra lligada", como la Pacífico de google fonts, o algo así... o poner un minibackoffice, en donde los padres pudieran añadir nuevas palabras o imágenes a su gusto... Niveles por edades... Buah, no? Se te va la pinza, nen...

## Nota técnica - Touch devices

Aunque interact.js viene dotada de eventos touch y multitouch, no me acaba de furular bien en Android (En iOS lo probé y fetén, en el HayFon de mi cuñao...)

En mi tablet viejuna Samsung, puedes jugar, pero tienes que arrastrar las letras muy lentamente.

En el chrome de mi movil Moto G Play, en cuanto tocas una letra se va al quinto pino. Además, esto es curioso, tuve un conflicto con el evento "pull for refresh" este nativo de recargar la página... Pude deshabilitarlo añadiendo el tag:

<intelxdk:crosswalk xwalk-command-line="--disable-pull-to-refresh-effect" />

que flipa, yo no sabía ni que existía (lo encontré en una web mu rara que hablaban de apps híbridas y del apache cordova y cosas de esas).

Eso es lo mas guay de estos experimentillos, que aparecen movidas, y aprendes cosicas...
