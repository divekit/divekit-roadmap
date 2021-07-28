---
type: useCase
acronym: feedbackArchivDurchsuchen
responsible: 
    - ako
title: Feedback suchen
description: Ein Studierender durchsucht das Feedback-Archiv nach ähnlichen Problemen, um gegebenenfalls ähnliche Lösungen oder anders formuliertes Feedback als Inspiration zu nutzen.
primaryActor: studierende
secondaryActors: 
    - wmaAutonomousLecturerInf
    - wmaProg
    - profInf
trigger: Ein Studierender bearbeitet eine Aufgabe und braucht Inspiration.
precondition: Ein Feedback-Archiv mit einträgen existiert.
postcondition: Der Studierende kann sich an vergangenen Hilfestellungen orientieren.
functionalRequirement: FeedbackArchiv
history:
    v1:
        date: 2021-07-17
        comment: initially created
todo: 
    - (sbe) die secondaryActors kommen im Use Case nicht vor!
    - (sbe) Das Szenario fängt irgendwie mittendrin an. Was (welche Nutzeraktion) kommt vorher?
    - (sbe) Versetzen Sie sich mal in die Situation eines Entwicklungsteams - wären Sie in der Lage, auf der Basis dieser Beschreibung Software zu bauen? Mir wäre insbesondere unklar, was genau ein "Feedback" in diesem Kontext ist. (Der Rest ist klar)   
---


## Hauptszenario

* 1) Ein Studierender öffnet das Feedback-Archiv
* 2) Ein Studierender gibt einen wichtigen Begriff in der Suche ein
* 3) Das System gibt eine Liste mit Feedbacks aus die den Begriff enthalten
* 4) Der Studierende wählt ein Feedback aus
* 5) Das System stellt das Feedback detailliert dar

## Alternativszenario

* 3a) Das System gibt eine Liste mit Feedbacks aus, die einen *ähnlichen* Begriff enthalten

## Ausnahmeszenario 

* 3a) Das System findet kein Feedback das den genauen oder einen ähnlichen Begriff enthält

**Andere Nachbedingung**: Studierender kann kein altes Feedback für seine Arbeit verwenden
