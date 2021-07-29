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
    - studierende
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
    - (sbe) "precondition Das Setting muss implementiert sein" - das macht man eher nicht, man geht davon aus, dass ein beschriebenes Feature auch implementiert ist. Oder haben Sie das anders gemeint? Dann bitte präzisieren. 
    - (sbe) "Als User zählt bei diesem Use Case jeder Stakeholder, der mit diesem System interagiert und seine visuellen Settings anpassen möchte." - daher kommen dann auch die vielfachen primaryActors (mit Error). Aber der Darkmode ist doch hauptsächlich für die Studies interessant. Die Lehrenden nutzen gar nicht die Test-Webseite, sondern steuern Divekit hauptsächlich über Config Files, die mit IntelliJ oder VSCode erstellt werden. Da gibts einen Darkmode. 
    - (sbe) "1) Der User entscheidet sich für die Änderung seiner visuellen Einstellungen" - das ist noch keine Aktion, eher ein Trigger. Dafür ist der momentane Trigger "Der User ruft das Darkmode-Setting auf" eine Aktion, statt einem Auslöser.
    - (sbe) Alternativszenario macht keinen Sinn, oder?
---

Als User zählt bei diesem Use Case jeder Stakeholder, der mit diesem System interagiert und seine visuellen Settings anpassen möchte.

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




