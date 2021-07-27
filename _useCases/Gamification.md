---
type: useCase
acronym: Gamification
responsible: 
    - psc
title: 
description: Ein Student wurd durch Gamification motiviert
primaryActor: studierende
secondaryActors:
    - wmaProg
    - wmaDev
trigger: Studierender arbeitet im DiveKit
precondition: Studierender hat Zugriff auf seine Aufgaben
postcondition: Studierender ist motiviert die Aufgabe fertig zu stellen bzw. die nächste Aufgabe anzufangen
functionalRequirement: MotivationDurchGamification
history:
    v1:
        date: 2021-07-23
        comment: initially created

todo:
---


## Hauptszenario

* 1) Der Studierende ruft seine Aufgabenübersicht auf
* 2) Der Studierende wählt die erste Aufgabe aus
* 3) Der Studierende erhält ein Errungenschaft für die Auswahl der ersten Aufgabe
* 4) Der Studierende erarbeitet die Aufgabe und committed seinen Stand
* 5) Der Studierende erhält eine Errungenschaft für das erste Committen
* 6) Der Studierende finalisiert die erste Aufgabe
* 7) Der Studierende erhält eine Errungenschaft für die Abgabe der ersten Aufgabe
* 8) Der Studierende ist motiviert und beginnt mit der zweiten Aufgabe

## Alternativszenario

* 7a) Die abgegebene Aufgabe enthält Fehler
* 7b) Der Studierende erhält die Errungenschaft _Nobody is perfect_

## Ausnahmeszenario 

entfällt, da die Ausnahme nur bei Nichtnutzung des Divekits relevant wäre

### Hinweis

Da für die funktionale Anforderung das Thema Gamification nur oberflächlich angeschnitten wird, werden in diesem Use Case lediglich exemplarische Spielelemente einer möglichen Motivation beschrieben. Konkret erhält der Studierende _Achievements/Errungenschaften_ für Interaktionen/Tätigkeiten mit dem Divekit. 




