---
title: Archivo independiente,Creación, apertura y modificación.
linktitle: Archivos
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  example:
    parent: Example Topic
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1 
---
Creacion de archivos en visual studio code.
Las actividades básicas de todo editor de texto es permitirnos crear nuevos archivos y modificar archivos existentes.

Creación de un archivo
Desde el menú de opciones de VSCode seleccionamos "Archivo -> Nuevo archivo" (o mediante las teclas de atajo Ctrl + N):

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto015.jpg)

Ahora en la ventana de edición procederemos a codificar un archivo HTML básico:
![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto016.jpg)

Todavía no aparecen las etiquetas HTML coloreadas ya que no hemos guardado el archivo en el disco duro donde indicaremos con la extensión el tipo de archivo.

Para grabar el archivo desde el menú de opciones elegimos "Archivo->guardar" (o mediante las teclas de atajo Ctrl + S):

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto017.jpg)

Si introducimos un cambio con el editor VSCode podemos comprobar que en la pestaña cambia la cruz por un círculo indicando que debemos grabar los cambios introducidos:

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto019.jpg)

Para actualizar los cambios en el archivo debemos seleccionar nuevamente la opción "Archivo guardar" o (Ctrl + S).

Podemos crear varios archivos y tenerlos abiertos en forma simultanea, cada uno en una pestaña diferente.

Creemos nuestro segundo archivo dando los pasos que ya vimos "Archivo -> Nuevo archivo" o (Ctrl + N), luego escribamos nuestra segunda página HTML y la grabemos con la opción "Archivo->guardar" o (Ctrl + S):

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto020.jpg)

Cambio entre pestañas
Mediante el mouse podemos seleccionar la pestaña del archivo que necesitemos editar.

También podemos cambiar entre pestañas mediante las teclas (Alt y la tecla de números):

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto021.jpg)

(Seleccionamos la segunda pestaña presionando Alt+2)

Podemos también cambiar entre pestañas mediante las teclas (Ctrl y alguna de las teclas Av Pag. y Rt Pag):

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto022.jpg)

(Se van seleccionando las pestañas de izquierda a derecha o viceversa)

Por último desde el menú de opciones de VSCode podemos cambiar entre pestaña seleccionando alguna de las dos opciones: Ir -> Cambiar editor -> Editor siguiente o la Editor anterior:

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto031.jpg)

Grabar todos los archivos modificados.
Para probar esta opción introduzcamos algunos cambios en las dos pestañas de los archivos 'pagina1.html' y pagina2.html'. Podemos ver en el primer ícono de la izquierda que hay dos archivos modificados sin grabar
La opción del menú que graba todos los archivos modificados es (Archivo->Guardar todo) o el atajo de las teclas (Ctrl + K, luego soltamos las teclas control + K y presionamos finalmente la tecla S):

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto024.jpg)


Cerrar pestañas.
Tenemos tres formas de cerrar una pestaña:

Mediante el mouse podemos presionar sobre la cruz de la pestaña (si no se ha grabado nos aparece un diálogo para confirmar que se guarden los cambios)

También podemos cerrar la pestaña activa presionando las teclas Ctrl + W:

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto025.jpg)

Cerrar la pestaña activa presionando las teclas Ctrl + F4:

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto026.jpg)

Abrir archivos.
Para abrir un archivo almacenado en el disco podemos hacerlo seleccionando desde el menú de opciones: Archivo->Abrir archivo:

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto030.jpg)
El atajo de teclas para que aparezca el diálogo de apertura de archivo es: Ctrl + O.

El atajo de teclas para que aparezca el diálogo de apertura de archivo es: Ctrl + O.

Crear otro archivo a partir de uno existente.
Es muy común tener que a partir de un archivo existente generar otro. Para esto debemos tener seleccionada la pestaña con el archivo y luego desde el menú de opciones seleccionar 'Archivo -> Guardar como...
Problemas a partir del archivo 'pagina2.html' generar un archivo llamado 'pagina3.html' con el mismo contenido:

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto028.jpg)

En el diálogo que aparece indicamos el nuevo nombre de archivo: 'pagina3.html'

Esta misma acción la podemos hacer mediante las teclas:

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto029.jpg)

Guardado automático.
Si queremos desentendernos de la grabación de los archivos podemos activar la opción de "Autoguardado". Para activar esta funcionalidad en Visual Studio Code debemos ir a la opción de menú: Archivo -> Autoguardado y dejarla tildada (si la seleccionamos nuevamente se desactiva la opción)

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto027.jpg)

A partir de ese momento cada cambio que hagamos a un archivo luego se ven reflejados en el disco donde se almacena (es decir no necesitamos ejecutar 'Archivo->Guardar')

**Abrir carpeta**
Vimos en el concepto anterior la metodología para editar archivos que nos presenta VSCode.

Cuando tenemos que trabajar con un conjunto de archivos que se encuentran en una carpeta lo más conveniente es utilizar la funcionalidad de "Abrir carpeta" para que se nos muestre la lista de archivos contenidos en la misma y no tener que abrir en forma individual cada archivo.

Hay varias formas de poder hacer esta actividad:

Presionar el botón de "Explorador" de la "barra de actividades" que se encuentra al lado izquierdo:

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto032.jpg)

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto033.jpg)

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto034.jpg)

Si salimos del editor VSCode, al regresar en otro momento queda almacenada la última carpeta abierta.

Cerrar carpeta
Cuando se abre una nueva carpeta se cierra la carpeta abierta actualmente, pero si queremos podemos cerrar la carpeta abierta actualmente mediante la opción del menú "Archivo -> Cerrar carpeta":

También podemos cerrarlas con las teclas de atajo (Ctrl + K, F):

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto039.jpg)