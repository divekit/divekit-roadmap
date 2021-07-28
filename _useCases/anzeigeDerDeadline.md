---
type: useCase
acronym: AnzeigederDeadline
responsible:
    - ama
title: Anzeige der Deadline
description: Eine studierende Person möchte Informationen über die Deadline einer Aufgabe erhalten
primaryActor: studierende
trigger: Die studierende Person sieht sich die Informationen über die Deadline an.
precondition: Die studierende Person hat sich die Informationen über die Deadline angesehen.
postcondition: Die studierende Person erhält die Informationen über die Aufgaben Deadlines.
functionalRequirement: Anzeige der Deadline
history:
    v1:
        date: 2021-07-22
        comment: initially created
todo:
    - (sbe) Precondition ist "Die studierende Person hat sich die Informationen über die Deadline angesehen." Schritt 1 ist "Der Studierende möchte Informationen über die Deadlines der zu erledigenden Aufgaben erhalten", also ein Wunsch, keine Aktion ... das ergibt zusammen keinen Sinn. 
    - (sbe) Die Aktion ist komplett trivial - der Studierende öffnet einfach eine (statische?) Webseite und schaut nach. Dafür brauche ich eigentlich keinen Use Case. Schauen Sie doch nochmal in die zugrundeliegenden Artefakte - FR, Goals, Szenarien - ob das so gemeint sein kann. 
    - (sbe) Inwiefern ist das Alternativszenario ein alternativer Ablauf? 
    - (sbe) das Ausnahmeszenario macht keinen Sinn
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