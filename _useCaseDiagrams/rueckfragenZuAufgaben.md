---
type: useCaseDiagram
acronym: useCaseDiagramRueckfragenZuAufgaben
responsible: 
    - aha
title: Use Case Diagram Rückfragen zu Aufgaben
functionalRequirement: RueckfragenZuAufgaben
useCases:
useCasesDetailedWithScenario:
    - rueckfrageStellen
diagram: ./diagrams/useCaseRueckfragenZuAufgaben.svg
history:
    v1:
        date: 2021-07-19
        comment: initially created
    v2:
        date: 2021-07-27
        comment: fix use case ref
        
todo:
---

## Beschreibung

Das Use-Case-Diagramm stellt die Interaktionen der funktionalen Anforderung _Rückfragen zu Aufgaben_ dar.

Die Anforderung besteht aus folgenden Interaktionen:

|Interaktion|Akteur|Inhalt|
|-----------|------|------|
|Aufgaben abrufen|Student|Der Student ruft seine Aufgabenstellungen im Divekit ab.|
|Rückfrage stellen|Student|Der Student schreibt den WMAs eine Nachricht mit einer Rückfrage zu einer der Aufgabenstellungen.|
|Rückfragen abrufen|WMA|Der WMA ruft die Mailbox ab, in der die Nachrichten mit den Rückfragen landen.|
|Rückfrage beantworten|WMA|Der WMA schaut sich die Rückfrage-Nachricht an und verfasst eine Antwort darauf.|



