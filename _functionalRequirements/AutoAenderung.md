---
type: functionalRequirement
acronym: AutoAenderung
responsible:
    - jlü
    - duz
title: Automatische Erkennung von Änderungen an Dateien
goals: 
    - autoUpdate
implementationStatus: implemented
prefilterPriorizationPoints: 2
source:
    - [beobachtungstagebuch, PB1]
history:
    v1:
        date: 2021-07-08
        comment: initially created
    v2:
        date: 2021-07-12
        comment: Präzisierung
    v3:
        date: 2021-07-12
        comment: Added all responsible authors and added reason
    v5:
        date: 2021-07-16
        comment: Modified responsibles as discussed
todo:
    - (sbe) ich glaube zu wissen, was gemeint ist - Änderung an Dateien, die mit der Aufgabenstellung geliefert werden, aber durch Studierende nicht verändert werden dürfen, z.B. pom.xml. Bitte in Titel, Formulierung und Begründung präzisieren. 
---

Das DiveKit muss Änderungen der Nutzenden an den Dateien erkennen und entsprechend darauf reagieren.

## Begründung

Geänderte Dateien führen meist zu Fehlern, die durch die Umsetzung der Anforderung nicht mehr vorkommen sollten.
