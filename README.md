# ZeusMonitoringTool
 Monitoring Tool  
 Die erste version dieses Tools ist ein Prototyp um Probleme zu finden und aus diesen zu lernen.  
Auch die verwendeten Sprachen sind nicht fix.

## Beschreibung
### Server
 Der Server (PHP und HTLM in V1) soll regelmäsig die eingetragenen Server(Clients die überwacht werden sollen) Pingen und die Daten aus einer Datenbank(die der Client dort hineinschreibt) anzeigen.

### Client  
Die erste Version des Clients soll in Python geschrieben werden. Der Client soll regelmäßig Daten wie CPU, Ram usw auslastung in die Datenbank (SQL) am Server Schreiben.


### App
Die Daten aus der DB am Server sollen auch über eine App angezeigt werden können. (Flutter)

## Vorgehensweise
### Server
#### Backend
##### PHP

##### SQL DB
MySQL

#### Frontend
Erste Version HTML Tables, die Die Daten anzeigen.  
Später kann ich Grafiken hinzufügen (Nice2Have).


### Client
#### Python
Geplant ist ein python script, dass beim starten des servers automatisch mitgestartet wird und dann regelmäsig Daten(zpu ram speicher auslastung) in die DB am monitoring Server schreibt.
