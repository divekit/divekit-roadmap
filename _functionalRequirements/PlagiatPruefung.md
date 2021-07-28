---
type: functionalRequirement
acronym: PlagiatPruefung
responsible: 
    - cpo
title: Plagiatsprüfung
goals:
    - Betrugsverhinderung 
source:
    - [workshop, waltDisney]
implementationStatus: open
prefilterPriorizationPoints: 1
kano:
    type: excitement
    reasoning: >
        Eine integrierte Plagiatsprüfung würde abgeschriebene Lösungen schneller aufdecken und abschreckend wirken. 
        Allerdings zählt dies nicht zu den wichtigsten Features und in Zweifelsfällen können einzelne Abgaben einer 
        manuellen Prüfung unterzogen werden.
history:
    v1:
        date: 2021-07-08
        comment: initially created
    v2:
        date: 2021-07-16
        comment: added goal
    v3:
        date: 2021-07-16
        comment: added kano classification 
    v4:
        date: 2021-07-28
        comment: Anforderung mit Satzschablone präzisiert
todo: 

---

Wenn ein Nutzer eine Lösung einreicht, die in großen Teilen mit einer Lösung von einer anderen Persson übereinstimmt,
sollte das System ein Fraud-Flag setzen, welchen den wmaProg dazu auffordert, die betroffenen Abgaben genauer zu 
überprüfen.

## Begründung

Plagiate sollten so weit wie möglich unterbunden werden. Wenn das System einen Plagiatsverdacht feststellt, soll menschlich
überprüft werden, ob dieser Verdacht wahr ist. So sollten falsche Positive nicht zu einer falschen Beschuldigung führen.
