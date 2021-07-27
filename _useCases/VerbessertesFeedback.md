---
type: useCase
acronym: verbessertesFeedback
responsible: 
    - fgr
title: Verbessertes Feedback
description: Ein*e Student*in kann sich zusätzliches Feedback anzeigen lassen.
primaryActor: mma
secondaryActors:
    - wmaProg
    - profInf
    - profMa
    - profBwl
trigger: Der/die User*in gibt seine Aufgaben ab
precondition: > 
    Eine Musterlösung wurde zusammen mit den Aufgaben erstellt und es existiert für korrigierte Abgaben eine Option "Zusätzliches Feedback anzeigen".
postcondition: Der/Die User*in bekommt zusätzliches Feedback.
functionalRequirement: verbessertesFeedback
history:
    v1:
        date: 2021-07-22
        comment: initially created
todo: 
    - mma ist Stakeholder - hier ist aber eine StakeholderRole gefragt (sbe)
---

Als User*in gelten alle Studenten, welche Aufgaben im Divekit abgeben.

## Hauptszenario

* 1) Die Abgabe wird von profInf, profMa, profBwl oder wmaProg kontrolliert.
* 2) Der/Die User*in bekommt das Ergebnis, das die Aufgabe mit unter 55% der Punkte bestanden wurde.
* 3) Der/Die User*in bekommt Verbesserungsvorschläge angezeigt.
* 4) Der/Die User*in bekommt die Musterlösung angezeigt.

## Alternativszenario

* 2a) Der/Die User*in bekommt das Ergebnis, das die Aufgabe mit über 55% der Punkte bestanden wurde.
* 2b) Der/Die User*in wählt die Option "Zusätzliches Feedback anzeigen" aus.
## Ausnahmeszenario 

* 4a) Es konnte für die Aufgabe(n) keine Musterlösung erstellt werden.
* 4b) Es wird keine Musterlösung angezeigt.

**Andere Nachbedingung**: Der/Die User*in bekommt kein zusätzliches Feedback.


