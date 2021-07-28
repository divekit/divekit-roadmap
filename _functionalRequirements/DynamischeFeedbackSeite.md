---
type: functionalRequirement
acronym: DynamischeFeedbackSeite
responsible: 
    - hbu
    - jlü
title: Die Feedback-Seite muss dynamisch und interaktiv sein
goals: 
    - entlastungAutoSystem
    - organisationKompakt
    - entlastung
    - autoUpdate
implementationStatus: open
prefilterPriorizationPoints: 0
source:
    - [sources/walt_disney_miro.pdf]
    - [beobachtungstagebuch, AV1]
history:
    v1:
        date: 2021-07-07
        comment: initially created
    v2:
        date: 2021-07-15
        comment: Fixed goales
    v3:
        date: 2021-07-16
        comment: Did TODOs
    v4:
        date: 2021-07-27
        comment: merge duplicate
todo:
---

Das DiveKit muss eine Feedback-Seite generieren, die bei der automatisierten Abgabe erstellt wird.

## Begründung

Die statische Seite gibt keine Auskunft darüber, ob gerade etwas passiert und wie lange es ggf. noch dauert.
Eine bessere Interaktivität würde das Benutzererlebnis verbessern und die Daten könnten besser dargestellt werden.
Die neue Seite sollte Informationen dynamisch und interaktiv darstellen. Zu den Informationen gehören
ob und welche Tests bestanden sind und ggf. warum sie rot (fehlgeschlagen) sind, mögliche Fehlerquellen und Hilfe zur Lösung und der Stand der
automatisierten Bearbeitung nach dem commit/push.
