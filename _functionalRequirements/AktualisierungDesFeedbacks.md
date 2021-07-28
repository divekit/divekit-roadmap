---
type: functionalRequirement
acronym: AktualisierungDesFeedbacks
responsible:
    - jlü
    - duz
title: Feedback automatisch aktualisieren
goals: 
    - entlastungKorrektur
    - fehlerVerständlichkeit
    - autoUpdate
implementationStatus: implemented
prefilterPriorizationPoints: 0
source:
    - [beobachtungstagebuch, AV1]
history:
    v1:
        date: 2021-07-08
        comment: initially created
    v2:
        date: 2021-07-08
        comment: Entfernung der Begründung
    v3:
        date: 2021-07-12
        comment: Added all responsible authors, added reason
    v4:
        date: 2021-07-15
        comment: Fixed goales
    v5: 
        date: 2021-07-16
        comment: Modified responsibles as discussed
todo:
    - (sbe) Was wäre denn die Alternative ...? Ist dieses Requirement wirklich sinnvoll, oder formuliert es nur eine Selbstverständlichkeit, die gar nicht anders sinnvoll geht?
    - (sbe) warum nur "soll"? 
---

Das DiveKit soll die Ergebnisse auf der Testübersichtsseite nach der Prüfung eines Testes selbstständig aktualisieren.

## Begründung
Damit die Interaktion intuitiver und einfacher gestaltet werden kann, ist es sinnvoll, diese Anforderung umzusetzen.
