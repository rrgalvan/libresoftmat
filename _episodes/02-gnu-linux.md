---
title: "El sistema operativ GNU/Linux"
teaching: 15
exercises: 15
questions:
- "¿Qué es el software libre?"
- "¿Qué tipos de licencias libres existen?"
- "¿Existen licencias libres para documentos, vídeos y material
  multimedia"
objectives:
- Distinguir el software libre de aquél que no lo sea.
- Distinguir las propiedades de los distintos tipos de licencia libre.
- Saber dotar de licencia libre a un programa o a material multimedia.
keypoints:
- El hecho de que un programa sea libre depende del hecho de que su autor decida ceder a los usuarios una serie de libertades
- Esta cesión de libertades se debe cristalizar en una licencia
- Existen distintos tipos de licencias libres. Algunas exigen
  reconocer al autor original y otras exigen que los trabajos
  derivados siguan siendo libres
- Las licencias Creative Commons se suelen usar para publicar material multimedia con licencia libre
---

## Sistemas operativos

Un *sistema operativo* es un conjunto de programas que gestiona los recursos de hardware de un equipo informático y provee servicios a las aplicaciones o programas que son ejecutados. El sistema operativo, por tanto, encarga de enlazar las apicaciones ejecutadas por el usuario con el hardware de la máquina.

<center> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/dc/Operating_system_placement-es.svg/250px-Operating_system_placement-es.svg.png" alt="Sistema Operativo" style="width: 160px;"/> </center>

Según esta definición, no debe confundirse el sistema operativo con el
conjunto de herramientas que suele distribuirse junto a él, como
explorador de ficheros, navegador web o programas de configuración. En
efecto, éstas no son más que aplicaciones especializadas en
determinadas tareas y por tanto se colocan sobre el sistema operativo.

### Un poco de historia

La noción de Sistema Operativo surge en la década de los 50 y a lo
largo de los años 60 se introducen los conceptos fundamentales, entre ellos:

- Sistema *multiusuario*: aquél que ofrece servicio y procesamiento a múltiples
  usuarios de forma (aparentemente) simultánea. Estos usuarios pueden
  tener distintos privilegios de acceso a los recursos del sistema.
- Sistema *multitarea*: aquél que permitie que varios procesos o aplicaciones se
  ejecuten (aparentemente) al mismo tiempo, compartiendo uno o más
  procesadores.

En los años 70 aparece el sistema operativo *UNIX*, que de una u otra
forma ha marcado a los sistemas operativos actuales. Dotado de
características multiusuario y multitarea, se extendió rápidamente, en
distintas versiones que se distribuyeron en universidades y compañías
gubernamentales de Estados Unidos. El sistema UNIX no tenía licencia
libre, pero la Universidad de Berkley mantuvo una versión conocida
como *BSD*, que sería más adelante publicada con una licencia libre.

En la década de 1980 un grupo de académicos y programadores
voluntarios, liderados por Richard M. Stallman y cristalizados en
torno a la *Free Software Foundation*, comenzaron un proyecto para
crear el primer sistema operativo completamente libre, de tipo UNIX. A
este proyecto se le llamó *GNU* (acrónimo recursivo: GNU = GNU's Not
UNIX).

En los años 90, el sistema GNU estaba maduro con la excepción de su
pieza fundamental: el núcleo del sistema operativo. En 1991, un
estudiante llamado Linus Torvalds desarrolló un núcleo para
computadoras al que llamó *Linux* y dotó de licencia GPL. Este núcleo
fue integrado por el proyecto GNU, dando pie al sistema operativo
*GNU/Linux* (aunque, por muchas personas, es conocido simplemente como
Linux).

De forma paralela, en los años 80 apareció un sistema llamado
NeXTSTEP, basada en un sistema UNIX BSD proveniente de los
años 1970. En los años 1990, Apple, después de años de éxitos
fabricando ordenadores con un sistema operativo multitarea pero
monousuario, llamado Mac OS, necesitaba una renovación. En 1997 compró
NeXTSTEP y nació así el sistema UNIX actual que es llamado *Mac OS X*.

Simultáneamente, en la década de 1980, Microsoft lanzó el sistema
operativo MS-DOS, influenciado por UNIX, del que heredaba algunas
características como el uso de subdirectorios y de tuberías. Orientado
a ordenadores personales, MS-DOS no contaba con características de
multitarea y multiusuario. Estas características se incluyeron
paulatinamente, a lo largo de las décadas de 1990 y 2000, en los
sitemas Windows, que sustituyeron a MS-DOS.

## El sistema operativo GNU/Linux

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
