---
type: useCase
acronym: userPreferencesBearbeiten
responsible: 
    - hbu
title: User Preferences Bearbeiten
description: Ein Benutzer bearbeitet seine User Preferences
primaryActor: studierende
trigger: Benutzer möchte User Preferences bearbeiten
precondition: Der Benutzer ist angemeldet
postcondition: Der Benutzer hat seine User Preferences auf die von ihm gewünschten Einstellungen gesetzt (Einstellungen sind persistiert) und wirken dementsprechend
functionalRequirement: BereitstellungUserPreferences
history:
    v1:
        date: 2021-07-22
        comment: initially created
todo:
    - (sbe) Insgesamt etwas zu wenig detailliert.
---


## Hauptszenario

* 1) Benutzer meldet sich an
* 2) Benutzer navigiert zu Benutzereinstellungen
* 3) Benutzer sieht seine aktuellen Benutzereinstellungen
* 4) Benutzer ändert seine Benutzereinstellungen (bswp. Farbendarstellung für Farbenblinde)
* 5) Die geänderten Einstellungen werden remote persistiert

## Alternativszenario

-

## Ausnahmeszenario 

-

**Andere Nachbedingung**: Die Änderungen sind nicht persistiert.
