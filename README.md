Buechereimanager-UI
===================

Büchereimanagement für das CAG in Cloppenburg.


Der hier verfügbare Sourcecode muss vor dem Bauen noch angepasst werden!
Ändern sie bitte in Form1.h UND Suchmaske.h folgende Zeilen:
Form1.h:
  Zeile 29-32:
  		dbhost="Hier Ihren MySQL Host";
			dbport="Hier Ihren MySQL Port";
			dbuser="Hier Ihren MySQL Usernamen";
			dbpass="Hier Ihr MySQL Passwort für den Usernamen";
Suchmaske.h:
  Zeile 22-25:
    	dbhost="Hier Ihren MySQL Host";
			dbport="Hier Ihren MySQL Port";
			dbuser="Hier Ihren MySQL Usernamen";
			dbpass="Hier Ihr MySQL Passwort für den Usernamen";
      
Programmiert wurde dieses Programm in Visual C++ mit .Net4.0 in Visual Studio 2012.
Um das Programm korrekt programmieren zu können, benötigen sie:
  - Visual Studio 2012 (Edition egal) + !!UPDATE 2!!
  - MySQL Connector/Net 6.6.5 oder neuer
Systemanforderungen:
  - Windows XP,Vista,7,8 oder neuer
  - 25MB freien Arbeitsspeicher beim Start des Programms
  - Konstante Verbindung mit dem MySQL Server(Entweder über Internet oder LAN)
  - MySQL Connector/Net 6.6.5 oder neuer(die selbe Version, die zum Bauen verwendet wurde)
  - Microsoft .Net Framework 4.0
