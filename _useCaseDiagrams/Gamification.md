---
type: useCaseDiagram
acronym: Gamification
responsible: 
    - psc
title: Use Case Diagram für Gamification
functionalRequirement: MotivationDurchGamification
useCases:
useCasesDetailedWithScenario:
    - Gamification
diagram: ./diagrams/useCaseGamification.jpg
history:
    v1:
        date: 2021-07-23
        comment: initially created
    v2:
        date: 2021-07-28
        comment: Verbesserungen aus Review umgesetzt
todo: 
---

## Beschreibung

Dieses Usecase-Diagramm stellt eine mögliche Option der funktionalen Anforderung _Lernmotivation durch Gamification_ dar.

Der primäre Nutzer ist hierbei der Studierende, der durch die Interaktion mit dem System (Divekit) entsprechende Errungenschaften erlangen kann.

Exemplarisch wird im Use Case Diagramm die Auswahl, Bearbeitung und als Erweiterung das Finalisieren einer Aufgabe abgebildet.

Der Studierende erhält bei der Auswahl der ersten Aufgabe eine Errungenschaft.

Der Studierende erabeitet dann die Aufgabe und stellt, sobald ein erster Bearbeitungsstand vorliegt, den ersten Commit und pushed diesen in sein Repo. Das System checkt, ob die Bedingungen für eine Errungenschaft erfüllt sind. Der Studierende erhält eine weitere Errungenschaft.

Der Studierende finalisiert die Aufgabe und pushed diese zur Überprüfung in das System. Ist die Überprüfung erfolgreich, wird eine Errungenschaft vergeben.

Weist die Aufgabe Fehler auf, vergibt das System auch Errungenschaften.




