# INFORME-LABORATORIO-2
1) OBJETIVOS

Objetivo General: 

-Comprobar experimentalmente el Análisis de Mallas.


Objetivos Especificos:

-Realizar la medicion de los elementos de las respectivas mallas del circuito
-Ideetnificar cuales son las mallas
-Simular, analizar y comparar los valores obtenidos dentro del circuito armado.

2) Marco Teórico


El análisis de mallas se basa en el cálculo de las diversas magnitudes que se encuentran dentro del circuito, también trata sobre identificar cuales son las mallas, por lo tanto, se define una malla como el camino cerrado que forman dos o mas ramas de un circuito. En una malla la suma de todas las tensiones con su respectivo signo, estas son determinadas por el hecho de que son entradas o salidas, son iguales a cero, que es un principio de la ley de Kirchhoff de las mallas. Una malla también se puede definir como una trayectoria cerrada que no encierra dentro de sí a ningún elemento del circuito.

Para el análisis se aplica LVK que son la ley de voltajes de Kirchhoff para expresar voltajes en función de corrientes, a un conjunto de lazos para encontrar todas las corrientes del lazo, y de ahí partir a la obtención de las corrientes de la rama. LVK dice que la suma algebraica de las caídas de voltaje en un circuito cerrado o mall es igual a cero

El tipo de circuito que tenemos y la forma de las mallas, se pueden tener muchas posibilidades de conexión de las fuentes:

•	De corriente controladas
•	De voltaje independientes
•	De voltaje controladas
•	De corriente independientes no compartidas por varias mallas
•	Independientes compartidas por varias mallas


Existe un método llamado, general o por inspección, el cual el número mínimo de lazos independientes que hay que definir para tener un sistema de ecuaciones linealmente independientes que se deben tener está dado por:


    #lazos independientes= #ramas - #nodos +1

El método de la corriente de lazo es una variación del método de la corriente de malla, un lazo es cualquier trayectoria cerrada alrededor de un circuito. Para formar un lazo, se comienza en la terminal de algún componente y se traza un camino a través de elementos conectados hasta llegar nuevamente al punto de partida.
Usamos las mallas de un circuito para generar las ecuaciones establecidas de LVK. La corriente de lazo designa una corriente que fluye únicamente alrededor de un lazo. 


3) Explicacion del procedimiento

Armamos el circuito en tikercard para la sumulacion del circuito, el cual este esta formado por dos fuentes de voltaje de 18 y 5 voltios, tambien está compuesta de 5 resitencias, de 820 ohm, 1.2kohm, 390 ohm, 1kohm, 2.2k ohm.

Se identifica las tres mallas, o las trayectorias cerradas que no encierran ningun otro elemento del circuito, por lo cual tenemos la malla 1 formada por la resistencia de 820ohm y 1kohm, la segunda malla esta compuesta por 1.2kohm y 2.2kohm y la tercera por una resitencia de 390 ohm. Su analisis sera por medio de las leyes de voltaje de kirchhoff, el cual dice que la suma algebraica de las caidas de voltaje en un circuito cerrado o malla es igual a cero.

Prtimeramente se va a rmar el circuito en el simulador, y conseguimos los voltajes y corrientes mediante la medicion con el multimetro en las conexiones que se deben realziar voltaje en paraleleo y corrientes en serie. En los calculos se debe cocalculas el voltaje total el que aliemtna a todo el circuito y despues su intensidad de corrientes, y asi obtener los voltajes y corrientes de cada malla establecida.



4)Calculo de error.


5) video.


6) Conclusiones

-El calculo de mallas nos ayuda identificar, cuanta energia fluye dentro de una parte del circuito

7) Bibliografia.

Mecafenix, I. (2020, 22 junio). Ley de voltaje de Kirchhoff. Ingeniería Mecafenix. Recuperado 22 de noviembre de 2021, de https://www.ingmecafenix.com/electronica/ley-de-voltaje-de-kirchhoff/

El método de la corriente de malla (artículo). (s. f.). Khan Academy. Recuperado 22 de noviembre de 2021, de https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-mesh-current-method

Salazar, A. (2012). 3. Análisis Por Nodos Y Mallas 3.1. 35–62. http://wwwprof.uniandes.edu.co/~ant-sala/cursos/FDC/Contenidos/03_Analisis_por_Nodos_y_Mallas.pdf

Secundario, N., & Educación, M. (n.d.). Guía de estudio 7 : Mallas y Nodos. Instituto Nacional de Educacion Tecnológica, 1–9. http://www.inet.edu.ar/wp-content/uploads/2020/07/ELECTRONICA_Gu--a07-Mallas-y-Nodos.pdf




