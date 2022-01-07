---
layout: post
title: "iSH app, un Linux en tu iPad"
date: 2022-01-07 08:280:43 +0100
categories: paranoia personal
comments: true
permalink: 2022/01/07/ish-app-un-inux-en-tu-ipad
---

Y de nuevo, siguiendo con la misma temática de mi último post, en el que escribí sobre utilidades del terminal, de la línea de comandos, hoy os descubro una app para iOS que he descubierto recientemente. Se llama [iSH](https://ish.app) y permite ejecutar una distro Linux (sabor Alpine para más señas) dentro de una app de iOS. Llegados a este punto pueden pasar dos cosas, que te importe bastante poco el tema y digas ¿para qué quiero yo eso? o bien que digas un Linux en mi iPad ¡cómo mola! Para el segundo grupo, van los siguientes párrafos. 

Tan sencillo como instalar la app y ejecutarla y ya estaréis en una **consola linux de Alpine 3.14**. Boom. Y ahora qué, bueno pues ahora todo porque tendréis acceso al repositorio de paquetes de Alpine y de ahí a instalar lo que necesitéis. Parece que la app vivía de hace tiempo entre las sombras y los jailbreaks pero recientemente Apple ha aprobado su distribución en la App Store, parece que hay alguna política que ha cambiado y a raíz de esto, se permite distribuir la app y funciona perfectamente. 

Bien, llegados a este punto, qué tal va, qué opciones se permiten, para qué lo uso... bueno pues primero **lo malo**: olvidaros de ejecutar cualquier entorno gráfico o aplicaciones avanzadas, dicen por ahí que los dockers no van (no he probado) y además el performance no es nada bueno. Pensad que esta app está emulando una arquitectura x86 en un sandbox de una app de iOS, o sea bueno, tomadlo como que se abre un mundo de posibilidades y de control pero es como si tuviéseis una máquina virtual ahí sin mucho más y, por otro lado, no todo funciona pimpam en este entorno, está bastante limitado y **hay que andar un poco a prueba y error**.

**Y ahora lo bueno**. Muchas aplicaciones funcionan bastante bien en este entorno de consola linux: **vim, mutt, ranger, msmtp, pyton, node, npm, nginx, openssh**... y en cambio otras pues no tanto. En el caso de vim por ejemplo, hay cantidad de plugins que funcionan y otros que no van muy finos y hay que buscar alternativas. También se pueden instalar fuentes alternativas (y algunas nerdfonts) a través de apps como Fontcase o iFont y aquí también hay que ir un poco a prueba y error para que os funcionen. Otra cosa interesante, poder montar carpetas de vuestro iPad o de vuestro iCloud en este entorno Linux, y de esta forma tener acceso a ellos. Otra cosa bastante guay si usáis la consola y las herramientas que vimos en el post anterior, es conectaros a vuestro mac por ssh, solo tenéis que saber la IP local de vuestro mac y conectaros remotamente.    

Posibilidades, frikear, cacharrear, cosas nuevas, sistemas alternativos, entornos de pruebas, programar en tu iPad, acceder a tus archivos en iCloud y un sistema en evolución. La verdad os digo, vale la pena probarlo, seguro que le encontráis un uso que se adapta a vuestras necesidades. Si os mola vim, ya podéis desinstalar iVim (si nunca lo tuvisteis) porque esto es una alternativa muchísimo mejor y completamente gratuita (al menos de momento).

Y sí, como ya habéis sospechado, estoy escribiendo este post, con neovim, ejecutándose remotamente en mi mac al que conecto vía ssh desde iSH en mi iPad, escribiendo en el sofá de casa, con mi Plank EZ y mi iPad Pro en el respaldo del apoyabrazos.



