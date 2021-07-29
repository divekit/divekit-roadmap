---
type: functionalRequirement
acronym: AllgemeinesFeedback
responsible:
    - mwi
    - duz
title: Feedback zum Code nach bestandenem Tests
goals:
    - ganzheitlichesFeedback
    - motivation
    - studVorbereiten
implementationStatus: open
prefilterPriorizationPoints: 4
kano:
    type: excitement
    reasoning: >
        Die Möglichkeit für bestandene sowie nicht bestandene Tests Rückmeldung, also allgemeines Feedback zu allen
        eingereichten Lösungen, zu erhalten, ist als Begeisterungsmerkmal einzuordnen, da zu nicht bestandenen Aufgaben
        bereits Feedback gegeben wird und daher eine Grundlage für Verbesserung besteht. Wäre die Funktionalität allerdings
        vorhanden, könnte den Studierenden Rückmeldung darüber gegeben werden, wie "gut" ihre Lösung ist. Durch die
        Auseinandersetzung mit einer solchen Rückmeldung kann ebenfalls ein großer Lerneffekt erzielt werden.
source:
    - [beobachtungstagebuch, PC10]
history:
    v1:
        date: 2021-07-08
        comment: initially created
    v2:
        date: 2021-07-12
        comment: Added all responsible authors, modified FA and reason regarding the todo
    v3:
        date: 2021-07-16
        comment: Modified responsibles as discussed
    v4:
        date: 2021-07-16
        comment: Added kano reasoning
    v5:
        date: 2021-07-16
        comment: Added goals
    v6:
        date: 2021-07-26
        comment: modified regarding todo
    v7:
        date: 2021-07-29
        comment: modified reason and title regarding todo
todo:
---

Das DiveKit muss in der Lage sein, dem Studierenden zu nicht bestandenen Tests und auch bestandenen Tests Feedback zu geben.

## Begründung
Dem Benutzer soll auch eine Rückmeldung gegeben werden, wie “gut” eine Lösung ist. Es wird sich somit auch Feedback zu bestandenen Tests gewünscht. 

Vermutende Lösung des Business Analysten: Eine erarbeitete Lösung kann auch "unschön" gelöst sein und das ist nicht zielführend. Vermutlich wird sich gewünscht, dass Feedback zum geschriebenen Code erfolgt. Das kann zum Beispiel auf Basis bestimmter eingehaltener Strukturen basieren, Stichwort Clean Code, oder auch die Einhaltung von Konventionen beinhalten.
