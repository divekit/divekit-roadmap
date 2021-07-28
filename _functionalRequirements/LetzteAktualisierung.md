---
type: functionalRequirement
acronym: LetzteAktualisierung
responsible:
    - jlü
    - kru
title: Letzte Aktualisierung des Codes
goals: 
    - entlastungKorrektur
    - relevanteInformationen
implementationStatus: implemented
prefilterPriorizationPoints: 1
source:
    - [beobachtungstagebuch, AN2]
history:
    v1:
        date: 2021-07-08
        comment: initially created
    v2:
        date: 2021-07-12
        comment: Added all responsible authors
    v3:
        date: 2021-07-15
        comment: Fixed goales
    v4:
        date: 2021-07-16
        comment: Modified responsibles as discussed
    v5: 
        date: 2021-07-27
        comment: Add Erläuterung and modify FR 
todo:
    - (sbe) zumindest teilweise Duplikat von Zeitzone. Bitte abgrenzen oder zusammenführen.
---

Das DiveKit muss den Zeitstempel der letzten Aktualisierung des eingereichten Codes deutlich sichtbar und entsprechend der Zeitzone des Nutzers anzeigen.

## Erläuterung

Eine falsch angezeigte oder nicht vorhandene Zeit, wann der Code zuletzt eingereicht und somit überprüft wurde, hat in der Vergangenheit
oft für Verwirrungen geführt. 
