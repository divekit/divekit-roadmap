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
    v2:
        date: 2021-07-29
        comment: fix todo
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

* 3a) Der Student stellt seine Rückfragen nicht über das System, sondern über einen anderen Weg (z.B. Vorlesung, E-Mail)
* 4a) Ende des Szenarios durch Verlassen des Systems.

## Ausnahmeszenario

* 6a) Das System sendet dem WMA eine Benachrichtung per E-Mail, der hat jedoch eine falsche E-Mail-Adresse im System hinterlegt. Die Benachrichtigung kommt daher nicht an.

**Andere Nachbedingung**: WMA hat die Benachrichtigung nicht erhalten.




