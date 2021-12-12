# Net_Practice
<!--
What is TCP/IP?
TCP/IP (stands for Transmission Control Protocol/Internet Protocol) is a suite of communication protocols used to interconnect network devices on the internet, being TCP and IP two main protocols, though others are included in the suite. 

What is TCP/IP for?
TCP/IP specifies how data is exchange over the internet by providing communications that identify how it should be broken into packets, addressed, transmitted, routed and received at the destination.

TCP defines how applications can create channels of communication across a network.It also manages how a message is assembled into smaller packets before they are then transmitted over the internet and reassembled in the right order at the destination address.
IP defines how to address and route each packet to make sure it reaches the right destination
A subnet mask tells a computer, or other network device, what portion of the IP address is used to represent the network and what part is used to represent hosts, or other computers, on the network.

How TCP/IP works?
TCP/IP uses the client-server model of communication in which a user or machine (a client) is provided a service, like sending a webpage, by another computer (a server) in the network.


Una dirección IP es un número de 32 bits. Identifica de forma única un host (equipo u otro dispositivo, como una impresora o enrutador) en una red TCP/IP.

Para que este proceso funcione, una dirección IP tiene dos partes. La primera parte de una dirección IP se usa como dirección de red, la última parte como dirección host.
Si toma el ejemplo 192.168.123.132 y lo divide en estas dos partes, obtiene 192.168.123. Host .132 de red o 192.168.123.0: dirección de red. 0.0.0.132: dirección host.


El segundo elemento, que es necesario para que TCP/IP funcione, es la máscara de subred. El protocolo TCP/IP usa la máscara de subred para determinar si un host está en la subred local o en una red remota.



What is a host??



Para que una red de área extensa TCP/IP (WAN) funcione eficazmente como una colección de redes, los enrutadores que pasan paquetes de datos entre redes no conocen la ubicación exacta de un host al que se destina un paquete de información. Los enrutadores solo saben a qué red es miembro el host y usan la información almacenada en su tabla de rutas para determinar cómo obtener el paquete a la red del host de destino. Después de entregar el paquete a la red del destino, el paquete se entrega al host correspondiente.



<table>
  <tr align=center>
    <th colspan="2"> Concept </th>
    <th>Meaning </th>
    <th> ... </th>
  </tr>
  <tr align=center>
    <td rowspan="2">IP address</td>
    <td>Definition</td>
    <td>The Internet Protocol (IP) is a 32-bit number that defines how to address and route each packet to make sure it reaches the right destination.</td>
    <td></td>
  </tr>
  <tr align=center>
    <td>Types</td>
    <td>TCP/IP supports three classes of Internet addresses depending on the network's size: Class A (8-bit network address and a host address), Class B (16-bit network address and a 16-bit host address), and Class C (24-bit network address and an 8-bit local host address). When a C class Internet address contains a 0 as the host address portion, TCP/IP sends a wildcard address on the network, so all machines with a class C and the same network address should respond to the request. </td>
    <td></td>
  </tr>
  <tr align=center>
    <td rowspan="2">Subnet mask</td>
    <td>Definition</td>
    <td> A subnet mask is a 32-bit number that tells the system what the subnet partioning scheme is, i.e. whether the destinatios is on the same network as the source or in a remote one. The subnet mask consists of high bits (1's) corresponding to the bit positions of the network and subnetwork address, and low bits (0's) corresponding to the bit positions of the host address.</td>
    <td></td>
  </tr>
  <tr align=center>
    <td>Address comparison</td>
    <td>The destination address and the local network address are compared by performing the logical `AND` and exclusive `OR` on the subnet mask of the source host</td>
    <td></td>
  </tr>
</table>

-->
