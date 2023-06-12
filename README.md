# Proyecto con Mikrotik


## Configuración HAP

En nuestro dispositivo HAP tenemos:
 ·  Bridge -> Creamos la red 192.168.3.0 y asignamos al bridge esa red con la ip 192.168.3.1. 
    Luego lo asignamos a las interfaces eth2, 3, y 5. 
    Añadimos un pool de 192.168.3.10-192.168.3.20 y seleccionamos en el bridge en donde va a dar DHCP.
  
 
 · Bridge1 -> Creamos la red 192.168.1.0 y asignamos al bridge1 esa red con la ip 192.168.1.1 y
    luego lo asignamos a la interfaz eth4. 
    Añadimos un pool de 192.168.1.10-192.168.1.20 y seleccionamos en el bridge en donde va a dar DHCP que en éste caso sería la eth4.
 
 
 · Bridge2 -> Creamos la red 192.168.2.0 y asignamos al bridge2 esa red con la ip 192.168.2.1. 
   Ésta red es la inalámbrica, entonces configuraremos el pool con la 192.168.2.10-192.168.2.20 y se lo asignaremos al bridge2 en las interfaces Wlan1 y Wlan2.
   
   
   
   
  
  ## Configuración HEX
  
En nuestro dispositivo HEX tenemos:
 ·  En la interfaz eth1 tenemos una ip que recibe del DHCP del dispositivo HAP de la red 192.168.1.0.


 ·  Bridge -> Asignamos la red 192.168.88.0 que viene por defecto en el dispositivo junto con el DHCP a la eth2. 
    
    
 ·  Bridge1 -> Creamos la red 192.168.4.0 y asignamos al bridge1 esa red con la ip 192.168.4.1. 
    Luego lo asignamos a las interfaces eth3, 4, y 5. 
    Añadimos un pool de 192.168.4.10-192.168.4.20 y seleccionamos en el bridge en donde va a dar DHCP.
    
         
   
  
