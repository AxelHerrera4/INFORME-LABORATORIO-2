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

![](https://github.com/AxelHerrera4/INFORME-LABORATORIO-2/blob/1b244cbf74fcb54ed945d27fe93aecf23668e3ff/imagenes/mapa%20del%20lab2.png)

3) Explicacion del procedimiento

Armamos el circuito en tikercard para la sumulacion del circuito, el cual este esta formado por dos fuentes de voltaje de 18 y 5 voltios, tambien está compuesta de 5 resitencias, de 820 ohm, 1.2kohm, 390 ohm, 1kohm, 2.2k ohm.

Se identifica las tres mallas, o las trayectorias cerradas que no encierran ningun otro elemento del circuito, por lo cual tenemos la malla 1 formada por la resistencia de 820ohm y 1kohm, la segunda malla esta compuesta por 1.2kohm y 2.2kohm y la tercera por una resitencia de 390 ohm. Su analisis sera por medio de las leyes de voltaje de kirchhoff, el cual dice que la suma algebraica de las caidas de voltaje en un circuito cerrado o malla es igual a cero.

Prtimeramente se va a rmar el circuito en el simulador, y conseguimos los voltajes y corrientes mediante la medicion con el multimetro en las conexiones que se deben realziar voltaje en paraleleo y corrientes en serie. En los calculos se debe cocalculas el voltaje total el que aliemtna a todo el circuito y despues su intensidad de corrientes, y asi obtener los voltajes y corrientes de cada malla establecida.

![](imagenes/circuito.png)


Calculo de la priemera malla:

18 V-V_R1-V_R2=0
18-820 I-1000(I_1-I_2 )=0
18-1820 I_1+1000I_2=0
1820 I_1=1000I_2+18
I_1=1000/1820 I_2+18/1820


calculo de la segunda malla:

-V_R2-V_R3-V_R4=0
-1000(I_2-I_1 )-1200I_2-2200(I_2-I_3 )=0
-4400I_2+1000I_1+2200I_3=0





Calculo de la tercera malla:

-V_R4-V_R5-5=0
2200(I_3-I_2 )+390I_3+5=0
2590I_3-2200I_2+5=0
2590I_3=2200I_2-5
I_3=2200/2590 I_2-5/2590


![](imagenes/voltaje.png)



intensidad 2:

-4400I_2+1000(1000/1820 I_2+18/1820)+2200(2200/2590 I_2-5/2590)=0
-4400I_2+549.45I_2+9.89+1868.72I_2-4.24=0
(-4400+549.45+1868.72) I_2=4.24-9.89
-1981.82I_2=-5.64
I_2=(-5.64)/(-1981.82)=2.84 mA

intensidades restantes:

I_1=1000/1820 (2.84*10^(-3)  )+18/1820
I_1=11.45 mA
I_3=2200/2590 (2.84*10^(-3) )-5/2590
I_3=0.488 mA 



![](imagenes/intensidad.png)


Tabla de resultados obetenidos:


![](imagenes/tabla.png)



4)Calculo de error

No existe error alguno por lo que se obtuvo los mismos resultados por lo tanto su porcentaje de error es cero.

![](imagenes/error_tabla.png)




5) video.



6) Conclusiones

-El calculo de mallas nos ayuda identificar, cuanta energia fluye dentro de una parte del circuito.

-Mediante la simulación virtual logramos observar al momento de conectar el multimetro en serie en cada punto, ver un sucede con la intensidad en cada malla ya que está formado por 3 mallas y cada uno tiene una intensidad distinta de los demás. También logramos ver qué sucede con los voltajes en cada resistencia del mismo la cual la sumatoria en cada malla es cero.

- la ley de corrientes de Kirchoff se cumple para cualquier malla del circuito, aplicando cualquier método de resolución

7) Bibliografia.

Mecafenix, I. (2020, 22 junio). Ley de voltaje de Kirchhoff. Ingeniería Mecafenix. Recuperado 22 de noviembre de 2021, de https://www.ingmecafenix.com/electronica/ley-de-voltaje-de-kirchhoff/

El método de la corriente de malla (artículo). (s. f.). Khan Academy. Recuperado 22 de noviembre de 2021, de https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-mesh-current-method

Salazar, A. (2012). 3. Análisis Por Nodos Y Mallas 3.1. 35–62. http://wwwprof.uniandes.edu.co/~ant-sala/cursos/FDC/Contenidos/03_Analisis_por_Nodos_y_Mallas.pdf

Secundario, N., & Educación, M. (n.d.). Guía de estudio 7 : Mallas y Nodos. Instituto Nacional de Educacion Tecnológica, 1–9. http://www.inet.edu.ar/wp-content/uploads/2020/07/ELECTRONICA_Gu--a07-Mallas-y-Nodos.pdf




