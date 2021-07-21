---
type: useCase
acronym: LösungenBeiDrittsystemEinreichen
responsible: 
    - jlü
title: Lösungen einreichen
description: Ein * e Student * in 
primaryActor: 
    - student
secondaryActors:
    - profInf
trigger: Student * in will Lösung einreichen
precondition: Student * in hat eine Aufgabe, die in einem Drittsystem zu lösen ist 
postcondition: eingereichten Lösungen wurden übermittelt und überprüft
funcionalRequirements: 
    - API
history:
    v1:
        date: 2021-07-21
        comment: initially created

todo: 
---


## Hauptszenario

* 1) Der * Die Dozent * in stellt die Aufgabe, dass ein Docker Container Image erstellt werden soll
* 2) Student * in sieht die Aufgabe
* 3) Student * in löst die Aufgabe
* 4) Student * in reicht die Lösung vollständig ein
* 5) Lösung wird an Drittsystem zur Validierung geschickt 

## Alternativszenario

* 5a) Die Lösung wird einer manuellen Korrektur unterzogen
* 5b) Dozent * in prüft die Lösung im Drittsystem

## Ausnahmeszenario 

* 3a) Der * Die Student * in hat keine Lust die Aufgabe zu bearbeitn 
* 4a) Es werden keine Lösungen eingereicht
* 5a) Das Drittsystem bekommt keine Lösungen zur Validierung


**Andere Nachbedingung**: Lösung wird nicht eingereicht und somit nicht an das Drittsystem übermittelt




