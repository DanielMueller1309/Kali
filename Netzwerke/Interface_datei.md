###Beispiel für Interface

> ``sudo nano /etc/network/interfaces``

```
auto eth0
iface eth0 init static
  address <ip-adresse>
  netmask <netzmaske>
  gateway <gateway-ip>
  dns-nameservers <nameservers-ip>
```
