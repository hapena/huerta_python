# huerta_python


                                                           HUERTA INTELIGENTE
                                                           
                                                           
Descripción del proyecto:

El proyecto Huerta Inteligente se plantea en el contexto de la revolución industrial 4.0 y el uso de las TIC en el ámbito urbano; debido a la constante necesidad del uso adecuado de los recursos naturales y en la búsqueda  de incrementar y mejorar la producción de  productos de primera necesidad se genera la idea de automatizar  las huertas existentes o de generar nuevas huertas tecnológicas y controladas para autoconsumo.
La Academia Cisco del colegio Jorge Gaitán Cortés utilizará cómo herramientas mediadoras la programación en Python y Arduino, los conceptos de Internet de las Cosas y Redes para mejorar y crear las condiciones de producción de alimentos de primera necesidad en entornos controlados para espacios urbanos como patios o terrazas de casas o edificios. 
En el proyecto participarán estudiantes de grado décimo y undécimo de la academia CISCO, quienes generarán   prototipos del sistema de control de la huerta inteligente a través de distintos sistemas que monitorean y generan las condiciones óptimas para el mejoramiento de la producción de productos como verduras, hortalizas, frutas, legumbres o plantas aromáticas.
Debido a todo lo anterior el sistema creado se podrá ir mejorando y actualizando según las tecnologías que vayan saliendo en el mercado.
El proyecto será asesorado por los instructores de la Academia SED-CISCO Jorge Gaitán Cortes IED.

Los estudiantes están en proceso de certificación CISCO en Partner: PCAP - Programming Essentials in Python, IoT Fundamentals: Connecting Things y CCNAv7: Introduction to Networks.
Se cuenta con el material de laboratorio ofrecido por la institución educativa; entre ellos las plataformas de desarrollo basadas en hardware Libre (Arduino UNO R3, Raspberry Pi 4 Modelo B 4gb Kit, Esp32 Wifi + Bluetooth 4.2 Ble Nodemcu Esp32s), sensores y actuadores; además en la parte del software se trabaja, Python 3, Arduino, Thonny IDE, y las plataformas de desarrollo de Cisco Webex Teams. 	

Ambiente de desarrollo: 

                        
![image](https://user-images.githubusercontent.com/71275875/137029844-ef56fb11-10c6-4d38-80aa-a4bb50134257.png) ![image](https://user-images.githubusercontent.com/71275875/137029863-eaca112c-4a7f-4b29-8f76-93c3647d0e63.png)



En este apartado se procederá a explicar el contenido el cual es la base para que el programa funcione de la manera establecida, se abordarán aspectos del código y se profundizará en el circuito conformado para este proyecto. 


Circuito:

![image](https://user-images.githubusercontent.com/71275875/136988483-073d0be7-3961-4b2b-9fb6-14ea4bb24947.png)


Distribución de Pines:

![image](https://user-images.githubusercontent.com/71275875/137044704-2f3d14c3-6367-4f59-a3f0-a7560df8fffa.png)



Recursos:

Modulo ESP32 – 30 Pines: 
 
 ![image](https://user-images.githubusercontent.com/71275875/136988836-bb348b8a-5a54-4472-ac89-adfbb2bf81f9.png)


Creado y desarrollado por Espressif Systems, ESP32, una serie de microcontroladores de bajo costo y de bajo consumo con sistema en chip con Wi-Fi y Bluetooth de modo dual integrados. Este dispositivo tomaría los datos de nuestro sensor y así mismo enviando estos registros de temperatura a la nube.

Sensor de temperatura y humedad DTH11:

 ![image](https://user-images.githubusercontent.com/71275875/136988862-27d5f0e1-7615-4448-962e-6dc1a25da979.png)

 
El DHT11 es un sensor digital de bajo costo de temperatura y humedad. El sensor de humedad utiliza un principio capacitivo mientras que el de temperatura utiliza un termistor. El sensor se integra fácilmente con un Arduino dado que contiene librerías desarrolladas específicamente para el mismo. Las lecturas del sensor sólo pueden realizarse cada dos segundos. El sensor Cuenta con 3 pines (Vcc, GND, OUT) conectados que se conectan a los pines de la tarjeta en el mismo orden a (3.3v, GND, Pin15).

Luz LED 5mm:
 
 ![image](https://user-images.githubusercontent.com/71275875/136988895-b82f9508-9d54-42d0-b04e-e181456c1051.png)

Diodos que  disponen de un ánodo y un cátodo suelen utilizarse en dispositivos electrónicos como iluminaciones de semáforos, juguetes, publicidades e incluso como alarmas, la funcionalidad varía dependiendo del enfoque que le quiera brindar su usuario. El led cuenta con dos pines (ánodo  y cátodo) que se conectan a los pines de la tarjeta en el mismo orden a (GND, Pin2 y Pin4).


Sensor de humedad suelo: 

![image](https://user-images.githubusercontent.com/71275875/136988975-20836032-2713-4d83-b3b3-df2434e0c371.png)

 
El módulo sensor de humedad de suelo resulta ser otro módulo que utiliza la conductividad entre dos terminales para determinar ciertos parámetros relacionados a agua, líquidos y humedad.  El sensor Cuenta con 3 pines ( + , - , s) conectados que se conectan a los pines de la tarjeta en el mismo orden a (3.3v, GND, Pin39).


IFTTT: 
 
 ![image](https://user-images.githubusercontent.com/71275875/136989039-16e56031-b42a-4ae1-8dc9-efb28fa83843.png)

Como aplicación gratuita para programar funciones o tareas para realizarlas de forma automática utilizamos IFTTT una plataforma basada en servicio web dando como resultado la captura de la temperatura, humedad  y a su vez enviando esta información a una BD como hoja de cálculo en drive y correos electrónicos de Google.

![image](https://user-images.githubusercontent.com/71275875/136990488-24e27c78-e6ee-496c-813f-79865622f114.png)

Es una plataforma en línea y aplicación Android. Permite automatizar procesos: desde inicios de sesión hasta programación con diferentes aplicaciones Android. 


Thonny:

 ![image](https://user-images.githubusercontent.com/71275875/136989086-a85faa6b-b64f-4bb6-9096-705f47307683.png)

Thonny es un IDE de Python para principiantes, desarrollado en la Universidad de Tartu, Estonia, que tiene un enfoque diferente ya que su depurador está diseñado específicamente para el aprendizaje y la programación de enseñanza. ... Instalación sencilla; viene integrado con python 3.6




Lenguaje de programación Python Vers. 3.9 

![image](https://user-images.githubusercontent.com/71275875/136989112-df0c981f-bdb5-4d4b-b267-f85415738a31.png)

 
Python es un lenguaje de escritura rápido, escalable, robusta y de código abierto, ventajas que hacen de Python un aliado perfecto para la Inteligencia Artificial. Permite plasmar ideas complejas con unas pocas líneas de código, lo que no es posible con otros lenguajes.

El codigo:


El código ha sido escrito en el lenguaje de programación Python con un enfoque orientado a objetos, haciendo uso de una de las diferentes modalidades que nos brinda este lenguaje, en este caso se construyó en MicroPython y se hicieron uso de librerías enfocadas al funcionamiento del sensor DHT11 y sensor de Agua.

1.(Líneas 1 a 3) En primer lugar, se importan los módulos “machine, time, urequests, network, DHT11”, para usar los pines de la tarjeta, leer los diferentes sensores y establecer comunicación Wifi para envío de datos a internet a través del uso de diferentes Apis.

    import network, time, urequests
    from dht import DHT11
    from machine import Pin, ADC


2.(Líneas 5 a 10) Creamos los diferentes objetos que me permitirán realizar la lectura de los diferentes sesnores; entre ellos el objeto “sensor_Hs” que utiliza el pin 36 de la tarjeta para medir la humedad del suelo;
  El “bojeto sensorDHT” que utiliza el pin 15 de la tarjeta y permitirá leer temperatura y humedad ambiente.
  Los Objetos “rojo y Verde” que utilizan los pines 2y 4 y que serán los indicadores de niveles altos o adecuados de las diferentes variables.

    sensor_Hs = ADC(Pin(36))  # Creamis el objeto para realizar la lectura de humedad de suelo
    sensor_Hs.width(ADC.WIDTH_12BIT)  # permite regular la precisión de lectura
    sensor_Hs.atten(ADC.ATTN_11DB) # permite trabajar con 3.3v
    sensorDHT = DHT11 (Pin(15))  # Creamos el objeto DHT11 y asignamos el pin apara leer temperatura
    rojo = Pin(2, Pin.OUT)  # Creamos el objeto rojo y asignamos el pin
    verde= Pin(4, Pin.OUT)  # Creamos el objeto verde y asignamos el pin
 

3.(Líneas 14 a 25) Seguido al paso anterior procedemos a crear una nueva función que va a permitir la conexión Wifi de la tarjeta ESP32 a la red especificada en el fragmento de código "conectaWifi". 

    def conectaWifi(red, password):
         global miRed
         miRed = network.WLAN(network.STA_IF)     
         if not miRed.isconnected():              #Si no está conectado…
              miRed.active(True)                   #activa la interface
              miRed.connect(red, password)         #Intenta conectar con la red
              print('Conectando a la red', red +"…")
              timeout = time.time ()
              while not miRed.isconnected():           #Mientras no se conecte..
                  if (time.ticks_diff (time.time (), timeout) > 10):
                      return False
         return True

4.(Líneas 30 a 36) Luego procedemos a realizar el llamado a la función conectaWifi con las credenciales del usuario.
  Imprimimos los datos de conexión y creamos las variables url_1 y url_2 que nos va a permitir hacer uso de los applets creados en la página IFTTT:
  
  url_1: Utiliza el applet que envía datos de los sensores a una hoja de cálculo de Google.
  url_2: Utiliza el applet que envía datos de los sensores a un correo electrónico de Google.
  
          if conectaWifi("red", "password"):

              print("Conexión exitosa!")
              print('Datos de la red (IP/netmask/gw/DNS):', miRed.ifconfig())

              url_1 = "https://maker.ifttt.com/trigger/sensor_dth/with/key/XXXXXXXXXXXXXXXX?"  #  Applet IFTTT
              url_2 = "https://maker.ifttt.com/trigger/correo_emergencia/with/key/XXXXXXXXXXXXXXXX?" # Applet IFTTT

5.(Líneas 40 a 51) Creamos la función While True; el ciclo infinito que inicia los sensores realiza la lactura de las variables y envia los datos a la url_1.

      while (True):

              time.sleep (4)
              sensorDHT.measure()
              temp=sensorDHT.temperature()
              hum=sensorDHT.humidity()
              hum_suelo =  int(sensor_Hs.read())
              print ("T={:02d} ºC, H={:02d}, Hs={:02d} = %".format (temp,hum, hum_suelo))
              respuesta_1 = urequests.get(url_1+"&value1="+str(temp)+"&value2="+str(hum)+ "&value3="+str(hum_suelo))      
              print(respuesta_1.text)
              print (respuesta_1.status_code)
              respuesta_1.close ()

6.(Líneas 53 a 83) Creamos las condicionales “if y else” que de acuerdo a los valores de las variables enviaran alertas a los correos electrónicos haciendo uso de la url_2 y encenderán o apagaran los leds indicadores.


      if hum_suelo < 300 :

                  respuesta_2 = urequests.get(url_2+"&value1="+str(hum_suelo))      
                  print(respuesta_2.text)
                  print (respuesta_2.status_code)
                  respuesta_2.close ()
                  time.sleep(10)
                  rojo.value(1)
                  verde.value(0)

              elif temp> 25 :

                  respuesta_2 = urequests.get(url_2+"&value1="+str(temp))      
                  print(respuesta_2.text)
                  print (respuesta_2.status_code)
                  respuesta_2.close ()
                  time.sleep(10)
                  rojo.value(1)
                  verde.value(0)

              else:

                  rojo.value(0)
                  verde.value(1)
 
 
Resultados: 

a. Como resultado de la tarea programada podemos observar el histórico de eventos en un documento en linea de Google Drive, que ha generado el sensor y estos datos son tomados directamente del evento creado. 
 
 ![image](https://user-images.githubusercontent.com/71275875/136993813-950a1359-cb12-4925-8634-298e5a4b14c6.png)


b. Evento creado  genera una alerta y esta se envié por medio de correo electrónico de gmail a un usuario establecido.

![image](https://user-images.githubusercontent.com/71275875/136994295-93c2ed5f-cc6a-4085-99fa-801bb7023ebe.png)


c. Se visualiza en consola de Thonny el funcionamiento de la lectura de sensores; envío de datos y envío de alertas. 

![image](https://user-images.githubusercontent.com/71275875/136993377-8e02d2ca-c75e-472a-80db-6a32bcc36f36.png)

d. Se encienden los leds al generar alertas.

![image](https://user-images.githubusercontent.com/71275875/136994884-f00c12af-350b-41f6-bdf0-e16399d94931.png)


CONCLUSIONES:

se realizó el sistema de control para la Huerta Inteligente, donde al realizar un registro de la temperatura ambiente, Humedad ambiente, y humedad de suelo que será guardado en una hoja de cálculo Google, además de enviar un correo al de alerta a un usuario seleccionado una vez se superen niveles determinados, garantizando así que se lleve un control efectivo del cultivo. Esto se realiza en varios pasos primero se verifica la disponibilidad de conexión de internet, luego se realizan las lecturas a traves de los sensores y por ultimo se utilizan las apllets creadas en IFTTT para envio y almacenamiento de información.

Fue de gran ayuda el conocimiento adquirido en Python y Thonny para que se pudiera llevar a cabo este proyecto y darle una solución al problema planteado ya que, con este lenguaje y este IDE respectivamente, que nos permiten programar en microprocesadores como lo es la tarjeta ESP32 donde están guardados los archivos con la codificación lógica necesaria para cumplir con los objetivos para llegar a la solución del problema.

IFTTT fue muy importante para la realización de envío de información tanto a las hojas de cálculo de Google como a los correos electrónicos ya que de una forma muy sencilla se crea la conexión facilitando así el envío y recepción de información desde la ESP32 a las aplicaciones cabe resaltar que adicional se debe configurar el acceso a la red WIFI desde la ESP32 para su buen funcionamiento en el momento de realizar los envíos.

GitHub fue de gran ayuda ya que ente podemos encontrar muchos proyectos, donde podemos encontrar codificación lógica que nos puede ayudar a dar nuestro primer paso para la realización de nuevos proyectos y generar así las posibles soluciones a diferentes problemas que se puedan plantear.



Video:
https://youtu.be/3Nmunmac9s4
