---
title: "Curso Boostrap desde cero"
summary: Bootstrap es un framework de CSS que nos facilita y estandariza el desarrollo de sitios web.
weight: 1
date: 2020-02-05
tags: ["Deep Learning"]
categories: ["curso", "boostrap","css"]
description: "El mejor curso de boostrap desde cero"
draft: false
--- 
# 
![](https://www.diariodeunprogramador.net/wp-content/uploads/2018/08/bootstrap.jpg)


Bootstrap es un framework de CSS que nos facilita y estandariza el desarrollo de sitios web.
Esta pensando para que se adapte tanto a las pantallas de equipos de escritorio como a móviles y tablets.

Bootstrap es desarrollado y mantenido por la empresa Twitter y la ha liberado como un producto Open Source.

Tiene una filosofía muy intuitiva para el maquetado de sitios web que puede ser rápidamente aprendida por desarrolladores que no vienen del mundo del diseño web.

La versión estable actual es la 4.x

El corazón de este framework es un archivo CSS que lo podemos descargar del sitio http://getbootstrap.com.

Luego debemos enlazar a nuestra página con el archivo boottrap.min.css y ya podemos utilizar esta librería.
La primera clase que podemos probar es class="container" (esta muestra todo el contenido del div centrado), además el framework ya define estilos por defecto para una gran cantidad de elementos HTML de la página, por ejemplo define la tipografía de tipo Helvética.

El código mínimo de nuestra página es:
 
```html
<!DOCTYPE html> 
<html> 
<head> 
  <title>Prueba de Bootstrap</title> 
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <link href="css/bootstrap.min.css" rel="stylesheet"> 
</head> 
<body> 
  <div class="container" style="background-color:#ccc">
    <h1>Titulo</h1> 
    <p>Esto es una prueba de bootstrap 4.</p>
  </div> 
</body> 
</html> 
```
En el concepto anterior vimos que para trabajar con el framework Bootstrap 4 debemos descargarlo del sitio http://getbootstrap.com.

Hay una segunda forma de trabajar con Bootstrap sin tener que descargar el framework y consiste en utilizar un servidor donde se alojan todos los archivos de Bootstrap.

Si vamos a utilizar un CDN (Content Delivery Network - red de entrega de contenidos) luego nuestro esqueleto de página html tendrá una estructura similar a esta:
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <title>Hola Mundo</title>
  </head>
  <body>
     <div class="container" style="background-color:#ccc"> 
       <h1>Hola Mundo!</h1>
     </div>
     
    <!-- Si utilizamos componentes de Bootstrap que requieran Javascript agregar estos tres archivos -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  </body>
</html>
```
En lugar de cargar el archivo "bootstrap.min.css" de nuestro servidor, lo hacemos del servidor "https://maxcdn.bootstrapcdn.com":

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
    integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
Las ventajas de utilizar esta forma de cargar el framework Bootstrap 4 es:

Reduce la carga de nuestros servidores (importante si utilizamos un hosting compartido con recursos limitado)
Facilita que Bootstap 4 quede en caché del navegador y se vuelva a cargar cada vez que se visita una web que lo utilice.
Reduce la latencia.
Reducción de costos de nuestros servidores por requerir menor ancho de banda y tráfico.
Como desventaja podríamos decir:

Está la posibilidad que el servidor donde se aloja Bootstrap 4 se caiga, si bien es mucho más probable que nuestro servidor sobre todo si es un hosting compartido es el que tenga problemas.
No podemos probar en forma local nuestro sitio web si no se encuentra conectado a internet.
Más adelante veremos componentes de Bootstrap 4 que si las utilizamos debemos importar una serie de archivos Javascript. Estos archivos pueden estar en nuestro servidor o inclusive como hemos visto en este concepto estar almacenados en CDN.

Los tres archivos Javascript requeridos son:

jquery-3.2.1.slim.min.js

popper.min.js

bootstrap.min.js

Si quieres aprender desarrollo front-end con Bootstarp 4 practicando poco a poco con las tecnologías más potentes y solicitadas en el mercado y quieres subir de nivel en el desarrollo web y aumentar tus oportunidades laborales ¡Este es tu CURSO!
