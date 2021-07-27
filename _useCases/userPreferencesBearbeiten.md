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
postcondition: Der Benutzer hat seine User Preferences auf die von ihm gewünschten Einstellungen gesetzt (Einstellungen sind persistiert)
functionalRequirement: BereitstellungUserPreferences
history:
    v1:
        date: 2021-07-22
        comment: initially created

todo:

---


## Hauptszenario

* 1) Benutzer meldet sich an
* 2) Benutzer sieht seine aktuellen Benutzereinstellungen
* 3) Benutzer ändert seine Benutzereinstellungen 
* 4) Die geänderten Einstellungen werden remote persistiert

## Alternativszenario

-

## Ausnahmeszenario 

* 4a) Die Verbindung zur Datenbank ist unterbrochen
* 4b) Das frontend meldet dem Benutzer, dass die Änderungen nicht gespeichert wurden konnten

**Andere Nachbedingung**: Die Änderungen sind nicht persistiert.
