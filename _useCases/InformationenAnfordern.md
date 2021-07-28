---
type: useCase
acronym: informationenAnfordern
responsible: 
    - kru
title: Informationen anfordern
description: Das DiveKit muss in der Lage sein Studierenden weiterführende Informationen (zum Beispiel Videos/Webseiten/Vorlesungsmaterialien) zu konkreten Fehlern zur Verfügung zu stellen.
primaryActor: studierende
secondaryActors:
    - wmaAutonomousLecturerInf
trigger: Student:in stößt auf Fehler.
precondition: Student:in kann den Fehler nicht adhoc lösen.
postcondition: Student:in besitzt weitere Informationen zum Fehler.
functionalRequirement: WeiterfuehrendeInformationen
history:
    v1:
        date: 2021-06-02
        comment: initially created
    v2:
        date: 2021-07-18
        comment: added scenarios
    v3:
        date: 2021-07-26
        comment: added missing FR
todo: 
    - (sbe) Das Szenario fängt irgendwie mittendrin an. Was (welche Nutzeraktion) kommt vorher?
    - (sbe) was ist XYZ? bitte lieber etwas Konkretes nehmen. Ist mir tatsächlich unklar, wenn ich nur das Szenario lese. 
    - (sbe) Versetzen Sie sich mal in die Situation eines Entwicklungsteams - wären Sie in der Lage, auf der Basis dieser Beschreibung Software zu bauen? Natürlich sollte ein UC keine Implementierung (z.B. backend-seitig) spezifizieren. Aber mir ist auch der Bedienablauf ziemlich unklar, also z.B. _wo_ die Studentin einen Link zur Lösung sieht.
    - (sbe) Vielleicht kann man zumindest _skizzieren_, wie das System zu dem Vorschlag kommt - z.B. sowas wie Pattern Matching auf eine Exception  
    - (sbe) Das Alternativszenario sprengt den organisatorischen Rahmen ziemlich gründlich - wenn bei _jedem_ Fehler der WMA Hilfe anbietet. M.E. reicht es, wenn einfach in der Hinweis-Datenbank kein Link hinterlegt ist und da dann steht "keine Ahnung, guck halt selbst in stackoverflow und Buch X, Y und Z" (sinngemäss, grins)
    - (sbe) Das Ausnahmeszenario bezieht sich auf das Alternativszenario, oder? Unüblich. Eher auf das Hauptszenario. Vielleicht gibts hier kein Ausnahmeszenario. 
---


## Hauptszenario
* 1) Student:in fordert Informationen zum Fehler an.
* 2) System durchsucht XYZ nach Informationen zum Fehler.
* 3) System findet Informationen zum Fehler.
* 4) System zeigt dem Studierenden die Informationen zur Verfügung.

## Alternativszenario
* 3a1) System findet keine Informationen zum Fehler.
* 3a2) System informiert WMA und Student:in über fehlende Informationen.
* 3a3) WMA kontaktiert Student:in und biedet Hilfe an.

## Ausnahmeszenario 
* 3a1) WMA hat keine Ressourcen nicht freu und lehnt Kontakt ab. 
* 3a2) System teilt dem Studierenden mit, dass keine Informationen gefunden werden konnten.

**Andere Nachbedingung**: Student:in besitzt keine weitere Informationen zum Fehler.
