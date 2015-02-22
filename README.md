Systemnahes Programmieren
=========================

Ziel dieser Arbeit ist die Implementierung der Laboraufgabe/n und deren Dokumentation.

Grundvorrausetzung ist das ALLE Teile selbst programmiert werden. Es dürfen also keine STL
Klassen verwendet werden. Dies ist notwendig um die vorher eingeführten Konzepte in der Praxis 
zu vertiefen.

Die Aufgabe selbst wird in mehrere Teile unterteilt:

- Puffer
  + File
    Filezugriff realisieren über "open" unter Verwedung des Flag "O_DIRECT"
    Ausrichtung der Puffer "posix_memalign"
  + String
    da die String Klasse nicht verwendet werden darf, muss man sich selbst eine basteln.
  + SmartPointer

- Scanner
  + HashTable
    Hier werden erkannte Zeichen gespeichert
  + DoppeltVerketteListe
    Mit der die Tabelle arbeitet um die Position der Erkannten Zeichen zu speichern
  
- Automat
  + Zustandsübergangstablle
    Der Automat muss in der Lage sein vorwärts und rückwärts zu springen und so Token und Lexeme zu erkennen
  
- Symboltabelle

- Tests
  der Test nimmt zwei Dateien entgegen, eine Ein und Ausgabe Datei

Jeder Teil benötigt ein eigenes "Makefile-Projekt" in Eclipse. Noch ist nicht ganz klar was damit genau gemeint ist.

Die Dokumentation erfolgt, in diesem Beispiel, im Code und wird mit Doxygen generiert.