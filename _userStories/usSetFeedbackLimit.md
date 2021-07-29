---
type: userStory
acronym: usSetFeedbackLimit
responsible:
    - tza
title: Feedback-Obergrenze setzen
functionalRequirement: FeedbackLimit
asA: lehrende
iWantTo: Die Einstellung einer Obergrenze für die Anzahl von Feedback-Anfragen vornehmen
forThisReason: damit die Studierenden durch mehrere Feedback-Anfragen vollständige Lösung nicht erfragen können
history:
    v1:
        date: 2021-07-23
        comment: initially created
    v2:
        date: 2021-07-29
        comment: User Story kleiner gemacht, indem auf mehrere aufgeteilt.

todo:
    - (sbe) (von tza verkürzt) US Ist zu groß
    - (tza) (Antwort) Ich habe jetzt noch paar weitere US's daraus gemacht. Hier wird auch davon ausgegangen, dass unterschiedliche Einstellungen durch den Nutzer bereits möglich sind und jetzt nur noch eine neue dazu kommt. Es soll locker in einem Sprint umgesetzt werden.

---

## Hinweise
Es wird dem Nutzer ermöglicht eine neue Einstellung vorzunehmen.
Es wird die Obergrenze für die Anzahl von Feedback-Anfragen gesetzt.
Dies muss persistiert werden, um im weiteren Verlauf berücksichtigt zu werden.

Siehe auch:
- [Feedback-Obergrenze überwachen](./usMonitorFeedbackLimit.md)
- [Feedback-Obergrenze erreicht](./usFeedbackLimitReached.md)
- [Warnung über Feedback-Obergrenze](./usFeedbackLimitWarning.md)
