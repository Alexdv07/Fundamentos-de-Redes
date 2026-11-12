
### Actividad 3.1

Figura explicando el por que los cables van en pares

![[Pasted image 20261015165547.png]]


### Actividad 3.2

¿Por que los puntos de intercambio reducen la latencia?
Reducen la latencia ya que envían los datos directamente por una ruta mas segura y directa en vez de enviarlo atreves de  redes de terceros externas

### Actividad 3.3

Nombre: Diego Alejandro

Campo 1
Dato de ejemplo: 10101010 10101010 10101010 10101010 10101010 10101010 10101010 10101011 (8 bytes)
Nombre del campo: Preambulo
Para qué sirve: Sirve para sincronizar los relojes de las tarjetas de red del emisor y el receptor para antes de que se transmitan los datos reales, el byte final es el que marca el limite exacto en donde inician los datos de la trama

Campo 2
Dato de ejemplo: FFFF.FFFF.FFFF (6 bytes)
Nombre del campo: Direccion MAC de destino
Para qué sirve: Indica a que dispositivo local va ir dirigida la trama

Campo 3
Dato de ejemplo: 0001.4321.ABCD (6 bytes)
Nombre del campo: Direccion MAC de origen
Para qué sirve: Identifica la tarjeta de red del dispositivo que esta enviando la trama

Campo 4
Dato de ejemplo: 0x0806 (2 bytes)
Nombre del campo: Ethertype
Para qué sirve: Etiqueta que indica que protocolo de la capa superior esta viajando dentro de la carga útil de la trama Ethernet

Campo 5
Dato de ejemplo: ¿Quién tiene la IP 192.168.1.2? Responde a 192.168.1.1 (entre 46 y 1500 bytes)
Nombre del campo: Carga útil/Paquete ARP
Para qué sirve: Transmite la información real que las aplicaciones o protocoles necesitan comunicar

Campo 6
Dato de ejemplo: 0x3A7F91C2 (4 bytes)
Nombre del campo: Secuencia de verificación de trama
Para qué sirve: Se utiliza para detectar errores de transmisión en el medio físico, el emisor calcula el código basado en el contenido de la trama y lo recalcula en base a ser recibida si no coincide la trama fue alterada

### Actividad 3.4

| Característica               | Switch Capa 2                                          | Switch Capa 3                                           |
| ---------------------------- | ------------------------------------------------------ | ------------------------------------------------------- |
| **Capa de operación**        | Capa de Enlace de Datos (Capa 2)                       | Capa de Red (Capa 3)                                    |
| **Identificador base**       | Direcciones MAC                                        | Direcciones **IP** y MAC                                |
| **Enrutamiento (_Routing_)** | No puede enrutar                                       | Sí, conecta diferentes subredes                         |
| **Dominio de Broadcast**     | Uno solo (a menos que se usen VLANs)                   | Rompe y gestiona múltiples dominios                     |
| **Uso principal**            | Conectar computadoras, impresoras y servidores locales | Núcleo de redes empresariales (_Core_) y unión de VLANs |
| **Costo**                    | Económico                                              | Más costoso                                             |