---
type: useCase
acronym: tutorialVorschlagen
responsible: 
    - duz
title: Tutorial vorschlagen
description: Das System schlägt dem Nutzer ein Tutorial in Form eines Videos vor
primaryActor: lehrende
secondaryActors:
    - potAnwender
trigger: Nutzer ruft einen Teil des Systems zum ersten Mal auf
precondition: Nutzer ist eingeloggt und "hat Funktion bereits benutzt" flag steht auf "nein"
postcondition: Nutzer ist mit Nutzung vertraut
functionalRequirement: SchnellerLernprozess
history:
    v1:
        date: 2021-07-17
        comment: initially created
    v2:
        date: 2021-07-26
        comment: modified Scenarios and Actors regarding review
    v3:
        date: 2021-07-29
        comment: modified Scenarios regarding todos
todo: 
---


## Hauptszenario

* 1) Nutzer registriert sich im System und öffnet eine Seite
* 2) Das System erkennt, dass dieser Teil des Systems noch nicht genutzt wurde
* 3) Auf der geöffneten Seite werden Tutorial-Vorschläge eingeblendet
* 4) Nutzer wählt ein Tutorial-Video aus
* 5) Nutzer sieht sieht sich ein eingeblendetes Tutorial-Video an

## Alternativszenario

* 4a) Der Nutzer kennt sich bereits mit dem System aus und klickt die Tutorial-Vorschläge weg

## Ausnahmeszenario 

* 3a) Es existiert kein Tutorial für diese Funktion
* 5a) Das Tutorial für die Funktion ist veraltet
* 6) Das Tutorial hat dem Nutzer nicht weitergeholfen, weil die Schritte nicht nachvollziehbar sind

**Andere Nachbedingung**: Der Nutzer ist **nicht** mit der Nutzung vertraut.