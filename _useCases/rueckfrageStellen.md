---
type: useCase
acronym: rueckfrageStellen
responsible: 
    - aha
title: Rückfrage stellen
description: Ein Student stellt eine Rückfrage zu einer Aufgabe
primaryActor: studierende
secondaryActors:
    - wmaAutonomousLecturerInf
trigger: Student hat eine Frage zu einer Aufgabenstellung
precondition: Der Student hat die Liste seiner Aufgaben erhalten.
postcondition: Der WMA hat eine Nachricht mit der Rückfrage zur Aufgabe erhalten und wurde darüber benachrichtigt.
functionalRequirement: RueckfragenZuAufgaben
history:
    v1:
        date: 2021-07-19
        comment: initially created
todo: 
---


## Hauptszenario

* 1) Der Student ruft seine Aufgabenstellungen ab.
* 2) Der Student stellt fest, dass es bezüglich einer der Aufgabe Klärungsbedarf gibt.
* 3) Der Student klickt neben der problematischen Aufgabenstellung auf den _Rückfrage stellen_ Button.
* 4) Der Student formuliert seine Fragen und klickt auf _Senden_.
* 5) Das System erstellt aus dem Freitext (Fragen) und der Aufgabenstellung die Nachricht an den WMA und schiebt diese in dessen Postfach.
* 6) Das System sendet dem WMA eine Benachrichtigung darüber, dass er eine neue Rückfrage in seinem Postfach hat.

## Alternativszenario

_entfällt_

## Ausnahmeszenario 

* 3a) Der Student stellt seine Rückfragen nicht über das System, sondern über einen anderen Weg (z.B. Vorlesung)
* 4a) Ende des Szenarios durch Verlassen des Systems.

**Andere Nachbedingung**: WMA wurde auf anderem Wege informiert.




