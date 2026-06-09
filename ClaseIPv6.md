Clase Direccionamiento IPv6
128 bits maneja / 16 biets

IPv4
IPv4 maneja 32 bits / 4 biets (dividir para 8)
El rango total para ivp4 es 224.0.0.0 a 239.255.255.255
Las partes que tiene ipv4 es dirección de red y host

IPv6
En ipv6 no hay brodcast si no se llama Anycast

IPv6 usa hexadecimal

Esta escrito en cuatro separados por dos puntos : y en hexteto grupo de 8. Cuando se ponen dos ceros :: significa que hay ceros.
Existen mecanismos por los que ipv4 y ipv6 se pueden comunicar. También funcionan con dos métodos Dual-stack permitiendo que ipv4 e ipv6 coexistan. Tunneling método para transportar siendo un túnel que transporta de ipv6 a ipv4. Traducción que permite que se comuniquen 
Un ipv6 tienen 32 valores hexadecimales 

2001:0DB8:0000:1111:0000:0000:0000:0200 (estos es hextetos y deben ser 8)
2001:0DB8:0000:1111::0200 (cuando esta :: es porque van ceros y en total debe haber un hexteto de 8)

Regla1. La primera regla que permite reducir la notación de direcciones IPv6 es
que se puede omitir cualquier 0 (cero) inicial en cualquier sección de
16 bits o hexteto. Cuando se ve solo una letra o numero antes habían ceros
Regla2. Los dos puntos dobles (::) pueden reemplazar cualquier cadena única y contigua de uno o más segmentos de 16 bits (hextetos) que estén compuestas solo por ceros. Los dos puntos solo se pueden poner una sola vez.
Las partes de ipv6 es Prefijo (64 bits) e ID de interfaz (64 bits)
La dirección de loopback de ipv6 es ::1/128 o simplemente ::1

Dirección sin especificar es :: o sea 0000:0000:0000:0000:0000:0000:0000:0000

IPv6
• Una dirección de 128 bits que
contiene un prefijo de routing
global, Id. de subred e Id. de
interfaz.
• Utiliza un formato hexadecimal
con rango de 0 a 9 y de A a F.
• Unidad de transmisión máxima
de hasta 1280 bytes.
• Las direcciones de red y de
difusión se asignan a una
interfaz o dispositivo final.
• Cifrado IPsec nativo

IPv4
• Esquema de asignación de
direcciones de 32 bits que
contiene una porción de red y un
host.
•Utiliza formato binario entre 0 y 1.
• Unidad de transmisión máxima
de hasta 576 bytes.
• Las direcciones de red y de
difusión no se pueden asignar a
una interfaz o dispositivo final.
• Se deben utilizar tecnologías de
VPN para cifrar paquetes IPv4. 
