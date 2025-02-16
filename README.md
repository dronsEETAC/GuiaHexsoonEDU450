# Guía para el Montaje, configuración y preparación para pruebas de vuelo de un dron Hexsoon EDU 450
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

Por otro lado, la figura 3.7 (izquierda) determina en qué sentido (CW o CCW) debe girar cada motor según su posición en la carcasa. Recordemos que los motores 1 y 3 de la figura, que son los delanteros, están fijados a los soportes de color naranja. A la vista de la figura 3.6 queda claro que los motores con punto blanco (que son los que giran en sentido CCW) deben ocupar las posiciones 1 y 2. Esta disposición se muestra también en la figura 3.7 (derecha).

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

El armazón resultante de la actividad anterior	 
Emisora de radio	 
MicroSD (Normalmente ya dentro de la emisora)	 
Receptor de radio	 
Cable UBEC para alimentar el receptor de radio	 
El servo	 
El connector en T	 
La batería	 

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
 

https://www.youtube.com/watch?v=LyPtzv0y5DE

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
 

https://www.youtube.com/watch?v=qYo99q0HZMg


### 5. Calibración de la radio
Antes de configurar la radio para controlar el dron, es necesario calibrarla. En el siguiente vídeo se muestra cómo realizar esta operación.

https://youtu.be/plLWhwmY-rM

### 6. Configuración
Para controlar el dron desde el transmisor de radio, necesitamos crear un modelo que asocie cada uno de los actuadores que queremos utilizar con uno de los canales del transmisor. Para crear el modelo, se puede utilizar el software Open TX Companion que debe instalarse en la computadora (descargar desde https://www.open-tx.org/ ).

Para crear el modelo, primero debes poner la radio en modo USB, como se muestra en este vídeo.

 
https://youtu.be/Z0F_QMYElzo

Ahora ya se puede crear el modelo. El vídeo muestra cómo hacerlo.

 

https://youtu.be/eyahLlB3fH0

Estos son los pasos que se pueden ver en el vídeo:

1.	Iniciar Open TX.
2.	Cargar los modelos que ya tiene en ese momento el transmisor (que está conectado a la computadora mediante USB).

ATENCIÓN: Aunque el vídeo no lo muestra, es importante verificar que los sticks de la radio estén configurados correctamente (en Estados Unidos la configuración de los sticks es diferente a la de Europa). Las dos imágenes de la figura 4.6 indican cómo realizar esta verificación.     
<img src="https://github.com/user-attachments/assets/46ec777c-19d3-40b9-93e4-06017cbb0a0f" width="400" height="150">     
**Figura 4.6:** Verificar que los sticks de la emisora están en el modo correcto

3.	Crear un nuevo modelo (newModel en el vídeo)
4.	Para la asignación de las palancas del transmisor a los canales, sigue la tabla siguiente:


Thr o Throttle	Movimiento vertical de la palanca izquierda: Elevación o descenso del dron.
	canal 3
Ail o Roll	Movimiento horizontal de la palanca derecha: Desplazamiento del dron de derecha a izquierda.
	canal 1
Ele o Pitch	Movimiento vertical de la palanca derecha: Dirección del dron hacia adelante o hacia atrás.
	canal 2
Rud o Yaw	Movimiento horizontal de la palanca izquierda: Rotación del dron sobre su propio eje.
	canal 4

5.	Asignar el interruptor SB (que tiene tres posiciones) al canal 5.
6.	Asignar el interruptor SF (que tiene dos posiciones) al canal 7.
7.	Simular el modelo para verificar que es correcto.
8.	Guardar el modelo en el transmisor.

Aunque el vídeo no lo muestre, es conveniente asignar el interruptor SC (con tres posiciones) al canal 6. Más adelante se indicará para qué se necesitarán los interruptores SB, SC y SF.

También puedes crear un modelo utilizando directamente el radiotransmisor, como se muestra en este vídeo:
https://youtu.be/ZFuazchCv4o

Por último, es necesario vincular el transmisor (con el modelo creado) al receptor. El procedimiento depende del tipo de protocolo utilizado por el receptor (ACCESS o ACCST). Estos vídeos describen el procedimiento para cada caso.

 
(ACCESS) https://youtu.be/07qpdApsCAI

(ACCST) https://youtu.be/k5EPJiipXcc
### 7. Prueba
La prueba consiste en conectar cada uno de los motores y el servo a diferentes canales de la radio para verificar que todo funciona correctamente. El siguiente vídeo muestra cómo hacerlo.
 

https://youtu.be/1nugfbtLK9Q

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
8. Invertir el movimiento de Pitch
La configuración predeterminada del piloto automático hace que el pitch del dron esté invertido. Es decir, cuando movemos la palanca de la derecha hacia adelante, el dron se mueve hacia atrás. Este comportamiento es poco natural, por lo que es necesario invertir el canal del pitch en la emisora. Esto se puede hacer directamente en la radio, como muestra la figura 4.7. (Este proceso lo has podido ver en uno de los videos anteriores).    
<img src="https://github.com/user-attachments/assets/3a5fb2e4-59d4-4ef9-801f-3b3e06ad2740" width="400" height="250">    
**Figura 4.7:** Inversión de la señal de pitch

