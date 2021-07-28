---
type: useCase
acronym: LösungenBeiDrittsystemEinreichen
responsible: 
    - jlü
title: Lösungen einreichen
description: Ein*e Student*in
primaryActor: studierende
secondaryActors:
    - profInf
trigger: Student*in will Lösung einreichen
precondition: Student*in hat eine Aufgabe, die in einem Drittsystem zu lösen ist 
postcondition: eingereichten Lösungen wurden übermittelt und überprüft
functionalRequirement: API
history:
    v1:
        date: 2021-07-21
        comment: initially created
    v2:
        date: 2021-07-27
        comment: update primary actor
todo:
    - (sbe) Description ist unvollständig
    - (sbe) "5) Lösung wird an Drittsystem zur Validierung geschickt" - was ist hier mit einem Drittsystem gemeint? Ist mir unklar. Vielleicht mit Beispiel? Ist sowas wie GoogleCloud gemeint? 
    - (sbe) "5) Lösung wird an Drittsystem zur Validierung geschickt" - bitte machen Sie daraus eine Aktiv-Formulierung. Wer schickt? Das System? Der Prof? Ich wäre für ersteres (und vermute, dass Rene Wöärzberger sowas auch im Kopf hat).
    - (sbe) "Die Student*in hat keine Lust die Aufgabe zu bearbeitn " - finde ich nicht so passend für Ausnahme. Wie wäre es denn z.B. mit Zugangsproblemen zum Drittsystem (Credentials fehlend?)
---


## Hauptszenario

* 1) Die Dozent*in stellt die Aufgabe, dass ein Docker-Container-Image erstellt werden soll
* 2) Student*in sieht die Aufgabe
* 3) Student*in löst die Aufgabe
* 4) Student*in reicht die Lösung vollständig ein
* 5) Lösung wird an Drittsystem zur Validierung geschickt 

## Alternativszenario

* 5a) Die Lösung wird einer manuellen Korrektur unterzogen
* 5b) Dozent*in prüft die Lösung im Drittsystem

## Ausnahmeszenario 

* 3a) Die Student*in hat keine Lust die Aufgabe zu bearbeitn 
* 4a) Es werden keine Lösungen eingereicht
* 5a) Das Drittsystem bekommt keine Lösungen zur Validierung


**Andere Nachbedingung**: Lösung wird nicht eingereicht und somit nicht an das Drittsystem übermittelt




