---
type: useCase
acronym: barrierefreiheit
responsible: 
    - jsp
title: Barrierefreiheit
description: Ein User kann die Form der Barrierefreiheit einstellen
primaryActor: 
    - profBwl
    - profInf
    - profMa
    - studierende
    - wmaAutonomousLecturerInf
    - wmaDev
    - wmaProg
secondaryActors:
trigger: Der User ruft die Einstellung für Barrierefreiheit auf
precondition: Das System muss die Funktion anbieten und die visuelle Änderung vornehmen können
postcondition: Farben sind aus dem System verschwunden und werden durch Symbole/Text ersetzt
functionalRequirement: Barrierefreiheit
history:
    v1:
        date: 2021-07-21
        comment: initially created
todo: 
    - (sbe) deutlicher Überlapp mit UC "branding" - bitte abgrenzen oder zusammenführen
    - (sbe) precondition "Das System muss die Funktion anbieten" - das macht man eher nicht, man geht davon aus, dass ein beschriebenes Feature auch implementiert ist. Oder haben Sie das anders gemeint? Dann bitte präzisieren. 
---

Als User zählt bei diesem Usecase jeder Stakeholder, der mit diesem System interagiert und seine visuellen Settings anpassen möchte.

## Hauptszenario

* 1) Der User entscheidet sich für die Änderung seiner visuellen Einstellungen
* 2) Der User geht in die Einstellungen
* 3) Der User navigiert zum Bereich Barrierefreiheit
* 4) Der User ändert die Darstellung auf Symbole
* 5) Das System zeigt Ergebnisse mit Symbolen statt Farben an

## Alternativszenario

* 4a) Der User ändert die Darstellung zu einer Textform
* 5a) Das System zeigt Ergebnisse als Text anstelle von Farbe an.

## Ausnahmeszenario 

Bei korrekter Implementierung der Barrierefreiheit visuallisierung kann es zu keinem Ausnahmeszenario kommen.

**Andere Nachbedingung**: Der Student kann plötzlich wieder Farben erkennen?




