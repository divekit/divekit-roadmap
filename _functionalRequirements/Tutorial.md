---
type: functionalRequirement
acronym: Tutorial
responsible: 
    - jsp
title: Tutorial für Umgebungseinstellungen
goals: 
    - fehlerFalscheKonfig
implementationStatus: open
prefilterPriorizationPoints: 0
source:
    - [Workshop, Workshop 6-3-5-No.2, Schwerpunkt Technik No.1]
history:
    v1:
        date: 2021-07-08
        comment: initially created
    v2:
        date: 2021-07-15
        comment: Fixed goales
    v3:
        date: 2021-07-16
        comment: update todos
    v4:
        date: 2021-08-01
        comment: fix todos
todo:  
    
---

Das DiveKit muss eine Bedienhilfe anbieten, in welchem der Nutzer die Standardeinstellungen nachprüfen kann.

## Begründung

Bei fehlerhaften Umgebungseinstellungen (pom.xml) soll dem Nutzer die Möglichkeit gegeben sein nachzuschauen, wie diese korrekt auszusehen haben.
Hierbei soll beachtet werden, dass der Nutzer eine Vorlage zum korregieren hat und nicht beispielsweise ein Rollback zu einem bestimmten Commit zu machen oder ein compare mit einer älteren Version der pom.xml.

Aus dieser FA könnte man aber auch eine generelle Bedienhilfe Ableiten, welche je nach anwendungsfall einen enormen Mehrwert bieten kann
