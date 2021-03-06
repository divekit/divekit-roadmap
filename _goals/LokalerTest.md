---
type: goal
acronym: LokalerTest
responsible: 
    - fgr
    - jlü
    - kru
    - duz
    - ako
title: Lokale Tests für Aufgaben der Studenten
source: 
    - [Workshop 6-3-5-No.2, Schwerpunkt Aufgaben]
    - [Beobachtungstagebuch, PS1]
    - [beobachtungstagebuch, PC8]
    - [beobachtungstagebuch, PC9]
belongsTo: 
isTopLevel: true
history:
    v1:
        date: 2021-06-16
        comment: initially created
    v2: 
        date: 2021-07-21
        comment: fixed todos for spelling, gender neutral, sources
    v3: 
        date: 2021-07-27
        comment: enhance description to address todo 
    v4:
        date: 2021-07-29
        comment: enhance description and remove todo
    v5:
        date: 2021-07-29
        comment: combined with zeitnaheUeberpruefung as requested
ignore: w005
todo:
---

## Beschreibung

Von den Student*innen wird sich gewünscht, dass die Aufgaben aus dem DiveKit auch lokal auf ihrem Rechner getestet werden können, 
anstatt diese erst einmal in das DiveKit committen zu müssen, und mit dem Ergebnis lokal weiterzuarbeiten. Dabei soll es nicht darum gehen, dass 
die Aufgaben manuell von Betreuer*innen getestet werden, sondern darum, dass die Tests die zum automatischen auswerten 
der Lösungen gedacht sind, von den Student*innen ausgeführt werden können, ohne das der produzierte Code in das Repository gepushed werden muss. 


## Begründung

Das lokale Testen der Aufgaben würde den Student*innen viel Zeit ersparen, da sie nicht warten müssen, bis das Ergebnis
hochgeladen und ausgewertet wurde, sondern ein direktes Feedback und direkte Korrekturmöglichkeiten in ihrer lokalen Umgebung 
möglich wären. Zudem gäbe es nur noch einen Commit pro Aufgabe, was es übersichtlicher für die Betreuer*innen des Modules macht.
