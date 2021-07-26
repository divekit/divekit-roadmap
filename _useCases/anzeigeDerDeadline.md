---
type: useCase
acronym: anzeigeDerDeadline
responsible:
    - ama
title: Ausführliches Feedback
description: Eine studierende Person möchte Informationen über die Deadline einer Aufgabe erhalten
primaryActor: 
    - student
trigger: Die studierende Person sieht sich die Informationen über die Deadline an.
precondition: Die studierende Person hat sich die Informationen über die Deadline angesehen.
postcondition: Die studierende Person erhält die Informationen über die Aufgaben Deadlines.
functionalRequirement: AnzeigederDeadline
history:
    v1:
        date: 2021-07-22
        comment: initially created
todo:
---

## Hauptszenario

* 1) Der Studierende möchte Informationen über die Deadlines der zu erledigenden Aufgaben erhalten
* 2) Der Studierende öffnet die Seite, in dem die Aufgaben-Deadlines hinterlegt sind
* 3) Das System zeigt dem Studierenden die Aufgaben-Deadlines
* 4) Der Studierende sucht nach den Deadlines und notiert sich die Termine
* 5) Der Studierende strukturiert seine Aufgaben


## Alternativszenario
* 1a) Es gab eine Mitteilung das die Deadlines von einigen Aufgaben verschoben wurden
* 1b) Einige Deadlines mussten aus organisatorischen Gründen zeitlich nach hinten verschoben werden

## Ausnahmeszenario
* 2a) Das Datum der Deadline liegt schon in der Vergangenheit 
* 3b) Das System zeigt die Deadlines nicht an