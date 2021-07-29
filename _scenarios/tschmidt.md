---
type: scenario
acronym: tschmidt
title: Übersicht und zusammenfassung von Ergebnissen von allen Studenten
persona: tschmidt
scenarioTypes: 
    - main
    - alternative
    - exception 
responsible: 
    - tza
source:
    - [interview, fkrampe, 00-09-47]
    - [interview, fkrampe, 00-13-25]
    - [interview, fkrampe, 00-27-17]
history:
    v1:
        date: 2021-06-11
        comment: initially created
todo:
    - (sbe) warum wird das Alternativszenario gewählt? (tza) siehe [interview, fkrampe, 00-13-25] und leider konnte ich mir keinen besseren Weg vorstellen, das Ziel mit anderen Systemmitteln zu erreichen. 
---

## Beschreibung

Thomas ist für das Softwaretechnik 1 Praktikum zuständig. Dieses Semester nehmen 145 Studierenden daran teil.
Der Abgabetermin für den ersten Meilenstein war gestern Abend. Deshalb möchte Thomas sich den Überblick
verschaffen und wissen, wer das Praktikum bestanden hat und wer nicht. Er benötigt diese Informationen,
da er dies dem Prüfungsamt melden muss und er die Studierenden entsprechend informieren möchte.

Da die Studierenden für den Meilenstein die Aufgaben ausschließlich mit dem DiveKit bearbeiten mussten,
geht Thomas wie folgt vor:

### Hauptszenario

* Er öffnet die DiveKit-Seite.
* Er navigiert zur Ergebnisübersicht.
* Darin sieht er eine Liste der Studierenden mit ihren Namen und Matrikelnummern.
  Für jeden Studierenden wird der Anteil der gelösten Aufgaben und die Bewertung des Bestehens angezeigt.
* Es sieht unter anderem die berechnete Durchfallquote und die Anzahl von Studierenden, die bestanden haben.
* Er drückt auf die Schaltfläche "Exportieren".
* Das System erstellt eine Excel-Datei (Word-Datei) und lädt sie auf den Rechner von Thomas herunter.
* Thomas schreibt eine E-Mail an das Prüfungsamt und fügt die exportierte Datei hinzu.

### Alternativszenario

* Er öffnet die DiveKit-Seite.
* Er navigiert zur Übersicht, wo alle Testseiten aufgelistet sind.
* Er erstellt manuell die Excel-Datei mit der Auflistung von Studierenden und allen notwendigen Spalten.
* Nacheinander öffnet er die Testseiten der Studierenden und befüllt entsprechend die Excel-Datei.
* Thomas schreibt eine E-Mail an das Prüfungsamt und fügt die befüllte Datei hinzu.

### Ausnahmeszenario

* Er öffnet die DiveKit-Seite.
* Er navigiert zur Ergebnisübersicht.
* Obwohl die Studierenden die Aufgaben gelöst haben, haben sie vergessen die Lösungen zu pushen.
  Infolgedessen hat niemand (oder nur wenige) das Praktikum bestanden.
* Thomas kann diese Ergebnisse nicht exportieren und muss die Studierenden darauf aufmerksam machen
  und ggf. den Meilensteintermin verschieben.

