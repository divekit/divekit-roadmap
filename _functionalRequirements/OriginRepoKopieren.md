---
type: functionalRequirement
acronym: OriginRepoKopieren
responsible: 
    - hbu
title: Origin Repo muss kopiert werden
goals: 
    - entlastungAufgabenerstellung
    - entlastung
source:
    - [interview, fkrampe, Minute 00-09-47]
    - [interview, fkrampe, Minute 00-25-49]
implementationStatus: implemented
prefilterPriorizationPoints: 3
history:
    v1:
        date: 2021-06-18
        comment: initially created
    v2:
        date: 2021-06-18
        comment: added goals
    v3:
        date: 2021-07-15
        comment: Fixed goales
todo:
    - (sbe) Duplikat mit ZufaelligeGenerierungAufgaben. Bitte zusammenführen oder abgrenzen. 
---

Das DiveKit muss ein Origin-Git-Repository mit Aufgaben für jeden Studenten individuell kopieren und bereitstellen.

## Begründung

Diese funktionale Anforderung bietet Studenten die Möglichkeit, die Aufgaben der
Meilensteine (die in einem Repo sein können) einzelnd zu bearbeiten. Dieser Schritt muss automatisiert sein,
damit nicht manuell eine Vielzahl von Repos geklont werden muss.

