---
type: userStory
acronym: usSetFeedbackLimit
responsible:
	- tza
title: Feedback-Obergrenze setzen
funcionalRequirement: FeedbackLimit
asA: 
    - dozent
iWantTo: Die Einstellung einer Obergrenze für die Anzahl von Feedback-Anfragen vornehmen
forThisReason: damit die Studierenden durch mehrere Feedback-Anfragen vollständige Lösung nicht erfragen können
history:
	v1:
		date: 2021-07-23
		comment: initially created

todo:
	
---

## User Story
Als Lehrender möchte ich eine Obergrenze für die Anzahl von Feedback-Anfragen zu setzen,
damit die Studierenden durch mehrere Feedback-Anfragen vollständige Lösung nicht erfragen können.

## Hinweise
Nachdem der Lehrende die Obergrenze festgelegt hat, verbietet das System dem Studierenden,
die *(n + 1)*-te Anfrage zu senden (wobei *n* die festgelegte Obergrenze ist).
Die Studierenden werden durch eine entsprechende Meldung darauf aufmerksam gemacht.
