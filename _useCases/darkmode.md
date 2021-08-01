---
type: useCase
acronym: darkmode
responsible: 
    - ngi
title: Darkmode
description: Ein User kann den Darkmode aktivieren
primaryActor: studierende
trigger: Der User entscheidet sich für die Änderung seiner visuellen Einstellungen
precondition: Der User mag das Darkmode-Setting und findet es besser als die Standard-Ansicht
postcondition: Das Darkmode-Setting ist aktiviert
functionalRequirement: Darkmode
history:
    v1:
        date: 2021-07-20
        comment: initially created
    v2:
        date: 2021-07-31
        comment: specified wording and actor
todo:

ignore: w051, w670
---

Als User zählt bei diesem Use Case jede Stakeholder-Rolle, welche mit dem Frontend des DiveKits interagiert und das Darkmode-Setting in den visuellen Einstellungen aktivieren möchte. Das sind primär die Studierenden, da die anderen Stakeholder-Rollen das DiveKit hauptsächlich über Config-Files steuern und diese in externen Tools (z.B. IntelliJ) erstellen.

## Hauptszenario

* 1) Der User ruft die Seite mit den Einstellungen auf
* 2) Der User aktiviert das Darkmode-Setting
* 3) Das System ändert die visuelle Ansicht zum Darkmode





