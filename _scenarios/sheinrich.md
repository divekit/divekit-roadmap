---
type: scenario
acronym: sampleScenario
title: Einfache Individualisierung von Aufgaben
persona: sheinrich
scenarioTypes:
    - main
    - exception
    - positive
    - negative
    - concrete
    - abstract
    - interaction
    - system
responsible:
    - mba
source:
    - [interview, nnProf, Minute 00:04:22]
    - [interview, nnProf, Minute 00:07:30]
    - [interview, nnProf, Minute 00:14:01]
    - [interview, nnProf, Minute 00:25:27]
    - [interview, nnProf, Minute 00:32:46]
    - [interview, nnProf, Minute 00:40:56]
    - [interview, nnProf, Minute 00:47:44]
    - [interview, nnProf, Minute 00:57:57]
history:
    v1:
        date: 2021-06-18
        comment: initially created
todo:        
    - (sbe) zu viele Szenariotypen - bitte lassen Sie nur die Szenariotypen oben im Front Matter übrig lassen, für die es auch wirklich ein Szenario gibt
    - (sbe) Negativszenario - "dass sich manche über die Konstellation ihrer Datensätze beschweren. In den Nachrichten heißt es, dass die Datensätze keinen Sinn für eine Datenanalyse machen." - Das klingt nach einem Bug im Tool? Wenn dem so ist - so etwas wird grundsätzlich nicht modelliert, man nimmt immer an, dass das System fehlerfrei läuft. Negativszenario heißt, dass das Tool falsch oder missbräuchlich benutzt wird, entweder von Siegmund oder seinen Studies. Vielleicht kann man das Negativszenario in diese Richtung "drehen".
    - (sbe) "solange die Ergebnisse reingeschmissen" - bitte keine Umgangssprache in Szenarien.
     
---

## Beschreibung

### Positive Szenarien

Siegmund hat sich letzte Woche vom Tool eine große Menge an Datensätzen generieren lassen. Diese hat er in der ersten Veranstaltung an die Studierenden verteilt. Diese bearbeiten selbständig die ebenfalls generierten Aufgaben zu den dazu gehörigen Datensatz. In einer Feedback Runde hat er viel positives seitens der Studierenden zurückbekommen, denn sie werden mit Hilfe des Tools durch die Aufgaben geleitet und mit permanentem Feedback versorgt, was die Lernkurve erheblich verbessert hat.

Das Semester neigt sich dem Ende und Siegmund würde sich gerne einen Notenkorridor vom Tool ausgeben lassen, um eine Einschätzung machen zu können wie wohl der Notenschnitt ausfallen könnte. Dafür öffnet er seine Anwendersicht des Tools und bedingt dafür die vorgesehene Funktion. Das Tool gibt in Form einer Datei diesen gewünschten Notenkorridor für alle Teilnehmer aus.

### Negative Szenarien

Siegmund hatte sehr lange seine Mathematik Veranstaltung vorbereitet und war fest davon überzeugt, dass die neue Methodik mit dem Tool auf helle Ohren stoßen wird. Er präsentierte seine Veranstaltung den Studenten, die sofort versuchten, das Tool zu installieren und zu benutzen. Dabei hatten die Studenten, die überwiegend Ingenieure sind, erhebliche Probleme bei der Installation und darauffolgend mit der Benutzung des Tools.

Siegmund hat seine Datensätze generiert und sie an die Studenten verteilt. Kurz nachdem die Durchführung Datenanalyse von den Studenten begonnen wurde, haben Siegmund erste Nachrichten erreicht, dass sich manche über die Konstellation ihrer Datensätze beschweren. In den Nachrichten heißt es, dass die Datensätze keinen Sinn für eine Datenanalyse machen. 

### Missbrauch Szenario

Siegmund konnte im Log des Tools feststellen, dass einige Studenten ihre Aufgaben mit einer Art Brute Force Methode gelöst haben. Sie haben solange die Ergebnisse reingeschmissen, bis sie genau das raus hatten was das Tool von ihnen wollte. Somit ist der eigentliche Sinn des Tools völlig verloren gegangen. 
