MySQlDump von Daniel Schlichtholz
Version 0.9.2
http://www.daniel-schlichtholz.de/board


Willkommen und viel Spa� bei der Benutzung von MySqlDump mit PHP. 

Die Benutzung erfolgt auf eigene Gefahr. 
Ich kann nicht f�r Datenverluste verantwortlich gemacht werden.

Was hat sich in dieser Version ge�ndert:
----------------------------------------
Die Datei "index.php" ist als neue Schaltzentrale hinzugekommen.
Von hier aus kann man jetzt alle Aktionen ausl�sen.
Hier habe ich die Erweiterung von Elax und pus234 eingebaut - Vielen Dank.

Erweiterung von Joachim Leicht eingebaut (http://nic.eu.ki) - Vielen Dank.
Das Dumpfile kann nun als Email verschickt werden.

Es ist die Datei "cron_dump.php" hinzugekommen.
Diese Datei eignet sich als Aufrufziel eines Cronjobs, da sie auf 
Ausgaben v�llig verzichtet. Sie orientiert sich aber an den Einstellungen 
in der config.php.

Ich habe alle Funktionen in die Datei "functions.php" ausgelagert.
Das macht die anderen Dateien �bersichtlicher und vereinfacht eine 
Erweiterung durch andere Programmierer.

In "config.php" kann man nun den "neuer_sql-Befehl-Code" selbst einstellen.
(Es kann auch ein l�ngerer String sein.)

Bugfix: 
bei register_globals=off verga� "dump.php" den Namen der Backupdatei - gefixt


Viel Spa� mit dem Script.
DSB (Daniel Schlichtholz)