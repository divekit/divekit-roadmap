---
type: useCase
acronym: aufgabenMitGleicherSchwierigkeit
responsible: 
    - mba
title: Gleiche Schwierigkeit
description: Das System garantiert Aufgaben zu generieren, die den gleichen Schwierigkeitsgrad haben
primaryActor: lehrende
secondaryActors:
    - profInf
    - profMa
    - profBwl
    - wmaDev
    - wmaInf
    - wmaProg
trigger: Nutzer möchte Aufgaben generieren
precondition: Aufgabenmuster wurde festgelegt
postcondition: Nutzer erhält generierte Aufgaben, die alle auf dem selben Schwierigkeitsgrad basieren
functionalRequirement: GleicheSchwierigkeit
history:
    v1:
        date: 2021-07-19
        comment: initially created
todo: 
    - (sbe) die secondaryActors kommen sämtlich nicht im Use Case vor!
    - (sbe) Description "Das System garantiert Aufgaben zu generieren, die den gleichen Schwierigkeitsgrad haben" - wie soll das gehen? Wie kann das System das "garantieren", wo die Aufgaben durch Menschen gestellt werden?
    - (sbe) Viele Begriffe sind nicht erklärt und sind mir unklar - was ist die "Aufgabengenerierung", was ist ein "Muster"?  
    - (sbe) Versetzen Sie sich mal in die Situation eines Entwicklungsteams - wären Sie in der Lage, auf der Basis dieser Beschreibung Software zu bauen? 
    - (sbe) Alternativszenario 3b - "Der Nutzer stellt die fehlenden Informationen ein". Was könnten das für Informationen sein?
    - (sbe) Ausnahmeszenario - in 3c werden doch Aufgaben generiert. Dann stimmt die andere NB nicht. 
---


## Hauptszenario

* 1) Nutzer öffnet die Aufgabengenerierung
* 2) Nutzer stellt sein Muster dem DiveKit bereit, welches individualisiert werden soll
* 3) Das DiveKit generiert individualisierte Aufgaben
* 4) Nutzer erhält individualisierte Aufgaben mit gleichem Schwierigkeitsgrad

## Alternativszenario

* 3a) Das DiveKit kann die Generierung nicht starten auf Grund von fehlenden individualisierungs Einstellungen
* 3b) Der Nutzer stellt die fehlenden Informationen ein
* 3c) Das DiveKit generiert die Aufgaben

## Ausnahmeszenario 

* 3a) Der Nutzer übermittelt dem DiveKit fehlerhafte Informationen zum generieren der Aufgaben, worauf hin das DiveKit keine Aufgaben generieren kann
* 3b) Der Nutzer korrigiert die Informationen
* 3c) Das DiveKit generiert die Aufgaben

**Andere Nachbedingung**: Nutzer ist mit Divekit nicht vertraut und kann keine Aufgaben generieren




