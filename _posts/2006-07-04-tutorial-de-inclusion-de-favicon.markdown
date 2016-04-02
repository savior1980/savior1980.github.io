---
layout: post
title: Tutorial de inclusión de favicon
date: '2006-07-04T00:00:00+00:00'
permalink: 2006/07/04/tutorial-de-inclusion-de-favicon/
---
<img style="display:block; margin:0px auto 10px; text-align:center;" src="http://photos1.blogger.com/blogger/6639/1972/1600/tmp10_dup_7e5a42d8dbf1a1a8d756bc6abffc185a.png" border="0" alt="" />
Para la inclusión de un favicon (ese icono que véis en junto a la URL del blog) hay que seguir los siguientes pasos:

Primero hay que seleccionar la imagen para generar el favicon, hay servicios web que la generan <a href="http://www.html-kit.com/favicon/">como éste</a> (que recomendaron en <a href="http://www.microsiervos.com/archivo/diseno/favicons-animados.html">microsiervos</a>) que es muy completo y gratuito o bien <a href="http://www.degraeve.com/favicon/">este otro</a>.

Seguidamente hay que subir el archivo generado a algún sitio web para acceder a él, <a href="http://www.photobucket.com">photobucket</a> (o blogger sin ir más lejos) por ejemplo y obtener la URL de acceso.

Para finalizar en vuestra plantilla, dentro de los tags de <span style="font-weight:bold;">< head ></span> hay que poner el código siguiente:
<span style="font-weight:bold;">< link rel="shortcut icon" href="favicon.ico" / ></span> dónde hay que sustituir "favicon.ico" por la URL de acceso a la imagen del favicon y recordar de quitar los espacios al principio y al final del tag. Si lo queréis animado (con gif adicional) deberéis incluir además: 
<span style="font-weight:bold;">< link rel="icon" href="favicon1.gif" type="image/gif" / ></span> donde favicon1.gif es el otro archivo que debe seguir los mismos pasos que el .ico.

Fin, ya tenéis favicon, recargad el blog y lo veréis activo.

Esta entrada es a petición de <a href="http://alvele.blogspot.com/">Alvele Camur</a> que me envía un correo preguntándome por el asunto. (Alvele resulta más útil si me envías la URL de tu blog, para que no tenga que buscarla en blogger ;) )
