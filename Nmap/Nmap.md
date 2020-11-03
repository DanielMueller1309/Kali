###Befehle
`nmap -sV -p 1-65535 <ip>/<subnetz>`

-sV: Service identification
-p: Portangaben von/bis

`nmap -sP <ip>/<subnetz>`
-sP: Pingscan (sendet einen icmp echo request, TCP SYN zu Port 443, TCP ACK zu Port 80)(als root auch ARP request)

`nmap -sS -sU -Pn <ip>/<subnetz>`
-sS: TCP Scan
-sU: UDP scan
-Pn: Überspringt den Ping Scan und denkt einfach der Host ist UP. Kann bei eingeschalteter Firewall nützlich sein.

`nmap -T4 -A <ip>/<subnetz>`
-T[0-5]: geschwindigkeit von 0 langsam zu 5 schnell
-A: OS und Versionscheck

Befehle:
-O: Betriebssystem
-sL: DNS-Abfrage
-F: 100 verbreitesten Ports
-v: verbose-ausführlich
