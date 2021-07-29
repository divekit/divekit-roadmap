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
        date: 2021-07-29
        comment: added use cases

todo: 
---

## Beschreibung

Die funktionale Anforderung „Weiterführende Informationen“ hängt von den aufgelisteten Use Cases ab. Dabei wurde der Hauptanwendungsfalls als "Informationen anfordern" identifiziert.

|No.|Interaktion|Akteur|Inhalt|
|---|-----------|------|------|
|1|Informationen anfordern|Student:in|Die Student:in ruft weiterführende Informationen zum Fehler ab.|
|2|Informationen pflegen|WMA|Der wissenschaftliche Mitarbeiter (WMA) pflegt die Informationen, welche zu den Fehlern eingebunden sind.|
|2.1|Informationen bearbeiten|WMA|Der wissenschaftliche Mitarbeiter (WMA) erstellt und bearbeitet die Informationen zu den Fehlern.|
|2.2|Informationen löschen|WMA|Der wissenschaftliche Mitarbeiter (WMA)  löscht die Informationen zu den Fehlern, wenn diese veraltet oder selbst fehlerhaft sind.|


