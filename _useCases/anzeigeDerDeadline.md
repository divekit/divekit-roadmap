---
type: useCase
acronym: AnzeigederDeadline
responsible:
    - ama
title: Anzeige der Deadline
description: Eine studierende Person möchte Informationen über die Deadline einer Aufgabe erhalten
primaryActor: studierende
trigger: Die Deadline der Aufgabe einsehen
precondition: Aufgaben Deadlines wurden auf der Testseite festgelegt
postcondition: Der Studierende erhält die Informationen über die Deadline der Aufgaben
functionalRequirement: Anzeige der Deadline
history:
    v1:
        date: 2021-07-22
        comment: initially created
    v2:
        date: 2021-07-29
        comment: changes on trigger, precondition, Hauptszenario
    v3:
        date: 2021-08-01
        comment: change Hauptszenario
todo:
---

## Hauptszenario

* 1) Der Studierende öffnet die Deadlines Übersicht auf der Testseite
* 2) Das System zeigt dem Studierenden die Deadlines auf der Testseite an
* 3) Der Studierende sucht nach den Deadlines von seinen Aufgaben.