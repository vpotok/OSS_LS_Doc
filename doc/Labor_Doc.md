# Labor Dokumentation vom 12.11.2021
## VM erstellen:

* Vollständige VMs sind bereits im Labor Storages (/netexport) vorhanden und können als VM-Link erstellt werden 
 <br>-> VM-Links sind eine Art Blauprint Kopie der Ursprungs-VM, alle neuen veränderungen werden serpart auf meinem Rechner gesichert
* Tutorial findet sich unter **start.nwt.fhstp.ac.at/wiki/doku.php/index**

<li> </li>
<li> </li>
<li> </li>
<li> </li>


### Mini WH Linux-Befehle.
# Anzahl an Enter (\n) mit cat in einer Datei
<br>
`` zB cat text.txt | wc -l ``
<br>
``wc -> Wortcount ; -l -> new Lines also ENTER``
<br>

`` Verschiebungen mit "<" und ">"``

<br>
Fehlermedlungen bei einem _find ._ in ein weiters File speichern
``find . 2> fehler_erg.txt``
or 
``find . 2>1 erg.txt``


tee Command
Output wird ausgeführt und in ein File gespeichert
``command | tee file.txt``
