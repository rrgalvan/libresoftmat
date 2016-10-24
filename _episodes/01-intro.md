---
title: "Software Libre en Matemáticas"
teaching: 15
exercises: 5
questions:
- "¿Qué software estudiaremos en este curso? ¿Por qué software libre?"
objectives:
- Objetivo 1
- Objetivo 2
keypoints:
- Clave 1
- Clave 2
---

En este apartado se listarán los distintos módulos que componen la asignatura **Software en Matemáticas** impartida en el Máster en Matemáticas, dentro de la Universidad de Cádiz. En todos ellos se estudian programas matemáticos, orientados a distintas áreas (sistemas operativos, aplicaciones de escritorio, programas de cálculo simbólico o numérico, edición de textos matemáticos..., *e-learning*,...) con un denominador común: todos ellos tienen **licencia libre**.

## Ficha de la asignatura


> ## Contenidos
> La asignatura se organizará en los módulos siguientes:
>
> 1. El **software libre y el sistema Linux**: instalación, administración y uso cotidiano *(temas 1 y 2)*.
> 2. Introducción a **sistemas de cálculo** con software libre. Resolución de modelos matemáticos usando Maxima y/o Python (*temas 3 y 4)*.
> 3. Introducción a **LaTeX**. Manejo del LaTeX. Beamer: Elaboración y presentación de un trabajo, tesis o conferencia (*temas 5 y 6)*.
> 4. Curso de **Moodle**. Creación de ficheros "scorm" *(temas 7 y 8)*.
>
> Estos cuatro módulos pretenden barrer una amplia gama de software y herramientas informáticas relacionadas con las matemáticas, incluyendo el punto de vista de su uso en labores profesionales y, en particular, en la *docencia* y la *investigación* en matemáticas. Todo el software estudiado tiene un denominador común: su *licencia libre* que, como veremos, ofrece al usuario libertad para copiarlo y utilizarlo sin restricciones significativas.
{: .callout}

Se puede acceder a la información completa sobre la asignatura través de su la información académica del máster:
[http://masteres.ugr.es/doctomat/pages/info_academica/guias_docentes](http://masteres.ugr.es/doctomat/pages/info_academica/guias_docentes). A continuación, se lista la asignatura general de la asignatura, tal y como se la información académica. Además, en algunos de los módulos anteriores se, ofrecerá bibliografía específica.

> ## Bibliografía general
>
> - William Stallings Sistemas operativos : aspectos internos y principios de diseño , Edit. Prentice-Hall, 2005.
> - Andrew S. Tanenbaum Redes de Computadoras, Edit. Prentice-Hall, 1998.
> - "Getting Started with Ubuntu", [https://ubuntu-manual.org](https://ubuntu-manual.org)
> - Python 3 tutorial, [https://docs.python.org/3/tutorial/index.html](https://docs.python.org/3/tutorial/index.html)
> - A. B. Downey, Think python, Green Tea Press, [http://greenteapress.com/wp/think-python](http://greenteapress.com/wp/think-python)
> - Leslie Lamport. LATEX: A Document Preparation System. Addison-Wesley, Reading, Massachusetts, segunda edición, 1994.
> - Michel Goossens, Frank Mittelbach and Alexander Samarin. The LATEX Companion. Addison-Wesley, Reading,  Massachusetts, 1994
> - [http://exelearning.net/exelearning-2-1-manual-tutorial](http://exelearning.net/exelearning-2-1-manual-tutorial)
> - [https://docs.moodle.org/31/en/Main_page](https://docs.moodle.org/31/en/Main_page)
{: .callout}

## El software libre

![Mapa conceptual del software libre](https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/Mapa_conceptual_del_software_libre.svg/800px-Mapa_conceptual_del_software_libre.svg.png)I

- **¿Qué es el software libre?** El término software libre se refiere
  al conjunto programas informáticos que, por elección manifiesta de
  su autor, puede ser *utilizado* libremente (con cualquier fin),
  *estudiado y modificado*, *redistribuido* y *publicado*
  (eventualmente, con adaptaciones o mejoras). En
  la práctica, para que un programa pueda ser considerado libre, es
  indispensable que su *licencia* certifique cada una de estas
  características (o libertades). A este tipo de licencias se les
  llama *licencia libre*.

- **¿Qué relación hay entere software libre y software gratuito?** De
  la definición de software libre se deduce que éste puede ser copiado
  y distribuido gratuitamente. No obstante, existen modelos de negocio
  basados en la venta de software libre (por ejemplo una persona puede
  comprar software libre si éste viene acompañado de soporte técnico u
  otras ventajas). Por otro lado, no todo el software gratuito
  es libre (obviamente). Con frecuencia, se denomina *freeware* al software
  gratuito que no es libre, debido a que no garantiza todas las libertades
  citadas anteriormente.

- **¿Cuando nació este concepto?** La definición del software libre
  coincidió con el nacimiento del movimiento de software libre,
  encabezado por Richard Stallman y la consecuente fundación en 1985
  de la *Free Software Foundation*, con la intención de colocar la
  libertad del usuario informático como propósito ético fundamental.


Un programa informático es software libre si otorga a los usuarios todas estas libertades de manera adecuada. De lo contrario no es libre. Existen diversos esquemas de distribución que no son libres, y si bien podemos distinguirlos sobre la base de cuánto les falta para llegar a ser libres, su uso bien puede ser considerado contrario a la ética en todos los casos por igual.2

El software libre suele estar disponible gratuitamente, o al precio de coste de la distribución a través de otros medios; sin embargo no es obligatorio que sea así, por lo tanto no hay que asociar «software libre» a «software gratuito» (denominado usualmente freeware), ya que, conservando su carácter de libre, puede ser distribuido comercialmente. Análogamente, el software gratis o gratuito incluye en ocasiones el código fuente; no obstante, este tipo de software no es «libre» en el mismo sentido que el software libre, a menos que se garanticen los derechos de modificación y redistribución de dichas versiones modificadas del programa.

Tampoco debe confundirse software libre con «software de dominio público». Éste último es aquel que no requiere de licencia, pues sus derechos de explotación son para toda la humanidad, porque pertenece a todos por igual. Cualquiera puede hacer uso de él, consignando su autoría original. Este software sería aquel cuyo autor lo dona a la humanidad o cuyos derechos de autor han expirado. Si un autor condiciona su uso bajo una licencia, por muy débil que sea, ya no es del dominio público.


## Compilación con GNU C++

Con frecuencia se utilizan editores especializados o entornos integrados para la compilación de ficheros C++, que permiten combinar la edición, compilación y ejecución de los programas en entornos de escritorio. Muchos de estos entornos permiten utilizar proyectos de compilación en formatos *Make* y/o *CMake*.

>
> ## Algunos editores y entornos integrados recomendados
>
>  Los siguientes editores tiene en común tener una licencia libre y ser multi-plataforma (GNU/Linux, MacOS, Windows). Se presentan de menor a mayor facilidad de uso (definida como pendiente inicial de la curva de aprendizaje).
>
> - [Code::Blocks]
> - [Eclipse]
> - [Emacs]
> - [Vim]
{: .discussion}

En vez de optar por un entorno integrado, los conceptos serán independientes del editor utilizado. Se incluye así la posibilidad de utilizar editores (como [Emacs], [Vi] o [Nano]) dentro de terminales UNIX. Este caso es usual en sesiones remotas (en entornos UNIX que son ejecutados en servidores remotos).

>
> ## Edición del programa `holamundo.cpp`
>
> Ejercicio: utilizando la consola UNIX:
>
> 1. Crear, dentro del directorio de inicio del usuario, un directorio llamado `proyectos` y dentro de él uno nuevo llamado `c++`
> 2. Crear, dentro del directorio `c++`, un fichero llamado `holamundo.cpp` que contenga el código C++ que fue introducido anteriormente
>
{: .challenge}

Antes de procesar el programa anterior, debemos asegurarnos de contar con un compilador C++ adecuado. Aquí nos centraremos en el compilador GNU C++, que forma parte de [GCC] (GNU Compiler Collection).

>
> ## Instalación del compilador GNU C++
>
> - GNU C++ tiene licencia libre y puede instalarse en todos los sistemas operativos usuales.
> - En entornos GNU/Linux basados en Debian (como Ubuntu), es suficiente teclear en la consola UNIX la siguiente orden (que instalará además otras herramienteas como el compilador GNU C o la herramienta de compilación Make:
>
> ~~~
> sudo apt-get install build-essential
> ~~~
> {: .bash}
{: .discussion}

Utilizando este compilador y suponiendo que nos encontramos, dentro de la consola UNIX, en el directorio c++, podemos compilar el programa `holamundo.cpp` mediante la siguiente orden:

> ~~~
> g++ holamundo.cpp -o holamundo
> ~~~
> {: .bash}

Como resultado, contaremos con un programa ejecutable llamado `holamundo`, situado en el directorio actual. Por supuesto, el nombre `holamundo` puede modificarse o, incluso, la opción `-o holamundo` puede ser eliminada (y en este caso, el programa resultante se llamará `a.out`). A continuación, podemos ejecutar el programa de la siguiente forma,

> ~~~
> ./holamundo
> ~~~
> {: .bash}

obteniendo el siguiente resultado:

> ~~~
> ¡Hola mundo!
> ~~~
> {: .output}

>
> ## Otras opciones de compilación
>
> El compilador `g++` admite muchas otras opciones, entre ellas:
>
> - `-l`: Utilizar una biblioteca
> - `-I`: Explicitar un directorio desde donde incluir ficheros
> - `-Wall`: Al compilar, mostrar tanos mensajes de aviso (*warnings*) como sea posible (para poder localizar posibles errores).
>
> Por ejemplo, consideremos el siguiente programa, al que llamaremos `ejemplo2.cpp`
>
> ~~~
> #include <iostream>
> #include <cmath> // Biblioteca matemática de C
> int main()
> {
>   // Declaramos dos números en doble precisión.
>   double x, y=3; // A y le asignamos un valor
>   std::cout << "La raíz de " << y << " es " << sqrt(y) << std::endl;
> }
> ~~~
> {: .cpp}
>
> En él se calcula la raíz de *y=3*. Se declara una variable, *x*, que no se utiliza, lo que podría ser un indicio de errores en futuras versiones.
> Si compilamos con la opción `-Wall`, el compilador nos advertirá de este heho:
>
> ~~~
> g++ -Wall ejemplo1 -o ejemplo1
> ~~~
> {: .cpp}
>
> ~~~
> math.cpp: In function ‘int main()’:
> math.cpp:7:10: warning: unused variable ‘x’ [-Wunused-variable]
>    double x, y=3; // A y le asignamos un valor
>           ^
> ~~~
> {: .output}
{: .discussion}

## Tipos de datos, variables, funciones y aritmética

La sintaxis básica de C++ está basada en C con algunas extensiones, como muestran el siguiente ejemplos. Para conocer más detalles, puede consultarse un tutorial como el contenido en el capítulo 2 de [[B. Stroustrup (4th edition)]]

> ## Un ejemplo más extenso
> En el siguiente ejemplo se muestra un programa C++ que define dos funciones y, utilizándolas junto a un bucle *for*, las aplica a un rango de valores
>
> ~~~
> #include <iostream>
>
> // Calculate the square of double precision floating-point number
> double square(double x)
> {
>   return x*x;
> }
>
> // Print a formated string showing the square of x
> void print_square(double x)
> {
>   std::cout << "The square of " << x
> 	    << " is: " << square(x) << std::endl;
> }
>
> int main()
> {
>   int nSquares = 5;
>   double x=1;
>   for (int i=0; i<nSquares; i++)
>     {
>       print_square(x);
>       x++;
>     }
> }
>
> ~~~
> {: .cpp}
{: .callout}

El resultado debe ser el siguiente:

> ~~~
> The square of 1 is: 1
> The square of 2 is: 4
> The square of 3 is: 9
> The square of 4 is: 16
> The square of 5 is: 25
> ~~~
> {: .output}

En el programa anterior se pueden observar algunas diferencias con el clásico lenguaje C. Entre ellas, la posibilidad de declarar e inicializar las variables en el cuerpo de las funciones. Por ejemplo, en el bucle `for` anterior, se declara y se utiliza directamente la variable que actuará como contador (`int i=0`).

> ## Variantes del programa anterior
>
> Como ejercicio, se propone programar una variante del programa anterior que:
>
> - Sustituya la función `square` por $$f(x)=\cos(x^2+1)$$
> - Sustituya el bucle `for` por un bucle `while`
>
{: .challenge}


[Code::Blocks]: http://www.codeblocks.org
[Eclipse]: [Code::Blocks] http://www.eclipse.org/downloads/packages/eclipse-ide-cc-developers/marsr
[Emacs]: https://www.gnu.org/software/emacs
[Vim]: http://www.vim.org
[Vi]: http://www.vim.org
[Nano]: https://www.nano-editor.org
[GCC]: http://gcc.gnu.org
[B. Stroustrup (4th edition)]: http://www.stroustrup.com/4th.html
