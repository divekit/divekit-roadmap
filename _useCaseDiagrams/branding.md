---
type: useCaseDiagram
acronym: branding
responsible: 
    - ngi
title: Use Case Diagram Branding
functionalRequirement: BereitstellungUserPreferences
useCases: 
    - Aufrufen der Seite mit den Einstellungsmögichkeiten für das Branding
    - Anpassen der Einstellungsmöglichkeiten der Standardansicht
    - Anpassen der Einstellungsmöglichkeiten der Darkmode-Ansicht
    - Anpassen der individuellen Header
    - Anpassen der individuellen Icons
    - Automatisches Abspeichern der Einstellungen durch das System
useCasesDetailedWithScenario:
    - branding
diagram: ./diagrams/useCaseBranding.jpg
history:
    v1:
        date: 2021-07-22
        comment: initially created
    v2:
        date: 2021-08-01
        comment: fix functionalRequirement because merge
    v3:
        date: 2021-08-01
        comment: updated usecase diagram, added usecases
todo: 
---

## Beschreibung

Dieses Usecase-Diagramm stellt die Interaktionen eines hochschulexternen Anwenders dar, die für die Änderung des Brandings relevant sind.

Dabei kann der externe Anwender nach dem Aufrufen der Seite mit den Einstellungsmöglichkeiten für das Branding drei verschiedene Anpassungen vornehmen um das Design des Systems and das Branding seiner Hochschule anzupassen.
* Anpassen der Einstellungen für die farbliche Gestaltung der graphischen Oberfläche für die drei verschiedenen Ansichten Standard und Darkmode
* Anpassen von individuellen Headern
* Hochladen individueller Icons

Nach dem Anpassen der entsprechenden Einstellungsmöglichkeit wird die Änderung automatisch vom System abgespeichert.

Voraussetzung für das Aufrufen dieser Einstellungsmöglichkeiten ist ein Login in das System mit der entsprechenden Berechtigung, beispielsweise als Verwalter.



