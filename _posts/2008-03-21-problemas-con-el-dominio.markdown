---
layout: post
title: Problemas con el dominio
date: '2008-03-21T00:00:00+00:00'
permalink: http://resistancefutile.com/2008/03/21/problemas-con-el-dominio/
---
Si habéis entrado a <a href="http://reistancefutile.com">este blog</a> o al de <a href="http://childrenatyourfeet.com">Cristina</a> durante esta mañana, os habréis encontrado con la típica página de que el dominio estaba libre o expirado, al final hemos podido arreglarlo, había un fallo en la configuración del dominio que tenemos en Yahoo.

La verdad que entre que los de Yahoo tuvieron problemas para cobrarme de la VISA (hace días lo modifiqué a Paypal y sin problemas de momento) y los del hosting no me avisaron que me caducaba el servicio si no pagaba, no sé qué es lo que ha producido el error, pero el hecho es que ya está solucionado.

Además la caché de OSX me continuaba cargando el dominio aparcado, hasta que no he pasado Cocktail (creo que voy a comprar su licencia) cepillándome las cachés y he reiniciado, no ha vuelto a la normalidad el tema.

Qué disgustos de buena mañana de Viernes de pasión :D

<strong>Actualización</strong>: Siguen los problemas con Yahoo Domains, el muy cabrón sigue cambiándo el puto NameServer por la cara, voy a enviarles un correo no muy amable a los del yahoo smallbusiness.

<strong>Actualización 2</strong>: he encontrado este comando que me parece muy útil para casos como el que describía anteriormente, <em>dscacheutil -flushcache</em> limpiará la caché de DNS del sistema y de esta manera se soluciona que tras el cambio se  quede el dominio aparcado en la caché. Si no conseguís acceder al blog, sería interesante que lo ejecutáseis en vuestros Leopards.
