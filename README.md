# Ejercicio-Redes-Packet-Tracer

## En este ejercicio he creado cinco redes, que paso a comentar a continuación

* Primera Red
  * Esta red tiene a su vez 3 sub redes de cuatro ordenadores cada una.
  * La primera subred soporta 100 host con lo que los ordenadores tienen 
    una IP desde 192.168.1.2 hasta 192.168.1.5 y como máscara de red 255.255.255.128    
  * La siguiente subred soporta 30 host por lo que la IP de sus cuatro ordenadores comprende la IP desde 
    192.168.1.129 hasta 192.168.1.132 y con máscara de red 255.255.255.224
  * La tercera subred soporta 6 host así que sus cuatro ordenadores tienen una IP comprendida entre
    192.168.1.161 y 192.168.1.164 con una máscara de red de 255.255.255.192. Además esta subred puede salir fuera
    por lo que es conectada a un router de IP 192.168.1.10
    
* Segunda Red
  * Esta red tiene 8 ordenadores con DHCP, por lo que son conectados a un servidor que proporciona el comienzo de dirección
    IP de 198.162.2.0 con máscara de red 255.255.255.0, así que los 8 ordenadores obtienen una dirección IP sucesivamente desde
    la que rige el servidor, todos con la misma máscara de red.
 
* Tercera Red
  * Esta red tiene 4 ordenadores con DHCP por lo que seguimos el mismo procedimiento que con la red anterior y los conectamos a un  
    servidor que establece un comienzo de dirección IP desde 192.168.3.0 y una máscara de red de 255.255.255.0, con lo que los cuatro
    ordenadores obtienen una IP sucesiva a la indicada por el servidor,
    
* Cuarta Red
  * Esta red tiene 4 ordenadores con IP fija, establecida desde 192.168.4.2 hasta 192.168.4.5 con máscara de red de 255.255.255.0
  * Además esta red tiene otros 5 ordenadores conectados a un punto de acceso, y estos ordenadores son con DHCP así que el punto de
    acceso está a su vez conectado a un servidor que establece un comienzo de IP de 192.168.4.0 con máscara de red de 255.255.255.0
    
* Quinta Red
  * Esta red tiene 5 ordenadores con IP fija, comprendidas entre 192.168.5.2 y 192.168.5.6 con máscara de subred de 255.255.255.0
  
* Todas las redes están a su vez conectadas a routers
* Aprovechando el switch de la quinta red hay conectados cuatro servidores, tres de ellos almacenan una dirección http diferente
  y el cuarto almacena una dirección DNS de los anteriores
