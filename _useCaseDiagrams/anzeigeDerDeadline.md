---
type: useCaseDiagram
acronym: UCD_anzeigeDerDeadline
responsible:
    - mwi
title: Use Case Diagramm Anzeige der Deadline
functionalRequirement: AnzeigederDeadline
useCases:
    - Testseite aufrufen
    - Deadline spezifizieren
useCasesDetailedWithScenario: 
    - AnzeigederDeadline
diagram: ./diagrams/useCaseAnzeigeDerDeadline.png
history:
    v1:
        date: 2021-07-22
        comment: initially created
    v2:
        date: 2021-08-01
        comment: fixed todo
todo:
---

## Beschreibung

Hier werden Interaktionen mit dem System dargestellt, die von der funktionalen Anforderung _Anzeige der Deadline_ abstammen.

Beim Use Case _Testseite aufrufen_ ruft die studierende Person die persönliche Testseite in DiveKit auf. Neben anderen Informationen
wird auf dieser die Deadline der abzugebenden Aufgaben dargestellt. Diese werden immer dargestellt, wenn eine Deadline vom Dozenten
spezifiziert wurde.

Beim Use Case _Deadline spezifizieren_ legt der Dozent bei der Bereitstellung der zu bearbeitenden Aufgaben die Deadline
für diese fest.

