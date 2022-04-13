---
type: useCase
acronym: verbessertesFeedback
responsible: 
    - fgr
title: Verbessertes Feedback
description: Ein*e Student*in kann Verbesserungsvorschläge ansehen.
primaryActor: studierende
secondaryActors:
    - wmaProg
    - profInf
    - profMa
    - profBwl
trigger: Der/die User*in gibt seine Aufgaben ab
precondition: > 
    Es muss eine Möglichkeit geben, die Ergebnisse zu den Aufgaben und das Ergebnis der Kontrolle einzureichen und 
    Verbesserungsvorschläge anzuzeigen.
postcondition: Der/Die User*in bekommt zusätzliches Feedback.
functionalRequirement: VerbessertesFeedback
history:
    v1:
        date: 2021-07-22
        comment: initially created
todo: 
---

Als User*in gelten alle Studenten, welche Aufgaben im Divekit abgeben.

## Hauptszenario

* 1) Die Aufgabe wird einem passenden Prüfer (wmaProg, profInf, profMa oder profBWL) zugeordnet.
* 2) Die Abgabe wird von dem/der Prüfer*in kontrolliert.
* 3) Der/Die Prüfer*in gibt das Ergebnis an Divekit.
* 4) Der/Die User*in wird benachrichtigt, das sein*e Aufgaben kontrolliert wurde.
* 5) Der/Die User*in schaut sich seine Ergebnisse an.
* 6) Der/Die User*in schaut sich Verbesserungsvorschläge für seine Abgabe an.

## Alternativszenario

## Ausnahmeszenario 

* 6a) Es wurden keine Verbesserungsvorschläge eingereicht und damit werden auch keine angezeigt.


**Andere Nachbedingung**: Der/Die User*in bekommt kein zusätzliches Feedback.


