# Guía para el Montaje, configuración y preparación para pruebas de vuelo de un dron Hexsoon EDU 450 (versión 2)
## Presentación
En esta guía se describe, paso a paso, el proceso de montaje, configuración y pruebas de vuelo de un dron. El punto de partida es un kit con todos los componentes necesarios, que se muestra en la figura 0.1.  
<img src="https://github.com/user-attachments/assets/842b8bbd-00a6-4751-b6da-0cb329c5aa3e" width="400" height="300">      
**Figura 0.1:** El kit   

El resultado final es el dron que se muestra en la figura 0.2, bien configurado y preparado para volar.    
<img src="https://github.com/user-attachments/assets/f1ae0ac4-1545-4fba-a412-fd283c784590" width="400" height="250">     
**Figura 0.2:** El dron resultante

El dron es un cuatrimotor que incorpora un piloto automático. El dron puede ser guiado manualmente a través de la emisora de radio, pero también desde una estación de tierra (por ejemplo, un portátil) que ejecute el software Mission Planner. Usando ese mismo software es posible también crear misiones en forma de secuencia de puntos a recorrer de manera automática por el dron. Finalmente, también es posible desarrollar nuestra propia estación de tierra (por ejemplo, en Python), lo cual multiplica las posibilidades de aprendizaje, experimentación y también diversión. La figura 0.3 muestra dos ejemplos. A la izquierda se muestra la pantalla de una web app que permite controlar el dron desde cualquier teléfono móvil. A la derecha se muestra una imagen de una aplicación de escritorio que permite controlar el dron con las posiciones de la mano.   
<img src="https://github.com/user-attachments/assets/c8f92816-01e5-4a30-afb5-701f54207c97" width="400" height="150">      
**Figura 0.3:** Un par de aplicaciones que pueden desarrollarse para controlar el dron 

Mission Planner también incluye un simulador que permite probar la mayoría de las acciones sin necesidad de volar el dron, de manera que en el momento del vuelo se minimicen las posibilidades de fallo.

El resultado final es un equipo que permite diseñar un gran abanico de actividades formativas en diversas áreas de la ciencia y la tecnología, como pueden ser: mecánica, electrónica, electricidad, física, matemáticas, programación de ordenadores, etc.    
   
## Las actividades
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

## Actividad #1: Lo más básico de los drones y sus componentes
### 1. Presentación
En esta actividad se describen los aspectos más básicos de un dron y de los elementos que lo componen. El objetivo es ofrecer un marco global, sencillo pero completo que les permita contextualizar correctamente cada una de las actividades.

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

## Actividad #2: Unboxing
En la figura 2.1 se muestran todos los componentes que se necesitan para el montaje y configuración del dron. Antes de iniciar el montaje es importante verificar que se dispone de todos esos componentes y herramientas.    
En este documento explica dónde adquitir el kit y (si se prefiere) dónde encontrar cada uno de los componentes por separado.   
<img src="https://github.com/user-attachments/assets/fcbf153a-8615-4830-b53b-d48c41880931" width="400" height="1000">      
**Figura 2.1:** Componentes y herramientas necesarias para el montaje del dron
 
## Actividad #3: Montaje de la carcasa (parte 1)
### 1. Presentación
En esta actividad se dan los primeros pasos del montaje de la carcasa del dron (brazos con motores, plataformas, placa de distribución, etc.). Es una actividad ideal para personas habilidosas, que se puede hacer con buena música de fondo.   
### 2. Preparación de los 4 motores   
Como se muestra en las imágenes de la figura 3.1, los motores deben atornillarse a los soportes. Hay dos soportes de color naranja (que irán en la parte delantera del dron) y dos soportes negros (parte trasera). Es muy importante observar que hay dos motores que tienen un punto blanco en el eje y dos que no lo tienen. Debe haber un motor con punto blanco en un soporte naranja y el otro con punto blanco en un soporte negro.   
Finalmente, observa la dirección en la que deben colocarse los motores respecto al soporte. La parte donde están los cables debe estar orientada en la dirección que indica la pequeña ranura circular del soporte.   

 
 <img src="https://github.com/user-attachments/assets/dd23f606-6bc7-4a55-906a-5751494f98c8" width="400" height="200">      
 	 
**Figura 3.1:** Montaje de los motores en sus soportes

### 3. Preparación de los 4 brazos
La figura 3.2 muestra cómo preparar cada uno de los 4 brazos del dron.   
<img src="https://github.com/user-attachments/assets/786e5283-ce58-45bc-bd96-e9a64110b799" width="300" height="300">       
**Figura 3.2:** Preparació de los brazos
### 4. Conectar los cables de los LEDs a la placa de distribución de energía    
Las conexiones necesarias se muestran en la figura 3.3.    
<img src="https://github.com/user-attachments/assets/aa6690ed-5138-4c73-a3c5-8d6771b0f0ba" width="300" height="300">      
**Figura 3.3:** Conexiones para el control de los LEDs

Se debe conectar cada uno de los cuatro cables de colores (uno por LED), el cable POWER2 para alimentar el autopiloto (que está en el kit del Orange Cube) y el conector doble necesario para el control de los LEDs. Observad cómo se han protegido con cinta aislante negra estos dos últimos cables para evitar el roce del cable con los bordes de la plancha negra a la que se atornillará la placa de distribución de energía.    
### 5. Atornillar la placa de distribución de energía a la plancha superior
La figura 3.4 indica cómo realizar esta operación. Fíjate que las dos planchas negras que vienen en el kit Hexsoon son diferentes. La superior es la mostrada en la figura. Es importante respetar la colocación exacta de la placa sobre la plancha y su orientación. Tanto el cable POWER2 como el conector doble de control de los LEDs deben salir por la parte superior de la plancha.   
<img src="https://github.com/user-attachments/assets/ae67f852-4e86-4db6-ba36-7a6db48cff38" width="300" height="200">     
**Figura 3.4:** Colocación de la placa de distribución de energía en la plancha superior 

### 6. Introducir en cada brazo un variador ESC 
La figura 3.5 muestra cómo realizar esta operación. Por un lado, se deben conectar los variadores a los cables de alimentación procedentes de la placa de distribución de energía (esquina superior derecha de la figura 3.5). Por otro lado, el otro extremo de los variadores se debe conectar a los motores, según el sentido de giro, tal y como se indica en la figura 3.6. Es importante tener en cuenta que los motores con punto blanco girarán en sentido antihorario y los motores con punto negro lo harán en sentido horario.   
 <img src="https://github.com/user-attachments/assets/d90dcd36-0036-4a37-84dd-22d711f05ecf" width="300" height="200">     
**Figura 3.5:** En cada brazo hay que introducir un variador para controlar el motor    
<img src="https://github.com/user-attachments/assets/e1fc9206-5623-47e2-aa91-37d352502f93" width="400" height="150">     
**Figura 3.6:**  Conexión del motor al variador ESC según el sentido de giro (imagen elaborada por los alumnos de Master de drones Júlia y Gerard)    

### 7. Disponer los brazos y motores correctamente en relación con la plancha superior
Este es un paso sencillo pero muy importante, ya que decisiones incorrectas pueden causar errores graves en el momento de las pruebas de vuelo.

Ahora necesitaremos tener a mano las hélices que se enroscarán en los motores. Se puede observar que tenemos dos hélices con un punto blanco, que solo se pueden enroscar en los motores con el punto blanco, y dos hélices sin este punto, para los otros dos motores.

Una simple observación de cada hélice determina en qué dirección debe girar para que la hélice empuje el aire que la rodea hacia abajo y, como nos enseñó Newton, se genere la fuerza de sustentación que empuja la hélice hacia arriba. En concreto, las hélices con el punto blanco deben girar en sentido contrario al de las agujas del reloj (counterclockwise o CCW) y las que no tienen este punto en sentido de las agujas del reloj (clockwise o CW).

Por otro lado, la figura 3.7 (izquierda) determina en qué sentido (CW o CCW) debe girar cada motor según su posición en la carcasa. Recordemos que los motores 1 y 3 de la figura, que son los delanteros, están fijados a los soportes de color naranja. A la vista de la figura 3.7 queda claro que los motores con punto blanco (que son los que giran en sentido CCW) deben ocupar las posiciones 1 y 2. Esta disposición se muestra también en la figura 3.7 (derecha).

Observar también en esta figura que se han añadido extensiones a los cables trenzados de los motores delanteros (naranjas). Estas extensiones facilitarán ciertas conexiones más adelante.

Se puede observar que cada motor tiene sobre la palabra HEXSOON unas flechitas que indican el sentido de giro (estas flechitas ya no aparecen en versiones más recientes del kit). Esta es una ayuda más para confirmar que hemos tomado la decisión correcta. Pero ATENCIÓN: se ha observado que en algunos casos estas flechitas están equivocadas. Lo importante para tomar la decisión correcta es lo que hemos dicho antes: observar la forma de las hélices, determinar cuál debe ser su sentido de giro y colocar los motores en el lugar que corresponde, de acuerdo con la figura 3.7.   
<img src="https://github.com/user-attachments/assets/eb128a57-a8a5-4ccf-bec5-de371352dd49" width="400" height="150">  
**Figura 3.7:** Sentido de giro de los motores según su posición
### 8. Fijar el motor al brazo
El resultado de esta operación se muestra en la figura 3.8. No es una operación trivial y requiere cierta habilidad manual.   
<img src="https://github.com/user-attachments/assets/c01bad3b-34c3-4dfb-8532-2671e05405f0" width="300" height="200">  
**Figura 3.8:** Motor conectados al extremo del brazo

Para el proyecto de UAS no vamos a utilizar los LEDs así que no te preocupes si no ves el LED en el kit.   

### 9. Fijar los brazos a las planchas superior e inferior
Las imágenes de la figura 3.9 muestran cómo realizar esta operación. Observad de nuevo cómo los siguientes cables deben emerger por la parte superior de la carcasa:

* Los 4 cables trenzados para controlar los motores.
* El cable POWER2 para alimentar el autopiloto.
* El cable con el conector doble para controlar los LEDs.
* El cable para alimentar la Raspberry Pi en un futuro.
<img src="https://github.com/user-attachments/assets/4e92f2b3-4d2c-420c-b5dc-b71135a71c0d" width="400" height="100">

**Figura 3.9:** Fijar  los brazos a las dos planchas

### 10. Separar al máximo posible los cables de la placa de distribución de energía
Esta operación se puede realizar como se muestra en la figura 3.10. El objetivo es que el posible calentamiento de la placa no pueda afectar a los cables.   
<img src="https://github.com/user-attachments/assets/352afbd8-a3b2-48a4-9680-9cbe858122df" width="300" height="300">  
**Figura 3.10:** Separar lo máximo posible los cables de la placa de distribución de energía


## Actividad #4: Radio Control
### 1. Presentación
En esta actividad se configura la emisora de radio con la que controlaremos los motores y el servo. Para ello, necesitaremos los elementos que se indican en la figura 4.1.    
<img src="https://github.com/user-attachments/assets/9c61cbae-3a80-4b10-9457-397b406501bb" width="400" height="800">   
**Figura 4.1:** Componentes necesarios para esta actividad

### 2. Conceptos básicos
La emisora de radio puede generar señales de radio a través de hasta 24 canales. Estos canales se multiplexan usando flexible division multiplexing.

La señal que se emite por cada canal se controla desde uno de los actuadores de la emisora (ver la figura 4.2): palancas (sticks), interruptores (switches SA, SB, etc.) o botones (knobs S1, S2). Por ejemplo, moviendo una de las palancas se puede variar la señal que se emite por uno de los canales.    
<img src="https://github.com/user-attachments/assets/f535fc30-2ba6-4ebb-b21d-a971bc9cedf0" width="400" height="200">  
**Figura 4.2:** Los diferentes actuadores de la emisora de radio

La señal multiplexada es separada por el receptor, obteniendo así las señales de cada uno de los canales. La señal de cada canal se convierte en una señal PWM, que se emite a través de la salida del receptor correspondiente a este canal (hasta 8 canales diferentes en el receptor que vamos a utilizar). Ver la figura 4.3.    
<img src="https://github.com/user-attachments/assets/6d38dcd3-8c20-4108-b565-b5b0323cbe35" width="200" height="200">   
**Figura 4.3:** Las 8 salidas del receptor que emiten las señales PWM correspondientes a los 8 canales 

Cada uno de las señales PWM generados por el receptor puede controlar un dispositivo diferente. Dependiendo de la amplitud de los pulsos de la señal (que dependerá de la señal recibida por el canal correspondiente), el motor conectado a este canal girará a más o menos velocidad, o el servomotor adoptará una posición u otra. Esta capacidad de control individualizado de dispositivos mediante señales PWM es fundamental en el funcionamiento de los sistemas controlados por radio, ya que permite una gran variedad de aplicaciones y ajustes precisos en función de las necesidades específicas de cada usuario. Para complementar esta explicación básica, se recomienda ver el vídeo mencionado.
[![](https://markdown-videos-api.jorgenkh.no/url?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DLyPtzv0y5DE)](https://www.youtube.com/watch?v=LyPtzv0y5DE)


### 3. Cargar la batería del transmisor
Para cargar la batería del transmisor, solo necesitas conectarlo a una computadora mediante USB. El transmisor viene con el cable necesario, que se conecta a la parte posterior del transmisor y a cualquier puerto USB de la computadora. La luz indicadora se pondrá en verde, como se muestra en la figura 4.4.    
<img src="https://github.com/user-attachments/assets/ef667639-7d7f-489e-b00f-46e2826c3a51" width="300" height="400">    
**Figura 4.4:** Carga de la batería de la emisora

Como indica el documento pequeño que viene con el transmisor, la luz verde se apagará cuando la batería esté completamente cargada.

### 4. Insertar la tarjeta MicroSD
La figura 4.5 muestra cómo insertar la tarjeta MicroSD en el transmisor.     
<img src="https://github.com/user-attachments/assets/038ac382-6416-403d-bf4a-55de81651145" width="300" height="300">    
**Figura 4.5:** Inserción de la MicroSD en la emisora

De hecho, la tarjeta MicroSD no es imprescindible para el funcionamiento del transmisor. Sin embargo, la incorporación de la tarjeta amplía notablemente la capacidad de almacenamiento, lo que permite agregar sonidos, música y elementos que pueden mejorar mucho la experiencia del usuario del transmisor. En esta guía no dedicaremos más tiempo a esta cuestión. Se pueden encontrar más detalles en este vídeo:
 
[![](https://markdown-videos-api.jorgenkh.no/url?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DqYo99q0HZMg)](https://www.youtube.com/watch?v=qYo99q0HZMg)

### 5. Calibración de la radio
Antes de configurar la radio para controlar el dron, es necesario calibrarla. En el siguiente vídeo se muestra cómo realizar esta operación.      
[![](https://markdown-videos-api.jorgenkh.no/url?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DplLWhwmY-rM)](https://www.youtube.com/watch?v=plLWhwmY-rM)


### 6. Configuración
Para controlar el dron desde el transmisor de radio, necesitamos crear un modelo que asocie cada uno de los actuadores que queremos utilizar con uno de los canales del transmisor. Para crear el modelo, se puede utilizar el software Open TX Companion que debe instalarse en la computadora (descargar desde https://www.open-tx.org/ ).

Para crear el modelo, primero debes poner la radio en modo USB, como se muestra en este vídeo.

[![](https://markdown-videos-api.jorgenkh.no/url?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DZ0F_QMYElzo)](https://www.youtube.com/watch?v=Z0F_QMYElzo) 

Ahora ya se puede crear el modelo. El vídeo muestra cómo hacerlo.

 
[![](https://markdown-videos-api.jorgenkh.no/url?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DeyahLlB3fH0)](https://www.youtube.com/watch?v=eyahLlB3fH0)


Estos son los pasos que se pueden ver en el vídeo:

1.	Iniciar Open TX.
2.	Cargar los modelos que ya tiene en ese momento el transmisor (que está conectado a la computadora mediante USB).

ATENCIÓN: Aunque el vídeo no lo muestra, es importante verificar que los sticks de la radio estén configurados correctamente (en Estados Unidos la configuración de los sticks es diferente a la de Europa). Las dos imágenes de la figura 4.6 indican cómo realizar esta verificación.     
<img src="https://github.com/user-attachments/assets/46ec777c-19d3-40b9-93e4-06017cbb0a0f" width="400" height="150">     
**Figura 4.6:** Verificar que los sticks de la emisora están en el modo correcto

3.	Crear un nuevo modelo (newModel en el vídeo)
4.	Para la asignación de las palancas del transmisor a los canales, sigue la tabla siguiente:

| Operación | Descripción | Canal |
|-----------|-----------|-----------|
| Thr o Throttle  |Movimiento vertical de la palanca izquierda: Elevación o descenso del dron.| canal 3|
| Ail o Roll	  |Movimiento horizontal de la palanca derecha: Desplazamiento del dron a derecha e izquierda.| canal 1|
| Ele o Pitch	  |Movimiento vertical de la palanca derecha: Dirección del dron hacia adelante o hacia atrás.| canal 2|
| Rud o Yaw  |Movimiento horizontal de la palanca izquierda: Rotación del dron sobre su propio eje.| canal 4|

5.	Asignar el interruptor SB (que tiene tres posiciones) al canal 5.
6.	Asignar el interruptor SF (que tiene dos posiciones) al canal 7.
7.	Simular el modelo para verificar que es correcto.
8.	Guardar el modelo en el transmisor.

Aunque el vídeo no lo muestre, es conveniente asignar el interruptor SC (con tres posiciones) al canal 6. Más adelante se indicará para qué se necesitarán los interruptores SB, SC y SF.

También puedes crear un modelo utilizando directamente el radiotransmisor, como se muestra en este vídeo:    
[![](https://markdown-videos-api.jorgenkh.no/url?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DZFuazchCv4o)](https://www.youtube.com/watch?v=ZFuazchCv4o)    

Por último, es necesario vincular el transmisor (con el modelo creado) al receptor. El procedimiento depende del tipo de protocolo utilizado por el receptor (ACCESS o ACCST). Estos vídeos describen el procedimiento para cadZFuazchCv4oa caso.

[![](https://markdown-videos-api.jorgenkh.no/url?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D07qpdApsCAI)](https://www.youtube.com/watch?v=07qpdApsCAI)     
(protocolo ACCESS)     

[![](https://markdown-videos-api.jorgenkh.no/url?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3Dk5EPJiipXcc)](https://www.youtube.com/watch?v=k5EPJiipXcc)     
(protocolo ACCST)    

### 7. Prueba
La prueba consiste en conectar cada uno de los motores y el servo a diferentes canales de la radio para verificar que todo funciona correctamente. El siguiente vídeo muestra cómo hacerlo.
 
[![](https://markdown-videos-api.jorgenkh.no/url?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D1nugfbtLK9Q)](https://www.youtube.com/watch?v=1nugfbtLK9Q)


Esta es la secuencia de pasos que se pueden ver en el vídeo:
1.	Se conecta el conector T a la batería.
2.	Se conecta el conector UBEC al conector T.
3.	Se conecta el conector UBEC para alimentar el receptor.
4.	El servo se conecta al canal 5, que se controla mediante el interruptor SB.
5.	El servo se conecta al canal 7, que se controla mediante el interruptor SF.
6.	Se conecta uno de los motores al canal 1, que se controla con el movimiento de roll (movimiento horizontal de la palanca derecha). Se utiliza uno de los cables trenzados como extensión para ayudar.
7.	Se conecta la placa de distribución de energía a la batería para alimentar los motores.
8.	Se hace girar el motor con el movimiento de roll.
9.	Se conecta el mismo motor al canal 3, que se controla con el movimiento de throttle (movimiento vertical de la palanca izquierda). Se observa el diferente comportamiento de la palanca de throttle y la palanca para el roll.
10.	Se verifica que los motores giren en el sentido correcto. El vídeo muestra que este no es el caso en uno de los motores. Es el momento de cambiar las conexiones del variador ESC con el motor hasta conseguir que el sentido de giro del motor sea el correcto. Esta es una operación molesta porque hay que desatornillar el brazo y desconectar el LED para poder cambiar las conexiones del variador al motor.
11.	Se sigue el mismo proceso con todos los motores.
### 8. Invertir el movimiento de Pitch
La configuración predeterminada del piloto automático hace que el pitch del dron esté invertido. Es decir, cuando movemos la palanca de la derecha hacia adelante, el dron se mueve hacia atrás. Este comportamiento es poco natural, por lo que es necesario invertir el canal del pitch en la emisora. Esto se puede hacer directamente en la radio, como muestra la figura 4.7. (Este proceso lo has podido ver en uno de los videos anteriores).    
<img src="https://github.com/user-attachments/assets/3a5fb2e4-59d4-4ef9-801f-3b3e06ad2740" width="400" height="250">    
**Figura 4.7:** Inversión de la señal de pitch
   
## Actividad 5: El Autopiloto
### 1. Presentación
En esta actividad se realizarán las primeras configuraciones básicas del piloto automático. Se trata del Pixhawk Orange Cube. El kit correspondiente contiene los elementos que se muestran en la figura 5.1.    
 <img src="https://github.com/user-attachments/assets/b965afaa-6dfc-4886-96c2-6a12a1beb776" width="400" height="400">      
**Figura 5.1:** Componentes del kit Orange Cube     


### 2. Conceptos básicos
El piloto automático es un dispositivo muy sofisticado. Es capaz de generar la combinación adecuada de señales PWM necesarias para realizar las operaciones básicas de vuelo: despegar, aterrizar, moverse hacia adelante, a la izquierda o a la derecha, rotar, etc. Para hacerlo, debe estar conectado al receptor de radio, para que este pueda enviar las órdenes que llegan del transmisor de radio. Esta conexión se muestra en la figura 5.2. El receptor de radio tiene una salida que se llama SBUS OUT, por la cual envía de forma multiplexada las señales que recibe por los diferentes canales de radio (además de generar por separado las señales PWM correspondientes a cada canal, tal como hemos visto en la actividad anterior). La salida SBUS OUT debe conectarse a la entrada RCIN del piloto automático con el cable que se incluye en el kit de complementos.     
 <img src="https://github.com/user-attachments/assets/02c86fd4-bf06-42e3-8d0b-f8ef3949bdb9" width="400" height="300">    
**Figura 5.2:** Connexión del receptor de radio con el autopiloto    

Como es lógico, las órdenes que daremos ahora desde el transmisor de radio ya no serán operaciones simples como las que vimos en la actividad (acelerar un motor específico moviendo una de las palancas). Sería imposible controlar el vuelo del dron a partir de órdenes de esta naturaleza. Ahora, cuando movamos una palanca o un interruptor, estaremos ordenando al piloto automático que realice una operación más compleja (despegue, gire a la derecha, regrese a casa, etc.).    

Recuerda que en la actividad anterior se preparó un modelo para el transmisor de radio (newModel) en el cual, por ejemplo, se asoció el canal 1 al movimiento horizontal de la palanca derecha. La señal recibida por el piloto automático a través de este canal se usará para controlar el movimiento de Roll (desplazamiento del dron derecha/izquierda). Lo mismo ocurre con otros canales, como se indica en la siguiente tabla.   
| Canal | Actuador | Movimiento |
|-----------|-----------|-----------|
| 1	| Ail	Roll | izquierda/derecha |
| 2	| Ele	Pitch | delante/atrás |
| 3	| Thr	Throttle |elevación/descenso |
| 4	| Rud	Yaw | giro sobre sí mismo |

El piloto automático también es capaz de generar las señales de control de los motores necesarias para mantener la estabilidad del dron, según el modo de vuelo elegido. Por ejemplo, si queremos en modo AltHold, el piloto automático mantendrá la altitud constante mientras el piloto no la modifique desde el transmisor. Para hacerlo, el piloto automático utilizará la información que obtiene de sensores internos (barómetro, acelerómetro, giroscopio). La precisión de esta operación podría mejorar si incorporamos al dron un sensor externo adicional, como un altímetro láser, que proporcionaría más información al piloto automático. En el caso de que queramos en modo Loiter, el piloto automático utilizará la señal GPS que recibe del exterior para mantener la estabilidad con mayor precisión que solo con los sensores internos, aunque solo podremos volar en modo Loiter si estamos en un lugar donde llegue la señal GPS. Como es lógico, en algún momento hay que decirle al piloto automático qué modo de vuelo debe usar (hay muchos otros, además de AltHold y Loiter). Para hacerlo, utilizaremos el interruptor SB del transmisor, que tiene tres posiciones, lo que nos permitirá seleccionar uno de entre tres modos de vuelo. Por ahora, los que se configurarán son estos tres:   

* AltHold: Estabiliza la altitud (y también pitch y roll) usando los sensores internos.
* Loiter: Estabiliza la altitud (y también pitch y roll) pero usando la señal GPS. Requiere cobertura GPS.
* RTL (Return To Launch): El dron regresará automáticamente al punto desde el que despegó. Este modo también requiere cobertura GPS para que el dron tenga geolocalizado el punto de despegue.    

El piloto automático también es capaz de ejecutar automáticamente un plan de vuelo, es decir, recorrer una secuencia de puntos geolocalizados (que normalmente llamamos waypoints). En este caso, es necesario disponer de una estación terrestre donde se configurará el plan de vuelo y se enviará al piloto automático. La estación terrestre también puede recoger los datos de telemetría que enviará el piloto automático durante el vuelo para analizarlos posteriormente. El software de estación terrestre más utilizado (y gratuito) es Mission Planner, que es el que utilizaremos en los siguientes pasos.    
### 3. Pasos de la actividad
Los pasos se indican en la tabla, que será la guía de esta actividad. Para cada paso tenemos una indicación del minuto/segundo del vídeo indicado en el apartado 1, donde se describe el paso que se debe hacer. Algunos pasos tienen una nota aclaratoria que hay que leer antes de hacer el paso correspondiente.    

| Paso | Descripción | Instrucciones |
|-----------|-----------|-----------|
| 1	| Conectar el receptor de radio, el receptor GPS y el buzzer al autopiloto | https://youtu.be/2Jm9zshM1Sc |
| 2	| Instalar Mission Planner al portatil | https://ardupilot.org/planner/docs/mission-planner-installation.html |
| 3	| Instalar en el autopiloto el firmware requerido e indicar el tipo de Frame e Initial Parameter Setup | https://youtu.be/MUiUbNqETsk |
| 4	| Configurar algunos parámetros. Después de hacerlo, debemos reiniciar el autopiloto: DATA -> Actions -> PREFLIGHT REBOOT_SHOOT Si todo es correcto, se encenderán los LEDs y se escuchará el silbido del buzzer | https://youtu.be/8aF4e0XCMpo (Nota 1) |
| 5	| Calibrar el acelerómetro y Brújula (Compass) | https://youtu.be/slux0oX2Qig |
| 6	| Calibrar la radio | https://youtu.be/0Ii1I8D2gro (Nota 2) |
| 7	| Configurar los modos de vuelo (seleccionar: AltHold, Loiter y RTL) y RTL altitude | https://youtu.be/PNEuuCZnhX0 (Nota 3) |

**Nota 1**    
Como se indica en el vídeo, estos son los parámetros que se deben configurar:

CAN_P1_DRIVER -> 1    
GPS_TYPE -> 9    
NTF_LED_TYPES -> 231    
BRD_SAFETY_DEFLT -> 0   

Haz clic en "Write Params" al finalizar. Las funciones del bus CAN estarán disponibles después de reiniciar el autopiloto.

**Nota 2**    
Al calibrar la radio verás los valores máximo y mínimo de la señal PWM generada por cada uno de los actuadores. De momento, sólo son importantes los valores generados por el acelerador. Tome nota de estos valores (estos valores deben ser similares a 982 y 2006)

**Nota 3**    
El modo de vuelo RTL se utiliza cuando quieres que tu dron vuelva a la posición inicial inmediatamente (por ejemplo, en caso de problemas). Para ello, el dron subirá hasta alcanzar una altitud determinada y volará directamente a casa. Debes configurar esta altitud en la lista completa de parámetros, como se muestra en la figura 5.3. Una buena elección es 7 metros.
 <img src="https://github.com/user-attachments/assets/483e606c-f060-48eb-bff5-4e259b09b968" width="400" height="200">    
**Figura 5.3:** Configuración de la altura para RTL

## Actividad #6: Montaje de la carcasa (parte 2)   
### 1. Presentación
En esta actividad finalizaremos el montaje de la carcasa incorporando, entre otros elementos, el receptor de radio, el autopiloto (al cual conectaremos los motores), el receptor GPS y la radio de telemetría. La figura 6.1 muestra el aspecto del dron una vez finalizada esta actividad (aunque las hélices solo se colocarán en el momento de realizar las pruebas de vuelo).   
<img src="https://github.com/user-attachments/assets/2994a2ed-6a16-42f1-9ad5-70507fd1965c" width="400" height="300">    
**Figura 6.1:** El dron al final de esta actividad    

Para facilitar el proceso, a continuación, se detallan una serie de pasos a seguir (con imágenes que pueden ser útiles). En el siguiente vídeo se proporciona información que puede ser muy útil para algunos pasos.     
[![](https://markdown-videos-api.jorgenkh.no/url?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DmwJNhkAG2bE)](https://www.youtube.com/watch?v=mwJNhkAG2bE)  


Varios de los dispositivos se conectarán al autopiloto. La figura 6.2 muestra las diferentes entradas para conexiones de Orange Cube, a las que nos referiremos al describir cada uno de los pasos.     
 <img src="https://github.com/user-attachments/assets/515596bd-70dc-4655-b33f-ec981c0a684e" width="400" height="200">    
**Figura 6.2:** Entradas para conexiones al Orange Cube

### 2. Fijar el autopiloto a la plancha superior
Para este paso, es recomendable observar el vídeo al minuto 4:30. Las imágenes de la figura 6.3 pueden ser de ayuda.    

ATENCIÓN: Es crucial que el autopiloto quede perfectamente centrado en la plancha superior. El centro geométrico del cubo naranja debería coincidir con el centro geométrico de la plancha.    
 <img src="https://github.com/user-attachments/assets/f6aaa27f-d478-448d-8b48-eb5b2330f7ae" width="400" height="250">    
**Figura 6.3:** Fijar el autopiloto a la plancha superior

### 3. Conectar el receptor de radio al autopiloto y alimentar el autopiloto    
Recuerda que la conexión entre el receptor y el autopiloto se realiza con un cable que conecta SBUS OUT del receptor con RCIN del autopiloto. Esta conexión proporciona alimentación al receptor de radio (que en la actividad #5 se alimentaba con el adaptador UBEC). Presta atención a la polaridad de los tres pines implicados en la conexión. Aunque aún no es el momento de fijar el receptor de radio a las planchas de la carcasa, puede ser conveniente ir eligiendo el lugar donde se colocará para que el cableado sea lo más sencillo posible.    

Por otro lado, recuerda que para alimentar el autopiloto debes utilizar el cable POWER2 que se conectó a la placa de distribución de energía. La figura 6.4 muestra estas conexiones.    
 <img src="https://github.com/user-attachments/assets/8b8475d0-5987-471b-bca5-7663cf1a7754" width="400" height="500">     
**Figura 6.4:** Conexiones para alimentar al autopiloto y para conectarlo al receptor de radio 

### 4. Conectar los motores al autopiloto    
Para este paso se recomienda ver el vídeo en el minuto 6:25. Es importante tener en cuenta que los motores están numerados según se muestra en la figura 6.5 (izquierda). Cada motor debe conectarse a la salida MAIN OUT correspondiente del autopiloto, como se muestra en la figura 6.5 (derecha).

Recuerda que los motores colocados en los soportes naranjas (los motores delanteros) tienen unas extensiones que pueden facilitar esta conexión. Es perfectamente posible que la conexión se pueda hacer sin la ayuda de estas extensiones, lo cual es preferible para que el "lío" de cables sea el menor posible.     
<img src="https://github.com/user-attachments/assets/9e2d335d-9077-4b1a-8ce6-c7ac2da91d9a" width="400" height="200">    	 
**Figura 6.5:** Connexión de los motores al autopiloto 

### 5. Instalar el receptor GPS   
El receptor GPS debe colocarse en la parte delantera de la placa superior. Las imágenes de la figura 6.6 pueden ayudar en este paso.

Observa que el cable negro debe pasar por el interior del soporte. Este cable tiene dos conectores. Aunque solo es necesario conectar el con cables rojos/negros a CAN1 (como se muestra en la imagen derecha), se recomienda conectar también el otro conector (blanco/verde) a CAN2 (cosa que no se muestra en la imagen derecha).    
<img src="https://github.com/user-attachments/assets/32628979-53f6-44ea-9ec4-4ecbdb4d6839" width="400" height="300">    	 
**Figura 6.6:** Instalación del receptor GPS    
### 6. Instalar la radio de telemetría
La radio de telemetría permitirá comunicar el autopiloto con Mission Planner, para permitir, por ejemplo, enviar órdenes al dron o recibir datos de telemetría durante el vuelo. Lógicamente, esta información no se puede enviar durante el vuelo a través de la conexión USB que se utilizó en la actividad #6 para conectar por cable el autopiloto y Mission Planner.

El kit de radio de telemetría contiene dos transmisores/receptores y los cables necesarios para la comunicación. Uno de los transmisores/receptores se conectará a una entrada USB del portátil. El otro se conecta al autopiloto en la entrada Telem1 (como se muestra en la figura 6.7).

Es conveniente ir seleccionando el lugar de las planchas donde se fijará más adelante el transmisor/receptor para facilitar el cableado.     
<img src="https://github.com/user-attachments/assets/a231a281-45a0-4fde-ba5d-70da0c36ed8c" width="400" height="300">   	  
**Figura 6.7:** Conexión de la radio de telemetría    
#### 7. Instalar el buzzer   
Como se muestra en la figura 6.8, el zumbador se conecta a la entrada USB del autopiloto.     
<img src="https://github.com/user-attachments/assets/fb424a8f-8672-4c8b-a037-8a18ae224ab2" width="400" height="500">    	 
**Figura 6.8:** Connexión del buzzer    
### 8. Incorporar las tiras de Velcro y las cintas que se usarán para fijar la batería
La figura 6.9 ilustra esta operación. Observen que como medida de sujeción adicional se coloca cinta de Velcro.   
<img src="https://github.com/user-attachments/assets/e5990d57-50b8-4ced-a784-5ff66f3aa3e4" width="400" height="200">   	   
**Figura 6.9:** Colocación de las cintras para sujetar la batería   
 
### 9. Fijar todos los elementos
Es el momento de fijar bien todos los elementos a la carcasa (receptor de radio, radio de telemetría), utilizando cinta de Velcro y bridas, tal como muestran las imágenes de la figura 6.10.   
<img src="https://github.com/user-attachments/assets/28e92c9f-ef12-440b-bc09-2c51d551c75a" width="400" height="200">   	   
**Figura 6.10:** Fijación de algunos elementos al armazón   

## Actividad #7: Más calibraciones
### 1. Presentación
En esta actividad completarás la configuración de la plataforma. Entre otras cosas, calibrarás el ESC y probarás los motores, configurarás los modos de vuelo y cargarás los parámetros por defecto de tu frame. Al final, la plataforma estará lista para la primera prueba de vuelo.
No olvides recopilar la información necesaria (fotos y/o vídeos) para incorporarla al sitio de tu proyecto.
### 2. Pasos
Los pasos a realizar se enumeran en la tabla. Para cada paso se indica el minuto: segundo del video donde se puede ver cómo hacer el paso. De nuevo, es importante leer las notas aclaratorias antes del paso correspondiente.
| Paso | Descripción | Vídeo |
|-----------|-----------|-----------|
| 1  | Configuración de la radio dde telemetría|https://youtu.be/6xqEbOzUQSo |
| 2  | Calibrado de los variadores ESC | https://youtu.be/wO8QJQpC3IM |
| 3  | Configuración del servo, FailSave y Arm/Disarm| https://youtu.be/D1ne2W3uEEE  (Nota 1)|
| 4  | Configuración del monitor de bateria| https://youtu.be/DGpoN0KlAYY |
| 5  | Test de motores| https://youtu.be/w6N368HIncc |
| 6  | Carga de parámetros seleccionados | https://youtu.be/9pilQ3uT8mA |
| 7  | Comprobaciones finales |https://youtu.be/Af_ygwTi_s0 (Nota 3) |

La mayoría de los pasos requieren que el autopiloto esté conectado con Mission Planner. Recuerden que tenemos dos maneras de realizar esta conexión: mediante el cable USB o mediante la radio de telemetría. En este caso, ya que los pasos se darán con el dron en tierra, cualquiera de las dos conexiones es posible. Sin embargo, ya que en actividades anteriores ya se han hecho operaciones con la conexión vía USB, se propone que los siguientes pasos se hagan con la conexión vía radio de telemetría, para verificar que funciona correctamente. No obstante, se observará que la comunicación a través de esta vía es más lenta.
Nota 1
El parámetro FailSave especifica qué debe hacer el piloto automático si el sistema falla. Por el momento, sólo nos interesa especificar qué hacer si el dron pierde contacto con la radio (también puedes especificar qué hacer en caso de batería baja). Como puedes ver en el video debes especificar dos cosas. El FS PWM es el valor de la señal del acelerador por debajo del cual el piloto automático considerará que se ha perdido la radio. Recuerda que tomaste una nota sobre la señal PWM mínima que generará el modo RTL del acelerador indica que el dron debe volver al origen en caso de fallo (nota 2 en actividad #5). Obviamente el FS PWM debe ser un valor inferior al mínimo (en el video se asigna un valor de 975, que es inferior a 982).
La segunda decisión es qué hacer en caso de fallo de radio. Una buena opción es volver a casa (RTL).
Nota 2
Armar el dron permite que los motores empiecen a girar. Tendrás que armar el dron antes de empezar a volarlo. Desarmarlo hará que los motores dejen de girar.
Nota 3
Ten en cuenta que, si intentas armar el dron en modo Loiter, el sistema te dirá que el dron no se puede armar debido a una mala señal GPS, a menos que intentes armarlo en el exterior, donde se recibe una buena señal GPS. Por lo tanto, si se encuentra en el aula, intente armarlo en modo Alt Hold.
Ten en cuenta que si intentas armarlo con la radio apagada el sistema dará un error. ¿Podría explicar por qué?
Incluso con la radio encendida, al intentar armar el dron probablemente tendrás el error que se muestra en el video: PreArm: Check FS_THR_VALUE. En principio, incluso con el acelerador totalmente bajado, la señal PWM que se genera es superior a la FS PWM. Por lo que el sistema debería poder armarse.
Sin embargo, hay un valor umbral de 10, para asegurar que el parámetro FS PWM no está demasiado cerca del mínimo PWM del acelerador. Recuerde que el mínimo PWM del acelerador es 982 y el FS PWM es 975. La diferencia es menor que el valor umbral. La diferencia es menor que el valor umbral. Esta es la razón de la notificación de PreArm Check. Simplemente cambia el valor de FS PWM a 972 (o menos) y la notificación desaparecerá.
Nota 4
Cuando se pilota el dron de manera manual es importante, especialmente en las primeras pruebas de vuelo, que la velocidad a la cual asciende o desciende el dron sea moderada. Esta velocidad se puede configurar tal como muestra la figura 7.1, en la cual se ve cómo se cambia la velocidad por defecto (250 cm/s) por una inferior (100 cm/s).    
 <img src="https://github.com/user-attachments/assets/de28a838-34ec-492c-8cda-67acb079371f" width="400" height="200">   	    
**Figura 7.1:** Modificación de la velocidad de ascenso y descenso en pilotaje manual    
   
Nivel de la batería 

Debe comprobar con frecuencia el nivel de carga de la batería, como se muestra en la imagen 7.2.    
 <img src="https://github.com/user-attachments/assets/bbfb72d3-4330-4739-9030-075e38d7fca6" width="400" height="300">   	   
**Figura 7.2:** Comprobación del nivel de bateria    
Usted debe verificar que la carga en cada célula es de al menos 3,7. Si no es así, es hora de cargar.






