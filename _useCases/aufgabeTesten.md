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
    - wmaDev
trigger: Student hat seine Aufgabe erledigt, und möchte sie testen lassen
precondition: Student hat sein Ergebnisse im Divekit eingetragen
postcondition: Der Student erhält ein Ergbnis oder eine Fehlermeldung
functionalRequirement: FehlermeldungAussagekraeftig
history:
    v1:
        date: 2021-07-19
        comment: initially created
    v2: 
        date: 2021-07-28
        comment: resolved issues from review
todo: 
    - (sbe) Schritt 2 - was genau heißt "speichert das Ergebnis"? DiveKit erfordert Commit+Push. Ist das gemeint? Dann sollten Sie es auch schreiben ;-)
    - (sbe) Schritt 3 fehlt
    - (sbe) wie genau soll "5) Das System teilt dem Nutzer mit, ob die Aufgabe korrekt erledigt wurde" erfolgen? Bekommt der Nutzer eine Mail o.ä.? Oder schaut er/sie auf der Testseite nach?
    - (sbe) Ausnahmeszenario modelliert einen Bug (Systemfehler). Das macht man nicht, dann lieber weglassen. Man geht bei der Modellierung von korrekt implementierter Software aus.
---


## Hauptszenario

* 1) Student schließt eine Aufgabe ab
* 2) Student speichert das Ergebnis
* 4) Das System führt eine automatische Überprüfung der Aufgabe durch
* 5) Das System teilt dem Nutzer mit, ob die Aufgabe korrekt erledigt wurde

## Alternativszenario

* 4a) Das Ergebnis der Aufgabe muss manuell überprüft werden
* 4b) Ein wmaProg wird informiert, dass die Aufgabe überprüft werden muss
* 4c) wmaProg prüft die Aufgabe und trägt ein, ob das Ergebnis korrekt ist, oder ob nachgebessert werden muss

## Ausnahmeszenario 

* 4a) Aufgrund eines Fehlers kann keine Überprüfung durchgeführt werden 
* 4b) Dem Studenten wird mitgeteilt, das derzeit aufgrund eines Systemfehlers keine Überprüfung möglich ist und es zu einem späteren Zeitpunkt erneut probiert werden soll
* 4c) Dem wmaDev wird mitgeteilt, dass sein Systemfehler vorliegt

**Andere Nachbedingung**: Prüfung nicht durchführbar, Student und wmaDev werden informiert, dass ein Systemfehler vorliegt




