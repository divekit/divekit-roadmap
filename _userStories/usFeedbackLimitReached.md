---
type: userStory
acronym: usFeedbackLimitReached
responsible:
    - tza
title: Feedback-Obergrenze erreicht
functionalRequirement: FeedbackLimit
asA: studierende
iWantTo: Mit einer Meldung darauf aufmerksam gemacht werden, dass ich die Obergrenze für Feedback-Anfragen erreicht habe und keine weiteren Anfragen senden kann
forThisReason: damit ich darauf reagieren kann
history:
    v1:
        date: 2021-07-29
        comment: initially created
todo:
    - (tza) Akzeptanzkriterien präzisieren.

---

## Akzeptanzkriterien:
* Nachdem der Benutzer erfolgreich eine Anfrage versendet hat, prüft das System prüft, ob der Benutzer die Feedback-Obergrenze erreicht hat
* Das ist der Fall, wenn:
    * Anzahl bereits ausgelöster Anfragen >= Feedback-Obergrenze
* In diesem Fall zeigt das System eine entsprechende Meldung an

## Notizen
(Die Akzeptanzkriterien müssen noch präzisiert werden, deswegen kann die User Story noch nicht eingeplant werden.)
