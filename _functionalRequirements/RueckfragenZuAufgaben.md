---
type: functionalRequirement
acronym: RueckfragenZuAufgaben
responsible:    
    - aha
title: Rückfragen zu Aufgaben
goals: 
    - betreuungRueckfragen
    - kommunikation
implementationStatus: open
prefilterPriorizationPoints: 2
kano:
    type: basic
    reasoning: >
        Es löst keine Begeisterung aus, wenn man direkt bei der Aufgabenstellung eine Rückfrage-Funktion zur Verfügung hat.
        Dafür ist das Feature zu funktional. Es würde aber nerven, wenn man häufiger mal Rückfragen stellen muss und dazu jedes
        Mal Umwege nehmen und die Aufgabenstellung manuell kopieren muss. Daher ist dieses Feature ein Basis-Feature.
source:
    - [workshop, waltDisney]
history:
    v1:
        date: 2021-07-08
        comment: initially created
    v2:
        date: 2021-07-15
        comment: fix goals
    v3:
        date: 2021-07-16
        comment: add kano
    v4:
        date: 2021-07-29
        comment: fix todo

todo:    
---

Das DiveKit soll Studierenden die Möglichkeit bieten, direkt Rückfragen zu Aufgaben zu stellen.
Dazu ist es sinnvoll, über einen Button an der Aufgabenstellung direkt eine neue Nachricht an den Betreuer
verfassen zu können, in die die Aufgabenstellung bereits vorformatiert eingebettet ist.
Wenn im Divekit bereits eine Chatfunktion implementiert wird (Goal _kommunikation_), dann ist es sinnvoll, diese
auch hierfür zu nutzen, gegebenenfalls aber eine separate "Mailbox" für die Rückfragen-Nachrichten einzubauen.
So wird das Stellen von Rückfragen stark vereinfacht und es gibt für Studierende wie auch Betreuer eine
eindeutige Anlaufstelle für alle offenen Fragen zu Aufgaben.

## Begründung

Vermeidung eines Medienbruchs und Ausnutzung des vorhandenen Systemkontexts zur Vereinfachung der Kommunikation.
