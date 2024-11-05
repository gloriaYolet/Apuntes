Lenguaje Makdown :
Objetivo:Proporcionar una herramienta para documentar codigo,
o aspectos tecnicos para compartirlos o tenerlos de referencia en Git U
Otra plataforma  


Makdown es un lenguaje de mercado ligero creado en el 2004
John Gruber, trata de conseguir la maxima legibilidad y .....

El objetivo de su creador fue hacer que la gente pudiera escribir usando
un formato de texto palno facil de leer, facil de escribir y con la 
posibilidad de convertir su documento en HTML valido

La gran simpleza de su sintaxis hizo que tuviera una rapida
adaptacion y popularidad en la comunidad de desarrolladores.

Actualmente aparte de permitir generar codigo HTML de forma
dinamica, tambien se emplea (casi deforma estandar) para la creacion
de documentacion tecnica y con la proliferacion de la arquictectura



Conocer sintaxis Mardown
1.-Parrafos [Parrafo 1...]
Lorem Ipsum es simplemente el texto de relleno de las imprentas y archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de las industrias desde el año 1500, cuando un impresor (N. del T. persona que se dedica a la imprenta) desconocido usó una galería de textos y los mezcló de tal manera que logró hacer un libro de textos especimen. No sólo sobrevivió 500 años, sino que tambien ingresó como texto de relleno en documentos electrónicos, quedando esencialmente igual al original. Fue popularizado en los 60s con la creación de las hojas "Letraset", las cuales contenian pasajes de Lorem Ipsum, y más recientemente con software de autoedición, como por ejemplo Aldus PageMaker, el cual incluye versiones de Lorem Ipsum.



_cursivo_
**negrita**
~tachado~
*_cursiva y negrita*
_~cursiva y tachado~_
**~negrita y tachado~**
**_~cursiva, negrita y tachado~_**

encabezados

#Encabezado Nivel 1
## Encabezado Nivel 2
### Encabezado Nivel 3
#### Encabezado Nivel 4
##### Encabezado Nivel 5
###### Encabezado Nivel 6

Divisiones
Un bloque de contenido
---
Este es otro bloque de contenido 


listas 
podemos utilizar las listas ordenadas y listas desordenadas

1. html5
1. css
1. javascript
1. Ajax
1. Json

listas desordenadas
- html5
- css
- javascript
- ajax
- json

Citas
Podemos dar formato de cita a un texto anteponiendo a la linea de texto un caracter de mayor que (>).
>la IA en el futuro remplazara muchas profesiones de TI. -
Gloria

>Chat Gpt debe poteciar el aprendizaje no suprimir mi estado autodidacta
>
>gloria

enlaces

[YouTube](https://www.youtube.com)
[Enlace a Google](https://www.google.com)

Imagenes

![Texto alternativo](URLdelaimagen)


tablas
|Columna 1|Columna 2|Columna 1|
|---------|---------|---------|  
|A        |---------|---------|
|D        |---------|---------|
|G        |---------|---------|


codigo 
podemos dar formato de codigo a un texto para ello se usa el acento grave(`).

este es `codigo` en linea.

En _javascript_ una varible se define asi:
`let saludo = "Hola Mundo`;



pero si queremos sacar un bloque completo de codigo utilizamos :

```   
js
let estudiante="juan perez";
let edad=19;
let isestudiante=true;
let calificacion=90.0;

<!--esto es un comentario-->