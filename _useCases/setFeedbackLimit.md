---
type: useCase
acronym: setFeedbackLimit
responsible: 
    - tza
title: Feedback-Obergrenze setzen
description: Es wird eine Obergrenze für die Anzahl von Feedback-Anfragen gesetzt, sodass die Studierende diese nicht überschreiten können. Dadurch wird das Risiko vermieden, dass die Studierenden durch Feedback vollständige Lösung erfragen
primaryActor: lehrende
secondaryActors:
    - student
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

todo:
    - (sbe) das Alternativszenario ergibt aus meiner Sicht Sinn. Man könnte das so machen, dass der Lehrende eine Strichliste führt und dann ab z.B. 5 Anfragen nicht mehr reagiert. Also machen Sie da ruhig ein Alternativszenario draus.
    - (sbe)
    - (sbe)
---

## Hauptszenario

* 1) Lehrender meldet sich an
* 2) Er navigiert zu den Einstellungen
* 3) Er wählt die Einstellung für Feedback-Obergrenze aus
* 4) Er gibt einen Wert ein (z.B.: 5)    
* 5) Er speichert die geänderte Einstellung


## Alternativszenario

Es wurde kein Alternativszenario gefunden

*Begründung:*
Die gewünschte Nachbedingung kann mit den im System vorhandenen Mitteln nicht alternativ erreicht werden.
Ein möglicher organisatorischer Umweg kann wie folgt beschrieben werden:
* Lehrender navigiert zu "Benachrichtigungsmenü"
* Er gibt eine Nachricht ein (mit der Information, dass die Studierenden nur eine bestimmte Anzahl von Feedback-Anfragen stellen dürfen und alle weitere Anfragen einfach ignoriert werden)
* Er versendet die Nachricht an alle teilnehmende Studierende

Die Nachbedingung ist aber nicht vollständig erreicht. Die Studierende können rein technisch weiterhin unbegrenzte Anzahl an Feedback-Anfragen stellen. 

## Ausnahmeszenario 

* 2b) Er navigiert zu den Einstellungen aber wird benachrichtigt, dass er nicht genug Rechte hat um die Einstellungen zu ändern *(dann weiter mit 3)*
* 4b) Er gibt einen Wert ein 
* 5b) Der Button zum Speichern ist ausgegraut

**Andere Nachbedingung**: Die Einstellung wurde nicht gespeichert. Die Studierende können weiterhin unbegrenzte Anzahl an Feedback-Anfragen stellen.
