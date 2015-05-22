# UDP TEST

Udp-test envia un ping al host puerto especificado.
```sh
# git clone https://github.com/tinolin/udp-test.git
# cd udp-test && chmod +x udp-test 
# cp udp-test /usr/bin
# udp-test <host> <port>
```
 

En el host destino chequeamos con "tcpdump udp host hostorigendelping"
> 15:28:01.228802363 IP host.38382 > client.port: UDP, length 8
