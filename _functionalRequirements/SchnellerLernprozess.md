---
type: functionalRequirement
acronym: SchnellerLernprozess
responsible:
    - mwi
    - kru
title: Schneller Lernprozess
goals:
    - geringeEinarbeitungszeit
source:
    - [beobachtungstagebuch, PC4]
implementationStatus: open
prefilterPriorizationPoints: 6
kano:
    type: basic
    reasoning: >
        Eine Erfüllung dieser Anforderung steigert zwar nicht direkt die Zufriedenheit, sorgt jedoch bei Fehlen dafür, dass die Unzufriedenheit stark zunimmt. Ein schneller (Kennen)Lernprozess wird als Basisfaktor eingestuft, da eine einfache, unkomplizierte Vorstellung des Systems ausschlaggebend ist, um effizient und effektiv damit arbeiten zu können. Fehlt diese Anforderung, so wird die Unzufriedenheit stark zu nehmen, da man meist zu anfang nicht weiß, wie mit dem System umgegangen werden muss. Auch der weitere Lernprozess sollte möglichst einfach gestaltet sein, andernfalls könnte die Nutzung demotivierend werden.
history:
    v1:
        date: 2021-07-07
        comment: initially created
    v2:
        date: 2021-07-12
        comment: Added all responsible authors and reason regarding todo
    v3:
        date: 2021-07-16
        comment: Modified responsibles as discussed
    v4:
        date: 2021-07-29
        comment: Updated reasoning & fr, added note 
    v5:
        date: 2021-07-31
        comment: fixed typos

todo:
    - (sbe) bitte genauer ausführen - das ist nahezu wortgleich die Wiederholung des Ziels. Welche Features braucht DiveKit, um das Ziel umzusetzen? Sonst bitte eher löschen, hat dann keinen Mehrwert. 
    - (kru) Ist die Lösung aus der Anmerkung zufriedenstellend?
---

Das DiveKit muss so aufgebaut sein, dass der (Kennen)Lernprozess durch kontextbezogene Hilfsmittel erleichtert wird.

## Begründung

Der Einsatz von kontextbezogenen Hilfsmitteln kann, bei Schwierigkeiten, die Nutzung und den Einstieg in das DiveKit vereinfachen. Diese können in Form von Pop-ups oder eingebundenen Tutorial-Videos eingebunden werden.

### Anmerkung

Von einer Aufteilung in mehrere Anforderungen wird hier wegen die bereits durchgeführte Kano-Priorisierung abgesehen, um diese nicht zu invalidieren. 
Es werden nachfolgend mögliche neue Anforderungen beschrieben:

* Das DiveKit soll dem Entwickler ermöglichen ein Tutorial einzubinden, um den Kennenlernprozess zu vereinfachen.
* Das DiveKit soll der Nutzer:in ermöglichen Hilfsdialoge o. Ä. für den Einstieg anzuzeigen.