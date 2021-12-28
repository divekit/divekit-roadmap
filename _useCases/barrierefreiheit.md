---
type: useCase
acronym: barrierefreiheit
responsible: 
    - jsp
title: Barrierefreiheit
description: Ein User kann die Form der Barrierefreiheit einstellen
primaryActor: studierende
trigger: Der User ruft die Einstellung für Barrierefreiheit auf
precondition: Der Nutzer leidet an einer Form der Farbschwäche
postcondition: Farben sind aus dem System verschwunden und werden durch Symbole/Text ersetzt
functionalRequirement: Barrierefreiheit
history:
    v1:
        date: 2021-07-21
        comment: initially created
    v2:
        date: 2021-07-29
        comment: fix todo
    v2:
        date: 2021-07-31
        comment: fix todo
todo: 

ignore: w051

---

Als User zählt bei diesem Usecase jeder Stakeholder, der mit diesem System interagiert und seine visuellen Settings anpassen möchte.

Dieser UC ist vom UC Branding deutlich abzugrenzen. Hierbei geht es ausschließlich um das Aktivieren/Deaktivieren von einer Barrierefreien Ansicht.
Diese ist vom System vorgegeben und nicht durch Einstellung der Uni änderbar. Vor Augen kann man sich das besonders gut führen, wenn man einmal die Barrierefreiheit und Branding in eine Kano-Klassifikation übernimmt.
Barrierefreiheit ist hier eindeutig ein Basismerkmal, wohingegen Branding, je nach Szenario, ein Leistungs- oder Begeisterungsmerkmal ist.

## Hauptszenario

* 1) Der User entscheidet sich für die Änderung seiner visuellen Einstellungen
* 2) Der User geht in die Einstellungen
* 3) Der User navigiert zum Bereich Barrierefreiheit
* 4) Der User ändert die Darstellung auf Symbole
* 5) Das System zeigt Ergebnisse mit Symbolen statt Farben an

## Alternativszenario

* 4a) Der User ändert die Darstellung zu einer Textform
* 5a) Das System zeigt Ergebnisse als Text anstelle von Farbe an.

## Ausnahmeszenario 

Bei korrekter Implementierung der Barrierefreiheit visuallisierung kann es zu keinem Ausnahmeszenario kommen.

**Andere Nachbedingung**: Der Student kann plötzlich wieder Farben erkennen?




