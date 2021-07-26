---
acronym: jintveen
type: interview
responsible: 
    - kru
    - duz
    - ako
stakeholder: jin
date: 2021-04-27
duration: 2h
location: Zoom-Meeting
transcriptUrl: 
history:
    v1:
        date: 2021-05-21
        comment: initially created & draft
    v2:
        date: 2021-06-07
        comment: updated data
todo:
---

## Interviewleitfaden

### Teilnehmer:
* Interviewer: Deniz Uzun
* Protokollant: Alexander Kosmehl, Kay Ruck
* Interviewpartner: Jann Intveen

### Modalitäten
* Dauer: 2 Stunden
* Datum: 27. April 2021
* Uhrzeit: 11:00 Uhr
* Ort: Zoom-Meeting

### Ziel 
Erster, technischer Überblick über das DiveKit.

### Begrüßung/Eröffnung
* Vorstellung der Interviewer & des Moduls / Kurses / Zwecks 
* Einverständnis für die Aufnahme bzw. das Anfertigen eines Transkriptes 
* Vorstellung des zu Interviewenden. 

### Fragenkatalog

#### Ist Zustand
* Wie sind Sie zu dem Projekt gekommen? / Welche Funktion nehmen Sie ein? 
* Wer benutzt das DiveKit? Welche Rollen sind am DiveKit beteiligt?
* Welche Ziele sollen durch das DiveKit erreicht werden? 
* Was soll vermieden werden?
* Wie glauben Sie, dass das System auf andere wirkt?  
    * Wie wirkt sich das DiveKit auf die Studierenden bzw. deren Leistung aus?
    * Wie ist der Ablauf bei einer Beschwerde eines Studenten?  
    * Wie kommen die Aufgaben bei den Studierenden an?
    * Glauben Sie das Mitarbeiter / Dozenten den Mehraufwand des Divekits akzeptieren? 
* Welche Richtlinien müssen eingehalten werden? (Datenschutz, Datensicherheit, Barrierefreiheit)
* Wie kommt das DiveKit zum Einsatz? (Systemstruktur)

#### Einschränkungen
* Welche Tools wurden zur Weiter-/Entwicklung genutzt? 
    * Gibt es eine Technologie, die angewandt / eingebunden werden soll?
    * Kann plattformunabhängig genutzt werden?
    * Wenn ja resultieren darauf Probleme? (vor allem technische)
* Welche Funktionalitäten hat das DiveKit? 
* Gibt es (personenbezogene) Daten?  
    * Wenn ja wie wird damit verfahren? 
    * Werden die Daten anonymisiert? 

#### Weiterentwicklung
* Wie ist die Weiterentwicklung geplant?
    * Gibt es Kriterien, welche diese beeinflussen?
* Gibt es weitere Bereiche bzw. Personen, mit denen wir sprechen sollten?
* Wenn Sie das DiveKit nochmal entwickeln könnten, würden Sie etwas ändern? Wenn ja was?
* Haben Sie sonstige Anmerkungen / Hinweise? Möchten Sie noch etwas Ergänzen? 

## Transkript
Link zum [Transkript](../sources/jintveen_transkript.pdf).

## Ergebnisprotokoll

### Digitale Lehre

#### Wie sind Sie zu dem Projekt gekommen? / Welche Funktion nehmen Sie ein?

* Arbeitet als WMA bei Prof. Bente
* Praxisnahes Coding als Anforderung
* Praxisnah -> Git -> Jeder eigenes Repo
* Macht von allem etwas, hauptsächlich Entwickler
* Stark in allen Prozessen miteinbezogen


#### Wer benutzt das DiveKit? Welche Rollen sind am DiveKit beteiligt?

* Betreuer
* Professoren
* WMAs

#### Wie ist da die Rechteverteilung?

* Alle GitLab Admin 
    * Grundsätzlich gleich
* Bei organisatorischem hat Prof das letzte Wort

####  Welche Ziele sollen durch das DiveKit erreicht werden? 

* Mehr Coden
* Realitätsnahe Tools (Git, IDE, ...)
* Extrinsische Motivation
* Kopieren von Lösungen erschweren
* Gruppenarbeit erlaubt, Studenten sollen sich aber mit eigener Aufgabe auseinandersetzen
* Mündliche Prüfungen machen es schwer Studenten durchfallen zu lassen
    * konkretere Benotung
    * kann nicht dem Vorrredner "nachplappern"
* Wohldefinierte Ziele durch Tests

#### Was soll vermieden Werden?

* Lehrender soll sich nicht auf Tool ausruhen
    * Weniger Arbeit in korrektur - mehr Zeit für Unterstützung
    * Keine Zeitverschwendung wenn jemand sehr gut klar kommt
    

#### Wie wirkt das System auf Andere? (Studierende und deren Leistung?)

* Eindruck von "Abfertigung" soll vermieden werden
    * Zuversichtlich, dass Studenten die einen Durchlauf mitgemacht haben das Gefühl verlieren
* Beratungsleistung erfolgt an richtigen Stellen
* Fernlehre von Praktika durch Corona sehr schwierig ("Klappt alles?"-Mails quasi unmöglich)
    * Initiative muss von Studenten ausgehen
    * Konkrete Tests machen Kommunikation einfacher
* Discord als virtuellen Klassenraum
* Nach erstem Durchlauf wurde Feedback eingeholt
    * "Asynchrones"-Arbeiten sehr positiv angekommen
    * Praktikums-/ Beratungstermine "on-demand"
    * Schnelle Beratung und Korrektur

#### Wie können Studenten Feedback geben / sich beschweren?

* Standard-Kommunikationskanäle E-Mail, Discord für alle Sorgen offen
* Beschwerden schwierig
    * Extrawünsche nicht umsetzbar
    * "Problem sitzt vor dem Rechner"-Beschwerden über Tests nervig
* Sollte das Tool / die automatischen Tests nicht gut ankommen, kann das Projekt abgebrochen werden
* Feedback geht definitiv nach der Menge
* Einzelne Rückmeldungen werden zwar gehört, können aber nicht unbedingt berücksichtigt werden
* Grundsätzlich werden die Repos aber nur auf Nachfrage angesehen
    * 150 Repos pro Semester lassen sich nicht standardmäßig prüfen
    * Integrierte Mechanismen warnen aber vor groben Fehlern

#### Glaubst du die Mitarbeiter / Dozenten würden den Mehraufwand in Kauf nehmen?

* Prinzipiell ja
* Weiterentwicklung wichtig, da einige Hürden vorhanden sind
    * Bessere Bedienung notwendig
    * Aktuell ohnehin noch in keinem Zustand den man Vorstellen möchte
* An vielen Stellen wie Klausuren kein tatsächlicher Mehraufwand
    * Hauptaufwand kommt von Individualisierung, welche auch ohne Tool aufwendig ist

#### Wird das Tool Fach- / Fakultätsübergreifend eingesetzt?

* Aktuell noch unbekannt
    * Marketing in Arbeit
    * Auch außerhalb der TH Köln(!)
* Interesse teilweise vorhanden
* Ein aktueller Fall (nicht namentlich benannt)
    * Fokus liegt eher auf Verteilung mit Git als auch individuellen Aufgaben
* Open-source in Überlegung

#### Gibt es Richtlinien bezüglich Datenschutz etc. die beachtet werden müssen?

* Studenten sollen nicht Repositories von anderen sehen können
* Ansonsten werden keine personenbezogenen Daten gespeichert
    * Studenten werden als UUID anonymisiert gespeichert
    * Lokal auf dem Rechner des Lehrenden gibt es eine Excel mit Zuordnungen
* E-Mail, CampusID etc. nur auf GitLab, aber nicht im DiveKit gespeichert


### Technisches

#### Wie ist das ganze System aufgebaut?

* GitLab gehört nicht zu DiveKit
    * Ähnliche Produkte wie GitHub etc. theoretisch auch nutzbar
    * Pipelines / GitLab CI von GitLab für den Kontext besonders praktisch
* DiveKit selbst ist ein kleines lokales Programm das Repositories mit Aufgaben und Tests anlegt
* Test-Library gehört nicht zum DiveKit da diese Programmiersprachenabhängig ist
* DiveKit an sich ist programmiersprachenunabhängig
* DiveKit ist ein TypeScript Programm
    * Händelt Web-Aspekte besser als Java
* Ergebnisseite für Studenten gehört mit zu DiveKit

#### Wie sieht es mit Platformunabhängigkeit aus?

* GitHub wird wegen der API nicht unterstützt
* Ilias komplett unbekannt
* Programmiersprachen wären teilweise übertragbar, Tests sind aber aktuell in Java geschrieben
    * Kotlin theoretisch schon unterstützt
* (TypeScript-Code lässt sich auf allen Betriebssystemen ausführen)

#### Struktur die DiveKit produziert

* DiveKit verarbeitet Dokument mit Platzhaltern
* Nach Ausführung verschiedene kleine Repos pro Student
    * Code Repo - zum Upload der Lösung
    * Test Repo - enthält ausgeführte Tests (für Studenten nicht sichtbar)
    * Testseite - Generierte Übersicht der Ergebnisse

#### Ist DiveKit nur für Praktika angedacht, oder auch für Klausuren?

* Wurde auch schon für Klausuren benutzt
* Individualisierung sehr praktisch
* Faire Verteilung wichtig
    * Verschiedene Gruppen von Aufgabentypen sind schwer zu verteilen
* Balance der Ähnlichkeit zwischen Aufgaben schwer

#### Schwierigkeiten bei der Aufgabengenerierung?

* Grammatik viel Aufwand
* 1:1, 1:n - Beziehungen schwierig in den Aufgaben zu formulieren
    * Fälle im Text ändern sich
    * Aufgabe muss aufeinmal eine Liste von Objekten aufzählen

#### Gäbe es Bereiche ohne Programmierung in denen man Divekit nutzen kann?

* Aktuell sehr objektzentrisch
    * Muss keine Objektorientierte Programmierung sein
    * Objekte in Diagrammen oder ähnlichem denkbar
* Reine Textindividualisierung auch möglich
* Individualisierte Parameter bei Rechenaufgaben

#### Gibt es noch Punkte mit denen du unzufrieden bist?

* Hätte von Anfang an mehr auf Robustheit achten müssen
* Bedienbarkeit für Nutzer verbessern damit diese auf Fehler reagieren können
* Tutorials und Videos für einfacheren, schnelleren Einstieg bereitstellen