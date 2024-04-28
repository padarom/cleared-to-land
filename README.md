# Cleared to Land
Cleared to Land war "Deutschlands erster Luftfahrtserver" in SA:MP. Ging online irgendwann 2011 oder früher. Originale Posts habe ich nicht mehr gefunden, nur die Veröffentlichung des Scripts nachdem wir den Server mangels Interesse wieder eingestellt haaben: https://breadfish.de/thread/87070-cleared-to-land-luftfahrtscript/?pageNo=1

## 1. Vorwort
wie in diesem Thread nachzulesen, habe ich Cleared to Land inzwischen beendet. Es war interessant mit anzusehen, wie das Interesse am Server anfangs immer weiter stieg, jedoch traurig wie es nach ein paar Wochen wieder sank. Da ich nicht will, dass das Script irgendwann von meinem System gelöscht wird, stelle ich es hiermit zum Download bereit. Es ist allerdings anzumerken, dass es noch keine finale Version darstellt, sondern lediglich in der Open Beta Phase war (welche immerhin recht erfolgreich war und einige Bugfixes sowie Neuerungen mit sich brachte). Kurz bevor wir aus der Open Beta ein Full Release machen wollten, sank die Aktivität allerdings fast schon ins Negative.

## 2. Benötigt
#### MySQL-Datenbanken

ticket - Felder: Name, Titel, Text (Alles varchar)  
benutzer - Felder: Name, Passwort, Frage, Antwort, Heimat (Bisher alles varchar), Cash, Points, Adminlvl (Integer)

#### Userfiles-Ordner

/cars/  
/Logs/

##### Plugins (sind im Download für Windows-Server vorhanden)
sscanf  
mysql (von G-StyleZzZ)
## 3. Infos zum Script
Das Script ist eigentlich ursprünglich aus Spaß/Langeweile entstanden und hat innerhalb der ersten 2 Wochen in meinem Bekanntenkreis recht hohes "Ansehen" geerntet. Nachdem ich einige Funktionen und Möglichkeiten hinzugefügt habe, entschloss ich mich dafür einen Server aufzumachen und fand zufällig noch am gleichen Tag jemanden der das gleiche vorhatte (r0ck4ff3, siehe hier). Eins folgte auf dem anderen und bevor ich mich versah war bereits die Vorstellung geschrieben, die Sponsoren waren da und das Projekt lief. Auf den Misserfolg danach möchte ich nicht nochmal weiter eingehen, aber er kam. Und da ich aktuell wie im Vorwort bereits erwähnt keine Verwendung mehr für das Script finde biete ich es hiermit zum Download für andere Scripter (zum Scripten üben, weiterentwickeln, wasweißich) bzw. Serverhosts an.  
Sollte eine große Nachfrage bestehen, so werde ich das Script vielleicht auch noch (sofern meine Zeit es zulässt) ein wenig mit den früher versprochenen Features weiterentwickeln und die neueren Versionen hier anheften.
Gegebenenfalls kann man es auch ressourcenschonender oder besser umsetzen, aber da die Open Beta nie ihr Ende fand, musste ich den Code auch noch nicht optimieren.  
Bitte beachtet also, dass das Script zwar spielbar ist, allerdings der Code nicht optimiert wurde (also der Ressourcenverbrauch etwas höher sein kann, als eigentlich benötigt).

Ich möchte hier die Featureliste des Scripts auch nicht allzu sehr erläutern, lediglich ein paar kleine Teile zum Nachlesen:

- Innovatives Login-/Register-/Passwortvergessensystem (Siehe u.A. auch eines der Tutorials in meiner Signatur)
- Levelingsystem o. "Story Mode" (Mit steigenden Punkten/Flügen mehr Flugzeuge nutzbar)
- Erfolgssystem (Erfolge und Belohnungen beim Levelup)
- Im Grunde drei verschiedene Berufe

  - Pilot - Ihr seid die Männer (oder Frauen), die hinter den Steuerhörnern der Maschinen sitzen und sie steuern.
  - Bodenpersonal - Ohne euch geht auf dem Rollfeld garnichts. Ihr seid für Betankten und Beladen zuständig. Außerdem gehört die Flughafenfeuerwehr und -polizei auch zu eurem Aufgabengebiet.
  - ATC (Air Traffic Controller) - Auch die Fluglotsen haben wir nicht vergessen. Für euch gibt es je nach Flughafengröße unterschiedliche Kontrollplätze und Kameraeinstellungen um ständig die Sicherheit in der Luft, wie auch am Boden zu gewährleisten.
- Chatsysteme für quasi alle Aufgabenbereiche (Boden, ATC, Admin, Ticketchat, OOC)
Ich kann euch leider nicht versprechen auf Scriptfragen direkt eine Antwort zu finden, das ist immerhin bereits 2 Monate her in denen ich das Script nicht 1x angerührt habe.
Um die einzelnen Commands herauszufinden, bzw. euch in das Script hineinzufinden schaut es euch bitte selbst an, sind aktuell ca. 3600 Zeilen.



## 4. Vor dem Spielen
... müsst ihr Flugzeuge und Fahrzeuge erstellen. Dafür registriert ihr euch einfach ingame und setzt dann in der MySQL euer Adminlevel auf 1-3. Mit /car [ID] könnt ihr dann ingame die Fahrzeuge spawnen.
Mit `/setcolor [C1] [C2]` könnt ihr danach deren Farbe festlegen. Benötigt werden vorallem Tankfahrzeuge, Abschlepper und alle Flugzeugarten die im Script unterstützt werden.

## 5. Download
...

## 6. Credits gehen an

- Padarom - Scriptentwicklung
- r0ck4ff3 - Maps der 3 zusätzlichen Flughäfen
- andrediddi - "Seelischer" Beistand wenn es mal nicht so lief^^
- Die Spieler vom ehemaligen Cleared to Land

Ich hoffe ihr findet Gefallen an dem Script, auch wenn ich nicht wirklich viele Informationen dazu abgeben konnte.
Ich würde mich über Kritik oder Bewertungen sehr freuen.



Mit freundlichen Grüßen
Padarom
