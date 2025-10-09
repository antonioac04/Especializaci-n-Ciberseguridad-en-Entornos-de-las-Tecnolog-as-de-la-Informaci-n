![[Pasted image 20251009162118.png]]

TCP/IP no es un protocolo; esto lo podemos definir como una arquitectura de red. Pero si podemos indicar que si se encuentran separados si son un protocolo.

ARP: este protocolo traduce entre la capa 2 y la capa 3 por eso se encuentra repetido en la tabla

TCP: se encuentra orientado a conexión es más lento y más seguro comparado con UDP que este es más rápido pero menos seguro.

|   **TCP/IP**    |     **OSI**     |   **Nombre de la PDV**   |       Dispositivos       |                                   **Protocolos**                                    |           **Direcciones**            |
| :-------------: | :-------------: | :----------------------: | :----------------------: | :---------------------------------------------------------------------------------: | :----------------------------------: |
|   Aplicación    |   Aplicación    |          Datos           |   Gateway / Servidores   |                           DNS, HTTP, FTP, DHCP, SSH, SMTP                           |                                      |
|  Presentación   |   Aplicación    |          Datos           |   Gateway / Servidores   |                           DNS, HTTP, FTP, DHCP, SSH, SMTP                           |                                      |
|     Sesión      |   Aplicación    |          Datos           |   Gateway / Servidores   |                           DNS, HTTP, FTP, DHCP, SSH, SMTP                           |                                      |
|   Transporte    |   Transporte    |         Segmento         |    Sistema Operativo     |                  TCP (lento y seguro), UDP (rápido y poco seguro)                   |           Puertos (65535)            |
|    Internet     |       Red       |         Paquete          |          Router          |                                IPv4, IPv6, ICMP, ARP                                | Direcciones IP o Direcciones Lógicas |
| Acceso a la red | Enlace de datos |          Trama           | Switch / Punto de acceso | IEEE 802.3 (Ethernet), IEEE 802.11 (WiFi a, b, g,h,etc), IEEE 802.15 Bluetooth, ARP |       Dirección MAC o física.        |
|     Física      |      Bits       | Hub/Concentrador, Cables |                          |                                                                                     |                                      |
