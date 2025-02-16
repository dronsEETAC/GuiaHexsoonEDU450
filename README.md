# Guía para el Montaje, configuración y preparación para pruebas de vuelo de un dron Hexsoon EDU 450
## 1.	Presentación
En esta guía se describe, paso a paso, el proceso de montaje, configuración y pruebas de vuelo de un dron. El punto de partida es un kit con todos los componentes necesarios, que se muestra en la figura 1.  
<img src="https://github.com/user-attachments/assets/842b8bbd-00a6-4751-b6da-0cb329c5aa3e" width="300" height="300">      
Figura 1: El kit   

El resultado final es el dron que se muestra en la figura 2, bien configurado y preparado para volar.    
<img src="https://github.com/user-attachments/assets/f1ae0ac4-1545-4fba-a412-fd283c784590" width="300" height="300">     
Figura 2: El dron resultante

El dron es un cuatrimotor que incorpora un piloto automático. El dron puede ser guiado manualmente a través de la emisora de radio, pero también desde una estación de tierra (por ejemplo, un portátil) que ejecute el software Mission Planner. Usando ese mismo software es posible también crear misiones en forma de secuencia de puntos a recorrer de manera automática por el dron. Finalmente, también es posible desarrollar nuestra propia estación de tierra (por ejemplo, en Python), lo cual multiplica las posibilidades de aprendizaje, experimentación y también diversión. La figura 3 muestra dos ejemplos. A la izquierda se muestra la pantalla de una web app que permite controlar el dron desde cualquier teléfono móvil. A la derecha se muestra una imagen de una aplicación de escritorio que permite controlar el dron con las posiciones de la mano.   
<img src="https://github.com/user-attachments/assets/c8f92816-01e5-4a30-afb5-701f54207c97" width="500" height="200">      
Figura 3: Un par de aplicaciones que pueden desarrollarse para controlar el dron 

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

## 3. Actividad 1: Lo más básico de los drones y sus componentes
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

