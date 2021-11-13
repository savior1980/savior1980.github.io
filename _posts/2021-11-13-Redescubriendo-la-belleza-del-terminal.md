---
layout: post
title: "Redescubriendo la belleza del terminal"
date: 2021-11-13 21:00:43 +0100
categories: paranoia personal
comments: true
permalink: 2021/11/13/Redescubriendo-la-belleza-del-terminal
---

Siguiendo con la estela marcada por el último post, en el que escribí sobre Vim, hoy quería comentar un poco sobre cómo he redescubierto la belleza que esconde la línea de comandos, del terminal, de la consola. Es minimalismo extremo, consumo escaso de recursos (o vaya mucho más que cargar cualquier GUI claro) y uso intensivo del teclado, y además compatible ya para cualquier sistema operativo (linux, macos, windows o lo que queráis que pueda tener una aplicación de Terminal). Y ahí va un pequeño recopilatorio de las herramientas que uso y por qué las uso (y ojo con esto que no me considero ningún experto ni mucho menos, simplemente son herramientas que he ido descubriendo y que a mí me sirven).

## iTerm 2
No cuesta un duro, no cuesta ningún esfuerzo instalar, no cuesta nada de configurar, tiene tantas opciones que es difícil hacer una lista. Permite pestañas si te van las pestañas, permite personalizar la interfaz, la fuente, los colores, hasta límites difícilmente explicables. Hay otras opciones (y muy buenas), Alacritty, Fish, Hyper... pero yo elegí iTerm por su facilidad de uso. 

### ¿Para qué lo uso?
Pues básicamente como reemplazo de terminal del sistema. Lo tengo en el Dock, lo activo siempre, me sirve para bastantes cosas, como descubriréis a continuación si continuáis leyendo.

### Enlace oficial
[iTerm2](https://iterm2.com/)

## tmux
Agarraos que vienen curvas. **Tmux es un multiplexador de terminal**. ¿Cómo os habéis quedado? ¿Y eso qué puñetas es? Pues básicamente es añadir una dimensión más al terminal, en un sentido es similar a trabajar con pestañas en iTerm2 pero con muchísimo más control sobre qué ventanas están abiertas y con posibilidad de guardar sesiones y recuperarlas. Es como una navaja suiza del terminal, en la que simultáneamente, puedes tener corriendo multitud de herramientas en paralelo. Compartiendo o no la misma pantalla, en modo split o en ventanas (piénsalo como pestañas) separadas, y otra vez, con una capacidad de personalización muy bestia para que se adapte a tu flujo de trabajo. 

### ¿Para qué lo uso?
Pues bueno tengo una sesión con varias herramientas que describo a continuación corriendo en paralelo, pero es que además me permite muy fácilmente abrir una nueva ventana de terminal y hacer lo que sea, y cuando ese lo que sea termina, volver a otra ventana abierta o cerrar la ventana actual o moverme entre las distintas ventanas de terminal solo con el teclado. Y tiene muchísimas más posibilidades pero bueno, con esto que os explico, que es un poco la superficie, solo con esto ya vale la pena instalarla (se puede instalar con brew) y experimentar un poco con ella. Y hay mogollón de recursos online y de posts que explican sus entresijos. Se adapta como un guante a distintas tareas y si tienes que usar el terminal constantemente es una gran herramienta. 

### Enlace a github
[tmux](https://github.com/tmux/tmux)

## Neovim
**Neovim** que es una especie de fork de vim hecho en Lua, que añade bastantes opciones al ecosistema de plugins de Vim y que de alguna manera se está volviendo un IDE en toda regla con soporte a los LSP (language server protocol), que sirven para controlar sintaxis/coloreado, dar algunas advertencias (linter) y sobretodo para autocompletar código, de forma similar a como hace pues Visual Studio, o Pycharm o (ponga usted aquí el IDE que más le guste o que conozca).

Neovim **es ultraligero, y permanece en una sesión de terminal, es retrocompatible con todo lo que funcione sobre vim y tiene numerosos nuevos plugins** que por lo general (aunque en algunos casos es discutible) mejoran los que hay disponibles para vim. Por ejemplo, Telescope sin ir más lejos es una mejora, almenos para mí vaya y creo que objetivamente es mejor a FZF para búsquedas relativas o _fuzzy_ dentro de un proyecto/directorio. 

Además, cosa que yo no uso, pero lo comento por si alguien le pica el gusanillo, hay bastantes paquetes ya hechos que lo transforman en un IDE y preinstalan una serie de plugins ya enfocados a programar. Hay multitud de "distros" como Doom, NvChad, y otros si os va la droga dura pero no queréis ensuciaros las manos y cacharrear con mogollón de plugins y configuraciones. Lo bueno es que los instalas y a correr, lo malo es que eligen por ti, claro y si hay otro autocompletado que mola más u otro gestor de ficheros, al final tendrás que personalizar un poco el paquete a tu medida. 

### ¿Para qué lo uso?
Uso Neovim principalmente como editor de textos en markdown y como editor de código y además como pequeño gestor de notas relacionadas con mi día a día. Tengo distintas notas en markdown que me sirven para ordenar mi trabajo, seguir reuniones, como agenda de distintas tareas y como pequeños snippets de código a los que tengo que recurrir a menudo. Ojo no es que tenga todas mis notas ahí, no lo uso como un repositorio de notas. Para eso uso [Bear](https://bear.app/) que me permite categorizar por tags y encontrar muy rápidamente lo que busco.

### Enlace oficial
[Neovim](https://neovim.io/)

## Neomutt / mutt
Mutt (y su reversión Neomutt más moderna pero basada en el original, un poco como vim y neovim) son **clientes de correo del terminal** con los que puedes sincronizar una cuenta IMAP o POP (¿hay alguien que use pop?) y bueno pues todo a través de consola, puedes moverte por carpetas, recibir correo, enviar correo a través de SMTP y usan el editor de textos que tengas configurado en tu terminal (o sea Neovim, claro). Con ellos puedes leer, responder, descargar adjuntos, hasta cierto nivel previsualizarlos, hacer forward, clasificar emails en carpetas, borrarlos, marcarlos como leídos y algunas cosas básicas más.

Van razonablemente bien, tienen posibilidades de configuración, permiten definir shortcuts y personalización con _themes_.

### ¿Para qué lo uso?
**Tener un cliente de correo en el terminal, pues qué queréis que os diga, a mí me funciona bien pero no lo uso como herramienta principal**. Sí lo tengo abierto en la segunda pestaña de mi sesión tmux y lo consulto principalmente para no salir del terminal e ir más rápido con algunos correos que sean o de respuesta muy sencilla o algo muy puntual. También lo uso para borrar algunos correos que llegan de forma rápida y clasificar algunos otros rápidamente. Pero, vaya, mi cliente de correo principal sigue siendo [Mailmate](https://freron.com/), no obstante mutt se convierte como en una extensión de este en la consola, cosa que no está nada mal.

### Enlace oficial
[Neomutt](https://neomutt.org/) 
[mutt](http://www.mutt.org/)

## lf
**lf es un gestor de archivos que vive en el terminal**. Nace de ranger, otro clásico (bastado en python) y muy similar. **lf** es como una reversión también del programa clásico y más moderno y ligero. Tiene los mismo atajos, bebe de la filosofía vim para los atajos más comunes pero permite configurarlo hasta la saciedad. Y también ofrece soporte para varias herramientas añadidas con las que podrás visualizar detalles de los archivos o tener una previsualización de ellos directamente en el terminal, cosa que nunca está de más. Ahora sí, eso requiere ponerle un poco de cariño a la configuración de la herramienta, no obstante, de saque oye pues ya tienes bastante terreno cubierto y quizás no necesites más. 

Claro como todo buen gestor de archivos, permite todas las operaciones básicas, como copiar, cortar, pegar, navegar rápidamente, crear carpetas, borrarlas, renombrar archivos... ofrece también selección múltiple y puede lanzar lo que el sistema tenga predefinido para abrir ese archivo. Y, evidentemente, permite usar tu editor de texto favorito dentro del mismo terminal (otra vez Neovim) para abrir y editar los archivos de tipo texto o código. 

### ¿Para qué lo uso?
Pues lo tengo abierto en una sesión de tmux y lo uso para operar con ficheros rápidamente, gestionar rápidamente lo que tengo en la carpeta de descargas, mover archivos a documentos o a otras localizaciones en mi sistema. También para previsualizar brevemente a veces según qué archivos o para lanzar preview de algún pdf. En fin, **no es la panacea**, no os digo que reemplaza por completo al uso que hago de Finder, **pero si estás dentro del terminal, oye te da una libertad y navegación muy rápidas a través de teclado**. 

### Enlace al proyecto en github
[lf](https://www.url.com)

## htop
**htop** es una herramienta de monitorización de recursos del sistema. Como el monitor de actividad de Mac OS? Pues eso pero en el terminal. Y muy currado. Y con muchísimas posibilidades de filtro y de visualización de los procesos que corren en tu máquina. Puedes, como en la utilidad de mac, ordenar por un determinado criterio, ver el proceso que está consumiendo, ver en modo árbol o no, permite ver la ruta donde está ubicado el proceso, y puedes matarlo, pararlo, lo que quieras. 

### ¿Para qué lo uso?
Pues he dejado de usar la herramienta de Mac en este caso, casi siempre voy a través de htop, otra herramienta que tengo abierta siempre y que me resulta muy útil en el día a día. 

### Enlace oficial
[htop](https://htop.dev/)

## openfortivpn
Seguro que trabajando en casa, usáis un cliente de VPN. Hay muchos y para gustos, colores. A mí me ha tocado usar Fortigate y las aplicaciones que tienen para mac dan bastante pena, de hecho, yo la he apodado, y siempre cariñosamente, _la fortigaita_. Entonces pues bueno, hay unos tíos que se han preocupado de buscar un cliente CLI para las VPN Fortinet y ofrecerlo en código abierto. Pues ahí que vamos. Configurarlo es un juego de niños y te da pues eso control sobre la conexión y no tener ahí aplicaciones con GUI ensuciando tu menú o tu Dock, te conectas y listo.

### ¿Para qué lo uso?
Cuando tengo que conectarme a las herramientas o entornos de desarrollo que requieren de conexión VPN. He dejado de usar la herramienta del fabricante y actualmente accedo mediante terminal. Requiere permisos de admin, requiere contraseña en prompt, pero bueno las pones y listo. 

### Enlace al proyecto en github
[openfortivpn](https://github.com/adrienverge/openfortivpn)

Y hasta aquí las herramientas que más uso en el terminal, y cómo he redescubierto la belleza de usar la consola del sistema y las posibilidades que ahí se esconden. Otro día, podemos hacer un poco una revisión de los temas y colores que uso en el terminal, porque no, no se todo en blanco y negro... hay un mundo de color ahí también y grandes posibilidades de personalización en todas estas herramientas, ya sea a través del soporte que ellas mismas ofrecen (caso Neovim o Neomutt por ejemplo) o bien con la integración en la consola y el control que ejerce sobre ella iTerm2. 

Si usáis el terminal en vuestro día a día, seguro que ya conocíais la mayoría de estas herramientas (y si usáis alguna más compartidla!) y hay muchas más que no he destacado (bat, neofetch, ranger, lynx, pandoc, exa, ...), pero si no, échale un vistazo a lo que te estás perdiendo, igual no sirven para tu día a día, o igual sí, quién sabe, no se pierde nada por probarlo.



