---
type: useCaseDiagram
acronym: useCaseDiagramUserPreferences
responsible: 
    - hbu
title: Use Case Diagram User Preferences
functionalRequirement: BereitstellungUserPreferences
useCases:
    - Anmelden
useCasesDetailedWithScenario:
    - userPreferencesBearbeiten
diagram: ./diagrams/useCaseUserPreferences.svg
history:
    v1:
        date: 2021-07-22
        comment: initially created
todo: 
    - (sbe) ein UC-Diagramm mit einem Use Case ??? (den "Anmelden" zähle ich mal nicht)
    - (sbe) "er könnte sich aber (je nach User Preferences) auf die Darstellung anderer Prozess auswirken (bswp. die Darstellungen für farbenblinde Nutzer)." - diese UC sollten in diesem Diagramm auch dargestellt werden (zumindest eine Auswahl, damit es nicht zu viel Arbeit wird). Das ist doch der Sinn eines UC-Diagramms - dass man die UCs miteinander in einen Kontext bringt.
    - (sbe) Beziehung zu Anmelden ist eher anders herum mit include. Sonst wäre der User happy, wenn er sich einfach nur anmeldet. Und wenn er Lust hat, dann macht er noch mehr im System ;-)
---

## Beschreibung

Der Ablauf um die User Preferences zu bearbeiten (siehe Anforderung "BereitstellungUserPreferences") wird dargestellt.

Der Use Case Anmelden ist Voraussetzung für das Bearbeiten der User Preferences. Ohne Benutzerkonto können auch keine
Benutzereinstellungen bearbeitet werden.

Der Use Case User Preferences Bearbeiten ist der Kern des FR. Er kann ausgeführt werden, nachdem der Benutzer sich eingeloggt
hat (daher extends). Er muss nicht notwendigerweise ausgeführt werden um andere Funktionen zu nutzen, er könnte sich aber
(je nach User Preferences) auf die Darstellung anderer Prozess auswirken (bswp. die Darstellungen für farbenblinde Nutzer).



