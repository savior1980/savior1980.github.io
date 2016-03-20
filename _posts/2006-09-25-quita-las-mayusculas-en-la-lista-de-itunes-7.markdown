---
layout: post
title: Quita las mayúsculas en la lista de iTunes 7
date: '2006-09-25T00:00:00+00:00'
permalink: http://resistancefutile.com/2006/09/25/quita-las-mayusculas-en-la-lista-de-itunes-7/
---
<img style="float:right; margin:0 0 10px 10px;" src="http://photos1.blogger.com/blogger2/4553/2422/320/Imagen%201.1.png" border="1" alt="" />Uno de los aspectos que más odiaba de iTunes 7 es que los títulos de la lista lateral de navegación aparecieran en mayúsculas. Sí gente, podéis llamarme maníaco o lo que queráis pero no entnedí nunca porque "Biblioteca" pasaba a llamarse "BIBLIOTECA".

Pero gracias a <a href="http://www.macworld.com/weblogs/macosxhints/2006/09/itunes7caps/index.php?lsrc=mwrss">este artículo</a> en Macworld descubrí la manera de editar el fichero de localización apropiado para volver a la normalidad esos títulos y restablecer la nomenclatura de toda la vida, incluso, si no os gusta la palabra "Biblioteca" para referirse a vuestra colección de música y deseáis sustituirla por "Musicoteca" o "Toda mi música" o lo que queráis también podréis hacerlo, es sencillo y no requiere de Terminal, tan sólo aseguraos de tener iTunes inactivo mientras realizáis los siguientes pasos:

1- En el Finder, encima del icono de iTunes pulsad la opción "mostrar contenido del paquete" en el menú emergente que aparecerá con Ctrl+click o botón derecho.
2- Navegad hasta la carpeta <span style="font-style:italic;">Contents\Resources\Spanish.lproj\</span>
3- Botón derecho al archivo <span style="font-style:italic;">Localizable.strings</span> y seguidamente "Abrir con..." y usad un editor de texto, TextEdit va perfectamente.
4- Buscad las palabras "BIBLIOTECA", "STORE" y demás que queráis sustituir y cambiadlas.
5- guardad el archivo e iniciad iTunes, ya tendréis las molestas mayúsculas sustituidas con lo que vosotros queráis.
