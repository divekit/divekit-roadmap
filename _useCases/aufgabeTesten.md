---
type: useCase
acronym: UCaufgabeTesten
responsible: 
    - cpo
title: Aufgabe testen
description: Ein Student lässt eine Aufgabe auf Richtigkeit prüfen
primaryActor: studierende
secondaryActors:
    - wmaProg 
trigger: Student hat seine Aufgabe erledigt, und möchte sie testen lassen
precondition: Student sein Ergebnisse im Divekit eingetragen
postcondition: Der Student erhält ein Ergbnis oder eine Fehlermeldung
functionalRequirement: FehlermeldungAussagekraeftig
history:
    v1:
        date: 2021-19-07
        comment: initially created

todo: 
---


## Hauptszenario

* 1) Student schließt ein Aufgabe ab
* 2) Student speichert das Ergebnis
* 4) Das Systemm führt eine automatische Überprüfung der Aufgabe durch
* 5) Das System teilt dem Nutzer mit, ob die Aufgabe korrekt erledigt wurde

## Alternativszenario

* 4a) Das Ergebnis der Aufgabe muss manuell überprüft werden
* 4b) Ein wmaProg wird informiert, dass die Aufgabe überprüft werden muss
* 4c) wmaProg prüft die Aufgabe und trägt ein, ob das Ergebnis korrekt ist, oder ob nachgebessert werden muss

## Ausnahmeszenario 

* 4a) Aufgrund eines Fehlers kann keine Überprüfung durchgeführt werden 
* 4b) Dem Studenten wird mitgeteilt, das derzeit aufgrund eines Systemfehlers keine Überprüfung möglich ist und es zu einem späteren Zeitpunkt erneut probiert werden soll

**Andere Nachbedingung**: Prüfung nicht durchführbar, Student wird informiert, dass ein Systemfehler vorliegt




