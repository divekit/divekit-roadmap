---
type: useCase
acronym: UCausführlichesFeedback
responsible:
    - mwi
title: Ausführliches Feedback
description: Eine studierende Person holt ausführliches Feedback zu einer Aufgabe ein.
primaryActor: 
    - student
secondaryActors:
    - profBwl
    - profInf
    - profMa
    - wmaAutonomousLecturerInf
    - wmaProg
trigger: Die studierende Person hat eine Lösung zu einer Aufgabe eingetragen.
precondition: Die studierende Person hat die Aufgabe bearbeitet.
postcondition: Die studierende Person erhält ausführliches Feedback zur abgegebenen Lösung unabhängig davon, ob sie korrekt gelöst wurde oder fehlerhaft ist.
funcionalRequirements:
    - AllgemeinesFeedback
history:
    v1:
        date: 2021-07-22
        comment: initially created
todo: 
---

## Hauptszenario

* 1) Die studierende Person legt eine Lösung zur Prüfung vor.
* 2) Das System führt eine automatische Überprüfung der Lösung durch.
* 3) Das System teilt der studierenden Person mit, ob die Aufgabe korrekt erledigt wurde.
* 4) Das System teilt der studierenden Person mit, welche Aspekte (trotz Korrektheit) nicht optimal gelöst wurden.


## Alternativszenario

* 2a) Die Aufgabe muss manuell überprüft werden.
* 2b) Eine prüfberechtigte Person wird informiert, dass die Aufgabe geprüft werden muss.
* 2c) Die prüfberechtigte Person prüft die Aufgabe.
* 3a) Die prüfberechtigte Person trägt im System ein, ob die Aufgabe korrekt erledigt wurde.
* 4a) Die prüfberechtigte Person teilt der studierenden Person über das System mit, welche Aspekte (trotz Korrektheit) nicht optimal gelöst wurden.

## Ausnahmeszenario

* 2a) Das System findet bei der automatischen Überprüfung Anzeichen für ein Plagiat.
* 2b) Eine prüfberechtigte Person wird informiert, dass die Lösung Anzeichen für ein Plagiat enthält und manuell überprüft werden muss.
* 2c) Die prüfberechtigte Person überprüft die Lösung.
* 3a) Die prüfberechtigte Person vermerkt im System, dass die Überprüfung mehr Zeit benötigt.
* 3b) Das System teilt der studierenden Person mit, dass die Überprüfung mehr Zeit benötigt.

**Andere Nachbedingung**: Plagiat wurde erkannt, der Versuch wird als Betrugsversuch gewertet.