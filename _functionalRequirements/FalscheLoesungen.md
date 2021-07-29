---
type: functionalRequirement
acronym: FalscheLoesungen
responsible:
    - jlü
    - kru
title: Fehlermeldungen der fehlgeschlagenen Tests
goals: 
    - fehlerErkennung
implementationStatus: implemented
prefilterPriorizationPoints: 1
source:
    - [beobachtungstagebuch, PP2]
history:
    v1:
        date: 2021-07-07
        comment: initially created
    v2:
        date: 2021-07-10
        comment: Entfernung der Begründung und des Duplikats
    v3:
        date: 2021-07-12
        comment: Added all responsible authors
    v4:
        date: 2021-07-15
        comment: Fixed goales
    v5:
        date: 2021-07-16
        comment: Modified responsibles as discussed
todo:
---

Wenn die von den Studierenden eingereichte Lösung fehlerhaft ist, soll das DiveKit die Fehler feststellen, den Testprozess abbrechen und diesen Fehler als inkorrekt markieren.


## Begründung
<!--(sbe) bitte präzisieren - wie ist der Halbsatz "und diese als inkorrekt markieren" gemeint, wenn es sich zum Beispiel um Code handelt, bei dem der Test fehlschlägt? -->
Vermutung des Business Analysten, da keine Rücksprache mehr mit dem Autoren gehalten werden kann: 
Der Fehler soll dem Studierenden visuell angezeigt werden. Es könnte bei Code das Hervorheben der fehlerhaften Stellen durch Highlighting gemeint sein oder nur die Anzeige des Fehlerortes (Klassen-, Funktions- oder konkrete Zeilenangabe). Wie ausführlich das gestaltet werden soll, kann nicht ermittelt werden.  