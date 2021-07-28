---
type: useCaseDiagram
acronym: feedbackLimit
responsible:
    - tza
title: Use Case Diagram Obergrenze für Feedback
functionalRequirement: FeedbackLimit
useCases:
    - Obergrenze setzen
    - Feedback anfordern
    - Feedback geben
    - Aufgabe bearbeiten
    - Feedback einarbeiten
    - Benachrichtigung durchlesen
useCasesDetailedWithScenario:
diagram: ./diagrams/useCaseFeedbackLimit.jpg
history:
    v1:
        date: 2021-07-23
        comment: initially created
    v2:
        date: 2021-07-23
        comment: Review-Anmerkungen eingearbeitet
todo: 
    - (sbe) nur "Benachrichtigung durchlesen" ist mir unklar, sonst gut
---

## Beschreibung

Die funktionale Anforderung „Obergrenze für Feedback setzen“ hängt von vielen anderen Prozessen ab.

Der Hauptanwendungsfall dieser Anforderung ist "Obergrenze setzen". Dies wird von einem Lehrenden ausgelöst.

Die Obergrenze wird für Anzahl von Feedback-Anfragen gesetzt, deswegen muss zuerst möglich sein Feedback anzufordern.
Der Student kann das Feedback anfordern. Der Lehrende ist dagegen verpflichtet auf die Anfrage antworten bzw. das Feedback geben
(aber aus Systemsicht wird es nicht erzwungen).
Außerdem arbeitet der Student das Feedback ein, was ein Spezialfall von "Aufgabe bearbeiten" ist.
Sowohl der Student als auch der Lehrende werden über neue Feedback-Anfrage/-Antwort benachrichtigt.
Das System übernimmt diese Benachrichtigungsfunktion.



