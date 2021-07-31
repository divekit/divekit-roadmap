---
type: useCase
acronym: Gamification
responsible: 
    - psc
title: 
description: Ein Studierender wurde durch Gamification motiviert
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
    v3:
        date: 2021-07-31
        comment: Exemplarische Errungenschaften und Überlegungen zu Punktesystem aufgenommen
todo:
    - (sbe) Alternativszenario - vielleicht eher, dass WMA von Hand einen Scorerpunkt vergeben?
    - (psc) Mit Blick auf eine Entlastung sollte dies weitestgehend automatisiert sein
---

## Hauptszenario

* 1) Der Studierende arbeitet an einer Aufgabe
* 2) Der Studierende committed seinen Bearbeitungsstand
* 3) Der Studierende pushed diesen in das System
* 4) Das System überprüft, ob Bedingungen für eine Errungenschaft erfüllt sind
* 5) Es sind Bedingungen für eine Errungenschaft erfüllt
* 6) Das System vergibt für die erhaltene Errungenschaft Punkte
* 7) Das System informiert den Studiereden über den Erhalt einer Errungenschaft

## Alternativszenario

* 5a) Es sind keine Bedingungen für eine Errungenschaft erfüllt

### Hinweis

Da für die funktionale Anforderung das Thema Gamification nur oberflächlich angeschnitten wird, werden in diesem Use Case lediglich exemplarische Spielelemente einer möglichen Motivation beschrieben. Konkret erhält der Studierende _Achievements/Errungenschaften_ für Interaktionen/Tätigkeiten mit dem Divekit. Zudem werden Punkte für die erhaltenen Errungenschaften vergeben.

### Beispiele für Errungenschaften

* Für den ersten gestellten Commit - _Willkommen Neuling_ - 5 Punkte
* Für das Aufrufen einer bestimmten Seite im DiveKit (z. B. Seite über Aufgabenstellung) - _Wissen ist Macht_ - 5 Punkte
* Für den ersten Commit der bei den Tests zu Fehlern führt - _Nobody is perfect_ - 15 Punkte
* Für die erste fehlerfreiv gelöste Aufgabe - _Noob++_ - 25 Punkte
* etc.

