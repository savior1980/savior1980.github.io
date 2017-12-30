---
layout: post
title: Cambia el look de Gmail en tu navegador por la versión para el iPad
date: '2010-04-03T00:00:00+00:00'
permalink: 2010/04/03/cambia-el-look-de-gmail-en-tu-navegador-por-la-version-para-el-ipad/
---
<img src="/assets/zz1743ca7c.jpg" alt="Gmail en formato iPad " title="Gmail en formato iPad " width="500" height="332" class="centro" />Si queréis tener el _look_ que ofrecerá *Gmail en su versión para el iPad en vuestro Mac*, aquí os enseño un truco para hacerlo.

Como veréis en la captura que acompaña el post o si directamente lo probáis, la versión de Gmail para el iPad se *estructura en formato doble panel*, donde en el lado izquierdo de la pantalla tenemos la interfaz del correo tal como la vemos en un iPhone y en el lado derecho vemos directamente el correo o la conversación que tengamos seleccionada.

Poner esta interfaz en *en Safari es un juego de niños*: Basta con ir a las opciones y en la pestaña avanzado clicar el botón "Mostrar el menú de Desarrollo en la barra de menús". Heho esto accedemos al menú de Desarrollo y ahí,  vamos a Agente de usuario, seleccionamos "Otra..." y ponemos el siguiente texto:

<code>Mozilla/5.0 (iPad; U; CPU OS 3_2 like Mac OS X; en-us) AppleWebKit/531.21.10 (KHTML, like Gecko) Version/4.0.4 Mobile/7B334b Safari/531.21.10</code>

Listo, *accedemos a Gmail y podemos ver el resultado*. En la entrada extendida tenéis el proceso para el resto de navegadores y los enlances a la fuente original donde explica todo el proceso.

<!--more-->

Para el resto de navegadores el proceso de cambiar el agente de usuario es un tanto más complicado. En *Firefox deberemos hacer uso de la extensión* [User Agent Switcher](https://addons.mozilla.org/en-US/firefox/addon/59) la que nos permitirá también establecer el texto mostrado más arriba e identificar el navegador como un iPad.

*En Chrome es todavía más complicado*, deberemos editar (con un editor hexadecimal) la marca de agente de usuario de la aplicación, si queréis probarlo armaros de valor y de un editor como [HexEdit](http://www.versiontracker.com/dyn/moreinfo/vt3/10658) (para Mac) y tenéis las instrucciones para hacerlo en el vía. También existe una extensión para Chrome llamada [Chrome Chameleon User Agent Spoofer](https://chrome.google.com/extensions/detail/aafciojnlamllgpkpdkbamkfgbofhgcj) pero según nos cuentan los que ya la han probado no funciona del todo bien.

*Este truco no sólo sirve para Gmail*, podéis acceder a todas las webs [adaptadas para el iPad](http://www.applesfera.com/curiosidades/navega-ya-por-las-webs-especialmente-disenadas-para-el-ipad-desde-la-version-de-escritorio-de-safari) como las que muestran en [la página oficial de Apple](http://www.apple.com/ipad/ready-for-ipad/), aunque muchas de ellas siguen mostrando la interfaz para el iPhone. También os puede servir para testear cómo se vería vuestra web o blog en la nueva pantalla del dispositivo multimedia de Apple.

Finalmente, recordad que en Safari estos cambios no se guardan y que la próxima vez que queráis acceder deberéis seguir el mismo proceso.

(Vía [Cnet News](http://news.cnet.com/8301-27076_3-20001675-248.html))
