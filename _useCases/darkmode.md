---
type: useCase
acronym: darkmode
responsible: 
    - ngi
title: Darkmode
description: Ein User kann den Darkmode aktivieren
primaryActor: 
    - profBwl
    - profInf
    - profMa
    - student
    - wmaAutonomousLecturerInf
    - wmaDev
    - wmaProg
secondaryActors:
trigger: Der User ruft das Darkmode-Setting auf
precondition: Das Setting muss implementiert sein
postcondition: Das Darkmode-Setting ist aktiviert
functionalRequirement: Darkmode
history:
    v1:
        date: 2021-07-20
        comment: initially created

todo: 
---

Als User zählt bei diesem Usecase jeder Stakeholder, der mit diesem System interagiert und seine visuellen Settings anpassen möchte.

## Hauptszenario

* 1) Der User entscheidet sich für die Änderung seiner visuellen Einstellungen
* 2) Der User ruft die Seite mit den Einstellungen auf
* 3) Der User aktiviert das Darkmode-Setting
* 4) Das System ändert die visuelle Ansicht zum Darkmode

## Alternativszenario

* 3a) Der User entscheidet sich gegen die Aktivierung des Darkmode-Settings

## Ausnahmeszenario 

Bei korrekter Implementierung des Darkmode-Settings entfällt dies.

**Andere Nachbedingung**: Das Darkmode-Setting ist nicht aktiviert.




