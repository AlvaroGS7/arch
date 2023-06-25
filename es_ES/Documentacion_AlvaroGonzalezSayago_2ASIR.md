`         `![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.001.png)

`    `![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.002.png)



<a name="_page1_x82.00_y71.25"></a>HOJA RESUMEN – PROYECTO 



|**Título del proyecto:** Desarrollo de un Entorno Profesional para la Ciberseguridad||
| - | :- |
|**Autor:** Álvaro González Sayago** |**Fecha:** 02/06/2023** |
|**Tutor:** López Fernández, Olga María** ||
|**Titulación:** CFGS 2 Administración de Sistemas Informáticos en Red||
|**Palabras clave:** Ciberseguridad,  entorno profesional, kitty, bspwm, zsh, parrot, arch, black arch, pentesting, picom, polybar, sxhdk.||
|**Resumen del proyecto:** Crear un entorno profesional orientado a la ciberseguridad completamente desde cero con una distribución base, pudiendo personalizar por completo tanto el diseño gráfico de nuestro entorno como los atajos de teclado para una utilización lo más cómoda posible.  ||





ÍNDICE 

[HOJA RESUMEN – PROYECTO ................................................................................................2 ](#_page1_x82.00_y71.25)[Introducción ........................................................................................................................6 ](#_page5_x82.00_y71.25)[Introducción a la memoria. ...............................................................................................6 ](#_page5_x82.00_y98.25)[Descripción. .....................................................................................................................6 ](#_page5_x82.00_y265.25)[Objetivos generales y beneficios........................................................................................6 ](#_page5_x82.00_y542.25)[Motivaciones personales...................................................................................................7 ](#_page6_x82.00_y71.25)[Estructura de la memoria. .................................................................................................7 ](#_page6_x82.00_y288.25)[Estudio de viabilidad.............................................................................................................8 ](#_page7_x82.00_y71.25)[Introducción.....................................................................................................................8 ](#_page7_x82.00_y98.25)[Requisitos del sistema.......................................................................................................8 ](#_page7_x82.00_y191.25)[Requisitos. ....................................................................................................................8 ](#_page7_x82.00_y208.25)[Priorización de los requisitos..........................................................................................8 ](#_page7_x82.00_y438.25)[Alternativas y selección de la solución................................................................................9 ](#_page8_x82.00_y71.25)[Alternativa 1. KITTY sobre Arch Linux. ............................................................................9 ](#_page8_x82.00_y140.25)[Alternativa 2. BSPWM sobre Parrot. ...............................................................................9 ](#_page8_x82.00_y418.25)[Conclusiones.................................................................................................................9 ](#_page8_x82.00_y691.25)[Planificación del proyecto ............................................................................................... 10 ](#_page9_x82.00_y71.25)[Planificación temporal. ................................................................................................ 10 ](#_page9_x82.00_y140.25)[Evaluación de riesgos. ..................................................................................................... 11 ](#_page10_x82.00_y71.25)[Posibles riesgos........................................................................................................... 11 ](#_page10_x82.00_y126.25)[Plan de contingencia. .................................................................................................. 11 ](#_page10_x82.00_y193.25)[Presupuesto ................................................................................................................... 11 ](#_page10_x82.00_y371.25)[Estimación de coste material ....................................................................................... 11 ](#_page10_x82.00_y425.25)[Resumen y análisis coste-beneficio. ............................................................................. 11 ](#_page10_x82.00_y492.25)[Conclusiones .................................................................................................................. 11 ](#_page10_x82.00_y568.25)[Beneficios ................................................................................................................... 11 ](#_page10_x82.00_y585.25)[Inconvenientes ........................................................................................................... 11 ](#_page10_x82.00_y671.25)[Análisis de software............................................................................................................ 12 ](#_page11_x82.00_y71.25)[Introducción................................................................................................................... 12 ](#_page11_x82.00_y98.25)[Software utilizado........................................................................................................... 12 ](#_page11_x82.00_y168.25)[**Pacstrap** ..................................................................................................................... 12 ](#_page11_x82.00_y245.25)[**AwesomeWM**............................................................................................................. 12 ](#_page11_x82.00_y416.25)[**PICOM**........................................................................................................................ 13 ](#_page12_x82.00_y71.25)

[**ZSH** ............................................................................................................................ 13 ](#_page12_x82.00_y265.25)





[**LSD**............................................................................................................................. 14 ](#_page13_x82.00_y71.25)[**BAT** ............................................................................................................................ 14 ](#_page13_x82.00_y373.25)[**Powerlevel10k**............................................................................................................ 15 ](#_page14_x82.00_y71.25)

[**FZF** ............................................................................................................................. 15 ](#_page14_x82.00_y410.25)[**NeoVim** ...................................................................................................................... 16 ](#_page15_x82.00_y71.25)[**Mdcat** ........................................................................................................................ 16 ](#_page15_x82.00_y338.25)[**NeoFetch**.................................................................................................................... 17 ](#_page16_x82.00_y71.25)[**NvChad** ...................................................................................................................... 17 ](#_page16_x82.00_y486.25)[**BurpSuite** ................................................................................................................... 18 ](#_page17_x82.00_y71.25)[**Nmap** ......................................................................................................................... 18 ](#_page17_x82.00_y342.25)[**RustScan** .................................................................................................................... 19 ](#_page18_x82.00_y71.25)[**Plocate** ....................................................................................................................... 19 ](#_page18_x82.00_y401.25)[**Impacket** .................................................................................................................... 19 ](#_page18_x82.00_y580.25)[**Responder**.................................................................................................................. 20 ](#_page19_x82.00_y71.25)[**WhatWeb**................................................................................................................... 20 ](#_page19_x82.00_y339.25)[**Wfuzz** ......................................................................................................................... 21 ](#_page20_x82.00_y71.25)[**Evil-WinRM** ................................................................................................................ 21 ](#_page20_x82.00_y400.25)[**MetaSploit** ................................................................................................................. 22 ](#_page21_x82.00_y71.25)[**ExploitDB** ................................................................................................................... 22 ](#_page21_x82.00_y376.25)[Personalización del entorno. ............................................................................................... 23 ](#_page22_x82.00_y71.25)[Introducción................................................................................................................... 23 ](#_page22_x82.00_y98.25)[Personalización .............................................................................................................. 23 ](#_page22_x82.00_y168.25)[Manual de atajos & comodidades ....................................................................................... 26 ](#_page25_x82.00_y71.25)[Introducción................................................................................................................... 26 ](#_page25_x82.00_y98.25)[Atajos y comodidades ..................................................................................................... 26 ](#_page25_x82.00_y205.25)[Pruebas generales .............................................................................................................. 27 ](#_page26_x82.00_y71.25)[Introducción................................................................................................................... 27 ](#_page26_x82.00_y98.25)[Pruebas de uso. .............................................................................................................. 27 ](#_page26_x82.00_y154.25)[Resultados obtenidos...................................................................................................... 29 ](#_page28_x82.00_y386.25)[Conclusiones .................................................................................................................. 29 ](#_page28_x82.00_y478.25)[Webgrafía .......................................................................................................................... 30 ](#_page29_x82.00_y94.25)[Conclusión final .................................................................................................................. 31 ](#_page30_x82.00_y71.25)[Fin del documento ............................................................................................................. 31 ](#_page30_x222.00_y680.25)









<a name="_page5_x82.00_y71.25"></a>Introducción 

<a name="_page5_x82.00_y98.25"></a>Introducción a la memoria. 

En esta memoria recopilaré toda la documentación necesaria para explicar lo mejor y más completo posible mi proyecto, además, estará dividida por las secciones que considero son más importantes para su posterior explicación. 

La documentación constará de información tal como los objetivos del proyecto, costes, requisitos, ventajas, manuales de instalación/configuración, planificación, webgrafía, glosario de palabras etc. 

<a name="_page5_x82.00_y265.25"></a>Descripción. 

Este proyecto se basa en la creación de un entorno profesional de ciberseguridad, configurado completamente desde cero, usará paquetes y software de licencia gratuita, además de una distribución base y limpia.  

De los paquetes de los que estará compuesto el proyecto, en su mayoría a todos hay que instalarlos y configurarlos, siempre se aportará la fuente de instalación. 

Además de la configuración de paquetes, con este proyecto conseguiremos un sistema fácil de utilizar y muy personalizable. 

Recalcar que la inspiración de este proyecto es gracias a S4vitar: <https://www.youtube.com/@s4vitar>  

<https://www.twitch.tv/s4vitaar>  

[https://s4vitar.github.io ](https://s4vitar.github.io/)

<a name="_page5_x82.00_y542.25"></a>Objetivos generales y beneficios. 

Los objetivos generales de este proyecto son: 

- Aprender sobre los diferentes paquetes que se usen. 
- Priorizar la comodidad del usuario. 
- Obtener una interfaz completamente personalizable. 
- Conseguir atajos de teclado modificables. 
- Acabar con un sistema apto para la realización de técnicas de pentesting y ciberseguridad. 
- Uso de paquetes de coste cero mediante licencias gratuitas o de código abierto. 





<a name="_page6_x82.00_y71.25"></a>Motivaciones personales. 

Es un proyecto que me llama muchísimo la atención ya que es conseguir un entorno completamente diferente al que tenemos al inicio del proyecto además de tener muchas nuevas funcionalidades. 

Me llamó bastante la atención desde el principio por estar basado en Linux y tener tantos paquetes distintos con muchas utilidades diferentes, cada uno con su propia configuración. 

Me lo propongo como un reto a mí mismo ya que con tanto trabajo en una sola distribución, es muy complicado que no aparezcan varios errores por el camino, ya sean versiones, configuraciones, código etc.  

<a name="_page6_x82.00_y288.25"></a>Estructura de la memoria. 

La estructura intentaré que sea lo más sencilla posible. Estará dividida en 12 bloques, que serán los siguientes: 

- Introducción. (Este mismo bloque) 
- Estudio de Viabilidad. (Bloque a continuación) 
- Análisis. 
- Personalización del entorno. 
- Manual de atajos & comodidades. 
- Pruebas generales 
- Webgrafía 
- Conclusión final 
- Fin del documento 

Excepción: 

- Manual de Instalación & Configuración. (Documento a parte) 

Cada bloque es posible que esté dividido en apartados, y estos mismos apartados en 

subapartados. 

Cada bloque se separará del anterior mediante un salto de página (si son lo suficientemente grandes), para que el documento quede lo más limpio posible. 

Entre apartado y apartado habrá un espacio mínimo para aumentar la claridad del 

documento. 





<a name="_page7_x82.00_y71.25"></a>Estudio de viabilidad 

<a name="_page7_x82.00_y98.25"></a>Introducción. 

En este bloque documentaré de la mejor forma posible la viabilidad del proyecto, en aspectos generales, hablaré sobre requisitos, alternativas, planificación de recursos, riesgos etc. Será el apartado más grande y por lo tanto el que más organice el proyecto. 

<a name="_page7_x82.00_y191.25"></a>Requisitos del sistema 

<a name="_page7_x82.00_y208.25"></a>Requisitos. 

Como ya dije anteriormente, los requisitos serán prácticamente los mismos que las distribuciones base a utilizar. En este caso, la distribución base será Arch Linux: 



|**MÍNIMO** |**RECOMENDADO** ||||
| - | - | :- | :- | :- |
|**ARQUITECTURA** |x86 |x64 |||
|**RAM** |512MB |2GB |||
|**ALMACENAMIENTO** |1GB |20GB |||

Como recomendación personal, ya que se usarán bastantes paquetes grandes y ficheros de configuración, además de una instalación de interfaz gráfica desde cero, utilizaría la configuración de requisitos recomendada. 

<a name="_page7_x82.00_y438.25"></a>Priorización de los requisitos. 

Los requisitos principales serían el almacenamiento y la RAM, aunque lo recomendado sean 2GB yo intentaría conseguir 4GB o incluso 6. Además para un buen sistema operativo, intentaría también llegar a los 40GB de almacenamiento para asegurar que no acabemos con falta de espacio. 





<a name="_page8_x82.00_y71.25"></a>Alternativas y selección de la solución. 

Este proyecto se puede abarcar de dos grandes formas (son las que yo he planteado/encontrado, pero realmente puede hacerse de infinitas formas distintas y con cualquier distribución). 

<a name="_page8_x82.00_y140.25"></a>Alternativa 1. KITTY sobre Arch Linux. 

La primera alternativa es utilizar KITTY (emulador de terminal acelerado por GPU) y (Administrador de ventanas estilo Windows, pero para Linux) sobre Arch Linux. Utilizando los paquetes: 

- Pacstrap 
- Bootloader 
- AUR  ![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.003.png)
- VMware-tools  
- AwesomeWM  
- PICOM  
- ZSH  
- LSD  
- BAT  
- Powerlevel10k  
- FZF  
- Neovim 
- Mdcat 

<a name="_page8_x82.00_y418.25"></a>Alternativa 2. BSPWM sobre Parrot. 

La segunda y última alternativa, pero no menos importante, es utilizar BSPWM sobre Parrot. Utilizando los paquetes: 

- SXHKD 
- Polybar  ![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.004.png)
- ROFI  
- PICOM  
- Slimlock  
- Powerlevel10k  
- BAT  
- LSD  
- FZF  
- ZSH  
- Ranger  
- Oh My Tmux 
- fastTCPscan 

<a name="_page8_x82.00_y691.25"></a>Conclusiones. 

Las dos alternativas son aceptables y muy amplias, en mi caso utilizaré la primera ya que considero que puede dar más trabajo y es más interesante. Si el proyecto al final resultara no ser lo suficientemente grande, haría también la segunda alternativa (saldría en este documento final más adelante). 





<a name="_page9_x82.00_y71.25"></a>Planificación del proyecto 

En este apartado explicaré cual será la estructura a seguir a la hora de crear el proyecto, intentaré dividir la planificación en pasos lo más pequeños posibles para que esté recopilado todo lo importante. 

<a name="_page9_x82.00_y140.25"></a>Planificación temporal. 

La planificación del proyecto será la siguiente: 

1. Descarga de VMware. 
1. Descarga de la ISO de Arch. 
1. Creación de la máquina virtual con Arch. 
1. Definir las particiones con cfdisk. 
1. Definir partición SWAP. 
1. Formatear las particiones. 
1. Instalación de paquetes necesarios con PACSTRAP. 
1. Crear archivo fstab. 
1. Instalación del GRUB. 
1. Habilitamos AUR. 
1. Instalamción de los repositorios de Black Arch en Arch Linux. 
1. Instalación de la interfaz gráfica. 
1. Instalación de KITTY, VMware tools, Firefox, AwesomeWM y PICOM. 
1. Instalación de plugins para ZSH, LSD y BAT. 
1. Configuración KITTY y PICOM. 
1. Instalación y configuración de Powerlevel10k, FZF, Neovim. 
1. Instalación de herramientas de pentesting. 
1. Configuración de teclas. 
1. Definición de los nuevos atajos personalizados. 
1. Instalación de MDCAT para visualizar archivos Markdown. 

Remarcar que cada uno de los paquetes utilizados tendrá más adelante su apartado de explicación sobre su funcionamiento, configuración y enlaces/comandos de interés. 





<a name="_page10_x82.00_y71.25"></a>Evaluación de riesgos. 

En esta sección nombraré los errores más grandes y comunes que nos pueden ocurrir, así como la forma de evitarlos. 

<a name="_page10_x82.00_y126.25"></a>Posibles riesgos 

Como es un proceso de varias horas sobre un mismo sistema instalando y haciendo diversas configuraciones, y varias de ellas tienen que ver directamente con el sistema, es bastante probable que podamos tener algún fallo crítico en algún momento del proceso. 

<a name="_page10_x82.00_y193.25"></a>Plan de contingencia. 

Como recomendación haría snapshots en la máquina virtual después de cada instalación/configuración que se realice correctamente, así, si cometemos algún fallo podremos volver al paso anterior sin problema. 

Además, intentaría no tener más de 3 snapshots activas al mismo tiempo para evitar almacenamiento innecesario. Para ello podemos ir borrando snapshots antiguas a medida que vamos progresando en el proyecto. 

Una vez tengamos el SO final, haremos una última snapshot con nuestro sistema funcionando a la perfección. 

<a name="_page10_x82.00_y371.25"></a>Presupuesto 

En este apartado presentaré el coste material además del análisis coste-beneficio del 

proyecto. 

<a name="_page10_x82.00_y425.25"></a>Estimación de coste material 

Este proyecto nos costará un total de 0€. Todos los paquetes, distribuciones, imágenes y configuraciones utilizadas son de código abierto o de licencia gratuita para que cualquiera pueda tenerlo. 

<a name="_page10_x82.00_y492.25"></a>Resumen y análisis coste-beneficio. 

Al ser un entorno profesional de trabajo, con un coste de 0€ podríamos sacar una rentabilidad infinita, depende de nuestro trabajo. 

<a name="_page10_x82.00_y568.25"></a>Conclusiones 

<a name="_page10_x82.00_y585.25"></a>Beneficios 

- Obtención de un entorno profesional de pentesting. 
- Entorno 100% personalizable. 
- Totalmente gratuito y en su mayoría de código abierto. 
- Atajos configurables. 

<a name="_page10_x82.00_y671.25"></a>Inconvenientes 

- Largo de hacer. 
- Muchos paquetes distintos. 
- Muchas configuraciones distintas. 
- Muchos pasos a seguir. 





<a name="_page11_x82.00_y71.25"></a>Análisis de software 

<a name="_page11_x82.00_y98.25"></a>Introducción 

En este bloque, nombraré todo el software utilizado para el proyecto. Obviaré lo más básico como VMware pero documentaré las utilidades que considere más raras. Además, insertaré a ser posible su página oficial o en su defecto su página de GitHub. 

<a name="_page11_x82.00_y168.25"></a>Software utilizado. 

Sección donde documentaré de la forma más completa posible cada utilidad del 

proyecto. <a name="_page11_x82.00_y245.25"></a>Pacstrap 

Pacstrap es un instalador de paquetes que viene incluido en la distribución de Arch Linux de base. Similar a apt-get o apt. 

**Links de interés:** 

Manual de Arch:[  https://man.archlinux.org/man/pacstrap.8](https://man.archlinux.org/man/pacstrap.8)  

GitHub:  [ https://github.com/archlinux/arch-install-scripts/blob/master/pacstrap.in](https://github.com/archlinux/arch-install-scripts/blob/master/pacstrap.in)  

<a name="_page11_x82.00_y416.25"></a>AwesomeWM 

También llamado Awesome Window Manager, basado en C y en LUA. Diseñado para mejorar el entorno gráfico y pensado para desarrolladores. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.005.png)

**Links de Interés:** 

Página Oficial:   [https://awesomewm.org](https://awesomewm.org/)  

GitHub:   <https://github.com/awesomeWM/awesome>  Vídeo de Intro:   [https://www.youtube.com/watch?v=qKtit_B7Ke](https://www.youtube.com/watch?v=qKtit_B7Keo)o  





<a name="_page12_x82.00_y71.25"></a>PICOM 

Picom es un compositor para Xorg. Muy útil al usarlo con administradores de ventanas (Como AwesomeWM). Nos permite aplicar sombras, transparencias, efectos 3D etc. 

**Links de Interés:** 

Manual de Arch:  <https://wiki.archlinux.org/title/picom>  

GitHub:  <https://github.com/yshui/picom>  

Vídeo de intro:   [https://www.youtube.com/watch?v=t6Klg7CvUx](https://www.youtube.com/watch?v=t6Klg7CvUxA)A  

<a name="_page12_x82.00_y265.25"></a>ZSH 

También llamado. Es un terminal muy potente para sistemas operativos basados en Unix. También es actualmente utilizado en Kali Linux. OhMyZsh es totalmente opcional pero mejora el uso y configuración de ZSH. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.006.png)

**Links de Interés:** 

Manual de Arch:  <https://wiki.archlinux.org/title/picom>  

GitHub OhMyZSH:  <https://github.com/ohmyzsh/ohmyzsh>  

GitHub ZSH:  <https://github.com/zsh-users/zsh>  

Vídeo de intro:   <https://www.youtube.com/watch?v=ADytC9a2g2Y>   





<a name="_page13_x82.00_y71.25"></a>LSD 

También llamado LSDeluxe. Es una mejora del comando LS que nos permite colorear el output, añadir iconos y hacerlo mucho más visual. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.007.png)

**Links de Interés:** 

GitHub:  <https://github.com/lsd-rs/lsd>  

Vídeo de intro:   [https://www.youtube.com/watch?v=YQSGg9oWST](https://www.youtube.com/watch?v=YQSGg9oWSTo)o  

<a name="_page13_x82.00_y373.25"></a>BAT 

Una mejora del comando CAT. Al igual que LSD con LS, BAT nos permite ver el output de un CAT pero con colores e identificación de código. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.008.png)

**Links de Interés:** 

GitHub:  <https://github.com/sharkdp/bat>  

Vídeo de intro:   <https://www.youtube.com/watch?v=myg9zTf5aC8>  





<a name="_page14_x82.00_y71.25"></a>Powerlevel10k 

Powerlevel10k es simplemente un tema para la shell ZSH. Es muy configurable fácilemente y nos permite también añadir iconos en el prompt. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.009.png)

**Links de Interés:** 

GitHub:  <https://github.com/romkatv/powerlevel10k>  

Vídeo de intro:   [https://www.youtube.com/watch?v=KNLNyX9V1L](https://www.youtube.com/watch?v=KNLNyX9V1L8)8  

<a name="_page14_x82.00_y410.25"></a>FZF 

También llamado Fuzzy Finder. Es un buscador rápido y optimizado de archivos y carpetas mediante línea de comandos que nos muestra los archivos que va encontrando en tiempo real. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.010.png)

**Links de Interés:** 

GitHub:  [https://github.com/junegunn/fz](https://github.com/junegunn/fzf)f  

Vídeo de intro:   [https://www.youtube.com/watch?v=J0QuhUThM5](https://www.youtube.com/watch?v=J0QuhUThM5E)E  





<a name="_page15_x82.00_y71.25"></a>NeoVim 

Como su propio nombre indica, es VIM pero con interfaz y utilidades mejoradas. Utiliza un 30% menos de código que el VIM original. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.011.png)

**Links de Interés:** 

Página Oficial:   [https://neovim.io](https://neovim.io/)  

GitHub:  <https://github.com/neovim/neovim>  

Vídeo de intro:   [https://www.youtube.com/watch?v=x1TEI0Mxmk](https://www.youtube.com/watch?v=x1TEI0MxmkI)I  

<a name="_page15_x82.00_y338.25"></a>Mdcat 

Mdcat nos permite visualizar por consola archivos Markdown de forma sencilla. 

**Links de Interés:** 

GitHub:  <https://github.com/swsnr/mdcat>  

Manual de Arch:   <https://man.archlinux.org/man/community/mdcat/mdcat.1.en>  Vídeo de Intro:   [https://www.youtube.com/watch?v=HvAhAytfRd](https://www.youtube.com/watch?v=HvAhAytfRdY)Y  





<a name="_page16_x82.00_y71.25"></a>NeoFetch 

Utilidad para buscar información del sistema de forma sencilla desde la línea de comandos. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.012.png)

**Links de Interés:** 

GitHub:  <https://github.com/dylanaraps/neofetch>   

Manual de Arch:   [https://archlinux.org/packages/community/any/neofetch](https://archlinux.org/packages/community/any/neofetch/)/  Vídeo de Intro:   [https://www.youtube.com/watch?v=btyrzunEw](https://www.youtube.com/watch?v=btyrzunEwlI)lI  

<a name="_page16_x82.00_y486.25"></a>NvChad 

Utilidad que nos permite mejorar NeoVim e incluso hacerlo muy parecido a VSCode. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.013.png)

**Links de Interés:** 

GitHub:  <https://github.com/NvChad/NvChad>  

Página oficial:    [https://nvchad.com](https://nvchad.com/)  

Vídeo de Intro:   [https://www.youtube.com/watch?v=WaSriehjG6](https://www.youtube.com/watch?v=WaSriehjG6o)o  





<a name="_page17_x82.00_y71.25"></a>BurpSuite 

Plataforma gráfica para testear la seguridad de aplicaciones Web. Tiene versión Professional y Community siendo esta última gratuita. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.014.png)

**Links de Interés:** 

GitHub:  <https://github.com/thehackingsage/burpsuite>  Página oficial:    <https://portswigger.net/burp>  

Vídeo de Intro:   <https://www.youtube.com/watch?v=nXm324qSfRA>  

<a name="_page17_x82.00_y342.25"></a>Nmap 

Escáner de puertos por defecto, el más usado. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.015.png)

**Links de Interés:** 

GitHub:  <https://github.com/nmap/nmap>  

Página Oficial:    [https://nmap.org](https://nmap.org/)  

Vídeo de Intro:   <https://www.youtube.com/watch?v=blZXOqJwZt4>  





<a name="_page18_x82.00_y71.25"></a>RustScan 

Un escáner de puertos modernos, equiparable a Nmap. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.016.png)

**Links de Interés:** 

GitHub:  <https://github.com/RustScan/RustScan>    

Página Arch:    <https://archlinux.org/packages/community/x86_64/rustscan/>  Vídeo de Intro:   <https://www.youtube.com/watch?v=a6j8D6LhByM>   

<a name="_page18_x82.00_y401.25"></a>Plocate 

Herramienta para localizar archivos en todo el sistema rápidamente. 

**Links de Interés:** 

GitHub:  <https://github.com/Aetf/plocate>  

Página Arch:    <https://man.archlinux.org/man/plocate.1>  

Vídeo de Intro:   <https://www.youtube.com/watch?v=GnRvtqry1-M> 

<a name="_page18_x82.00_y580.25"></a>Impacket 

Una serie de herramientas creadas en Python para trabajar con protocolos de red. **Links de Interés:** 

GitHub:  <https://github.com/fortra/impacket>  

Página Arch:    <https://archlinux.org/packages/community/any/impacket/>  Vídeo de Intro:   [https://www.youtube.com/watch?v=Ule_iBhhaw](https://www.youtube.com/watch?v=Ule_iBhhawQ)Q  





<a name="_page19_x82.00_y71.25"></a>Responder 

Herramienta para conseguir rápidamente credenciales y posibles accesos remotos. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.017.png)

**Links de Interés:** 

GitHub:  [https://github.com/lgandx/Responde](https://github.com/lgandx/Responder)r  

Página Arch:    [https://aur.archlinux.org/packages/responde](https://aur.archlinux.org/packages/responder)r  Vídeo de Intro:   <https://www.youtube.com/watch?v=8VtzpIbvX2U>   

<a name="_page19_x82.00_y339.25"></a>WhatWeb 

Herramienta para extraer datos e identificar una Web en específico. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.018.png)

**Links de Interés:** 

GitHub:  <https://github.com/urbanadventurer/WhatWeb>  Página Arch:    <https://aur.archlinux.org/packages/whatweb>  Vídeo de Intro:   [https://www.youtube.com/watch?v=7Uo8bVL1Ox](https://www.youtube.com/watch?v=7Uo8bVL1OxI)I  





<a name="_page20_x82.00_y71.25"></a>Wfuzz 

Utilidad para escanear estructuras de directorios mediante fuerza bruta. Sirve para lo mismo que GoBuster pero de diferente forma. También se puede usar ffuf, dirb, dirbuster y dirsearch. Todos sirven para lo mismo pero depende de la comodidad del usuario. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.019.png)

**Links de Interés:** 

GitHub:  [https://github.com/xmendez/wfuz](https://github.com/xmendez/wfuzz)z  

Página Arch:    <https://aur.archlinux.org/packages/wfuzz>  

Vídeo de Intro:   [https://www.youtube.com/watch?v=AIj3pPKck9](https://www.youtube.com/watch?v=AIj3pPKck9Y)Y  

<a name="_page20_x82.00_y400.25"></a>Evil-WinRM 

Usado en sistemas Windows con el servicio WinRM activo, normalmente funcionando por el puerto 5985. Creado en ruby. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.020.png)

**Links de Interés:** 

GitHub:  <https://github.com/Hackplayers/evil-winrm>  

Página Arch:  <https://aur.archlinux.org/packages/ruby-evil-winrm>  Vídeo de Intro:   [https://www.youtube.com/watch?v=-6j3P0VB8a](https://www.youtube.com/watch?v=-6j3P0VB8ak)k  





<a name="_page21_x82.00_y71.25"></a>MetaSploit 

Framework que reúne vulnerabilidades, así como CVEs para su uso en pentesting. No es recomendado usarlo sin mirar directamente los scripts. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.021.png)

**Links de Interés:** 

GitHub:  <https://github.com/rapid7/metasploit-framework>  Página Arch:  <https://wiki.archlinux.org/title/Metasploit_Framework>  Página Oficial:   [https://www.metasploit.com](https://www.metasploit.com/)  

Vídeo de Intro:   <https://www.youtube.com/watch?v=ZOFsQi1NVsM>  

<a name="_page21_x82.00_y376.25"></a>ExploitDB 

Base de datos con todos los CVEs registrados y como explotarlos. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.022.png)

**Links de Interés:** 

GitLab:   <https://gitlab.com/exploit-database/exploitdb>  Página Oficial:   [https://www.exploit-db.com](https://www.exploit-db.com/)  

Vídeo de Intro:   [https://www.youtube.com/watch?v=ZeBwhK2hQr](https://www.youtube.com/watch?v=ZeBwhK2hQr4)4  





<a name="_page22_x82.00_y71.25"></a>Personalización del entorno. 

<a name="_page22_x82.00_y98.25"></a>Introducción 

A continuación, mostraré cuales son los ficheros que debemos editar para personalizar nuestro entorno. No mostraré la forma de editarlos ya que eso está explicado en el documento para la instalación y configuración del entorno. 

<a name="_page22_x82.00_y168.25"></a>Personalización 

Todos los ficheros de configuración para personalizar nuestro entorno se encuentran en “~/.config”. Especialmente, las carpetas importantes son **bspwm, kitty, picom y sxhkd.** 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.023.png)

**Fichero “bspwmrc”.** Sirve para definir atajos de teclado y comportamiento de 

ventanas. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.024.png)





**Fichero “kitty.conf”.** Sirve para modificar la apariencia de nuestro terminal, asignarle atajos de teclado y funcionalidad a ciertas teclas o combinaciones. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.025.png)

**Fichero “picom.conf”.** Utilizado para efectos de transparencia y opacidad, sombras de ventanas, animaciones y efectos de bordeado en las ventanas. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.026.png)





**Fichero “sxhkdrc”.** Utilizado para las combinaciones de teclas y atajos de teclado así como comandos personalizados. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.027.png)





<a name="_page25_x82.00_y71.25"></a>Manual de atajos & comodidades 

<a name="_page25_x82.00_y98.25"></a>Introducción 

En esta sección, mostraré los atajos que están configurados por mí, de manera por defecto al descargar la máquina virtual. Todos estos atajos se pueden cambiar en el fichero SXHKD, yo solo documentaré algunos. 

Adicionalmente, dejaré dentro del home de la propia MV, un fichero cheatsheet que tenga todos los comandos útiles. 

<a name="_page25_x82.00_y205.25"></a>Atajos y comodidades 



|**Utilidad** |**Combinación** |
| - | - |
|Buscar Comando |CTRL + R |
|Buscar interactivamente |CTRL + T |
|Abrir terminal |SUPER + ENTER |
|Cerrar terminal/pestaña |SHIFT + CTRL + W |
|Cambiar terminal |SUPER + FLECHA + IZQ/DER |
|Abrir pestaña |SHIFT + CTRL + T |
|Cambiar pestaña |SHIFT + CTRL + FLECHA IZQ/DER |
|Renombrar pestaña |SHIFT + CTRL + ALT + T |
|Bloquear sistema |CTRL + ALT + L |
|Borrar línea |CTRL + U |
|Tabla de Emojis |CTRL + SHIFT + U |
|Reiniciar GUI |CTRL + SHIFT + R |
|Abrir FireFox |CTRL + SHIFT + F |
|Abrir BurpSuite |CTRL + SHIFT + B |





<a name="_page26_x82.00_y71.25"></a>Pruebas generales 

<a name="_page26_x82.00_y98.25"></a>Introducción 

En este bloque, probaré las distintas utilidades para verificar su funcionamiento, así como el funcionamiento del sistema en general. 

<a name="_page26_x82.00_y154.25"></a>Pruebas de uso. 

Uso de una VPN de HackTheBox para conectarme a una máquina virtual. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.028.png)

Escaneo de puertos inicial con Rustscan. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.029.png)





Escaneo intensivo a los puertos encontrados con RustScan (22 y 50051). 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.030.png)

Instalación de utilidad grpcui. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.031.png)





Uso de la nueva utilidad contra la máquina virtual para obtener una página expuesta. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.032.png)

<a name="_page28_x82.00_y386.25"></a>Resultados obtenidos 

Tras usar el entorno un buen rato, haciendo uso de algunas utilidades y atajos de teclado ya mostrados anteriormente, puedo decir que sirve para trabajar de forma cómoda y rápida incluso sin estar todavía 100% acostumbrado al entorno. 

<a name="_page28_x82.00_y478.25"></a>Conclusiones 

Considero que es un entorno útil y simple para hacer pentesting, y más todavía si estuviera acostumbrado al 100%. En cuanto a las expectativas que tenía, podría haber sido mejor pero igualmente cumple mucho con lo que me propuse al principio. 





<a name="_page29_x82.00_y94.25"></a>Webgrafía 

[https://keepcoding.io/blog/que-es-metasploit-ciberseguridad](https://keepcoding.io/blog/que-es-metasploit-ciberseguridad/)/  

[https://www.ochobitshacenunbyte.com/2019/09/18/que-es-zsh-y-como-utilizar-sus-temas-y- complementos/](https://www.ochobitshacenunbyte.com/2019/09/18/que-es-zsh-y-como-utilizar-sus-temas-y-complementos/)  

[https://www.exploit-db.com/about-exploit-d](https://www.exploit-db.com/about-exploit-db)b  <https://www.hackingarticles.in/a-detailed-guide-on-evil-winrm/>  <https://wfuzz.readthedocs.io/en/latest/>  [https://www.geeksforgeeks.org/rustscan-faster-nmap-scanning-with-rus](https://www.geeksforgeeks.org/rustscan-faster-nmap-scanning-with-rust/)t/  <https://nmap.org/book/> [https://www.geeksforgeeks.org/what-is-burp-suite](https://www.geeksforgeeks.org/what-is-burp-suite/)/ [https://linuxhint.com/what-is-neofetch-for-linux](https://linuxhint.com/what-is-neofetch-for-linux/)/ <https://neovim.io/charter/> 

[https://www.freecodecamp.org/news/fzf-a-command-line-fuzzy-finder-missing-demo- a7de312403ff/ ](https://www.freecodecamp.org/news/fzf-a-command-line-fuzzy-finder-missing-demo-a7de312403ff/)

<https://platzi.com/tutoriales/2383-prework-linux/12567-bat-y-lsd/> [https://www.instructables.com/Bspwm-Installation-and-Configuration](https://www.instructables.com/Bspwm-Installation-and-Configuration/)/ <https://distro.tube/guest-articles/installing-and-using-sxhkd.html> [https://dev.to/abdfnx/oh-my-zsh-powerlevel10k-cool-terminal-1no](https://dev.to/abdfnx/oh-my-zsh-powerlevel10k-cool-terminal-1no0)0 <https://wiki.archlinux.org/title/Arch_User_Repository> <https://www.linuxfordevices.com/tutorials/linux/picom> [https://www.reddit.com/r/i3wm/comments/vxfyk9/what_is_picom_used_fo](https://www.reddit.com/r/i3wm/comments/vxfyk9/what_is_picom_used_for/)r/ <https://itsfoss.com/pacman-command/> 





<a name="_page30_x82.00_y71.25"></a>Conclusión final 

En resumen, me ha gustado mucho hacer este proyecto. Me he encontrado muchos errores e imprevistos por el camino pero al final gracias a las documentaciones y páginas de GitHub he conseguido ir encontrando la solución. 

Construir el entorno poco a poco y desde cero también me ha ayudado a ver cómo funciona un entorno por dentro y cómo están formados. Así como la forma de implementar distintos entornos gráficos y la forma de editarlos. 

También estoy bastante contento con el rendimiento final que tiene, aunque podría ser mejorable, sobre todo a la hora de abrir aplicaciones como FireFox, que tarda algo más de lo esperado. 

Además, he conseguido que sea lo suficientemente útil como para poder usarse en trabajos de ciberseguridad de manera profesional, o al menos lo suficientemente cómodo como para resolver máquinas de HackTheBox desde el entorno de manera sencilla. 

En general, estoy bastante satisfecho con mi proyecto. 

![](Aspose.Words.5d2801ea-bc3c-4453-b664-1114c9d9333f.033.png)

` `F<a name="_page30_x222.00_y680.25"></a>in del documento 


