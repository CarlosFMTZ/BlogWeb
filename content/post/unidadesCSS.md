---
title: "Unidades en CSS (em, rem, pt, px, vw, vh, vmin, vmax, ex, ch, ...)"
date: 2020-04-06
tags: ["css", "estilo", "pixeles"]
categories: ["front-end", "css"]
description: "Tutorial para encontrar las diferentes unidades con css"
draft: false
---

# 

CSS conoce varias unidades de medida. La unidad más conocida son los píxeles, pero hay otras unidades que no son tan populares pero muy útiles en algunos casos de uso.

Este artículo cubre unidades relativas, unidades absolutas y unidades de ventana gráfica.

| Medios    | Recomendado | Precio | Medios | Recomendado | Precio |
| :------- | :------: | -----: | :------: | :------: | -----: |
| Pantalla   | em      | 150€   | 1 | 2 | 3 |
| Item 2   | 3250     | 23,65€ | 1 | 2 | 3 |
|
Uso ocasional	Uso poco frecuente	No recomendado
Pantalla	em, rem,%	px	ch, ex, vw, vh, vmin, vmax	cm, mm, pulg, pt, pc
Impresión	em, rem,%	cm, mm, pulg, pt, pc	ch, ex	px, vw, vh, vmin, vmax
Unidades relativas
A diferencia de las unidades absolutas como píxeles, puntos o centímetros, también puede definir tamaños en unidades relativas como porcentaje, em o rem.
Las unidades relativas también cumplen con los estándares de accesibilidad .
En la mayoría de los navegadores, el tamaño de fuente predeterminado es 16px, puede usar este valor como base para los cálculos (por ejemplo, 16px equivale a 1em, 1rem o 100%).

Unidad	Descripción
%	porcentaje
em	tamaño de fuente del elemento (por ejemplo, 2.5em significa que la fuente es 2.5 veces más grande que la fuente normal)
movimiento rápido del ojo	tamaño de fuente del elemento raíz del documento
ch	ancho del carácter "0", en fuentes de espacio mono, donde todos los caracteres tienen el mismo ancho, 1ch equivale a 1 carácter
ex	altura x de la fuente actual, medida a la altura de la minúscula x


¿Cuál es la diferencia entre em y rem?
La diferencia radica en la herencia. El remvalor se basa en el elemento raíz ( html). Cada elemento secundario usa el htmltamaño de fuente como base de cálculo.

em por otro lado, se basa en el tamaño de fuente del elemento padre.

remhace que el cálculo del tamaño de fuente sea mucho más fácil. Con elementos anidados o incluso múltiples elementos anidados (por ejemplo, listas), el tamaño de fuente ya no tiene que calcularse en relación con el tamaño de fuente del elemento padre. remsiempre calcula el tamaño de fuente en relación con la htmletiqueta.

Diferentes familias de fuentes
Altura x de diferentes familias de fuentes

Todas las fuentes tienen el mismo tamaño (18 puntos), pero la barra roja indica que la altura x ( ex) de las fuentes es diferente.

ancho del carácter "0"

Las fuentes vuelven a tener el mismo tamaño (18 puntos). En este gráfico chse compara el ancho de caracteres ( ). Las fuentes monoespaciales tienen el mismo ancho para cada carácter, mientras que las fuentes serif o sans-serif pueden tener anchuras diferentes para cada carácter ( ies más angosto que o).

Unidades absolutas
Las unidades absolutas tienen un tamaño fijo, no se puede discutir cuánto mide un centímetro. Si tiene un caso en el que se requiere la longitud exacta, debe usar unidades absolutas (por ejemplo, para componentes que no deben redimensionarse). También pueden ser útiles si desea definir restricciones para evitar que las áreas se vuelvan demasiado anchas o demasiado estrechas. Las unidades absolutas no cambian según el tamaño de la pantalla, la dirección u otras variaciones.

Unidad	Descripción	
cm	centímetros	1 cm = 1 cm
mm	milímetros	10 mm = 1 cm
en	pulgadas	1 pulgada = 96px = 2.54 cm
px	píxeles	1 px = 1/96 de 1 en
pt	puntos	1 pt = 1/72 de 1 en
ordenador personal	pica	1pc = 12 pt


Unidades de ventana gráfica
Las unidades de ventana gráfica representan un porcentaje de la ventana gráfica actual del navegador.
La diferencia con las unidades de porcentaje es que las unidades de la ventana gráfica siempre se calculan como el porcentaje del tamaño de la ventana gráfica del navegador. Mientras que las unidades porcentuales heredan el tamaño de su elemento padre.

Unidad	Descripción
vw	1% del ancho de la ventana gráfica (50% significa la mitad del ancho de la ventana gráfica)
vh	1% de la altura de la ventana gráfica (50% significa la mitad de la altura de la ventana gráfica)
vmin	1% de la dimensión más pequeña de la ventana gráfica (vw o vh)
vmax	1% de la dimensión más grande de la ventana gráfica (vw o vh)


vminy vmaxpuede cambiar mientras se cambia el tamaño de la ventana del navegador o se cambia la orientación del teléfono móvil.
vmines el mínimo entre la altura o el ancho de la vista en porcentaje, dependiendo de cuál sea más pequeño.

vmax es el máximo entre la altura o el ancho de la ventana en porcentaje, según cuál sea mayor.

Si te gusta mi contenido, ¿podrías seguirme en Twitter? 
[![Alternate Text]({image-url})]({https://www.youtube.com/watch?v=ow7YMKnHZMQ&t} "Link Title")