---
type: useCase
acronym: Gamification
responsible: 
    - psc
title: 
description: Ein Student wurde durch Gamification motiviert
primaryActor: studierende
secondaryActors:
    - wmaProg
    - wmaDev
trigger: Studierender arbeitet im DiveKit
precondition: Studierender hat Zugriff auf seine Aufgaben
postcondition: Studierender ist motiviert
functionalRequirement: MotivationDurchGamification
history:
    v1:
        date: 2021-07-23
        comment: initially created
    v2:
        date: 2021-07-28
        comment: Verbesserungen aus Review umgesetzt

todo:
---

## Hauptszenario

* 1) Der Studierende arbeitet an einer Aufgabe
* 2) Der Studierende committed seinen Bearbeitungsstand
* 3) Der Studierende pushed diesen in das System
* 4) Das System überprüft, ob Bedingungen für eine Errungenschaft erfüllt sind
* 5) Es sind Bedingungen für eine Errungenschaft erfüllt
* 6) Das System informiert den Studiereden über den Erhalt einer Errungenschaft

## Alternativszenario

* 5a) Es sind keine Bedingungen für eine Errungenschaft erfüllt

### Hinweis

Da für die funktionale Anforderung das Thema Gamification nur oberflächlich angeschnitten wird, werden in diesem Use Case lediglich exemplarische Spielelemente einer möglichen Motivation beschrieben. Konkret erhält der Studierende _Achievements/Errungenschaften_ für Interaktionen/Tätigkeiten mit dem Divekit. 




