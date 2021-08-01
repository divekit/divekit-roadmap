---
type: useCase
acronym: aufgabenMitGleicherSchwierigkeit
responsible: 
    - mba
title: Gleiche Schwierigkeit
description: Das System tauscht bei der Erstellung von Aufgaben lediglich Schlüsselwörter aus
primaryActor: lehrende
secondaryActors:
trigger: Nutzer möchte Aufgaben individualisieren
precondition: Aufgabe wird eingepflegt und die Stellen die individualisiert werden sollen bestimmt
postcondition: Nutzer erhält individualisierte Aufgaben, die alle auf dem selben Schwierigkeitsgrad basieren
functionalRequirement: GleicheSchwierigkeit
history:
    v1:
        date: 2021-07-19
        comment: initially created
todo:
---


## Hauptszenario

* 1) Nutzer öffnet die Aufgaben Individualisierung
* 2) Nutzer stellt seine Aufgabe dem DiveKit bereit, welches individualisiert werden soll
* 3) Das DiveKit generiert individualisierte Aufgaben
* 4) Nutzer erhält individualisierte Aufgaben mit gleichem Schwierigkeitsgrad

## Alternativszenario

* 3a) Der Nutzer öffnet die Aufgaben Individualisierung
* 3b) Der Nutzer startet die Individualisierung
* 3c) Das DiveKit verlangt nach Aufgaben die individualisiert werden sollen
* 3d) Der Nutzer stellt die Aufgaben ein die individualisiert werden sollen
* 3c) Das DiveKit individualisiert die Aufgaben

## Ausnahmeszenario 

* 3a) Der Nutzer übermittelt dem DiveKit fehlerhafte Informationen zum Individualisieren der Aufgaben, worauf hin das DiveKit keine Aufgaben individualisieren kann
* 3b) Der Nutzer korrigiert die Informationen und zwar die Stellen die individualisiert werden sollen
* 3c) Das DiveKit generiert die Aufgaben




