###Module erklärt

#### auxiliary
Executing show auxiliary will display a listing of all of the available auxiliary modules within Metasploit. As mentioned earlier, auxiliary modules include scanners, denial of service modules, fuzzers, and more.

#### exploits
Naturally, show exploits will be the command you are most interested in running since at its core, Metasploit is all about exploitation. Run show exploits to get a listing of all exploits contained in the framework.
##### Aktive Exploits
Aktive Exploits nutzen einen bestimmten Host aus, werden bis zum Abschluss ausgeführt und dann beendet.

##### Passive Exploits
Passive Exploits warten auf eingehende Hosts und nutzen sie beim Herstellen einer Verbindung aus.

Passive Exploits konzentrieren sich fast immer auf Clients wie Webbrowser, FTP-Clients usw.
Sie können auch in Verbindung mit E-Mail-Exploits verwendet werden, die auf Verbindungen warten.


#### PAYLOADS
As you can see, there are a lot of payloads available. Fortunately, when you are in the context of a particular exploit, running show payloads will only display the payloads that are compatible with that particular exploit. For instance, if it is a Windows exploit, you will not be shown the Linux payloads.
