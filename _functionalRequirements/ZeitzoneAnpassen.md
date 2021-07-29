---
type: functionalRequirement
acronym: LetzteAktualisierung
responsible:
    - jlü
    - kru
title: Anpassen an die Zeitzone des Nutzers
goals: 
    - entlastungKorrektur
    - relevanteInformationen
    - robustheit
implementationStatus: implemented
prefilterPriorizationPoints: 1
source:
    - [beobachtungstagebuch, AN2]
    - [beobachtungstagebuch, PS3]
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
    v6: 
        date: 2021-07-27
        comment: Changed to ZeitzoneAnpassen & merged Zeitzone with LetzteAktualisierung

todo:
---

Das DiveKit muss die angezeigten Zeitstempel deutlich sichtbar und entsprechend der Zeitzone des Nutzers anzeigen.

## Erläuterung

Die fehlerhafte oder fehldende Zeitanzeige, hat in der Vergangenheit oft für Verwirrungen geführt. Dies gilt besonders die Einreichung und Überprüfung des Codes.