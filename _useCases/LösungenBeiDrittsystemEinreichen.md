---
type: useCase
acronym: LösungenBeiDrittsystemEinreichen
responsible: 
    - jlü
title: Lösungen einreichen
description: Ein*e Student*in muss eine Aufgabe in der Google Cloud lösen.
primaryActor: studierende
secondaryActors:
    - profInf
trigger: Student*in will Lösung einreichen
precondition: Student*in soll einen Docker Container erstellen, der auf der Google Cloud läuft
postcondition: eingereichtes Container-Image wurden übermittelt und überprüft
functionalRequirement: API
history:
    v1:
        date: 2021-07-21
        comment: initially created
    v2:
        date: 2021-07-27
        comment: update primary actor
    v3:
        date: 2021-07-29
        comment: update scenarios
todo:
---


## Hauptszenario

* 1) Die Dozent*in stellt die Aufgabe, dass ein Docker-Container-Image erstellt werden soll
* 2) Student*in sieht die Aufgabe
* 3) Student*in löst die Aufgabe
* 4) Student*in reicht die Lösung vollständig ein
* 5) Das DiveKit deployt die Lösung zur Validierung und zum Testen auf die Google Cloud

## Alternativszenario

* 5a) Die Lösung wird einer manuellen Korrektur unterzogen
* 5b) Dozent*in prüft die Lösung in der Google Cloud

## Ausnahmeszenario 

* 3a) Der*Die Student*in hat keine gültigen Zugangsdaten für die Google Cloud
* 4a) Der*Die Student*in kann keine Lösungen einreichen
* 5a) Die Google Cloud bekommt keine Lösungen der Aufgabe zur Validierung deployt


**Andere Nachbedingung**: Lösung kann nicht eingereicht werden und somit nicht an die Google Cloud übermittelt




