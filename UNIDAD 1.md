### Actividad 1.1

¿Qué espera aprender de esta materia?

Yo espero poder aprender lo básico de redes, poder aprender a configurar las redes, ver si podemos aprender algo de ciberseguridad que es algo que me llama mucho la atención

### Actividad 1.2

En un párrafo y con sus propias palabras, describa que tan importante considera a las redes informáticas y el motivo de esa importancia que usted considera

Las redes informáticas siento que son muy importantes ya que gracias a ellas nos podemos comunicar mediante el uso de nuestros dispositivos, son muy importantes para el ser humano actual ya que es la forma mas eficiente que tenemos para comunicarnos con otras personas y las redes informáticas son usadas diariamente por todo tipo de persona o maquina o sistema para poder comunicarse, mandar datos o información y por eso siento yo que son muy importantes ya que en la actualidad dependemos mucho de esto.
### Actividad 1.3
 ### Los 5 pilares de una red

una red computacional es un sistema complejo de intercambio de informacion , requeriendo una combinacion de infraestroctura fisica y reglas logicas para una comunidad efectiva

### 1 Nodos: El origen y Destino

Son dispositivos de inicio y destino como:
-Celular
-Computadora
-Audifonos
-Servidor
-Lavadora

 Intermedios:
-Modem
-Wifi mesh
-Laptop
-Satelite
-Antenas
-Switch
-Router

### 2 Enlaces: El camino físico

Medios Guiados (Con cables)

- **Cable de par trenzado:** El clásico cable de red (UTP/STP). Es **económico y flexible**, pero sufre interferencias a largas distancias.

- **Cable coaxial:** El cable de la televisión por cable. Tiene **buen blindaje** contra interferencias, pero es más rígido y costoso.

- **Fibra óptica:** Transmite datos mediante **pulsos de luz**. Ofrece la **máxima velocidad y distancia**, y es inmune a las interferencias eléctricas.

Medios No Guiados (Inalámbricos)

- **Ondas de radio:** Se propagan en todas direcciones. Ideales para **redes Wi-Fi y móviles**, pero son fáciles de interferir.

- **Microondas:** Viajan en línea recta (requieren visión directa entre antenas). Se usan para **enlaces satelitales** y torres de telefonía.

- **Infrarrojos:** Requieren alineación directa y distancias muy cortas (como el **control remoto** de la TV). No atraviesan paredes.

### 3 Direcciones: Identidad Digital
Direcciones
-IPv4
-IPv6
-DNS
### 4 Protocolos: El leguaje común 
- **1. Capa de Aplicación:** Es el nivel con el que interactúas directamente. Transforma tus acciones (como hacer clic en un enlace) en datos de red usando protocolos como **HTTP/HTTPS** (páginas web) o **SMTP** (correos).
- **2. Capa de Transporte:** Modula la conexión entre los dos puntos. Utiliza **TCP** si se requiere que los datos lleguen completos y sin errores (como un mensaje de texto), o **UDP** si se prioriza la velocidad inmediata (como una llamada de voz).
- **3. Capa de Internet:** Se encarga de la lógica de la ruta. Utiliza el protocolo **IP** para asignar direcciones a los dispositivos y decidir qué camino deben tomar los paquetes de datos para llegar a su destino.
- **4. Capa de Acceso a la Red:** Traduce los datos lógicos en impulsos físicos. Es la encargada de coordinar cómo el hardware (tarjetas de red, antenas) envía los bits a través de tecnologías como **Ethernet** (cable) o **Wi-Fi**.

### 5 Enrutamiento: Gestión de rutas

Conceptos Clave

- **Dirección IP de destino:** El router analiza cada paquete que le llega, lee la dirección IP hacia dónde va y decide a qué otra red enviarlo.
- **Tabla de enrutamiento:** Es el **mapa interno** que tiene cada router. Contiene una lista de rutas conocidas y las instrucciones de a dónde mandar los datos según su destino.
- **Métricas:** Son los criterios que usa el router para decidir cuál es el "mejor" camino. Puede ser la ruta **más corta**, la **más rápida** (con más ancho de banda) o la **menos saturada**.

### Actividad 1.4 y 1.5
## Arquitectura de redes

Una arquitectura de red es el conjunto de reglas y decisiones de diseño que definen como se organiza una red para que la comunicación funcione: que función cumple cada parte, en que orden se procesan los datos y quien tiene el control sobre que

La arquitectura no describe como están tendidos los cables

### Modelos de Referencia

Una red se diseña dividiéndola en capas independientes donde cada capa resuelve un problema especifico sin necesitar saber como trabajan las demás

#### Modelo OSI

Modelo de referencia de siete capas -- física, enlace, red, transporte, sesión, presentación, aplicación -- que describe, de forma teórica, todas las funciones que intervienen en una comunicación de red
#### Modelo TCP/IP

Modelo de 4 capas

1.- La aplicación genera el mensaje original: por ejemplo, el cuerpo de una petición HTTP o un correo. Todavía no lleva ningún encabezado de red

2.- La capa de transporte agrega su encabezado: define el puerto de origen y destino, y numera el segmento para poder reordenarlo después

3.- La capa de internet agrega su encabezado: incluye la dirección IP de origen y de destino, la información que usara el Router para decidir la ruta

4.- La capa de acceso a la red agrega su encabezado: incluye la dirección MAC del siguiente salto y prepara los datos para convertirse en señal

5.-  El paquete viaja por el medio físico -- cable, fibra u ondas de radio -- y llega a la capa de acceso a la red del receptor, todavía completamente encapsulado.

6.- La capa de acceso a la red del receptor retira su encabezado y entrega el resto hacia arriba: la capa de internet confirma que el paquete llego a la IP correcta.

7.- La capa de internet del receptor retira su encabezado y lo entrega a la capa de transporte, que usara el numero de puerto para identificar la aplicación correcta.

8.- La capa del transporte del receptor retira su encabezado. La aplicación recibe el mensaje original, intacto: exactamente el mismo dato con el que empezamos en el emisor

#### Encapsulamiento

Al bajar por las capas, cada una envuelve el dato con su propio encabezado, al llegar al destino, el proceso se invierte y cada capa retira el encabezado que le corresponde

22/09/2026

### Unidad 2 Tipos de Redes

Clasificar por alcance: Una forma comun de clasificar redes
#### Red de Área Personal (PAN)

que es una PAN conecta dispositivos que pertenecen a una sola persona y estan a muy corta distancia entre si, normalmente unos pocos metros.

Caracteristicas: Alcance de hasta 10 metros, bajo consumo de energia, y con frecuencia usa tecnologias inalambricas como bluetooth en lugar de cable

#### Red de Area Local (LAN)

Que es una Lan ? Conecta dispositivos dentro de un espacio fisico unico: una casa, una oficina, un salon de clase, o un solo edificio

Caracteristicas: Es la red que una sola organizacion controla y administra por completo; suele tener alta velocidad y bajo costo por su alcance limitado

#### Red Inalambrica de Area Local (WLAN)

Que es una WLAN ? Es una LAN que usa el espectro radioelctrico en lugar de cables para conectar los dispositivos dentro del mismo espacio

Caracteristicas: El acceso se hace a traves de uno o mas puntos de acceso (AP); a cambiode movilidad, elmedio es compartido y mas sensible a interferencia

#### Wifi Analyzer

Que es una CAN ? Conecta varias LAN de distintos edificios que pertenecen a la misma organización y están próximos entre si.

Características: Los edificios suelen enlazarse con fibra óptica para soportar mayor distancia y trafico; oda la red sigue bajo una sola administración

802.11.a

802.11.b

802.11.n

802.11.ac

802.11.g

802.11.ax

¿Que es el Internet?

Es la red de redes: millones de WAN, LAN y redes de poroveedores distintos, interconectadas y funcionando bajo un mismo conjunto de protocolos

ninguna empresa ni gobierno administra internet como un todo; cada red que la compone es administrada de forma independiente y se conecta a las demas por acuerdo mutuo
¿que la hace funcionar?

que es el tcp/ip ?
El **protocolo TCP/IP** es un conjunto de reglas básicas que permite a las computadoras y otros dispositivos comunicarse e intercambiar datos a través de Internet

¿Como se conectan las redes entere si?

A traves de proveedores de servicios de internet (ISP) organizados en niveles: los ISP locales se conectan a otros mas grandes y estos entre si hasta formar una red global

Puntos de intercambio (IXP) Sitios fisicos donde distintos ISP conectan su trafico directamente entre si en lugar de enviarlo por una ruta mas larga reducen latencia y costo de transito
