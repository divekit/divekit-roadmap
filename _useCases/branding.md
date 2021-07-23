---
type: useCase
acronym: branding
responsible: 
    - ngi
title: Branding
description: Ein Anwender einer externen Hochschule kann das Design des Systems individuell anpassen
primaryActor: 
    - anwenderExtern
secondaryActors:
trigger: Der externe Anwender ruft die Seite für das Anpassen des Designs an
precondition: Einstellungsmöglichkeiten für das Branding müssen implementiert sein und der externe Anwender muss als Verwalter im System eingeloggt sein
postcondition: Das Design des Systems ist an die externe Hochschule angepasst
funcionalRequirements: 
    - IndividuellesDesign
history:
    v1:
        date: 2021-07-22
        comment: initially created
todo: 
---


## Hauptszenario

* 1) Der externe Anwender möchte das Design des Systems an seine Hochschule anpassen
* 2) Der externe Anwender ruft die Seite mit den Einstellungsmöglichkeiten für das Branding auf
* 3) Der externe Anwender ruft die Einstellungsmöglichkeiten für die Standardansicht auf
* 4) Das System stellt das Standard-Stylesheet zur Verfügung
* 5) Der externe Anwender passt alle Elemente des Stylesheets so an, wie er es möchte bzw. wie es zum Branding seiner Hochschule passt
* 6) Der externe Anwender speichert die Einstellungen
* 7) Das System übernimmt die Einstellungen und zeigt die Oberflächen im neuen Design an

## Alternativszenario

* 3a) Der externe Anwender ruft die Einstellungsmöglichkeiten für die Darkmode-Ansicht auf
* 4a) Das System stellt das Darkmode-Stylesheet zur Verfügung

* 3b) Der externe Anwender ruft die Einstellungsmöglichkeiten für die barrierearme Ansicht auf
* 4b) Das System stellt das Stylesheet der barrierearmen Ansicht zur Verfügung

* 3c) Der externe Anwender ruft die Einstellungsmöglichkeiten für individuelle Header auf
* 4c) Das System stellt eine Übersicht aller möglichen Header zur Verfügung

* 3d) Der externe Anwender ruft die Einstellungsmöglichkeiten für die barrierearme Ansicht auf
* 4d) Das System stellt eine Übersicht aller möglichen Icons zur Verfügung

## Ausnahmeszenario 

**Andere Nachbedingung**: 




