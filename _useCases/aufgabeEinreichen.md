---
type: useCase
acronym: UCaufgabeEinreichen
responsible: 
    - cpo
title: Aufgabe einreichen
description: Ein Student reicht seine Aufgabe ein
primaryActor: studierende
secondaryActors:
    - wmaProg 
trigger: Student hat seine Aufgabe erledigt, und pusht das Ergebnis
precondition: Student hat seine Aufgabe erledigt, und möchte sie einreichen
postcondition: Der Student erhält das Ergbnis der Tests seiner Aufgaben
functionalRequirement: FehlermeldungAussagekraeftig
history:
    v1:
        date: 2021-07-19
        comment: initially created
    v2: 
        date: 2021-07-28
        comment: resolved issues from review
    v3:
        date: 2021-07-29
        comment: fundamental rework, changed to UCaufgabeEinreichen
todo: 
---


## Hauptszenario

* 1) Student schließt seine Aufgabe ab
* 2) Student committet und pusht das Ergebnis
* 3) Die pom.xml im Projekt des Studenten wird mit der entsprechenden Datei im hidden Repo verglichen
* 4) Der Vergleich ergibt, dass keine Änderungen vorgenommen wurden
* 5) Die Aufgabe wird an die Pipeline weitergereicht und compiliert
* 6) Auf der Testseite werden die Ergebnisse der automatischen Tests angezeigt

## Alternativszenario


## Ausnahmeszenario 

* 4a) Der Vergleich ergibt, dass der Nutzer unerlaubte Änderungen vorgenommen hat
* 4b) Auf der Testseite wird eine Fehlermeldung ausgegeben, die den Studenten darauf hinweist, dass die Date pom.xml unerlaubt
verändert wurde
* 4c) Es werden die unerlaubten Änderungen angezeigt, die rückgängig gemacht werden müssen.

**Andere Nachbedingung**: Student erhält eine Fehlermeldung. Das Compilieren und Testen des Ergebnisses wurde abgebrochen




