---
type: useCase
acronym: setFeedbackLimit
responsible: 
    - tza
title: Feedback-Obergrenze setzen
description: Die Anzahl der Feedback-Anfragen wird nach oben begrenzt, damit Studierende diese nicht überschreiten dürfen. (Dadurch wird das Risiko vermieden, dass die Studierenden durch Feedback vollständige Lösung erfragen)
primaryActor: dozent
secondaryActors:
trigger: Der Lehrende will nur eine bestimmte Anzahl von Feedback-Anfragen erhalten
precondition: Der Lehrende ist mit der entsprechenden Rolle angemeldet und kann die Einstellungen vornehmen
postcondition: Der Lehrende erhält maximal eine bestimmte Anzahl von Anfragen und die Studierende werden benachrichtigt, wenn sie diese Grenze überschreiten
funcionalRequirements: 
    - FeedbackLimit
history:
    v1:
        date: 2021-07-23
        comment: initially created

todo:

---

## Hauptszenario

* 1) Lehrender meldet sich an
* 2) Er navigiert zu den Einstellungen
* 3) Er wählt die Einstellung für Feedback-Obergrenze aus
* 4) Er gibt einen Wert ein (z. B.: 5)    
* 5) Er speichert die geänderte Einstellung


## Alternativszenario

* 2a) Er navigiert zu "Benachrichtigungsmenü"
* 3a) Er gibt eine Nachricht ein (mit der Information, dass die Studierenden nur eine bestimmte Anzahl von Feedback-Anfragen stellen dürfen und alle weitere Anfragen einfach ignoriert werden)
* 4a) Er versendet die Nachricht an alle teilnehmende Studierende


## Ausnahmeszenario 

* 2b) Er navigiert zu den Einstellungen aber wird benachrichtigt, dass er nicht genug Rechte hat um die Einstellungen zu ändern
* 4b) Er gibt einen Wert ein
* 5b) Der Button zum Speichern ist ausgegraut

**Andere Nachbedingung**: Die Einstellung wurde nicht gespeichert. Die Studierende können weiterhin unbegrenzte Anzahl an Feedback-Anfragen stellen.
