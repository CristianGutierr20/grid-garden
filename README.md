# grid-garden

-¡Bienvenido a Grid Garden, donde escribirás tu código CSS para cultivar tu jardín de zanahorias! Riega solo las áreas que tienen zanahorias usando la propiedad grid-column-start.

-Por ejemplo, grid-column-start: 3; regará el área comenzando por la tercera línea vertical, que es otra manera de decir el 3er borde vertical contando desde la izquierda de la cuadrícula.

-Oh oh, parece que hay malas hierbas creciendo en la esquina de tu jardín. Usa grid-column-start para envenenarlas. Fíjate en que las malas hierbas comienzan en el quinto borde vertical de la cuadrícula.

-Cuando grid-column-start se usa solo, la expansión por defecto del elemento en la cuadrícula será de exactamente una columna. No obstante, puedes extender el elemento varias columnas añadiendo la propiedad grid-column-end.

-Usando grid-column-end, riega todas las zanahorias evitando que se forme barro. ¡No queremos malgastar agua! Fíjate en que las zanahorias comienzan en el 1er borde vertical y terminan en el 4º.
 
 -Al emparejar grid-column-start y grid-column-end, podrías asumir que el valor final tiene que ser mayor que el valor inicial. ¡Pero no es el caso!

-Intenta establecer grid-column-end a un valor inferior a 5 para regar tus zanahorias

-Si prefieres contar las líneas de la cuadrícula comenzando por la derecha, puedes dar a grid-column-start y grid-column-end valores negativos. Por ejemplo, puedes establecerlos a -1 para indicar la primera línea comenzando por la derecha.

-Intenta establecer grid-column-end a un valor negativo.

-Ahora intenta establecer grid-column-start a un valor negativo.
-En lugar de definir un elemento en la cuadrícula basado en la posicion inicial y final, puedes definirlo basado en la longitud de columnas deseada usando la palabra clave span. Ten presente que span solo funciona con valores positivos.
-Intenta usar grid-column-end con la palabra clave span de nuevo para regar tus zanahorias.
-También puedes usar la palabra clave span con grid-column-start para establecer la anchura del elemento en relación a la posición final
-Escribir ambos grid-column-start y grid-column-end cada vez puede resultar cansado. Afortunadamente, grid-column es una propiedad abreviada que acepta ambos valores a la vez, separados por una barra oblicua.

Por ejemplo, grid-column: 2 / 4; establecerá el comienzo del elemento de la cuadrícula en la 2ª línea vertical de esta, y su final en la 4ª línea vertical.
