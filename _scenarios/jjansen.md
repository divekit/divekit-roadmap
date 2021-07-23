---
type: scenario
acronym: jjansen
title: System robuster machen
persona: jjansen
scenarioTypes:
    - main
    - alternative
responsible: 
    - aha
source: 
    - [interview, jintveen, Minute 01-06-57]
history:
    v1:
        date: 2021-07-22
        comment: initially created
    v2:
        date: 2021-07-23
        comment: fix todos from review

todo:
---

## Ausgangslage
Johannes Jansen arbeitet als Entwickler am System mit. Als er eine neue Funktion einfügen will, stellt er fest, dass es ein Problem gibt.
Johannes stellt fest, dass das System bei einem Feature ein anderes Verhalten zeigt, als er erwartet hatte.
Als er etwas weiter nachforscht, stellt er fest, dass das Verhalten dieser Komponente für diesen Fall nicht genau spezifiziert war.
Bei seiner Arbeit am System stellt er in der Folge immer wieder fest, dass Features, die zu Anfang des Projekts implementiert wurden, solche Probleme verursachen.

## Hauptszenario 
Johannes kommt die Idee, die grundlegenden Funktionen des Systems strukturiert durchzutesten, um solche Probleme zu
dokumentieren und zu beheben. Dadurch möchte er vermeiden, in Zukunft noch öfter vor solchen Problemen zu stehen. Zum
Beheben der Probleme plant er, sich ein bis zwei Wochen am Stück nur mit der Fehlersuche und -behebung zu beschäftigen
und währenddessen die Implementation neuer Funktionen ruhen zu lassen.

## Alternativszenario
Johannes behebt diese Probleme, wenn er beim Arbeiten auf sie trifft und dokumentiert die Probleme und Lösungen.
Den zum strukturierten Testen und Beheben der Probleme der Codebasis nötigen Zeitaufwand möchte er vermeiden und daher
weiterhin die Probleme dann beheben, wenn sie ihm beim Implementieren neuer Funktionen begegnen.