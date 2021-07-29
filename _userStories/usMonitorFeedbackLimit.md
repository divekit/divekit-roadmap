---
type: userStory
acronym: usMonitorFeedbackLimit
responsible:
    - tza
title: Feedback-Obergrenze überwachen
functionalRequirement: FeedbackLimit
asA: lehrende
iWantTo: Die eingestellte Obergrenze für die Anzahl von Feedback-Anfragen überwacht wird
forThisReason: damit die Studierende nicht mehr Anfragen stellen können, als es ihnen erlaubt wurde
history:
    v1:
        date: 2021-07-29
        comment: initially created

todo:

---

## Hinweise
Nachdem der Lehrende die Obergrenze festgelegt hat (siehe [Feedback-Obergrenze setzen](./usSetFeedbackLimit.md)),
verbietet das System dem Studierenden, die *(n + 1)*-te Anfrage zu senden (wobei *n* die festgelegte Obergrenze ist).
Die Studierenden werden durch eine entsprechende Meldung darauf aufmerksam gemacht (siehe [Feedback-Obergrenze erreicht](./usFeedbackLimitReached.md)).
