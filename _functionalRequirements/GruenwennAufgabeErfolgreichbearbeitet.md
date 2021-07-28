---
type: functionalRequirement
acronym: GruenwennAufgabeErfolgreichbearbeitet
responsible:
    - jlü
    - kru
title: Erst Grün, wenn Aufgabe erfolgreich bearbeitet
goals: 
    - entlastungKorrektur
    - entlastungAutoSystem
implementationStatus: implemented
prefilterPriorizationPoints: 2
source:
    - [beobachtungstagebuch, AN2]
history:
    v1:
        date: 2021-07-08
        comment: initially created
    v2:
        date: 2021-07-10
        comment: Anmerkung zum Todo
    v3: 
        date: 2021-07-12
        comment: Anmerkung hinzufügen
    v4:
        date: 2021-07-12
        comment: Added all responsible authors
    v5:
        date: 2021-07-15
        comment: Fixed goales
    v5:
        date: 2021-07-16
        comment: Modified responsibles as discussed
todo:
    - (sbe) bitte in der Format der Satzschablone bringen
    - (sbe) was genau wäre denn die Anforderung hier? Anscheinend war ja die Aufgabenstellung unzureichend durch Tests abgesichert, so dass eine falsche Lösung trotzdem grün wurde. Was genau müsste DiveKit für ein Feature haben, damit das nicht passiert?     
---

Das DiveKit darf den Status eines Tests erst dann auf grün setzen, wenn der Benutzer die Aufgabe erfolgreich bearbeitet hat.


###  Anmerkung
Bei einem Studenten sind die Tests durchgelaufen, obwohl die Aufgabe offensichtlich nicht richtig war
