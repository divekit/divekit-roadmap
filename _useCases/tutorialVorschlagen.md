---
type: useCase
acronym: tutorialVorschlagen
responsible: 
    - duz
title: Tutorial vorschlagen
description: Das System schlägt dem Nutzer ein Tutorial in Form eines Videos vor
primaryActor: profInf
secondaryActors:
    - profBwl
    - wmaAutonomousLecturerInf
    - wmaProg
trigger: Nutzer ruft einen Teil des Systems zum ersten Mal auf
precondition: Nutzer ist eingeloggt und "hat Funktion bereits benutzt" flag steht auf "nein"
postcondition: Nutzer ist mit Nutzung vertraut
functionalRequirement: SchnellerLernprozess
history:
    v1:
        date: 2021-07-17
        comment: initially created

todo: 
---


## Hauptszenario

* 1) Das System registriert einen Nutzer, der die Funktion noch nicht genutzt hat
* 2) Auf der geöffneten Seite werden Tutorial-Vorschläge eingeblendet
* 3) Nutzer sieht sieht sich ein Tutorial-Video an

## Alternativszenario

* 3a) Der Nutzer kennt sich bereits mit dem System aus und klickt die Tutorial-Vorschläge weg

## Ausnahmeszenario 

* 2a) Es existiert kein Tutorial für diese Funktion
* 3a) Das Tutorial für die Funktion ist veraltet
* 4) Das Tutorial hat dem Nutzer nicht weitergeholfen

**Andere Nachbedingung**: Der Nutzer ist **nicht** mit der Nutzung vertraut.