---
type: useCase
acronym: branding
responsible: 
    - ngi
title: Branding
description: Ein Anwender einer externen Hochschule kann das Design des Systems individuell anpassen
primaryActor: anwenderExtern
secondaryActors:
trigger: Der externe Anwender möchte das Design des Systems an seine Hochschule anpassen
precondition: Der externe Anwender muss als Verwalter im System eingeloggt sein
postcondition: Das Design des Systems ist an die externe Hochschule angepasst
functionalRequirement: BereitstellungUserPreferences
history:
    v1:
        date: 2021-07-22
        comment: initially created
    v2: 
        date: 2021-07-28
        comment: improvements after review
    v3:
        date: 2021-07-28
        comment: removed self explanatory precondition
    v4:
        date: 2021-07-29
        comment: removed barrierefreie Ansicht
    v5:
        date: 2021-08-01
        comment: fix functionalRequirement because merge
todo: 
---

## Hauptszenario

* 1) Der externe Anwender ruft die Seite mit den Einstellungsmöglichkeiten für das Branding auf
* 2) Der externe Anwender ruft die Einstellungsmöglichkeiten für die Standardansicht auf
* 3) Das System stellt die Standard-Einstellungen zur Verfügung
* 4) Der externe Anwender passt alle  Einstellungen so an, wie er es möchte bzw. wie es zum Branding seiner Hochschule passt
* 5) Der externe Anwender speichert die Einstellungen
* 6) Das System übernimmt die Einstellungen und zeigt die Oberflächen nach einem Server-Restart im neuen Design an

## Alternativszenario

* 2a) Der externe Anwender ruft die Einstellungsmöglichkeiten für die Darkmode-Ansicht auf
* 3a) Das System stellt die Darkmode-Einstellungen zur Verfügung

* 2b) Der externe Anwender ruft die Einstellungsmöglichkeiten für individuelle Header auf
* 3b) Das System stellt eine Übersicht aller möglichen Header zur Verfügung

* 2c) Der externe Anwender ruft die Einstellungsmöglichkeiten für Icons auf
* 3c) Das System stellt eine Übersicht aller möglichen Icons zur Verfügung
