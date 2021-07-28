---
type: useCase
acronym: verbessertesFeedback
responsible: 
    - fgr
title: Verbessertes Feedback
description: Ein*e Student*in kann sich zusätzliches Feedback anzeigen lassen.
primaryActor: studierende
secondaryActors:
    - wmaProg
    - profInf
    - profMa
    - profBwl
trigger: Der/die User*in gibt seine Aufgaben ab
precondition: > 
    Eine Musterlösung wurde zusammen mit den Aufgaben erstellt und es existiert für korrigierte Abgaben eine Option "Zusätzliches Feedback anzeigen".
postcondition: Der/Die User*in bekommt zusätzliches Feedback.
functionalRequirement: VerbessertesFeedback
history:
    v1:
        date: 2021-07-22
        comment: initially created
todo: 
    - mma ist Stakeholder - hier ist aber eine StakeholderRole gefragt (sbe)
    - (sbe) So wie die secondaryActors und Schritt "1) Die Abgabe wird von profInf, profMa, profBwl oder wmaProg kontrolliert." formuliert ist, sind alle 4 involviert und zufällig übernimmt einer von denen dann den Schritt. Gemeint ist aber vermutlich die generische "Lehrende" Rolle. 
    - (sbe) Im Hauptszenario fehlt am Anfang was. Der UC fängt "mittendrin" an.
    - (sbe) Zwischen Schritt 1 und 2 im Hauptszenario fehlen eine Menge Schritte. Dito zwischen den anderen Schritten
    - (sbe) Alternativszenario 2a - das ist keine Alternative, sondern eher eine Ausweitung (Extension) des UC.
    - (sbe) Insgesamt viel zu wenig detailliert. Vielleicht sollten Sie nur einen Teil modellieren, den dann aber so detailliert, dass man daraus Software machen kann - das ist der Anspruch. 
---

Als User*in gelten alle Studenten, welche Aufgaben im Divekit abgeben.

## Hauptszenario

* 1) Die Abgabe wird von profInf, profMa, profBwl oder wmaProg kontrolliert.
* 2) Der/Die User*in bekommt das Ergebnis, das die Aufgabe mit unter 55% der Punkte bestanden wurde.
* 3) Der/Die User*in bekommt Verbesserungsvorschläge angezeigt.
* 4) Der/Die User*in bekommt die Musterlösung angezeigt.

## Alternativszenario

* 2a) Der/Die User*in bekommt das Ergebnis, das die Aufgabe mit über 55% der Punkte bestanden wurde und wählt die Option "Zusätzliches Feedback anzeigen" aus.

## Ausnahmeszenario 

* 4a) Es konnte für die Aufgabe(n) keine Musterlösung erstellt werden und daher wird keine angezeigt.


**Andere Nachbedingung**: Der/Die User*in bekommt kein zusätzliches Feedback.


