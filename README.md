1.Estabilidad en sistemas discretos
Para esta clase se empezara a ver la estabilidad tanto en la funcion de LaPlace como en funcion de Z, observando la ubicacion de los polos circulo unitario (Z) como en el emisferio izquierdo.
Ademas vimos el test de jury y la forma de comprobar la estabilidad con este metodo

>1.1.🔑Estabilidad absoluta: Es estable cuando se tiene una salida limitada producto de una entrada limitada.

>1.1.1.🔑Espacio de LaPalece: Ubicaion de los polos, para el caso de un tiempon continuo, se habla de estabilidad al encontrarse todos los polos en el emisferio izquierdo (figura 1).

>1.1.2.🔑Espacio de Z: Ubicaion de los polos, para el caso de un tiempon discreto, se habla de estabilidad al encontrarse todos los polos dentro del circulo unitario (figura 2).

>1.2.🔑Test de Jury: Comprobacion matematica en base al denominador de funcion de transferencia en tiempo discreto (figura 3).

💡Ejemplo 1. Por ubicacion de polos\
Se tiene el sistema <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=G\left( z \right) =  \frac{4}{z^{4}-7.8z^{2}+12.4z+3}"><img src="http://www.alciro.org/cgi/tex.cgi?G\left( z \right) =  \frac{4}{z^{4}-7.8z^{2}+12.4z+3}" title="G\left( z \right) =  \frac{4}{z^{4}-7.8z^{2}+12.4z+3}" border="0" /></a>\
Evaluando la estabilidadd conn MATLAB {pzmap("nombre de la variable"))} al polinomio caracteristico (denominador)\
Se obtiene los polos <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=z= 5, z=3, z=0.2"><img src="http://www.alciro.org/cgi/tex.cgi?z= 5, z=3, z=0.2" title="z= 5, z=3, z=0.2" border="0" /></a> (inestable por estar fuera del circulo unitario)\
Se comprueba con el codigo root ("nombre de la variable") en MATLAB

💡Ejemplo 2.\
Se tienen los polos <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=z= 0.5, z=0.8, z=0.2"><img src="http://www.alciro.org/cgi/tex.cgi?z= 0.5, z=0.8, z=0.2" title="z= 0.5, z=0.8, z=0.2" border="0" /></a> \
Ya se entiende que estan dentro del circulo unitario, es estable el sitema

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


