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
    - (sbe) Postcondition sollte eher sein, dass die gänderten UserPrefs auch wirken.
    - (sbe) zwischen 1 und 2 im Hauptszenario fehlt was. Man sieht nicht sein Prefs direkt nach der Anmeldung. 
    - (sbe) am besten ein Beispiel für UserPrefs nehmen. So ist das sehr pauschal. Perspektive sollte die eines Entwicklungsteams sein - die sollen durch das Lesen von UCs in der Lage sein, die richtige Software zu implementieren!
    - (sbe) Ausnahmeszenario ist nicht valide - Bugs der Software werden nicht modelliert. 
    - (sbe) Insgesamt etwas zu wenig detailliert.
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
