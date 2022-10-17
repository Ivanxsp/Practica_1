# Posicionamiento

En esta práctica se pide la creación de una página
en la que demostraremos los conocimientos de HTML, CSS y JavaScript.

He seguido este orden en la creación de la página:

* Título (HTML, CSS).
* Menú lateral (HTML, CSS).
* Imágenes (HTML, CSS).
* Texto a la derecha (HTML, CSS).
* JavaScript.
* README.

## Título
He usado la etiqueta de HTML **p** en vez de usar un **h1** y la he
editado con CSS para obtener el resultado esperado.

## Menú
En este caso utilizo un contenedor para almacenar los botones con imagen
para darles tamaño y darles en un futuro la función de cambiar de imagen,
además de añadir un filtro de escala de grises que al
acercar el ratón desaparece.

## Imágenes
Las imágenes después de hacer pruebas con la etiqueta **img**
y comprobar que no funcionaba bien el posicionamiento, decidí crear un **div** por cada imagen
y añadir estas desde el propio CSS.

## Texto a la derecha
Al igual que el apartado anterior, también he generado para cada texto
un **div**.

==Tanto para las *imágenes* como para el *texto* he usado la etiqueta **z-index** en la
pareja que quería que apareciera primero asignando un valor de 100.==

## JavaScript
Después de todo esto llega la hora de darle los efectos a las imágenes.
En este caso tuve que investigar un poco y lo hice desde esta [página](https://www.w3schools.com/).
Usando la propiedad **zIndex** en JavaScript me permite traer al frente
la pareja de **div** que quiero.

## README
Por último he escrito este documento.