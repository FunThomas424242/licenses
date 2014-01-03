licenses project
================

Ein Projekt zur Katalogisierung von Softwarelizenzen. Ziel des Projektes ist es, dem Nutzer/Entwickler ein Mittel
an die Hand zu geben um eine Einbindung der Software von Drittanbietern bewerten zu k�nnen.

Das Projekt orientiert sich dabei an einem 3-stufigen Modell:

1. Aufbau einer Adjazenzmatrix mit der einzelne Verwendungsm�glichkeiten je Lizenz entsprechenden Bedingungen zugeordnet werden.
2. Aufbau eines Werkzeuges zur Bestimmung aller expliziten und impliziten Abh�ngigkeiten der zu bewertenden Software hinsichtlich 
der Lizenzen der Komponenten von denen sie transitiv abh�ngig ist.
3. Aufbau eines Werkzeuges welches automatisch auf Grundlage der unter (1) erstellte Adjazenzmatrix und der unter (2) gewonnenen
Informationen Lizenzkonflikte aufzeigt.

Literaturhinweise: 

* [ENG2012](http://www.bibsonomy.org/bibtex/23ad38e2fbc524230344bc7ea48979620/funthomas424242)

Aktueller Arbeitsstand
----------------------

Aktuell wird die [Adjazenzmatrix](https://raw.github.com/FunThomas424242/licenses/master/Lizenzmerkmale.fods) aufgebaut.

Aufbau der Adjazenzmatrix
--------------------------

*Anforderungen*: 

* Die Matrix sollte mit einer freien Spreadsheet Anwendung wie LibreOffice bearbeitet werden k�nnen. 
* Die Matrix sollte in einem diffbaren Format abgelegt werden um Pull Requests einarbeiten zu k�nnen

Als Format wurde *fods* ausgew�hlt. 

Ablage erfolgt unter: https://raw.github.com/FunThomas424242/licenses/master/Lizenzmerkmale.fods

Voranalysen und Übersetzungen
-----------------------------

Um die Adjazenzmatrix aufbauen zu können werden Voranalysen benötigt. Dazu werden Übersetzungen oder Extrakte im Internet gesucht
und verwertet. Falls kein ausreichendes Material gefunden werden kann wird selbst versucht eine Übersetzung evtl. 
auch nur teilweise zu erstellen. Der zentrale Einstiegspunkt in die Dokumente findet sich unter
[Analysedokumente](./analysis/Quellen.md)
