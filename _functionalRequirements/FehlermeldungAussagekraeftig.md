---
type: functionalRequirement
acronym: FehlermeldungAussagekraeftig
responsible: 
    - jsp
title: Aussagekräftige Fehlermeldungen
goals: 
    - fehlerFalscheKonfig
implementationStatus: open
prefilterPriorizationPoints: 4
source:
    - Workshop 6-3-5-No.2
history:
    v1:
        date: 2021-07-08
        comment: initially created
    v2:
        date: 2021-07-15
        comment: Fixed goales
todo: 
---

Bei fehlerhaften Umgebungseinstellungen (pom.xml), muss das DiveKit eine entsprechende Fehlermeldung erzeugen.

## Begründung

Wenn die DiveKit-Gui einen Fehler aufweist, welcher nicht auf Tests/Aufgaben zurückzuführen ist, sollte eine entsprechende Fehlermeldung angezeigt werden.
