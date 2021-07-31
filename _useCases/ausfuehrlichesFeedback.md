---
type: useCase
acronym: UCausführlichesFeedback
responsible:
    - mwi
title: Ausführliches Feedback
description: Eine studierende Person holt ausführliches automatisches Feedback zu einer Aufgabe ein.
primaryActor: studierende
secondaryActors:
trigger: Die studierende Person hat eine Lösung zu einer Aufgabe eingetragen.
precondition: Die studierende Person hat die Aufgabe bearbeitet.
postcondition: Die studierende Person erhält ausführliches Feedback zur abgegebenen Lösung unabhängig davon, ob sie korrekt gelöst wurde oder fehlerhaft ist.
functionalRequirement: AllgemeinesFeedback
history:
    v1:
        date: 2021-07-22
        comment: initially created
    v2:
        date: 2021-07-31
        comment: fixed todos as possible
todo:
    - (sbe) "4) Das System teilt der studierenden Person mit, welche Aspekte (trotz Korrektheit) nicht optimal gelöst wurden." Hier 
---

## Hauptszenario

1) Die studierende Person reicht eine Lösung durch ein _git commit/git push_ zur Prüfung ein.
2) Das System führt anhand der hinterlegten JUnit- und Markdown-Testbibliotheken eine automatische Überprüfung der Lösung durch.
3) Das System teilt der studierenden Person mit, ob die Aufgabe korrekt erledigt wurde.
4) Das System ermittelt mithilfe künstlicher Intelligenz die Optimalität der eingereichten Lösung.
5) Das System teilt der studierenden Person mit, welche Aspekte (trotz Korrektheit) nicht optimal gelöst wurden.


## Alternativszenario

Entfällt, da es sich hierbei um eine automatische Prüfung handelt und eine Lösung nur auf dem im Hauptszenario beschriebenen Weg eingereicht werden kann. 

## Ausnahmeszenario

* 2a) Das System findet bei der automatischen Überprüfung Anzeichen für ein Plagiat.
* 3a) Das System teilt der studierenden Person mit, dass die Überprüfung mehr Zeit benötigt.
* 3b) Das System informiert eine prüfberechtigte Person, dass die automatische Überprüfung Anzeichen für ein Plagiat gefunden hat und eine manuelle Prüfung erforderlich ist.

**Andere Nachbedingung**: Plagiatanzeichen wurden erkannt, eine manuelle Prüfung wurde eingeleitet.