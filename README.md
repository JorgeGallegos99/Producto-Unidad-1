## Producto Unidad 1
## Informe
## 1. PLANTEAMIENTO DEL PROBLEMA

<p style="text-align: justify;">   Dentro de los circuitos digitales es necesario poder interpretar y analizar condiciones y situaciones planteadas para la implementación de un circuito. En los circuitos propuestos se explica un evento determinado con parámetros en los que se desarrolla, son estos los puntos que se deben analizar y representar por medio de planteamiento de variables de entrada y salida, resolución de tablas de verdad, obtención de funciones, simplificación y finalmente el diseño y la implementación optimizada y requerida para cada circuito en los simuladores y laboratorios virtuales que sirven para representar estos circuitos.Además de todos los procesos anteriores, es necesario realizar la ejecución de uno de los circuitos planteados en la plataforma App Inventor, con las mismas características que posea la tabla de verdad resultante del análisis.</p>

## 2. OBJETIVOS

**OBJETIVO GENERAL**

<p style="text-align: justify;">Resolver tres tipos de circuitos combinacionales con diferentes condiciones cada uno, mediante el análisis e implementación utilizando simuladores virtuales de circuitos digitales con las diferentes compuertas, para verificar su funcionamiento además en App Inventor realizar uno de los tres circuitos. #.</p>

**OBJETIVOS ESPECÍFICOS**

-Analizar los circuitos combinacionales sus funciones de entrada y salida, tablas de verdad y el circuito que proponga la solución al problema.

-Utilizar los simuladores virtuales, para la implementación de las funciones de salidas que forman el circuito.

-Implementar el problema número tres con la utilización de compuertas Nor en el simulador virtual de circuitos digitales.

-Crear un programa en App Inventor capaz de resolver uno de los tres problemas propuestos.

## 3. ESTADO DEL ARTE

**CGACLC: Mejora del algoritmo genético a través de la agrupación para el diseño de circuitos lógicos combinacionales**

<p style="text-align: justify;"> Se plantea un nuevo método basado en algoritmos genéticos para el diseño de circuitos lógicos combinacionales. En este método se adopta el algoritmo k-means para optimizar el algoritmo genético con el objetivo de aumentar la eficiencia y reducir el costo de producción. CGACLC da como resultado una optimización del número de elementos del circuito a nivel     de puerta y el recuento de transistores en comparación con los algoritmos evolutivos ya propuestos.

**Autores:** 

- Zahra Alidousti

Departamento de ingeniería informática, Universidad de Isfahan, Isfahan, Irán
- Mohammad Ehsan Basiri

Departamento de Ingeniería, Universidad Shahrekord, Shahrekord, Ira

**Fecha y lugar de publicación:**

Fecha: 19-20 de abril del 2017
En la  tercera Conferencia Internacional sobre Reconocimiento de Patrones y Análisis de Imágenes (IPRIA)
Shahrekord, Iran

Este árticulo guarda relación con los problemas planteados, en que buscan resolver los circuitos al igual que se resolvieron los problemas pero ellos crean  un nuevo algoritmo usando lo conocido y se basan en la génetica de las compuertas con la finalidad de que la resolucion d estos circuitos se vuelva mas sencilla y se optimize el diseño de circuitos.

**Diseño de circuitos combinacionales de preservación de paridad utilizando compuerta reversible

En este árticulo se diseña circuitos combinacionales para la preservacion de paridad mediante una puerta reversible que es creada, con el fin de buscar  la detección de errores en los sistemas digitales convencionales con la verificación de paridad es ahi donde utilizan la puerta logica llamada SMS integrada que tiene la propiedad de preservación de paridad y produce todas las puertas booleanas primitivas. 

**Autores:**

-Trailokya Nath Sasamal
Departamento de Electrónica y Comunicación, NIT Kurukshetra-136119, India
-Anand Mohan
Departamento de Electrónica y Comunicación, NIT Kurukshetra-136119, India
-Ashutosh Kumar Singh
Departamento de Aplicaciones Informáticas, NIT Kurukshetra-136119, India

**Fecha y lugar de publicación:**
Fecha: 14-16 Octubre del 2016
Lugar: Dehradun, India
En la conferencia: 2016 Segunda Conferencia Internacional sobre Tecnologías de Computación de Próxima Generación (NGCT)

Este árticulo guarda relación con los problemas planteados, en que  busca la resolucion de circuitos combinacionales sin embargo el articulo se refiere a aquellos  que prevervan la paridad, lo cual se diferencia del presente trabajo ya que se trabajo con circuitos combinacionales comunes, 
En el articulo lo cual crean una nuevo integrado llamada puerta reversible que cumple con la propiedad de preservación de paridad,y lo que  se realizo en el trabajo fue ocupar todo lo ya establecido.


**Diseño y análisis de baja potencia, alta velocidad 4 - Comparador de magnitud de bits**

En este diseño se analiza diferentes comparadores de magnitud de bits N más grandes de alta velocidad y baja potencia con la compuerta lógica NOR , se tiene en cuenta diferentes cosas como el rendimiento, para el consumo de la energía, el retraso y el Producto de retraso de energía con Vdd Sweep. Una vez analizado de manera general se centran en realizar  El diseño para el comparador propuesto que es baja potencia, alta velocidad 4. 
**Autores:**

- Pranay Singh
Shri G.S. Institute of Technology and Science,Indore,M.P.,India,452003
- Pramod Kumar Jain
Shri G.S. Institute of Technology and Science,Indore,M.P.,India,452003

**Fecha y lugar de publicación:**
27-28 DE Julio de 2018

 En la conferencia :2018 International Conference on Recent Innovations in Electrical, Electronics & Communication Engineering (ICRIEECE)
 **Lugar:** Bhubaneswar, India, India
 
 Este Articulo tiene relacion con el presente trabajo ya que ambos realizan comparadores pero de diferentes bits, sin embargo la implementacion se realiza de manera análoga con compuertas Nor y  los autores buscan primero hacerlo de forma general basandose en la potencia y en este trabajo se realizo directamente la comparacion teniendo en cuenta solo el problema planteado.

## 4.  MARCO TEÓRICO
<p style="text-align: justify;">Un circuito combinacional es un circuito electrónico, en el que el valor de sus salidas en un determinado instante, dependen del valor de las entradas en ese mismo instante. Es decir, es un circuito que carece de memoria. Trabajan con números, y con la tecnología con la que están realizados, estos números están representados en binario (Peiron Guárdia & Sánchez Carracedo, 2015).</p>

![jf1]( https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/jf1.png)

   **Figura 1:** Diagrama de un circuito lógico combinacional

<p style="text-align: justify;"> Es un circuito combinacional con "m” entradas y "n" salidas. Las salidas que se obtengan en un determinado instante van a depender de las entradas en ese preciso instante. Estos circuitos se caracterizan porque no almacenan información. Las salidas están relacionadas con las entradas a través de una función booleana.</p>

<p style="text-align: justify;"> Cada bit de salida de un circuito combinacional, se obtiene mediante una función booleana aplicado a las variables de entrada. Así, si un circuito tiene n salidas, necesitaremos n funciones booleanas para caracterizarlo.</p>

Así, un circuito combinacional que tiene 3 entradas: A, B y C, y dos salidas F, G, que son dos funciones booleanas que dependen de las variables de entrada: F (A, B, C) y G (A, B, C) (Ferrera , 2016).

![jf2]( https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/jf2.png)

**Figura 2:** Circuito combinacional con compuertas lógicas

<p style="text-align: justify;"> Los dispositivos electrónicos más elementales son las puertas lógicas y los bloques lógicos, que forman los circuitos lógicos. Estos últimos se pueden ver como un conjunto de dispositivos que manipulan de una manera determinada las señales electrónicas que les llegan (las señales de entrada), y generan como resultado otro conjunto de señales (las señales de salida). 
Existen dos grandes tipos de circuitos lógicos: </p> 

<p style="text-align: justify;">•	Los circuitos combinacionales
es, que se caracterizan porque el valor de las señales de salida en un momento determinado depende del valor de las señales de entrada en ese mismo momento. 
  
•	Los circuitos secuenciales, en los que el valor de las señales de salida en un momento determinado depende de los valores que han llegado por las señales de entrada desde la puesta en funcionamiento del circuito. Por tanto, tienen capacidad de memoria.
La operación de los circuitos combinacionales se entiende escribiendo las ecuaciones booleanas y sus respectivas tablas de verdad (Abad, 2017).</p>

![jf3](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/jf3.png)

   **Figura 3:**. Tabla de verdad de un circuito combinacional
          
## 5. DIAGRAMAS

**5.1 Diagramas de bloques**

<p style="text-align: justify;">Los tres circuitos  poseen un diagrama de bloques para explicar que  es lo que hace cada uno para resolver el problema propuesto.</p>
  
* Funcionamiento del Circuito  Votador se muestra en la figura 4.</p>

![Fgimg1.PNG](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/Fgimg1.PNG)

   **Figura 4:** Funcionamiento del Circuito Votador, Entradas, Proceso y Salida.
   
 * Funcionamiento del Circuito  Asignador de turno se muestra en la figura 5.</p>

![Fgimg3.PNG](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/Fgimg3.PNG)

   **Figura 5:** Funcionamiento del Circuito Asignador, Entradas, Proceso y Salidas,
   
* Funcionamiento del Circuito  Comparador de dos números de dos bits se muestra en la figura 6.</p>

![Fgimg2.PNG](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/Fgimg2.PNG)

   **Figura 6:** Funcionamiento del Circuito Comparador, Entradas, Proceso y Salidas.

**5.2 Diagramas Electrónico**

A continuación se muestran los diagramas Electronicos de lasimulacion del diseños de los 3 circuitos. 

*Circuito Votador*

![Fgimg5.png](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/Fgimg5.png)
   
   **Figura 7:** Diseño de Circuito Votador
   
*Circuito Asignador de Turnos*

![jdiagramaelectrico.png](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/jdiagramaelectrico.png)

   **Figura 8:** Diseño de Circuito Asignador de Turnos 

*Circuito Comparador *

![MFig10.jpeg](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/MFig10.jpeg)

   **Figura 9:** Diseño de Circuito Comparador
   
 **A continuación se muestra los diagramas Electrónicos en el laboratorio Virtual**
 
 *Circuito Votador*
 
![Fgimg6.PNG](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/Fgimg6.PNG)


   **Figura 10:** Implementación de Circuito Votador 
   
*Circuito Asignador de Turnos*
   
   **Figura 11:** Implementación de Circuito Asignador de Turnos

*Circuito Comparador *

   **Figura 12:** Implementación de Circuito Comparador. 
   
 **5.3 Diagrama de Flujo**
 
 Problema 3 implementado en la aplicacion App Inventor.
 
 ![Fgimg4.png](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/Fgimg4.png)

   **Figura 10:** Diagrama de Flujo 
   
   
 
## 6. LISTA DE COMPONENTES

En la Tabla 1 se muestra las herramientas  de software usadas para la simulacion de los tres circuitos se utilizó dos tipos de simuladores, y la aplicacion usada para el programa del circuito Comparador.

**Tabla 1: Herramientas de Software usadas para el diseño de los 3 circuitos.**

   |     **Herramientas de Software**      |                 
   |---------------------------------------|
   |            Proteus                    | 
   |       Constructor Virtual             |
   |          App Inventor                 | 
   
En la Tabla 2 se muestra los componentes electrónicos Para la realización del Circuito Votador.

**Tabla 2: Datos de los integrados usados para el diseño de los 3 circuitos.**

   | **N°**|**Integrados**	|  **Códigos**    |     
   |-------|--------------|----------------|
   |      1|   XOR	      |     74LS86       |
   |      1|   AND        |     74LS08       |
   |      1|   NOR        |     74LS04      |

**Tabla 3: Componentes electronicos del Circuito Votador**
  | **N°**|**Componentes Electronicos**	|    
   |-------|--------------|
   |      5|  Resistencias de 330       |    
   |      1|  Dip Switch 3 entradas       |     
   |      1|   Fuente de 5 V     |   
   |      1|   Led Green  | 
   
**Tabla 4: Datos de los integrados usados el Circuito Asignador de Turnos**

   | **N°**|**Integrados**	|  **Códigos**    |     
   |-------|--------------|----------------|
   |      1|   NOT	      |     74LS04        |
   |      3|   AND        |     74LS08       |
   |      1|   NOR        |     74LS32   |
   |      1|   NAND       |     74LS00       |

**Tabla 5 se muestra los componeentes electrónicos usados para Circuito Asignador de Turnos**
   | **N°**|**Componentes Electronicos**	|    
   |-------|--------------|
   |      6|  Resistencias de 330       |    
   |      1|  Dip Switch 4 entradas       |     
   |      1|   Fuente de 5 V     |   
   |      1|   Led Yellow  | 
   |      3|   display de 7 segmentos  |
   
**Tabla 6: Datos de los integrados usados el Circuito Comparador de 2 Bits**

   | **N°**|**Integrados**	|  **Códigos**    |     
   |-------|--------------|----------------|
   |      12|   NOR      |    74LS32         |
   
**Tabla 7: se muestra los componeentes electrónicos usados para  Comparador de 2 Bits**
   | **N°**|**Componentes Electronicos**	|    
   |-------|--------------|
   |      25|  Resistencias de 330       |    
   |      1|  Dip Switch 4 entradas       |     
   |      1|   Fuente de 5 V     |   
   |      3|   Led Green  | 
   |      3|   display de 7 segmentos  | 
                       
                      
### 7. MAPA DE VARIABLES
**Tabla 8: Mapa de variables**

![JMapaVariables.PNG](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/JMapaVariables.PNG)
                                                                                                                         
### 8. EXPLICACIÓN DEL CÓDIGO FUENTE

La pantalla principal de la aplicación llamada “Comparador Binario” se presenta de la siguiente manera, mostrando los dos números para ingresar por el teclado, los campos de texto  que muestran los resultados junto con los botones de comparar y borrar.

![MFig0](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/MFig0.PNG)

**Figura 10:** Pantalla de la aplicación Comparador Binario

1. Se crearon 2 variables globales denominadas:

![MFig1](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/MFig1.PNG)

**Figura 11:** Inicialización de variables

2. Se creó el ProcesoTranformar donde se asignan a las variables globales la representación decimal  de los números ingresados por teclado.
![MFig2](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/MFig2.PNG)

**Figura 12:** Proceso Transformar 

3. Se creó el ProcesoComparar en el que se comparan los valores resultantes de la transformación del proceso anterior, estableciendo condicionales para los siguientes casos: A=B, A<B Y A>B

De esta manera se asignaron dos resultados para cada caso propuesto, asignando un color en la casilla (como si fuera un led) de respuesta junto con el valor de cero (como si fuera un display) si ocuurren uno de los tres casos.

![MFig3](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/MFig3.PNG)

**Figura 13:** ProcesoComparar

4. Se establecieron dos botones de selección en la ventana principal del programa:
* Cuando el BotonComparar hace clic, se ejecutan los proncesos de Transformar y Comparar 
	
![MFig4](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/MFig4.PNG)
	
**Figura 14:** Boton Comparar

* Cuando el BotonBorrar hace clic, se reestablecen todos los valores

![MFig5](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/MFig5.PNG)

**Figura 15: ** Boton Borrar

**Explicacción del diseño los circuitos**
**1. Circuito Votador**
Se pretende diseñar un circuito Votador que tenga como entrada tres circuitos que pueden estar estables "1" o con falla "0", y que en la salida detecte el valor mayoritario de los tres circuitos. 
**Establecer las entradas del circuito**

A: Circuito 1		
B: Circuito 2
C: Circuito 3
Cada una de las entradas representa un circuito de manera que sabremos si se encuentra estable o fallando. 
Por lo tanto, se tienen 3 entradas y el número de combinaciones está dado por la expresión: 
Combinaciones=2^n
Combinaciones=2^3=8
**Establecer las salidas del circuito**
F : El Circuito Votador Funciona si la mayoria esta estable.

**Formulación de la tabla de verdad**
El análisis se realizó a través de la siguiente tabla:
|**A| B | C |   F**  | 
| 0 | 0 | 0 | **0**  | 
| 0 | 0 | 1 | **0**  | 
| 0 | 1 | 0 | **0**  | 
| 0 | 1 | 1 | **1**  | 
| 1 | 0 | 0 | **0**  | 
| 1 | 0 | 1 | **1**  | 
| 1 | 1 | 0 | **1**  |
| 1 | 1 | 1 | **1**  | 
**Obtener las funciones simplificadas**

Utilizamos los mintérminos para realizar la implementación del circuito ya que tenemos gual numero de 0y de 1 ademas  se usa lógica positiva

**F** = A’BC + A B’C + A B C’ + ABC

 *Simplificando obtenemos las siguientes funciones
 
**F** = C(A’B+A B’)+AC( B’+B)
**F**    = C(A⊕B)+AC 

Entonces la funcion a implementarse será.
	**F = C(A⊕B)+AC **


**2. Circuito asignador de turnos**

Se pretende diseñar un circuito que tenga como entradas la representación binaria de la hora actual menos ocho y que proporcione a la salida el número de turno que está trabajando (si procede) o "0" si es hora de descanso.
**Establecer las entradas del circuito**

A: Bit más significativo de la hora ingresada		
B: Bit menos significativo de la hora ingresada		

Las 4 entradas representan el parámetro de la hora ingresada para poder saber que turno le corresponde.
Por lo tanto, se tienen 4 entradas y el número de combinaciones está dado por la expresión: 

Combinaciones=2^n
Combinaciones=2^4=16

**Establecer las salidas del circuito**
Y :Bit más significativo de la salida.	
Z :Bit menos significativo de la salida.

Por lo tanto, las salidas del circuito son dependientes del valor de los números ingresados.
**Formulación de la tabla de verdad**
El análisis se realizó a través de la siguiente tabla:

|**TURNO	|HORAS	|HORAS – 8     |Y| Z**|
|1	|8 – 9 – 10	|0 – 1 – 2	|0|1|
|2	|11 – 12	|3 – 4		|1| 0|
|DESCANSO|13 – 14 – 15 | 5 – 6 – 7     | 0|0|
|3	|16 – 17 – 18	|8 – 9 – 10    |1 |1|

Tomando en cuentas estas consideraciones armamos la tabla de verdad. 
|**N|A	|B	|C      |D      |Y      |Z**  |
|---|---|----   |-------|-------|---    |---  |
|0  |0  |0	|0	|0  	|0	|1    |
|1  |0	|0	|0	|1  	|0	|1    |
|2  |0	|0	|1	|0	|0	|1    |
|3  |0	|0	|1	|1	|1	|0    |
|4  |0	|1	|0	|0	|1	|0    |
|5  |0	|1	|0	|1	|0	|0    |
|6  |0	|1	|1	|0	|0	|0    |
|7  |0	|1	|1	|1	|0	|0    |
|8  |1	|0	|0	|0	|1	|1    |
|9  |1	|0	|0	|1	|1	|1    |
|10 |1	|0	|1	|0	|1	|1    |

**4.	Obtener las funciones simplificadas**

Para realizar la implementación del circuito, podemos escoger los mintérminos o maxtérminos. Debido a que en las funciones existen más 1 que 0, se tomarán los mintérminos. Usando lógica positiva 

Z = A’B’C’D’ + A’B’C’D + A’B’CD’ + AB’C’D’ + AB’C’D + AB’CD’

Y = A’B’CD + A’BC’D’ + AB’C’D’ + AB’C’D + AB’CD’

 *Simplificando obtenemos las siguientes funciones
 
Z = B’C’ + B’CD’

Y = AB’C’ + A’BC’D’ + A’B’CD + AB’CD’


**3. Circuito comparador**

Se pretende diseñar un circuito comparador de dos números binarios cada uno de dos bits para los siguientes tres casos: A<B, A=B, A>B. Además, a la salida de cada función en el circuito deberá estar un display que muestre el número cero para cada uno de los casos.

**1. Establecer las entradas del circuito:**

A1:	Bit más significativo del número A

A0:	Bit menos significativo del número  A

B1:	Bit más significativo del número B

B0:	Bit menos significativo del número  B	

Por lo tanto, se tienen 4 entradas y el número de combinaciones está dado por la expresión: 

**Combinaciones=2^n**

C=2^4=16

**2. Establecer las salidas del circuito:**
A<B	m	Cuando A es menor a B	
A=B	i	Cuando A es igual a B	
A>B	M	Cuando A es mayor a B	

Por lo tanto, las salidas del circuito son dependientes del valor de los números ingresados.

**3. Formulación de tabla de verdad:**

Se analizan los dos números ingresados:

- Si A es 00 y B es 00

- A y B tienen el mismo valor de cero, entonces A=B y la función de salida i es verdadera y toma el valor de uno lógico mientras que las otras dos tomarán el valor de cero lógico.

- Si A es 01 y B es 10

- A toma el valor de 1 y B toma el valor de 2, entoces A<B y la función m es verdadera y toma el valor de uno lógico mientras que las otras dos tomarán el valor de cero lógico.

- Si A es 11 y B es 00
A toma el valor de 3 y B toma el valor de 0, entonces A>B y la función M es verdadera y toma el valor de uno lógico mientras que las otras dos tomarán el valor de cero lógico.

- Este mismo análisis se realiza hasta completar las 16 combinaciones dando como resultado la siguiente tabla de verdad:

|       |        |      |   |A<B |	A=B |	A>B|
|-------|-------|-------|---|---|---|---|
|**A1	|A0	|B1	|B0 |m  |i  |M**  |
|-------|-------|-------|---|---|---|---|
|0	|0	|0	|0  |0	|1	|0|
|0	|0	|0	|1  |1	|0	|0|
|0	|0	|1	|0	|1	|0	|0|
|0	|0	|1	|1	|1	|0	|0|
|0	|1	|0	|0	|0	|0	|1|
|0	|1	|0	|1	|0	|1	|0|
|0	|1	|1	|0	|1	|0	|0|
|0	|1	|1	|1	|1	|0	|0|
|1	|0	|0	|0	|0	|0	|1|
|1	|0	|0	|1	|0	|0	|1|
|1	|0	|1	|0	|0	|1	|0|
|1	|0	|1	|1	|1	|0	|0|
|1	|1	|0	|0	|0	|0	|1|
|1	|1	|0	|1	|0	|0	|1|
|1	|1	|1	|0	|0	|0	|1|
|1	|1	|1	|1	|0	|1	|0|


4. Se btener las funciones resultantes simplificadas para realizar la implementación del circuito, para ello se pueden escoger mintérminos o maxtérminos. 
Debido a que en las funciones existen más 1 que 0, se tomarán los mintérminos.
*Para A<B:

**m=** A1'A0'B1'B0+A1'A0'B1B0'+A1'A0'B1B0+A1'A0B1B0'+A1'A0B1B0+A1A0'B1B0

*Simplificación:

**m=** A1'B1+A0'B1B0+A1'A0'B0

*Para A=B:

**i=**A1'A0'B1'B0'+A1'A0B1'B0+A1A0'B1B0'+A1A0B1B0

*Simplificación:

**i=**A1'A0'B1'B0'+A1'A0B1'B0+A1A0B1B0+A1A0'B1B0'

*Para A>B:

**M=**A1'A0B1'B0'+A1A0'B1'B0'+A1A0'B1'B0+A1A0B1'B0'+A1A0B1'B0+A1A0B1B0'

*Simplificación:*

**M=** A1B1'+A0B1'B0'+A1A0B0'

### 9. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

En el circuito Asignador de Turnos para realizar la conexión entre las salidas de los circuitos y el display de 7 segmentos hicimos uso de un Decodificador  BCD de 7 segmentos  de ánodo común cuyas características se muestran en la tabla 9.

| **Código**|**Características**	|    
|---------- |--------------|
|       7447|  - Cada combinación de valores de las entradas activa varias salidas, en lugar de una sola.                                                             - Tiene cuatro líneas de entrada en código BCD y salidas capaces de excitar un display de siete segmentos para representar cualquier dígito de 0 a 9.                                                                                                                - Como existen dos tipos de decodificadores ánodo común y catodo común, existen dos tipos de display de 7 segmentos.                    - Evidentemente, decodificador y display tienen que ser del mismo tipo para poder ser conectados.                                        - Los displays de 7 segmentos son dispositivos que se utilizan para visualizar información.                                              -Cada segmento de un display está constituído por un LED.|  

 A continuacion se muestra el display de 7 segmentos utilizado en la simulacion del Constructor Virtual.

![jD1]( https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/jD1.png)

![jd2]( https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/jd2.png)

![jd3]( https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/jd3.png)

![jd4]( https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/jd4.png)

**Figura 16:** Display de 7 segmentos

Al implementar el Circuito Comparador de dos números de dos bits cada uno en la aplicación App Inventor, se necesita una herramienta para utilizar el programa creado por tal motivo se muestra en la tabla # las  aplicaciones que se uso para comprobar el programa.

|                 **Herramientas de Software**       |                  **Descripción**                      |
|----------------------------------------------------|-------------------------------------------------------|
|    Emulador de MIT App Inventor para computadores. | La aplicación MIT App Inventor te da directamente el emulador para probar el                                                          programa que estas creando.                             |
|Emulador de MIT App Inventor para sistemas Android. | Se puede descargar directamente de una tienda de aplicaciones. Ejemplo: Play                                                          Store                                                   |
|                       BLUESTACKS                    | Es un emulador de Android que se utiliza en la computadora y permite descargarse                                                      el MIT App Inventor para probar el programa creado.      |                          



## 10. APORTACIONES

Para poder implementar el display de 7 segmentos (ánodo común) en los circuitos asignados se utilizó el integrado 7447 correspondiente a un decodificador BCD a 7 segmentos, el cual nos ayudó a representar visualmente el resultado de las salidas correspondientes en sistema decimal.
![jintegrado]( https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/jintegrado.jpg)

**Figura17:** Interado del Decodificador 7447.


## 11. CONCLUSIONES
* Para desarrollar la implementación de los circuitos asignados previamente se realizo el análisis correspondiente en el cual definimos las variables de entrada, las funciones que debe realizar el circuito y las variables de salida, posterior a este análisis se realizo las correspondientes simulaciones para comprobar que el análisis que hicimos fue el correcto, por ultimo armamos los circuitos en el laboratorio virtual
* El uso de los simuladores virtuales nos ayudo a comprender de mejor manera el funcionamiento de nuestro cicuito, ademas a traves de los mismoc comprobamos que las funciones obtenidas de los circuitos estaba correctamente simplificadas
* Para el desarrollo del programa en AppInventor se elegio el tercer enunciado el cual comparaba dos numeros ingresando y nos devolvia si uno de los numero era mayor, menos o igual que el otro

## 12. RECOMENDACIONES
* 

## 13. CRONOGRAMA
![jcronograma]( https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/jcronograma.png)

**Figura 18 :** Cronograma realizado en Monday

## 14. BIBLIOGRAFÍA
Abad, P. (28 de Marzo de 2017). Sistemas Digitales . Obtenido de https://ocw.unican.es/pluginfile.php/313/course/section/261/tema_03.pdf

Ferrera , G. (17 de Diciembre de 2016). Electronica Digital . Obtenido de http://electronicadigital-circuitos.blogspot.com/2016/12/definicion-de-circuitos-combinacionales.html

Peiron Guárdia, M., & Sánchez Carracedo, F. (19 de Mayo de 2015). Circuitos logicos Combinacionales. Obtenido de https://www.exabyteinformatica.com/uoc/Informatica/Fundamentos_de_computadores/Fundamentos_de_computadores_(Modulo_3).pdf



## 15. ANEXOS
## 15.1 MANUAL DE USUARIO

Comparador Binario es una aplicación para Android que permitirá realizar la comparación de mayor, igual y menor entre dos números binarios de dos bits de una manera fácil y sencilla.
1. Ingresar los números binarios que desee comparar.

![MFig6](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/MFig6.PNG)

**Figura 19:** Ingreso de números

2. Seleccionar el botón Comparar para realizar la operación.

![MFig7](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/MFig7.PNG)

**Figura 20:** Selección del "Comparar"

3. La respuesta de la comparación se verá reflejada en un color dentro del campo de texto correspondiente al valor verdadero acompañado del número cero que debe aparecer en cuando hayan ocurrido uno de los tres casos.

![MFig8](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/MFig8.PNG)

**Figura 21:** Resultado obtenido 

4. Pulsar el botón Borrar para limpiar la pantalla e ingresar nuevos valores.

**Figura 22:**  Selección del "Borrar"

![MFig9](https://github.com/JorgeGallegos99/Producto-Unidad-1/blob/master/Img/MFig9.PNG)

## 15.2 HOJAS TÉCNICAS
