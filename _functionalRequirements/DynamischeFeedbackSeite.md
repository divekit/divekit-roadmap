---
type: functionalRequirement
acronym: DynamischeFeedbackSeite
responsible: 
    - hbu
title: Die Feedback-Seite muss dynamisch und interaktiv sein
goals: 
    - entlastungAutoSystem
    - organisationKompakt
    - entlastung
implementationStatus: open
prefilterPriorizationPoints: 0
source:
    - [sources/walt_disney_miro.pdf]
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
---

Das DiveKit muss eine Feedback-Seite generieren, die bei der automatisierten Abgabe erstellt wird.

## Begründung

Die statische Seite gibt keine Auskunft darüber, ob gerade etwas passiert und wie lange es ggf. noch dauert.
Eine bessere Interaktivität würde das Benutzererlebnis verbessern und die Daten könnten besser dargestellt werden.
Die neue Seite sollte Informationen dynamisch und interaktiv dargestllt werden. Zu den Informationen gehören
ob und welche Tests bestanden sind und warum, mögliche Fehlerquellen und Hilfe zur Lösung und der Stand der
automatisierten Bearbeitung nach dem commit/push.