---
type: userStory
acronym: usFeedbackLimitWarning
responsible:
    - tza
title: Warnung über Feedback-Obergrenze
functionalRequirement: FeedbackLimit
asA: studierende
iWantTo: Ich möchte gewarnt werden, dass ich bald die Obergrenze für Feedback-Anfragen erreicht habe
forThisReason: damit ich schnellstmöglich darauf reagieren kann
history:
    v1:
        date: 2021-07-23
        comment: initially created
    v2:
        date: 2021-07-29
        comment: Akzeptanzkriterien hinzugefügt

todo: 
    - (sbe) Glauben Sie, dass Sie diese US in einem Sprint umsetzen können? Ist zu groß (jedenfalls wenn das Limit auch überwacht wird) und in dieser Form als US unbrauchbar (ist eher ein Epic). Versuchen Sie einen sinnvollen ersten Schritt zu definieren!
    - (tza) (Antwort) Ich habe jetzt noch paar Akzeptanzkriterien hinzugefügt. Es kann wohl sein, dass es noch nicht vollständig ist. Was die Größe angeht, bin ich eigentlich davon überzeugt, dass es in einem Sprint umgesetzt werden kann. Ich bin beim Schreiben eigentlich davon ausgegangen, dass für diese US alle notwendige Daten im System vorhanden sind (also keine Umsetzung von Zero) und nur noch Fachlogik gebaut werden muss + noch Wartungsausgabe, was auch trivial sein soll. 
---

## Hinweise
Als Nutzer des Systems gilt jeder, der mit dem System Aufgaben bearbeiten kann und Feedback anfordert (Studierende).

## Akzeptanzkriterien:
* Bevor der Benutzer eine weitere Feedback-Anfrage sendet, prüft das System, ob der Benutzer bald die Feedback-Obergrenze erreicht.
* Für die Berechnung wird der sogenannte „Anfragen-Puffer“ benötigt\
  (zu klären: feste Anzahl oder konfigurierbar?)
* Die Warnung wird ausgelöst, wenn:
    * Anzahl bereits ausgelöster Anfragen >= Feedback-Obergrenze - Anfragen-Puffer
* Die angezeigte Warnung hat das Format: "Sie können nur noch \<Anzahl Restanfragen\> Feedback-Anfragen stellen."
    * Anzahl Restanfragen = Feedback-Obergrenze - Anzahl bereits ausgelöster Anfragen

## Notiz
Es muss geklärt werden, wann die Warnung angezeigt werden soll.
Vor der letzten Feedback-Anfrage ist es wahrscheinlich zu spät,
5 davor kann von manchen Studierenden als zu früh empfunden werden.
Eventuell ist eine Einstellmöglichkeit erforderlich.

(Die User Story kann noch nicht eingeplant werden, da noch einige Punkte zu klären sind.)
