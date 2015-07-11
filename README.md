Preludio
========

Piezas musicales aleatorias en LOGO.

Un pequeño proyecto infantil, que consistía en crear un programa que compusiera pequeñas piezas de música. El programa sigue las reglas de la armonía para concatenar acordes y escribe una melodía sobre ellos.
Escrito en LOGO en castellano, por ser el primer lenguaje de programación que aprendimos.

## Uso del programa
El programa está probado sobre *MSWLogo*, que puede instalarse en Windows y emularse bajo Wine en GNU/Linux. La salida midi puede dar problemas en algunos casos, y en GNU/Linux necesitará tener instalado `timidity`.

## Ejemplo
El archivo `preludio.wav` muestra un ejemplo de composición creada por el
programa. El archivo de audio final se obtuvo de sintentizar el archivo midi
con una librería de audio, añadiendo las dinámicas y la última nota manualmente.
