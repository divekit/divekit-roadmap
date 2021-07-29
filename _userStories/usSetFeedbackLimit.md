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

todo:
    - (sbe) Sie haben jetzt hier zwei gleiche (?) Versionen der US - einmal die oben durch das Front Matter definierte (asA ... iWantTo ... forThisReason), und unten nochmal als Text. Bitte nutzen Sie *nur* das Front Matter.    
    - (sbe) Glauben Sie, dass Sie diese US in einem Sprint umsetzen können? Ist zu groß (jedenfalls wenn das Limit auch überwacht wird) und in dieser Form als US unbrauchbar (ist eher ein Epic oder gar ein Theme). Versuchen Sie einen sinnvollen ersten Schritt zu definieren!            
---

## User Story
Als Lehrender möchte ich eine Obergrenze für die Anzahl von Feedback-Anfragen zu setzen,
damit die Studierenden durch mehrere Feedback-Anfragen vollständige Lösung nicht erfragen können.

## Hinweise
Nachdem der Lehrende die Obergrenze festgelegt hat, verbietet das System dem Studierenden,
die *(n + 1)*-te Anfrage zu senden (wobei *n* die festgelegte Obergrenze ist).
Die Studierenden werden durch eine entsprechende Meldung darauf aufmerksam gemacht.
