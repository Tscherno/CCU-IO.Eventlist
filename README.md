CCU-IO.Eventlist
================

Ereignistabelle für CCU.IO Log.

CCU.IO-Eventlist zeigt tabelarisch alle Zustandswechsel von Homematic-Geräten.

Natürlich ist CCU.IO erforderlich.

Bedienung: 
- http://ip-address:8080/eventlist/index.html aufrufen.
- Die Werte in Zeilen "Raum", "Bild" und "Typ" sind clickbar und man kann damit filtern. Zeiwetes Drucken löscht den Filter.<br>

##Installation
Einfach in das Verzeichnis www von ccu.io kopieren.

##Parameters:
 - loading  - Show loading process
 - advanced - Show events as text, like "Lamp in the kitchen is on"
 - lang     - Language
 - hmID     - Show only events for eventlist Homematic ID
 - states   - Show only state changes. Do not show temperature, humidity, all cyclic values
 - types    - Show "a"ll, Show only "v"ariables, show Only "d"evices
 - width    - Width of window

##Verwendete Software
* jQuery http://jquery.com/
* jqGrid http://www.trirand.com/blog/

##Changelog
*V 0.0.2
- Einstellbare Anzahl von Ereignissen auf der Seite


## License
Copyright (c) 2013 Denis Khaev deniskhaev@gmail.com
 
It is licensed under the Creative Commons Attribution-Non Commercial-Share Alike 3.0 license.
The full text of the license you can get at http://creativecommons.org/licenses/by-nc-sa/3.0/legalcode
 
Short content:
Licensees may copy, distribute, display and perform the work and make derivative works based on it only if they give the author or licensor the credits in the manner specified by these.
Licensees may distribute derivative works only under a license identical to the license that governs the original work.
Licensees may copy, distribute, display, and perform the work and make derivative works based on it only for noncommercial purposes.
 
Free for non-commercial use. 
 