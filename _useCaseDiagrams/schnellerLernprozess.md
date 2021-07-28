---
type: useCaseDiagram
acronym: useCaseDiagramSchnellerLernprozess
responsible: 
    - duz
title: Use Case Diagram Schneller Lernprozess
functionalRequirement: SchnellerLernprozess
useCases:
    - Tutorial einpflegen
    - Tutorial bearbeiten
    - Tutorial löschen
    - Tutorial durchführen
    - Kontextbezogene-Hilfen darstellen
    - Kontextbezogene-Hilfen einpflegen
    - Kontextbezogene-Hilfen bearbeiten
    - Kontextbezogene-Hilfen löschen
useCasesDetailedWithScenario:
    - tutorialVorschlagen
diagram: ./diagrams/useCaseSchnellerLernprozess.jpg
history:
    v1:
        date: 2021-07-17
        comment: initially created
    v2:
        date: 2021-07-27
        comment: modified diagram and use cases regarding review
todo:
    - (sbe) Nutzer ist "Lehrende*r"
    - (sbe) Nutzer muss auch mit Tutorial vorschlagen verbunden sein (ihr wird das ja vorgeschlagen, primary Actor!)
    - (sbe) ist Kontextbezogene-Hilfen darstellen wirklich ein eigenständiger UC? 
    - (sbe) Wenn ja, wäre das nicht eine include- statt extends-Beziehung (von Tutorial durchführen)?
    - (sbe) "Tutorial erstellen" fehlt, oder? War das nicht ein Video?
    - (sbe) sonst gut!
---

## Beschreibung

Das Use-Case Diagramm stellt mögliche Nutzungen des Systemteils "Schneller Lernprozess" dar.
