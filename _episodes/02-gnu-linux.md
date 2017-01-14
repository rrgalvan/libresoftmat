---
title: "El sistema operativo GNU/Linux"
teaching: 15
exercises: 15
questions:
- "¿Qué es un sistema operativo?"
- "¿Qué es el sistema operativo GNU/Linux?"
- "¿Qué son las distribuciones Debian, Ubuntu y Guadalinex?"
- "¿Por qué motivos puede interesarme usar sistemas operativos Linux?"
objectives:
- Distinguir las características de los sistemas operativos modernos y recordar su historia.
- Encuadrar a GNU/Linux dentro de los sistemas operativos actuales, en particular Ubuntu y Guadalinex.
- Apreciar la difusión GNU/Linux en servidores, computación científica y sistemas móviles.
keypoints:
- Los sistemas operativos UNIX han tenido, desde su creación unas excelentes propiedades
- Los sistemas GNU/Linux se encuentran entre los sistemas UNIX más extendidos
- Su difusión es enormemente significativa en servidores de internet y en computación científica
- Las licencias Creative Commons se suelen usar para publicar material multimedia con licencia libre
---

## Sistemas operativos

Un *sistema operativo* es un conjunto de programas que gestiona los recursos de hardware de un equipo informático y provee servicios a las aplicaciones o programas que son ejecutados. Así, el sistema operativo enlaza las apicaciones ejecutadas por el usuario con el hardware de la máquina.

<center> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/dc/Operating_system_placement-es.svg/250px-Operating_system_placement-es.svg.png" alt="Sistema Operativo" style="width: 160px;"/> </center>

Según esta definición, no debe confundirse el sistema operativo con el
conjunto de herramientas que suele distribuirse junto a él, como
explorador de ficheros, navegador web o programas de configuración. En
efecto, éstas no son más que aplicaciones especializadas en
determinadas tareas y por tanto se colocan sobre el sistema operativo.

### Un poco de historia

La noción de Sistema Operativo surge en la década de los 50 y a lo
largo de los años 60 se introducen los conceptos fundamentales, entre ellos:

- Sistema *multiusuario*: aquél que ofrece servicio y procesamiento a
  múltiples usuarios de forma simultánea. Estos usuarios pueden tener
  distintos privilegios de acceso a los recursos del sistema.
- Sistema *multitarea*: aquél que permitie que numerosos procesos o
  aplicaciones se ejecuten al mismo tiempo (quizás aparentemente),
  compartiendo uno o más procesadores.

En los años 70 aparece el sistema operativo *UNIX*, que de una u otra
forma ha marcado a los sistemas operativos actuales. Dotado de
características multiusuario y multitarea, UNIX se extendió
rápidamente, en distintas versiones que se distribuyeron en
universidades y compañías gubernamentales de Estados Unidos. El
sistema UNIX no tenía licencia libre, pero la Universidad de Berkley
mantuvo una versión conocida como *BSD*, que sería publicada en
décadas posteriores con una licencia libre. Las versiones con
licencia no libre fueron decayendo en popularidad con los años.

La clave estivo en el siguiente hecho: en la década de 1980 un grupo
de académicos y programadores voluntarios, liderados por Richard
M. Stallman y cristalizados en torno a la *Free Software Foundation*,
comenzaron un proyecto para crear el primer sistema operativo
completamente libre, de tipo UNIX. A este proyecto se le llamó *GNU*
(acrónimo recursivo: GNU = GNU's Not UNIX).

En los años 90, el sistema GNU estaba maduro con la excepción de su
pieza fundamental: el núcleo del sistema operativo. En 1991, un
estudiante universitario llamado Linus Torvalds desarrolló un núcleo
para computadoras al que llamó *Linux* y dotó de licencia GPL. Este
núcleo fue integrado por el proyecto GNU, dando pie al sistema
operativo *GNU/Linux* (aunque, por muchas personas, es conocido
simplemente como Linux). Este es el sistema que conocemos en la
actualidad, muy extendido en algunos campos (como en computación
científica y en servidores). A su vez, el núcleo *Linux* es hoy el
corazón de sistemas operativos como el popular *Android*.

De forma paralela, en los años 80 apareció un sistema llamado
NeXTSTEP, basado en un sistema UNIX BSD proveniente de los
años 1970. En los años 1990, Apple, después de años de éxitos
fabricando ordenadores con un sistema operativo multitarea pero
monousuario, llamado Mac OS, necesitaba una renovación. En 1997 compró
NeXTSTEP y de él nació el sistema *Mac OS X*, que es así un
sistema de tipo UNIX.

Simultáneamente, en la década de 1980, Microsoft lanzó el sistema
operativo MS-DOS, influenciado por algunas carateríasticas de UNIX
como el uso de subdirectorios y de tuberías. Orientado a ordenadores
personales, MS-DOS no contaba con características de multitarea y
multiusuario. Estas características se incluyeron paulatinamente, a lo
largo de las décadas de 1990 y 2000, en los sitemas Windows, que
sustituyeron a MS-DOS.

## El sistema operativo GNU/Linux

A partir de los años 90, el núcleo Linux se unió al sistema GNU, dando
lugar a un sistema operativo de tipo UNIX que contó con las numerosas
aplicaciones básicas que habían sido desarrolladas con licencia libre
por personas o instituciones de todo el mundo. Con el desarrollo
paralelo de internet, el número y la calidad de estas aplicaciones
crecería considerablemente.


Para facilitar la instalación y configuración del sistema, así como de
los miles de *paquetes de software* existentes (archivos en los se
distribuye un programa o programas junto a bibliotecas, documentación,
etc), nacieron distintas **distribuciones**
de GNU/Linux. Entre las primeras en aparecer (a principios de los años
90) se encuentran *RedHat* y *Debian*, distribuciones que crearon sus
propios sistemas de paquetes y de las que, a su vez, se derivaron
otras distribuciones. Nos centraremos en la última y en algunas de sus
derivaciones.

- [Debian](https://www.debian.org) es una distribución de GNU/Linux caracterizada por una amplia comunidad de miles de desarrolladores sin ánimo de lucro (algunas decenas de los cuales son [españoles](https://www.debian.org/international/spanish/desarrolladores)) que mantienen *decenas de miles de paquetes de software* libre. Una buena parte de ellos son programas de gran calidad, y todos ellos son directamente instalables en el sistema operativo desde repositorios en internet.  [Los paquetes se clasifican en secciones](https://packages.debian.org/stable/) temáticas, entre las que se encuentra la sección [*Mathematics*](https://packages.debian.org/stable/math/), que contiene una gran cantidad de paquetes. Además, otras secciones pueden ser interesantes para matemáticos: [*Science*](https://packages.debian.org/jessie/science/), [*Education*](https://packages.debian.org/jessie/education/), [*TeX*](https://packages.debian.org/jessie/tex/), [*Python*](https://packages.debian.org/jessie/python/),...  En la actualidad, Debian está disponible para nueve [arquitecturas de hardware](https://www.debian.org/ports/index.es.html#portlist-released), entre ellas los habituales procesadores Intel y AMD de ordenadores domésticos (32 y 64 bits).

- [Ubuntu](https://www.ubuntu.com/) es una distribución de GNU/Linux que fue derivada de Debian con el propósito de facilitar su uso por usuarios domésticos, centránose en las arquitecturas Intel y AMD y publicando versiones frecuentes: dos al año (abril y octubre, que son numeradas como X.04 y X.10, donde X es el año) y una versión estable cada dos años, llamada LTS (*Long Term Support*). Ubuntu tiene la ventaja de integrar los excelentes paquetes de software de Debian.

- [Guadalinex](http://www.guadalinex.org/) es la  distribución de GNU/Linux que publicó la Junta de Andalucía para centros docenes y para uso doméstico. Los motivos fueron de índole económica (independencia de proveedores de software y por tanto enorme ahorro de costes ante el despliegue de miles de ordenadores) pero también de carácter práctico (calidad de los entornos UNIX, ausencia de virus...) y relacionados con el impulso a la innovación tecnológica en el sector de las TIC andaluz (empresas andaluzas trabajando en el sector de los sistemas operativos). Originalmente, Guadalinex se derivó de Debian, pero las últimas versiones están basadas en Ubuntu.

## Los usos más habituales de GNU/Linux

### Software libre en el escritorio doméstico

Desde sus orígenes, GNU/Linux contó con programas de escritorio como
el entorno de ventanas *Xorg*, sobre el que se sitún entornos de
escritorio como **GNOME** (en el que se basa, por defecto, el
escritorio de Ubuntu) y *KDE*. Los escritorios configuran el entorno de
ventanas y le añaden funcionalidades como explorador de ficheros o
configuración del sistema. Otros programas con licencia libre como el
navegador web **Firefox**, el entorno de ofimática **Libre Office** (u
*Open Office*) o el programa de diseño y retoque fotográfico (de tipo
*Photoshop*) **Gimp** facilitaron el acceso a este sistema operativo para usuarios domésticos.
Aun así, GNU/Linux está lejos de ser un sistema operativo extendido entre el usuario medio.

> ## Ejercicio
>
> 1. Según la web especializada [*netmarketshare.com*](https://www.netmarketshare.com/operating-system-market-share.aspx), ¿cuál es el porcentaje de uso de sistemas GNU/Linux en ordendores personales?
> 2. ¿Puedes encontrar otros informes en internet que corroboren o contradigan los datos de la página web anterior?
{: .callout}

### Software libre en servidores web y en super-computación

También algunos de los
programas en los que se apoya internet, como el servidor de páginas
web *Apache* (del que depende más del 50% de las páginas web del
mundo).

> ## Ejercicios
>
> 1. ¿Cuál de las seis licencias creative commons se puede considerar como una licencia de tipo GPL?
> 2. ¿Cuál de las seis licencias creative commons se puede considerar como una licencia de tipo BSD?
> 3. La página web actual está basada en el diseño de [Software Carpentry](https://software-carpentry.org), un proyecto dedicado a la enseñanza de habilidades básicas de computación para científicos. Por cierto, el proyecto se centra en el Software libre. ¿A qué licencia está sujeto el material docente contenido en esta página web?
>
> > ## Soluciones
> >
> > 1. La  licencia "Creative Commons Atribución Compartir Igual" (CC-BY-SA) obliga a compartir los trabajos derivados con la misma licencia y, por tanto, es de tipo GPL.
> > 2. La  licencia "Creative Commons Atribución" (CC-BY) sólo obliga reconocer al autor original y, por tanto, es de tipo BSD.
> > 3. En la parte superior derecha de esta página se encuentra un enlace llamado *License*. En él se puede comprobar que este trabajo está sujeto a licencia CC-BY-SA.
> {: .solution}
>
{: .callout}
