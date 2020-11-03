### Wichtige Befehel

`check`
prüft ob ein Target anfällig für einen bestimmten Exploit ist, anstatt es tatsächlich auszunutzen.

`jobs`
Module die im Hintergrund Laufen

`search`
Suchbefehl

`sessions`
Mit dem Befehl können Sie erstellte Sitzungen auflisten, mit ihnen interagieren und sie abtöten. Die Sitzungen können Shells, Meterpreter-Sitzungen, VNC, etc. sein.

`set`
Der Befehl setz Framwork-Optionen und Parameter für aktuelles Modul,zum Beispiel RHOST,LHOST usw
Gegenstück `unset`
Global: `setg`

`save`
Speichert diese einstellungen von `set`

`show options`
Nützlich beim herausfinden welche Optionen in einem Modul eingestellt werden können bzw schon eingestellt sind.

`show targets`
Zeigt in einem exploit Modul an welche Targets damit exploitet werden können.

`use`
läst einem Module auswählen

`exploit -j`
verschiebt laufenden exploit in einen background job

`workspace`
Befehl um in der Datenbank gleichzeitig in verschiedenen Spaces zu Arbeiten.

`db_namp`
wie NMAP nur in msf

`host`
listet alle hosts aus dem __db_nmap__ scan auf

`services`
listet alle erkannten services aus dem __db_nmap__ scan auf
