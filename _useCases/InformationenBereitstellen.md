---
type: useCase
acronym: InformationenBereitstellen
responsible: 
    - xyz
title: Informationen Bereitstellen
description: Ein Gutachter bewertet den gemeldeten Schaden
primaryActor: gutachter (stakeholderRole)
secondaryActors:
    - sachbearbeiterin (stakeholderRole)
    - kunde (stakeholderRole)    
trigger: Kunde hat einen Schaden gemeldet
precondition: Gutachter wurde dem Fall zugewiesen
postcondition: Der Kunde erhält die Nachricht über die Höhe der Schadensbewertung
funcionalRequirement: 
    - 
history:
    v1:
        date: 2021-06-02
        comment: initially created
todo: 
---


## Hauptszenario

* 1) Gutachter identifiziert sich als zuständige Person
* 2) Gutachter begutachtet den Schaden
* 3) Der Gutachter beziffert den Schaden monetär 
* 4) Das System leitet den monetären Wert wird weiter an die Sachbearbeiterin
* 5) Die Sachbearbeiterin schließt den Fall ab und gibt die Auszahlung an den Kunden frei
* 6) Das System schickt eine automatisierte Nachricht an den Kunden 

## Alternativszenario

* 5a) Der monetäre Schaden übertrifft den Versicherungsschutz des Kunden
* 5b) Der Schaden wird auf den maximal zulässigen Wert gesetzt

## Ausnahmeszenario 

* 3a) Der Gutachten entdeckt Indizien, dass der Schaden von der Versicherung nicht akzeptiert wird (z.B. wegen Verdacht auf Betrug)
* 3b) Der Gutachter hinterlegt im System eine ausführliche Begründung
* 5a) Die Sachbearbeiterin leitet den Vorgang weiter an die interne Abteilung für Betrug
* 6a) Das System schickt eine Nachricht an den Kunden, dass die Bearbeitung noch Zeit benötigt. 

**Andere Nachbedingung**: Schaden wird nicht akzeptiert, es wird kein monetärer Wert zugewisesen (0€).




