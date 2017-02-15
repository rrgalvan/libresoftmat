---
title: "Software Libre en Matemáticas"
teaching: 15
exercises: 15
questions:
- "¿Qué es el software libre?"
- "¿Qué tipos de licencias libres existen?"
- "¿Existen licencias libres para documentos, vídeos y material
  multimedia"
objectives:
- Distinguir el software libre de aquél que no lo sea.
- Distinguir las propiedades de los distintos tipos de licencia libre
- Saber dotar de licencia libre a un programa o a material multimedia.
keypoints:
- El hecho de que un programa sea libre depende del hecho de que su autor decida ceder a los usuarios una serie de libertades
- Esta cesión de libertades se debe cristalizar en una licencia
- Existen distintos tipos de licencias libres. Algunas exigen
  reconocer al autor original y otras exigen que los trabajos
  derivados siguan siendo libres
- Las licencias Creative Commons se suelen usar para publicar material multimedia con licencia libre
---

- Prueba $\LaTeX$

- Prueba $$\LaTeX$$

## El software libre

![Mapa conceptual del software libre](https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/Mapa_conceptual_del_software_libre.svg/800px-Mapa_conceptual_del_software_libre.svg.png)I

- **¿Qué es el software libre?** El término *software libre* se refiere
  al conjunto programas informáticos que, por elección manifiesta de
  su autor, puede ser *utilizado* libremente (con cualquier fin),
  *estudiado y modificado*, *redistribuido* y *publicado*
  (eventualmente, con adaptaciones o mejoras). En
  la práctica, para que un programa pueda ser considerado libre, es
  indispensable que su *licencia* certifique cada una de estas
  características (o libertades). A este tipo de licencias se les
  llama *licencia libre*.

- **¿Cuándo nació este concepto?** La definición del software libre
  coincidió con el nacimiento del movimiento de software libre,
  encabezado por Richard M. Stallman y la consecuente fundación en 1985
  de la *Free Software Foundation*, para el desarrollo de aplicaciones
  informáticas en las que la libertad del usuario sea el *propósito
  ético* fundamental.

- **¿Qué relación hay entre software libre y software gratuito?** De
  la definición de software libre se deduce que éste puede ser copiado
  y distribuido gratuitamente. No obstante, existen modelos de negocio
  basados en la venta de software libre (por ejemplo una persona puede
  comprar software libre si éste viene acompañado de soporte técnico u
  otras ventajas). Por otro lado, no todo el software gratuito
  es libre (obviamente). Con frecuencia, se denomina *freeware* al software
  gratuito que no es libre, debido a que no garantiza todas las libertades
  que fueron señaladas en su definición.

- **¿Qué tipos de licencias libres existen?** Según el tipo de
  restricciones que imponen a la redistribución del código, podemos
  agrupar las licencias libres en los siguientes grupos:
  - *Dominio público*: Software que está sujeto a licencia, pues el
    autor ha donado sus derechos a toda la humanidad, o bien los
    derechos de autor ya han expirado. Por tanto, cualquiera puede
    conocer y hacer uso de este tipo de software.
  - *BSD* (Berkley Software Distribution). Es un tipo de licencias muy
    cercanas al dominio público y por tanto muy permisivas, pues la
    única restricción que imponen es para la modificación y
    redistribución del software es el *reconocimiento al autor
    original*. En particular, permiten la redistribución del código
    con una licencia que no sea libre.
  - *GPL* (GNU Public License). Es un tipo de licencia libre
    (introducida por la *free software foundation*) que es menos
    permisiva que las anteriores pues, al reconocimiento de la autoría
    del software, añaden la obligación de mantener el mismo tipo de
    licencia en los trabajos derivados. Este último tipo de "mecanismo
    legal" es conocido como *copyleft* (en un juego de palabras con el
    concepto de *copyright*).

- **¿Existen licencias libres para documentos, vídeos y material
  multimedia?** Existen distintos tipos de licencias orientadas a la
  publicación de material multimedia. Las más famosas son las
  conocidas como **Creative Commons**. Creative Commons publica una
  familia de licencias, que pueden ser seleccionadas para otorgar una
  serie de derechos concretos sobre el material publicado a terceras
  personas bajo ciertas condiciones. De esta forma, se consiguen
  licencias de tipos similares a los grupos de licencias descritos
  anteriormente. También se incluyen algunas condiciones (prohibición
  de publicar trabajos derivados y prohibición de uso con fines
  comerciales) que dan lugar a que *no todas las licencias Creative
  Commons son libres*, en un sentido estricto. Combinando estas
  condiciones, se definen seis licencias (además del dominio público),
  que se sumarizan en la siguiente gráfica. Se pueden consultar más
  detalles, por ejemplo, en la
  [página de Wikipedia](https://es.wikipedia.org/wiki/Licencias_Creative_Commons). Por
  cierto, todas las páginas de wikipedia están dotadas de una licencia
  libre, en concreto "Creative Commons Atribución Compartir Igual"
  (CC-BY-SA), que es una licencia de tipo *copyleft*.  <center> <img
  src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e9/Creative_Commons_Semaforoa.svg/800px-Creative_Commons_Semaforoa.svg.png"
  alt="Drawing" style="width: 400px;"/> </center>

- **¿Cómo publicar con licencia libre un programa u otro tipo de
  material?** Para dotar a un programa (o a material multimedia) de
  una licencia concreta, es suficiente indicar claremente (por
  ejemplo, en un archivo llamado *COPYRIGHT* que esté contenido en
  la carpeta principal del programa) el nombre del autor o autores
  junto a la licencia elegida. Es recomendable incluir el texto
  completao de la licencia (o, al menos, un enlace al lugar de
  internet donde se puede encontrar el texto).

- **¿Es suficiente con publicar un trabajo en internet para que éste
  tenga licencia libre?** No. Para que un programa o un documento
  multimedia tenga licencia libre es necesario especificar el nombre
  del autor y cuáles son las libertades que se ceden al usuario (a
  través de una licencia). En caso contrario, el programa o el
  documento tendrá todos los derechos reservados.


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
