---
type: useCase
acronym: informationenAnfordern
responsible: 
    - kru
title: Informationen anfordern
description: Das DiveKit muss in der Lage sein Studierenden weiterführende Informationen (zum Beispiel Videos/Webseiten/Vorlesungsmaterialien) zu konkreten Fehlern zur Verfügung zu stellen.
primaryActor: student
secondaryActors:
    - wmaInf
trigger: Student:in stößt auf Fehler.
precondition: Student:in kann den Fehler nicht adhoc lösen.
postcondition: Student:in besitzt weitere Informationen zum Fehler.
funcionalRequirement: 
    - 
history:
    v1:
        date: 2021-06-02
        comment: initially created
    v2:
        date: 2021-07-18
        comment: added scenarios

todo: 
---


## Hauptszenario
1.) Student:in fordert Informationen zum Fehler an.
2.) System durchsucht XYZ nach Informationen zum Fehler.
3.) System findet Informationen zum Fehler.
4.) System zeigt dem Studierenden die Informationen zur Verfügung.

## Alternativszenario
3a1.) System findet keine Informationen zum Fehler.
3a2.) System informiert WMA und Student:in über fehlende Informationen.
3a3.) WMA kontaktiert Student:in und biedet Hilfe an.

## Ausnahmeszenario 
3a1.) WMA hat keine Ressourcen nicht freu und lehnt Kontakt ab. 
3a2.) System teilt dem Studierenden mit, dass keine Informationen gefunden werden konnten.

**Andere Nachbedingung**: Student:in besitzt keine weitere Informationen zum Fehler.
