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
trigger: Die Student:in stößt auf einen Fehler auf der Testseite.
precondition: Die Student:in hat eine Aufgabe bearbeitet und bekommt nach dem pushen der Aufgabe einen Fehler auf der Testseite.
postcondition: Die Student:in besitzt weitere Informationen zum Fehler.
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
    v4:
        date: 2021-07-29
        comment: added content from todos

todo: 
---


## Hauptszenario
* 1) Die Student:in kann den Fehler nicht adhoc lösen und wählt auf der Testseite eine Schlatfläche neben der Fehlermeldung aus, um weiter Informationen anzufordern.
* 2) Das System durchsucht seine Hinweis-Datenbank nach Informationen zum Fehler.
* 3) Das System findet Informationen zum Fehler.
* 4) Das System zeigt dem Student:in die Informationen in einem seperaten Dialog an.

## Alternativszenario
<!-- UC ist zu klein für ein Altervativszenario -->

## Ausnahmeszenario 
* 3a1) Das System findet keine Informationen zum Fehler.
* 3a2) Die Student:in bekommt eine Nachricht anzeiget, dass keine Informationen vorhanden sind.

**Andere Nachbedingung**: Die Student:in besitzt keine weitere Informationen zum Fehler.

## Anmerkung:
Anmerkung des Buisness Analysten: Meiner Meiner nach würde ich die nachfolgenden Spezifizierungen zur Implentierung nicht oder nur "abgespeckt" in den Use Case integieren. Da es die Designentscheidung in der Entwicklung einschränken könnte.

* Die Nachricht bei fehlenden weiterführenden Informationen (3a2) würde etwas wie "Keine Informationen vorhanden. Bitte schauen Sie dem Fehler in einer Suchmaschiene Ihrer Wahl nach." beinhalten.
* Die erwähnte Schaltfläche kann ein Button oder Ähnliches sein.

### Skizzierung der Fehlermatchings

* Analyse ob es sich hierbei, um eine eigens geschriebene oder eine generische (bspw. MethodNotFound, etc) handelt
    * Bei eigens geschriebene Fehlermeldung sollte die Nutzer:in darauf hingewiesen werden. Da daduch die Suche in einer Suchmaschinen erschwert werden könnte.
    * Bei generellen Exception, könnte so etwas wie "Suche bei _Suchmaschiene Ihrer Wahl_ nach _aufgekommener Fehler_" einsetzt werden.  
* Anschließend die Klassennamen o.Ä. in der Exception analysieren und in der Datenbank (o.Ä.) nach Pattern suchen.