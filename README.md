# Guía para el Montaje, configuración y preparación para pruebas de vuelo de un dron Hexsoon EDU 450
## 1.	Presentación
En esta guía se describe, paso a paso, el proceso de montaje, configuración y pruebas de vuelo de un dron. El punto de partida es un kit con todos los componentes necesarios, que se muestra en la figura 0.1.  
<img src="https://github.com/user-attachments/assets/842b8bbd-00a6-4751-b6da-0cb329c5aa3e" width="300" height="300">      
**Figura 0.1:** El kit   

El resultado final es el dron que se muestra en la figura 0.2, bien configurado y preparado para volar.    
<img src="https://github.com/user-attachments/assets/f1ae0ac4-1545-4fba-a412-fd283c784590" width="300" height="300">     
**Figura 0.2:** El dron resultante

El dron es un cuatrimotor que incorpora un piloto automático. El dron puede ser guiado manualmente a través de la emisora de radio, pero también desde una estación de tierra (por ejemplo, un portátil) que ejecute el software Mission Planner. Usando ese mismo software es posible también crear misiones en forma de secuencia de puntos a recorrer de manera automática por el dron. Finalmente, también es posible desarrollar nuestra propia estación de tierra (por ejemplo, en Python), lo cual multiplica las posibilidades de aprendizaje, experimentación y también diversión. La figura 0.3 muestra dos ejemplos. A la izquierda se muestra la pantalla de una web app que permite controlar el dron desde cualquier teléfono móvil. A la derecha se muestra una imagen de una aplicación de escritorio que permite controlar el dron con las posiciones de la mano.   
<img src="https://github.com/user-attachments/assets/c8f92816-01e5-4a30-afb5-701f54207c97" width="500" height="200">      
**Figura 0.3:** Un par de aplicaciones que pueden desarrollarse para controlar el dron 

Mission Planner también incluye un simulador que permite probar la mayoría de las acciones sin necesidad de volar el dron, de manera que en el momento del vuelo se minimicen las posibilidades de fallo.

El resultado final es un equipo que permite diseñar un gran abanico de actividades formativas en diversas áreas de la ciencia y la tecnología, como pueden ser: mecánica, electrónica, electricidad, física, matemáticas, programación de ordenadores, etc.    
## 2.	Las actividades
El proceso de montaje, configuración y preparación para pruebas de vuelo del dron está detalladamente guiado por una secuencia de actividades que se enumeran en la tabla. Cada actividad tiene su guía detallada con explicaciones teóricas (cuando sea necesario), instrucciones precisas, imágenes y vídeos que deben ayudar en el proceso.

| # | Título | Descripción |
|-----------|-----------|-----------|
| #1  | Lo más básico de los drones y sus componentes| Un video que ofrece una visión global sobre los drones y sus componentes, y una colección de videos complementarios para profundizar|
| #2   |Unboxing| Enumeración de los componentes del kit|
| #3   | Montaje de la carcasa (parte 1)| Primera parte del montaje, en la que se instalan los motores, brazos, variadores ESC, etc.|
| #4   | Radio control| Configuración de la emisora de radio para controlar el dron   |
| #5   | El autopiloto| Configuración y primeras calibraciones del autopiloto|
| #6   | Montaje de la carcasa (parte 2)| Segunda parte del montaje, en la que se instala el autopiloto, el receptor GPS, el servo, las radios de telemetría, etc.|
| #7   | Más calibraciones|Últimas calibraciones para dejar el dron preparado para pruebas de vuelo|
| #8   | Simulador, geofences y planificación de misiones| Aspectos muy importantes para preparar las pruebas de vuelo|

## 3. Actividad #1: Lo más básico de los drones y sus componentes
### 1. Presentación
En esta actividad se describen los aspectos más básicos de un dron y de los elementos que lo componen. El objetivo es ofrecer a los participantes en el taller un marco global, sencillo pero completo que les permita ubicar correctamente cada una de las actividades del taller.

### 2. Vídeo introductorio
El vídeo siguiente describe estos aspectos básicos.

[![](https://markdown-videos-api.jorgenkh.no/url?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3Dc2Aa_KSdEwo)](https://www.youtube.com/watch?v=c2Aa_KSdEwo)

### 3. Videos complementarios
Los vídeos que aparecen a continuación profundizan en muchos de los conceptos y componentes que se mencionan en el vídeo introductorio. No es necesario mirarlos antes de comenzar. Pero es interesante tener presente que están por si conviene en algún momento revisar los conceptos con un poco más de profundidad.

Radio control:	 
https://www.youtube.com/watch?v=LyPtzv0y5DE

ESC:	 
https://www.youtube.com/watch?v=OZNxbxL7cdc

Motores Brushless: 	 
https://www.youtube.com/watch?v=uLutMoh4Ttg

Conexiones para radio control:	 
https://www.youtube.com/watch?v=GbUMC8h2uhU&t=8s

Configuración de la emisora de radio:	 
https://www.youtube.com/watch?v=azs1wmr4c7w

Flight controllers vs flight computers:	 
https://www.youtube.com/watch?v=PlKeFj5teo4

Mission Planner:	 
https://www.youtube.com/watch?v=z_sZUOrnfY8&t=3s

El autopiloto:	 
https://www.youtube.com/watch?v=m7THu-W-kjE&list=PLYsWjANuAm4rSLU7PQczfpQ9B4KbcPWsI&index=1

Modos de vuelo:	 
https://www.youtube.com/watch?v=mSSbjo9pYgM

## 2. Actividad #2: Unboxing
En la figura 2.1 se muestran todos los componentes que se necesitan para el montaje y configuración del dron. Antes de iniciar el montaje es importante verificar que se dispone de todos esos componentes y herramientas.    
En este documento explica dónde adquitir el kit y (si se prefiere) dónde encontrar cada uno de los componentes por separado.   
<img src="https://github.com/user-attachments/assets/fcbf153a-8615-4830-b53b-d48c41880931" width="500" height="1500">      
**Figura 2.1:** Componentes y herramientas necesarias para el montaje del dron
 
## 3. Actividad #3: Montaje de la carcasa (parte 1)
### 1. Presentación
En esta actividad se dan los primeros pasos del montaje de la carcasa del dron (brazos con motores, plataformas, placa de distribución, etc.). Es una actividad ideal para personas habilidosas, que se puede hacer con buena música de fondo.   
### 2. Preparación de los 4 motores   
Como se muestra en las imágenes de la figura 3.1, los motores deben atornillarse a los soportes. Hay dos soportes de color naranja (que irán en la parte delantera del dron) y dos soportes negros (parte trasera). Es muy importante observar que hay dos motores que tienen un punto blanco en el eje y dos que no lo tienen. Debe haber un motor con punto blanco en un soporte naranja y el otro con punto blanco en un soporte negro.   
Finalmente, observa la dirección en la que deben colocarse los motores respecto al soporte. La parte donde están los cables debe estar orientada en la dirección que indica la pequeña ranura circular del soporte.   

 
 <img src="https://github.com/user-attachments/assets/dd23f606-6bc7-4a55-906a-5751494f98c8" width="500" height="400">      
 	 
**Figura 3.1:** Montaje de los motores en sus soportes

### 3. Preparación de los 4 brazos
La figura 3.2 muestra cómo preparar cada uno de los 4 brazos del dron.   
<img src="https://github.com/user-attachments/assets/786e5283-ce58-45bc-bd96-e9a64110b799" width="300" height="300">       
**Figura 3.12:** Preparació de los brazos
### 4. Conectar los cables de los LEDs a la placa de distribución de energía    
Las conexiones necesarias se muestran en la figura 3.3.    
<img src="https://github.com/user-attachments/assets/aa6690ed-5138-4c73-a3c5-8d6771b0f0ba" width="300" height="300">      
**Figura 3.3:** Conexiones para el control de los LEDs

Se debe conectar cada uno de los cuatro cables de colores (uno por LED), el cable POWER2 para alimentar el autopiloto (que está en el kit del Orange Cube) y el conector doble necesario para el control de los LEDs. Observad cómo se han protegido con cinta aislante negra estos dos últimos cables para evitar el roce del cable con los bordes de la plancha negra a la que se atornillará la placa de distribución de energía.    
### 5. Atornillar la placa de distribución de energía a la plancha superior
La figura 3.4 indica cómo realizar esta operación. Fíjate que las dos planchas negras que vienen en el kit Hexsoon son diferentes. La superior es la mostrada en la figura. Es importante respetar la colocación exacta de la placa sobre la plancha y su orientación. Tanto el cable POWER2 como el conector doble de control de los LEDs deben salir por la parte superior de la plancha.

 
**Figura 3.4:** Colocación de la placa de distribución de energía en la plancha superior 

### 6. Introducir en cada brazo un variador ESC 
La figura 3.5 muestra cómo realizar esta operación. Por un lado, se deben conectar los variadores a los cables de alimentación procedentes de la placa de distribución de energía (esquina superior derecha de la figura 3.5). Por otro lado, el otro extremo de los variadores se debe conectar a los motores, según el sentido de giro, tal y como se indica en la figura 3.6. Es importante tener en cuenta que los motores con punto blanco girarán en sentido antihorario y los motores con punto negro lo harán en sentido horario.

 
**Figura 3.5:** En cada brazo hay que introducir un variador para controlar el motor 

 
**Figura 3.6:**  Conexión del motor al variador ESC según el sentido de giro (imagen elaborada por los alumnos de Master de drones Júlia y Gerard)

### 7. Disponer los brazos y motores correctamente en relación con la plancha superior
Este es un paso sencillo pero muy importante, ya que decisiones incorrectas pueden causar errores graves en el momento de las pruebas de vuelo.

Ahora necesitaremos tener a mano las hélices que se enroscarán en los motores. Se puede observar que tenemos dos hélices con un punto blanco, que solo se pueden enroscar en los motores con el punto blanco, y dos hélices sin este punto, para los otros dos motores.

Una simple observación de cada hélice determina en qué dirección debe girar para que la hélice empuje el aire que la rodea hacia abajo y, como nos enseñó Newton, se genere la fuerza de sustentación que empuja la hélice hacia arriba. En concreto, las hélices con el punto blanco deben girar en sentido contrario al de las agujas del reloj (counterclockwise o CCW) y las que no tienen este punto en sentido de las agujas del reloj (clockwise o CW).

Por otro lado, la figura 3.7 (izquierda) determina en qué sentido (CW o CCW) debe girar cada motor según su posición en la carcasa. Recordemos que los motores 1 y 3 de la figura, que son los delanteros, están fijados a los soportes de color naranja. A la vista de la figura 3.6 queda claro que los motores con punto blanco (que son los que giran en sentido CCW) deben ocupar las posiciones 1 y 2. Esta disposición se muestra también en la figura 3.7 (derecha).

Observar también en esta figura que se han añadido extensiones a los cables trenzados de los motores delanteros (naranjas). Estas extensiones facilitarán ciertas conexiones más adelante.

Se puede observar que cada motor tiene sobre la palabra HEXSOON unas flechitas que indican el sentido de giro (estas flechitas ya no aparecen en versiones más recientes del kit). Esta es una ayuda más para confirmar que hemos tomado la decisión correcta. Pero ATENCIÓN: se ha observado que en algunos casos estas flechitas están equivocadas. Lo importante para tomar la decisión correcta es lo que hemos dicho antes: observar la forma de las hélices, determinar cuál debe ser su sentido de giro y colocar los motores en el lugar que corresponde, de acuerdo con la figura 3.7.

 	 

**Figura 3.7:** Sentido de giro de los motores según su posición
### 8. Fijar el motor al brazo
El resultado de esta operación se muestra en la figura 3.8. No es una operación trivial y requiere cierta habilidad manual.

 
**Figura 3.8:** Motor conectados al extremo del brazo

Para el proyecto de UAS no vamos a utilizar los LEDs así que no te preocupes si no ves el LED en el kit

### 9. Fijar los brazos a las planchas superior e inferior
Las imágenes de la figura 3.9 muestran cómo realizar esta operación. Observad de nuevo cómo los siguientes cables deben emerger por la parte superior de la carcasa:

●	Los 4 cables trenzados para controlar los motores.
●	El cable POWER2 para alimentar el autopiloto.
●	El cable con el conector doble para controlar los LEDs.
●	El cable para alimentar la Raspberry Pi en un futuro.


 	 	 
**Figura 3.9:** Fijar  los brazos a las dos planchas

###10. Separar al máximo posible los cables de la placa de distribución de energía
Esta operación se puede realizar como se muestra en la figura 3.10. El objetivo es que el posible calentamiento de la placa no pueda afectar a los cables.

 
**Figura 3.10:** Separar lo máximo posible los cables de la placa de distribución de energía



