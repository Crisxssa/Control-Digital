1.Estabilidad en sistemas discretos
Para esta clase se empezara a ver la estabilidad tanto en la funcion de LaPlace como en funcion de Z, observando la ubicacion de los polos circulo unitario (Z) como en el emisferio izquierdo.
Ademas vimos el test de jury y la forma de comprobar la estabilidad con este metodo

>1.1.🔑Estabilidad absoluta: Es estable cuando se tiene una salida limitada producto de una entrada limitada.

>1.1.1.🔑Espacio de LaPalece: Ubicaion de los polos, para el caso de un tiempon continuo, se habla de estabilidad al encontrarse todos los polos en el emisferio izquierdo (figura 1).

>1.1.2.🔑Espacio de Z: Ubicaion de los polos, para el caso de un tiempon discreto, se habla de estabilidad al encontrarse todos los polos dentro del circulo unitario (figura 2).

>1.2.🔑Test de Jury: Comprobacion matematica en base al denominador de funcion de transferencia en tiempo discreto (figura 3).

💡Ejemplo 1. Por ubicacion de polos\
Se tiene el sistema 

$<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=G\left( z \right) =  \frac{4}{z^{4}-7.8z^{2}+12.4z+3}"><img src="http://www.alciro.org/cgi/tex.cgi?G\left( z \right) =  \frac{4}{z^{4}-7.8z^{2}+12.4z+3}" title="G\left( z \right) =  \frac{4}{z^{4}-7.8z^{2}+12.4z+3}" border="0" /></a>$

4. Ejemplos
Si en algún caso pretende dar un ejemplo explicativo ya sea a través de texto o através de ecuaciones matemáticos, utilizar la palabra 'Ejemplo' seguido de una numeración consecutiva dentro de la clase. Utilice el emoji 💡 antecediendo la palabra.

5. Ecuaciones
Para la edición de ecuaciones debe utilizar la etiqueta '$$' al comienzo y final de la ecuación para que la ecuación quede centrada ocupando una línea. Si se quiere que la ecuación quede integrada en el texto debe utilizar la etiqueta '$' al comienzo y final de la ecuación. Las ecuaciones pueden ser editadas utilizando el código LATEX, en el siguiente enlace encuentran un editor de ecuaciones que les genera el código. http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp . Sin embargo hay muchas otras herramientas que pueden utilizar para esto.

💡Ejemplo 1: si se va a representar la ecuación de la ley de Ohm se puede mostrar así 
R
=
V
I
 o también,

R
=
V
I

6. Figuras
Todas las figuras que incluya deben ser generadas por ustedes, no utilizar las figuras de las presentaciones. Para incluir figuras puede seguir los siguientes pasos:

Primero escribimos .
Después escribimos, dentro de los corchetes, el texto alternativo. Este es opcional y solo entra en acción cuando no se puede cargar la imagen correctamente.
Después escribimos, dentro de los paréntesis, la ubicación del archivo (ya sea una url o una ubicación dentro de algun folder local). Se recomienda poner las imágenes en una carpeta que se llame imágenes dentro del repositorio github para que no tengan problemas al cargar las imágenes.
💡Ejemplo 2:

<p align="center">
<img src="https://github.com/user-attachments/assets/82230ecf-2b59-4650-96b3-fb1a859ed5e7" width="400" height="400">
 </p>

$$Figura 1. Plano de estabilidad(tiempo continuo)$$

<p align="center">
<img src="https://github.com/user-attachments/assets/8e2e79d0-eeac-4ff6-863d-02ffe018c3aa" width="400" height="400">
 </p>

$$Figura 2. Plano de estabilidad(tiempo discreto)$$

<p align="center">
<img src="https://github.com/user-attachments/assets/57eb6c8a-21b6-4be3-878e-8580416e5c2b" width="400" height="300">
 </p>

$$Figura 3. Matriz Test de JURY$$

Incluya la respectiva etiqueta a modo de descripción de la figura y mantenga numeración consecutiva para todas las figuras de la clase.

7. Tablas
En caso de necesitar la inclusión de tablas para organizar información se recomienda el uso de la herramienta del siguiente enlace https://www.tablesgenerator.com/markdown_tables , la cual permite organizar la información dentro de la tabla y genera el código markdown automáticamente:

💡Ejemplo 3:

Resultado	x = número de intentos hasta primer éxito
S	1
FS	2
FFS	3
...	...
FFFFFFS	7
...	...
Tabla 1. Tabla de ejemplo

Cada tabla debe llevar la etiqueta que describa su contenido y numeración consecutiva para todas las tablas

8. Código
Teniendo en cuenta que el curso requiere del desarrollo de código matlab, c, c++ u otro. Si requiere incluir pequeños segmentos de código en los apuntes hágalos de la siguiente manera:

💡Ejemplo 4:

var sumar2 = function(numero) {
  return numero + 2;
}
9. Ejercicios
Deben agregar 2 ejercicios con su respectiva solución, referentes a los temas tratados en cada una de las clases. Para agregar estos, utilice la etiqueta #, es decir como un nuevo título dentro de la clase con la palabra 'Ejercicios'. Cada uno de los ejercicios debe estar numerado y con su respectiva solución inmediatamente despues del enunciado. Antes del subtitulo de cada ejercicio incluya el emoji 📚

10. Conclusiones
Agregue unas breves conclusiones sobre los temas trabajados en cada clase, puede ser a modo de resumen de lo trabajado o a indicando lo aprendido en cada clase

11. Referencias
Agregue un subtítulo al final donde pueda poner todas las referencias consultadas incluyendo el origen o fuente de los ejercicios planteados. Tambien dentro del texto referencie los textos o artículos consultados y las figuras y tablas dentro de la explicación de las mismas.
