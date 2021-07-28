---
type: useCaseDiagram
acronym: useCaseDiagramInformationenAbbilden
responsible: 
    - kru
title: Use Case Diagram weiterführende Informationen abbilden
functionalRequirement: WeiterfuehrendeInformationen
useCases:
    - Informationen anfordern
    - Informationen pflegen
    - Informationen bearbeiten
    - Informationen löschen
useCasesDetailedWithScenario:
    - informationenAnfordern
diagram: ./diagrams/UseCaseInformationenAbbilden.png
history:
    v1:
        date: 2021-07-16
        comment: initially created
    v2:
        date: 2021-07-20
        comment: added diagram
    v3:
        date: 2021-07-20
        comment: added use cases
todo: 
    - (sbe) im Diagramm heißt es Mitarbeiter und im UC "WMA"
    - (sbe) im UC kommt der WMA auch vor (bei Alternativszenario). Es gibt aber keine Linie vom WMA zu Information anfordern im Diagramm. 
    - (sbe) die Include-Beziehungen sind eher Inheritence
---

## Beschreibung

Die funktionale Anforderung „Weiterführende Informationen“ hängt von den aufgelisteten Use Cases ab. Dabei wurde der Hauptanwendungsfalls als "Informationen anfordern" identifiziert.

|No.|Interaktion|Akteur|Inhalt|
|---|-----------|------|------|
|1|Informationen anfordern|Student:in|Die Student:in ruft weiterführende Informationen zum Fehler ab.|
|2|Informationen pflegen|WMA|Der Mitarbeiter pflegt die Informationen, welche zu den Fehlern eingebunden sind.|
|2.1|Informationen bearbeiten|WMA|Der Mitarbeiter erstellt und bearbeitet die Informationen zu den Fehlern.|
|2.2|Informationen löschen|WMA|Der Mitarbeiter löscht die Informationen zu den Fehlern, wenn diese veraltet oder selbst fehlerhaft sind.|



