---
type: useCaseDiagram
acronym: branding
responsible: 
    - ngi
title: Use Case Diagram Branding
functionalRequirement: IndividuellesDesign
useCases:
useCasesDetailedWithScenario:
    - branding
diagram: ./diagrams/useCaseBranding.jpg
history:
    v1:
        date: 2021-07-22
        comment: initially created
todo: 
    - (sbe) Use Cases sind viel zu kleinteilig - schauen Sie sich mal die "User Happiness Rule" an
    - (sbe) Beziehungen zwischen UC sind entweder include, extends, oder Inheritence. Sie haben eine Menge einfacher Striche im Diagramm, die es in UML so nicht gibt.
---

## Beschreibung

Dieses Usecase-Diagramm stellt die Interaktionen eines hochschulexternen Anwenders dar, die für die Änderung des Brandings relevant sind.

Dabei kann der externe Anwender nach dem Aufrufen der Seite mit den Einstellungsmöglichkeiten für das Branding drei verschiedene Anpassungen vornehmen und das Design des Systems and das Branding seiner Hochschule anzupassen.
* Anpassen der Einstellungen für die farbliche Gestaltung der graphischen Oberfläche für die drei verschiedenen Ansichten Standard, Darkmode und Barrierearm
* Anpassen von individuellen Headern
* Hochladen individueller Icons

Nach dem Anpassen der entsprechenden Einstellungsmöglichkeit wird die Änderung abgespeichert.

Voraussetzung für das Aufrufen dieser Einstellungsmöglichkeiten ist ein Login in das System mit der entsprechenden Berechtigung, beispielsweise als Verwalter.



