---
type: functionalRequirement
acronym: FehlermeldungAussagekraeftig
responsible: 
    - jsp
    - cpo
    - jlü
title: Aussagekräftige Fehlermeldungen
goals: 
    - fehlerFalscheKonfig
implementationStatus: open
prefilterPriorizationPoints: 6
kano:
    type: basic
    reasoning: >
        Für die Studierenden sollte es deutlich ersichtlich sein, wenn Fehler durch unerlaubte Änderungen an Dateien erzeugt 
        werden, die von Studierenden nicht verändert werden sollten. Das Fehlen einer passenden Fehlermeldung könnte eine 
        unnötige Fehlersuche für den Studierenden verursachen und viel Frust erzeugen.
source:
    - [WOrkshop, Workshop 6-3-5-No.2, Schwerpunkt Technik No.1]
    - [beobachtungstagebuch, PB1]
history:
    v1:
        date: 2021-07-08
        comment: initially created
    v2:
        date: 2021-07-15
        comment: Fixed goales
    v3:
        date: 2021-07-16
        comment: added kano classification
    v4:
        date: 2021-07-29
        comment: improved kano classification reasoning
    v5: 
        date: 2021-07-30
        comment: merge duplicate
todo:
---

Bei fehlerhaften Umgebungseinstellungen (pom.xml), muss das DiveKit eine entsprechende Fehlermeldung erzeugen.

## Begründung

Wenn die DiveKit-Gui einen Fehler aufweist, welcher nicht auf Tests/Aufgaben zurückzuführen ist, sollte eine entsprechende Fehlermeldung angezeigt werden.
