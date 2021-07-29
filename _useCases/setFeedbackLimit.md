---
type: useCase
acronym: setFeedbackLimit
responsible: 
    - tza
title: Feedback-Obergrenze setzen
description: Es wird eine Obergrenze für die Anzahl von Feedback-Anfragen gesetzt, sodass die Studierende diese nicht überschreiten können. Dadurch wird das Risiko vermieden, dass die Studierenden durch Feedback vollständige Lösung erfragen
primaryActor: lehrende
secondaryActors:
    - studierende
trigger: Der Lehrende will nur eine bestimmte Anzahl von Feedback-Anfragen erhalten
precondition: Der Lehrende ist autorisiert und kann die Einstellungen vornehmen
postcondition: Der Lehrende erhält nur eine bestimmte Anzahl von Anfragen und die Studierenden können nun nur eine bestimmte Anzahl an Feedback-Anfragen stellen.
functionalRequirement: FeedbackLimit
history:
    v1:
        date: 2021-07-23
        comment: initially created
    v2:
        date: 2021-07-23
        comment: Review-Anmerkungen eingearbeitet
    v3:
        date: 2021-07-29
        comment: Alternativszenario wieder aufgenommen

todo:
    
---

## Hauptszenario

* 1) Lehrender meldet sich an
* 2) Er navigiert zu den Einstellungen
* 3) Er wählt die Einstellung für Feedback-Obergrenze aus
* 4) Er gibt einen Wert ein (z.B.: 5)    
* 5) Er speichert die geänderte Einstellung


## Alternativszenario

* 2a) Lehrender navigiert zu "Benachrichtigungsmenü"
* 3a) Er gibt eine Nachricht ein (mit der Information, dass die Studierenden nur eine bestimmte Anzahl von Feedback-Anfragen stellen dürfen und alle weitere Anfragen einfach ignoriert werden)
* 4a) Er versendet die Nachricht an alle teilnehmende Studierende
* 5a) Er führt eine Strichliste und ignoriert Anfragen über einer bestimmten Anzahl

Die Nachbedingung ist aber nicht vollständig erreicht. Die Studierende können rein technisch weiterhin unbegrenzte Anzahl an Feedback-Anfragen stellen. 

## Ausnahmeszenario 

* 2b) Er navigiert zu den Einstellungen aber wird benachrichtigt, dass er nicht genug Rechte hat um die Einstellungen zu ändern *(dann weiter mit 3)*
* 4b) Er gibt einen Wert ein 
* 5b) Der Button zum Speichern ist ausgegraut

**Andere Nachbedingung**: Die Einstellung wurde nicht gespeichert. Die Studierende können weiterhin unbegrenzte Anzahl an Feedback-Anfragen stellen.
