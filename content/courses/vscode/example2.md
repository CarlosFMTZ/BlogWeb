---
title: Configuracion de visual studio code 
linktitle: Configuracion vs code
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  example:
    parent: Example Topic
    weight: 2

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 2
---
Otra de las características fundamentales que tiene el editor de texto Visual Studio Code es la posibilidad de configurar sus funcionalidades como pueden ser fuentes, colores, tamaños de fuentes, tabulaciones, modos de presentar en pantalla el editor etc.

En este momento podemos configurar más de 540 características.

Para acceder a la ventana de configuración del VSCode lo podemos hacer de tres formas:

Desde el ícono de la rueda dentada que aparece en la parte inferior izquierda:

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto048.jpg)  

También podemos acceder a la pestaña de configuración desde el menú de barra seleccionando (Archivo -> Preferencias -> Configuración):

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto049.jpg)

Finalmente en cualquier momento podemos abrir la pestaña de configuración mediante las teclas (Ctrl + ,):

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto050.jpg)

Ventana de configuración
Del lado izquierdo nos muestran las distintas secciones que podemos configurar, y del lado derecho los valores que podemos asignarle:

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto051.jpg)

Primero se agrupan las propiedades que podemos configurar más utilizadas como puede ser espacios para tabulación, tamaño de fuente etc:

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto052.jpg)

Luego de efectuar un cambio en la ventana de "Configuración", por ejemplo el tamaño de la fuente:

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto053.jpg)

Cerremos la pestaña de configuración y abramos cualquier archivo, luego podemos comprobar que el tamaño de la fuente es ahora de 20 puntos:

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto054.jpg)

Configuración de usuario y configuración de área de trabajo
En el ejemplo anterior modificamos la "Configuración de usuario", ésta es aplicada a todos los archivos que se editen. Podemos definir configuraciones particulares a un área de trabajo, para eso el área de trabajo debe estar abierta.

Para probar la configuración de un área de trabajo primero hagamos la apertura de una área de trabajo que tengamos guardada y procedamos a entrar a "Configuración":

![](https://www.tutorialesprogramacionya.com/herramientas/vscodeya/imagentema/foto055.jpg)

Debemos seleccionar la opción "Espacio de trabajo" y recién pasar a modificar valores de configuración.

La configuración definida solo tiene efecto en esa área de trabajo, luego si cerramos dicha área de trabajo y abrimos otra veremos que la configuración hecha anteriormente no tiene efecto.

La configuración del área de trabajo VSCode lo resuelve modificando el archivo con extensión '.code-workspace':

```json
{
	"folders": [
		{
			"path": "C:\\TutorialVSCode"
		},
		{
			"path": "C:\\documentacion"
		}
	],
	"settings": {
		"editor.fontSize": 10
	}
}
```