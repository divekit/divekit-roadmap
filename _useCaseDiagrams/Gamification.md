---
type: useCaseDiagram
acronym: Gamification
responsible: 
    - psc
title: Use Case Diagramm für Gamification
functionalRequirement: MotivationDurchGamification
useCases:
    - Errungenschaften mit Bedingungen konfigurieren
    - Aufgabe auswählen
    - Bearbeitungsstand committen und pushen
    - Bedingungen für Errungenschaft prüfen
    - Bedingungen manuell prüfen
    - Aufgabe finalisieren
    - Errungenschaft erhalten
useCasesDetailedWithScenario:
    - Gamification
diagram: ./diagrams/useCaseGamification.jpg
history:
    v1:
        date: 2021-07-23
        comment: initially created
    v2:
        date: 2021-07-28
        comment: Verbesserungen aus Review umgesetzt
    v3:
        date: 2021-07-31
        comment: Verbesserungen aus Todos umgesetzt + Anmerkungen zu offenen Punkten addiert
todo: 
    - (sbe) Ist die Trennung in "Auswahl, Bearbeitung und als Erweiterung das Finalisieren einer Aufgabe" nicht zu kleinteilig? Siehe User Happiness Rule.
    - (psc) Schmaler Grad zwischen beiden Extremen. Das Finalisieren kann auch Tage dauern. Daher würde ich das Diagramm für diesen Kontext so lassen und im Falle einer Konkretisierung von Gamification erneut evaulieren. Als erste Idee sollte das passen.
    - (sbe) zumindest - was ist Unterschied zwischen "commit + push" und "finalisieren"? Wie bekommt das System und der WMA es mit, dass ab jetzt nichts mehr kommt?  
    - (psc) Der WMA sollte davon möglichst nichts mitbekommen und keine weitere Arbeit haben (siehe Ziel _Entlastung_). Die Errungenschaften sollten automatisiert geprüft und vergeben werden. Allerdings stellt sich hier die Frage, wie Gamification didaktisch sinnvoll integriert werden kann und ob dann eine rein automatisierte Überprüfung in allen Fällen möglich ist.
    - (sbe) wenn man die Trennung belässt - wann genau gibts doch Errungenschaft? Potenziell bei jedem der Schritte?
    - (psc) Theoretisch lassen sich zu allen erdenklichen Schritten Errungenschaften entwickeln. Diese können einzelne oder summierte Tätigkeiten sein. z. B. kann der 1000 Commit eine Errungenschaft auslösen
---

## Beschreibung

Dieses Usecase-Diagramm stellt eine mögliche Option der funktionalen Anforderung _Lernmotivation durch Gamification_ dar.

Der primäre Nutzer ist hierbei der Studierende, der durch die Interaktion mit dem System (Divekit) entsprechende Errungenschaften erlangen kann.

Exemplarisch wird im Use Case Diagramm allgemein die Arbeit (Auswahl, Bearbeitung und als Erweiterung das Finalisieren einer Aufgabe) mit dem DiveKit abgebildet. Aufgabenspezifische Errungenschaften werden hier nicht abgebildet. Dies bedeutet zudem, dass eine Überprüfung möglichst automatisiert erfolgen sollte.

Um Errungenschaften zu erhalten, sind diese im Vorfeld vom Entwickler mit Bedingungen zu konfiguieren.

Wählt der Studierende zum ersten Mal eine Aufgabe aus, so erfüllt er eine Bedingung und erhält somit eine Errungenschaft.

Der Studierende erabeitet dann die Aufgabe und stellt, sobald ein erster Bearbeitungsstand vorliegt, den ersten Commit und pushed diesen in sein Repo. Das System überprüft, ob die Bedingungen für eine Errungenschaft erfüllt sind. Zum Beispiel, ob der bereitgestellt Commit der aller erste ist. Der Studierende erhält eine weitere Errungenschaft.

Der Studierende finalisiert (dies wäre erfüllt, wenn die Aufgabe Kontrollmechanismen hat wie zum Beispiel Tests bei Codingaufgaben) die Aufgabe und pushed diese zur Überprüfung in das System. Ist die Überprüfung erfolgreich und werden Bedingungen einer Errungeschaft erfüllt, wird eine Errungenschaft vergeben.

Weist die Aufgabe hingegen Fehler auf, kann dies auch zum Erfüllen von Errungenschaften ausreichen und Errungenschaften vergeben.




