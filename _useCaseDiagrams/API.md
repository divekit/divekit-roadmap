---
type: useCaseDiagram
acronym: API
responsible: 
    - jlü
title: Use Case Diagram Erweiterung durch API 
functionalRequirement: API
useCases:
    - Individuelle Aufgabe stellen
    - Informationen bereitstellen
    - Informationen abrufen
    - Lösungen bereitstellen
    - Lösungen abrufen
    - Lösungen einreichen
useCasesDetailedWithScenario:
diagram: ./diagrams/usecaseAPI.png
history:
    v1:
        date: 2021-07-21
        comment: initially created
    v2:
        date: 2021-07-27
        comment: update description

todo:
---

## Beschreibung

Das Use Case Diagramm stellt einige Nutzungsmöglichkeiten für die funktionale Anforderung "API" dar.

Der Use Case "(Individuelle) Aufgabe stellen" beschreibt die Aktivität eine * r Dozent * in, die eine Aufgabe 
stellen möchte, die die Einbindung eines Drittsystems erfordert. 

Der Use Case "Informationen bereitstellen" wird durch das Drittsystem angestoßen. Notwendige Informationen werden an das 
System übermittelt.

Der Use Case "Informationen abrufen" kann nach dem Use Case "Informationen bereitstellen" durch die Studenten angestoßen werden.
Informationen, die durch das Drittsystem bereitgestellt wurden, können hier abgerufen werden.

Der Use Case "Lösung einsenden" wird von Studierenden ausgelöst. Nach dem Bearbeiten der durch die lehrende Person gestellte Aufgabe 
können die Studierenden ihre Lösung zu den Aufgaben einreichen. 

Der Use Case "Lösungen bereitstellen" muss nach dem Einsenden der Lösungen geschehen. Die eingereichten Lösungen müssen im DiveKit für 
die Dozierenden abrufbar sein.

Der Use Case "Lösungen abrufen" wird durch die Lehrenden angestoßen. Nachdem das Drittsystem, die durch Student * innen eingereichten Lösungen, bereitgestellt hat,
können diese die Lösungen abrufen und so korrigieren. 


