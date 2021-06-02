---
type: scenario
acronym: sampleScenario
title: Einfache Individualisierung von Aufgaben
persona: mkramüller
scenarioTypes: 
    - main
    - alternative
    - exception
    - positive
    - negative
    - concrete
    - abstract
    - interaction
    - system
    - explanatory
    - descriptive
    - explorational 
responsible: 
    - sbe
    - mba
source: 
    - [interview, fkrampe, Minute 21:02]
    - [workshop, 635method, p. 2 oben]
history:
    v1:
        date: 2021-05-04
        comment: initially created
todo: 
    - Auswählen von 1 oder mehr scenarioTypes
    - löschen wenn echte Szenarien da sind
---

## Beschreibung

Hier das Szenario-Template

###Beispiel für positives Hauptszenario:

Karl möchte mit seinem PKW zum Potsdamer Platz 1 nach Berlin tahren. Karl benutzt das Navigationssystem des Fahrzeugs, um die kürzeste Wegstrecke zu ermitteln. Er wählt „Ziel eingeben“. Das Navigationssystem zeigt im Display „Bitte Ort nennen oder manuell eingeben“ an. Karl wählt die Spracheingabe und spricht „Berlin“. Das System wählt Berlin Potsdamer Platz 1 als Zielort aus und die Navigation startet.

###Beispiel für negatives Szenario:

Karl möchte mit seinem PKW zum Neumarkt nach Köln tahren. Karl benutzt das Navigationssystem des Fahrzeugs, um die kürzeste Wegstrecke zu ermitteln. Er wählt „Ziel eingeben“. Das Navigationssystem zeigt im Display „Bitte Ort nennen oder manuell eingeben“ an. Karl wählt die Spracheingabe und spricht „Köln“. Das System bedauert den Zielort nicht finden zu können, da es ohne Internet Verbindung ein zu weit entferntes Ziel nicht finden kann. 

###Beispiel für missbrauchs Szenario:

Karl möchte mit seinem PKW zum Potsdamer Platz 1 nach Berlin tahren um eine Lieferung abzugeben. Karl benutzt das Navigationssystem des Fahrzeugs, um die kürzeste Wegstrecke zu ermitteln. Er wählt „Ziel eingeben“. Das Navigationssystem zeigt im Display „Bitte Ort nennen oder manuell eingeben“ an. Karl wählt die Spracheingabe und spricht „Berlin“. Durch einen Logikfehler im System kann er eingeben, dass er bereits dort war und das Paket abgegeben hat, was nicht stimmt.

###Beispiel für alternatives Szeanrio:

Karl möchte mit seinem PKW zum Potsdamer Platz 1 nach Berlin tahren. Karl benutzt das Navigationssystem des Fahrzeugs, um die kürzeste Wegstrecke zu ermitteln. Er wählt „Ziel eingeben“. Das Navigationssystem zeigt im Display „Bitte Ort nennen oder manuell eingeben“ an. Karl selektiert den Zielort durch Stifteingabe auf einer elektronischen Karte am Bildschirm des Systems. Das System wählt Berlin Potsdamer Platz 1 als Zielort aus und die Navigation startet.

###Beispiel für deskriptives Szenario:

Karl möchte mit seinem PKW zum Potsdamer Platz 1 nach Berlin tahren. Karl benutzt das Navigationssystem des Fahrzeugs, um die kürzeste Wegstrecke zu ermitteln. Er wählt „Ziel eingeben“. Das Navigationssystem zeigt im Display „Bitte Ort nennen oder manuell eingeben“ an. Karl wählt die Spracheingabe und spricht „Berlin“. Aufgrund von Hintergrundgeräuschen und der schlechten Aussprache erkennt das System das Wort nicht eindeutig. Durch die Ähnlichkeitsanalysen zeigt es das wahrscheinlichste Wort an, und zwar „Schwerin“. Es zeigt zudem im Display an „Ihre Eingabe konnte nicht eindeutig erkannt werden“ sowie die folgenden Interaktionsmöglichkeiten:
(1) Zielort akzeptieren (ja/nein)
(2) Neueingabe (neu)
(3) Ähnliche Orte anzeigen (ähnlich)
(4) Manuelle Eingabe (Taste „M“ drücken).
Karl spricht „ähnlich“, und das System listet die Orte „Schwerin“, „Berlin“ etc. auf. Karl spricht „Berlin“, und das System wählt Berlin als Zielort aus.

###Beispiel für exploratives Szenario

Karl möchte mit seinem PKW mittels Navigationssystem zu einem Zielort fahren. Es stellt sich zunächst die Frage, ob der Startpunkt der Fahrt immer die aktuelle Position des Fahrzeugs ist, oder ob Karl den Startpunkt selbst auswählt. Die automatische Wahl des Startpunkts vermeidet eine zusätzliche Benutzerinteraktion und unterstützt somit ein schnelles Navigieren. Die Eingabe des Startpunkts würde es ermöglichen, auch Strecken zu berechnen, die als Startpunkt nicht den aktuellen Standpunkt des Fahrzeugs besitzen. Damit würde das System u.a. eine komfortable Reiseplanung ermöglichen. Karl könnte somit unabhängig vom Standort des Fahrzeugs ermitteln, wie weit es von Paris nach Nizza ist und wie lange die voraussichtliche Fahrzeit beträgt, um dies für die Reiseplanung zu nutzen. Eine dritte Möglichkeit besteht darin, zwei Menüfunktionen einzuführen: „Navigation“ (mit automatischer Vorgabe Startpunkt = Standort) sowie „Navigation mit Startpunkteingabe“ und die Funktion „Navigation“ als Standardauswahl zu definieren. 

###Beispiel für erklärendes Szenario

Der Abstand zwischen den Fahrzeugen verringert sich weiter. Da das Fahrzeug mit hoher Geschwindigkeit (> 90 km/h! über die Autobahn fährt und daher vor einem evtl. Ausweichmanöver die Geschwindigkeit reduziert werden sollte, leitet der On-Board-Computer, um einen Auffahrunfall zu vermeiden, eine automatische Notbremsung ein. Durch das ABS bleibt das Fahrzeug lenkbar, und Karl kann somit ein Ausweichmanöver einleiten. Während des Bremsmanövers informiert das System Karl über die eingeleitete Notbremsung. Um nach Abschluss der Notbremsung Karl wieder die Kontrolle über sein Fahrzeug zu geben, stellt das System, wenn das vorausfahrende Fahrzeug mit verminderter Geschwindigkeit weiterfährt, wieder einen sicheren Abstand her und signalisiert Karl die Übergabe der Kontrolle.


