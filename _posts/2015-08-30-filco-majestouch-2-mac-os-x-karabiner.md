---
layout: post
title: Filco Majestouch 2 + Mac OS X = Karabiner
date: '2015-08-30T00:00:00+00:00'
permalink: 2015/08/30/filco-majestouch-2-mac-os-x-karabiner/
---

Como sabéis me agencié un [Filco Majestouch 2 tenkeyless](http://resistancefutile.com/2015/06/13/verano-de-novedades/) hace unos meses, es un buen teclado mecánico y podéis encontrarlo con layout en español en [keyboardco.com](http://www.keyboardco.com/keyboard/spanish-filco-majestouch-2-tenkeyless-nkr-tactile-action-keyboard.asp) y además con un servicio de atención al cliente excelente. El teclado está pensado para Windows, lleva sus teclas de función y no lleva teclas multimedia, pero es compatible con Mac OS X, en este post os voy a describir como hacer que este teclado brille con todo su esplendor en el sistema operativo de la manzana.

Lo primero de lo primero es bajar [Karabiner](https://pqrs.org/osx/karabiner/) que es un software gratuito de remapeo de teclado. ¿Ya lo tenéis?. Me espero. Bien si habéis terminado de descargarlo os diré que pocos programas funcionan tan bien, nunca he tenido ningún problema con él y consume muy poquitos recursos. A continuación os pondré capturas con la configuración que tengo a día de hoy configurada, pero las posibilidades que da el programa son enormes, lo mejor es experimentar un poco y ver cuál de las múltiples opciones que ofrece se adapta mejor a nuestra forma de trabajar.

Ya conocía Karabiner de antes (en su alter ego *KeyRemap4MacBook* cuando [DoubleCommand mostró flaquezas y falta de compatibilidad en Lion](:http://resistancefutile.com/2011/02/27/lo-que-mehagustado-y-nomehagustado-de-mac-os-x-10-7-lion-11a390/)), puesto que permite algunas opciones realmente geniales para mí, como es la posibilidad de pulsar Shift + Backspace para hacer el suprimir o _forward delete_, probadlo y me contáis si no es mucho mejor combinación que el fn+backspace, de entrada lo podéis hacer usando solo la mano derecha. Esta es una de mis opciones preferidas.

El *Filco Majestouch 2 tenkeyless no tiene teclas multimedia*, pero si son necesarias para vosotros, las podéis incorporar con Karabiner. En mi caso yo lo tengo al revés que cualquier teclado de Mac OS X, es decir las teclas se comportan como teclas de función normalmente (f1-f12) y toman su comportamiento multimedia cuando pulso la tecla _Fn_. ¿Cómo? ¿Que no encontráis la telca _Fn_ en el Filco? Ah amigos, es que no está, lo que he hecho es hacer que la tecla de botón secundario, al lado del alt, la "PC key" se comporte como _Fn_. Siguiendo esta línea también le he puesto funciones a las teclas de bloqueo y scroll lock (las que vienen después del Print Screen) puesto que si no, en Mac son bastante inservibles.

Sin más toda la configuración que hay que activar para tener lo que os he ido comentando:

<img src="/assets/Karabiner1.png" alt="Karabiner1" width="587" height="466" class="aligncenter size-full wp-image-2268" />

Hago un alto en el camino para comentar a continuación que la siguiente captura es para la configuración del teclado en español, no sois vosotros, hay algunas teclas que se han remapeado o intercambiado como el > y el º y que con Karabiner podemos volver a su estado original. Si activáis estas opciones, tendréis el teclado a vuestro gusto con el layout español:

<img src="/assets/Karabiner2.png" alt="Karabiner2" width="566" height="286" class="aligncenter size-full wp-image-2269" />

Una muy buena opción que ofrece el programa es la definición de perfiles. Así como tengo el macbook pro y en ocasiones tengo que desconectar el teclado y usar el propio del portátil, solo tengo de acordarme en cambiar de perfil Filco a no Filco por el iconito del menú (no me acuerdo nunca hasta que no puso físicamente command + c y acaba pulsándose alt+c que es el símbolo de copyright *Actualización:* hay una funcionalidad en el Karabiner para no remapear teclados internos, que igual es mejor opción).

De saque la tecla de Windows se mapea como Command en Mac OS X, pero el principal problema es que la disposición de teclas de izquierda a derecha en Windows es control-windows-alt-espacio y no control-alt-windows-espacio, que sería la disposición de teclas en cualquier teclado con configuración para Mac. Os recomiendo intercambiar las teclas sacándolas con un par de clips como recomiendan [en este post](http://www.cultofmac.com/271485/hacking-filcos-tenkeyless-majestouch-2-work-mac-review/) si no queréis haceros con un keypuller (son baratos, los encontráis en amazon y os servirán mejor si tenéis que cambiar más teclas como os cuento a continuación). Si lo hacéis recordad activar la opción de Karabiner "Swap Start (aka Command) and Alt Keys on Windows Keyboard".

Para completar la transformación de nuestro teclado windowsero en un teclado para Mac de pro, lo único que nos hará falta será comprar unas teclas de función acordes a los estándares maqueros, como la tecla command y la tecla alt-opción. En [elitekeyboards](https://elitekeyboards.com/products.php?sub=access#cherrymxkeys) y por cuatro dólares (literal) compré unas teclas rojas que le van de maravilla al teclado, hay opciones en otros colores y más discretas. También tienen keypullers por 6 pavos y van genial si tenéis que quitar varias teclas, yo quité los cuatro cursores, el esc y las dos teclas de windows y las dos teclas de alt para sustituirlos por sus correspondientes teclas alt y command.
