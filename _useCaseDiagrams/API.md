---
type: useCaseDiagram
acronym: API
responsible: 
    - jlü
title: Use Case Diagram Erweiterung durch API 
functionalRequirement: API
useCases:
    - Individuelle Aufgabe stellen
    - Aufgabe abrufen
    - Aufgabe bearbeiten
    - Lösung einsenden
    - Lösung abrufen
    - Informationen bereitstellen
    - Informationen abrufen
useCasesDetailedWithScenario: LösungenBeiDrittsystemEinreichen
diagram: ./diagrams/usecaseAPI.png
history:
    v1:
        date: 2021-07-21
        comment: initially created
    v2:
        date: 2021-07-27
        comment: update description
    v3: 
        date: 2021-07-30
        comment: update diagramm and description
todo:
---

## Beschreibung

Das Use Case Diagramm stellt einige Nutzungsmöglichkeiten für die funktionale Anforderung "API" dar. Hier wird eine Api für 
Google Cloud dargestellt. 

Der Use Case "(Individuelle) Aufgabe stellen" beschreibt die Aktivität eine*r Dozent*in, die eine Aufgabe 
stellen möchte, die die Einbindung eines Drittsystems erfordert. 

Der Use Case "Aufgabe abrufen" beschreibt die Aktivität, wenn ein*e Student*in die Aufgabe von dem Drittsystem abruft.

Anschließend kann die*der Student*in die Aufgabe bearbeiten. Dementsprechend folgt der Use Case "Aufgabe bearbeiten". 

Der Use Case "Lösung einsenden" wird von Studierenden ausgelöst. Nach dem Bearbeiten der durch die lehrende Person gestellte Aufgabe 
können die Studierenden ihre Lösung zu den Aufgaben einreichen.

Der Use Case "Lösungen abrufen" wird durch die Lehrenden angestoßen. Wenn die Studierenden die Aufgaben bearbeitet haben, 
kann der*die Dozent*in die Lösungen, die eingereicht wurden, abrufen. 


Der Use Case "Informationen bereitstellen" wird durch das Drittsystem angestoßen. Notwendige Informationen werden an das
System übermittelt.

Der Use Case "Informationen abrufen" kann nach dem Use Case "Informationen bereitstellen" durch die Studenten angestoßen werden.
Informationen, die durch das Drittsystem bereitgestellt wurden, können hier abgerufen werden.
