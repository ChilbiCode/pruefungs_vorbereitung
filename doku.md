# Dokumentation

Firma: Systemhauses Dresden-IT  
Kunde: 


## Installation

## IP - Bereich

### Netzwerk 

IP: 172.69.42.0

Domänenname: 


### Client1BM:

- local user: admin
- password: password7/

### Client2BM:

- local user: admin
- password: password7/



Verwenden Sie den privaten Adressbereich 172. …. 
Insgesamt werden im Endausbaus 70 IP-Adressen benötigt. 
Planen Sie den Domänennamen. 
Planen Sie die Computernamen für die Clients und 2 Server. 
Erstellen sie 2 Partitionen 
M:\ 60 GB NTFS 
N:\ 60 GB NTFS 
Erstellen Sie auf dem Laufwerk M:\ folgenden Ordner: Mediashop 
Erstellen sie folgende Unterordner: Basis 
Profiles 
Infos 
Erstellen Sie auf dem Laufwerk N:\ folgenden Ordner: Daten 
Erstellen sie folgende Unterordner: Buchhaltung 
Lager 
Vertrieb 
Einkauf 
Leitung 
Legen Sie folgende Benutzerkonten an, die Konten sollen über Servergespeicherte Profile 
und Basisverzeichnisse verfügen, das Basisverzeichnis ist mit dem Netzlaufwerk X:\
verbunden. 
Zugriffsrechte 
Name Funktion Tel. Abteilung LTG VT LG BUH EK 
Karin Berger Geschäftführerin 2210 Leitung MB MW MW MB MW 
Klaus 
Schnaicke 
Lagerleiter 2250 Lager MW MW MW MW 
Chris Loghan Vertriebsleiter 
Vertreter für Fr. 
Berger 
2220 Vertrieb MB MB MW MW MW 
Netze Sicherheit 
Sabine Brück Leiterin 
Buchhaltung 
2230 Buchhaltung MW MB MW MB MW 
Steve Delarue Mitarbeiter 
Einkauf 
2241 Einkauf X X MB X MB 
Tom 
Weisichnicht 
Mitarbeiter 
Vertrieb 
2221 Vertrieb X MB MW X MW 
Cemal Einkaufsleiter 2240 Einkauf MW MW MW MW MB 
Özdermir 
Claudia 
Özdemir 
Sekretariat Leitung 2200 Leitung MB MB MB MW MB 
Eva-Maria 
Schneider 
Mitarbeiterin 
Einkauf 
2242 Einkauf X X MW X MW 
Paul Krum Mitarbeiter Lager 2251 Lager X X X X MW 
Bettina 
Schellbaum 
Mitarbeiterin 
Lager 
2251 Lager X X X X MW 
Andre`Pau Azubi 2209 Leitung L L L L MW 
Mickie de 
Baxio 
Mitarbeiter 
Leitung und IT 
Domänenadmin 
2201 Leitung 
MB: Mitbesitzer | MW: Mitwirkender | L: Leser | X: Zugriff verweigert 
Aus Sicherheitsgründen sollen im Mediashop 8 stellige, komplexe Passworte verwendet 
werden. Das Passwortalter soll 90 Tage betragen. 
Das Konto soll nach maximal 4 Falschanmeldungen gesperrt werden die Kontosperrdauer 
soll 8 Std betragen. 
Auszubildende dürfen sich nur im der Zeit von 6:00 bis 19:00 Uhr anmelden. 
Für die Client PC´s und Benutzer sind Gruppenrichtlinien einzurichten 
Internet Startseite: EBZ Dresden 
Favoriten: Amazone.de 
edv-buchversand.de 
herdt.de 
Taskmanager darf nicht nutzbar sein 
Aufgabenplanung darf durch den Benutzer nicht zum starten oder beenden von Aufgaben 
genutzt werden 
Benutzer sollen keinen Zugriff auf die Windows Update Funktionen haben. 
Um eine ausreichende Verfügbarkeit des Systems sicherzustellen ist ein 2. 
Domänencontroller einzurichten. 
Hier soll es auf einen separaten Datenträger eine Freigabe für die Sicherung geben. 
Netze Sicherheit 
Auf dem 1. DC soll die WDS Rolle eingerichtet werden, über diesen WDS sind 1 WIN 10 
Clients inklusive Office 2016 als VM´s im HyperV einzurichten. 
In dem Netz soll ein WLAN zu Verfügung stehen. 
Der Internetzugang soll über die Routerfunktion am DC1 erfolgen. 
Die IP Adressen Vergabe erfolgt mit Ausnahme am DC1und DC2 über DHCP. 
Das Gesamte Projekt ist mit Hilfe der Windows Datensicherung zu sichern. 
Eine Dokumentation des Netzwerkes ist zu erstellen 