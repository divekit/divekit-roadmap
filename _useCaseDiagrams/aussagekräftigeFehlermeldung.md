---
type: useCaseDiagram
acronym: useCaseDiagramFehlermeldungAussagekraeftig
responsible: 
    - cpo
title: Use Case Diagram Aussagekräftige Fehlermeldung
functionalRequirement: FehlermeldungAussagekraeftig
useCases:
    - pom.xml überprüfen
    - Hilfe anfordern 
useCasesDetailedWithScenario:
    - UCaufgabeEinreichen
diagram: ./diagrams/useCaseAussagekräftigeFehlermeldung.jpg
history:
    v1:
        date: 2021-07-18
        comment: initially created
    v2:
        date: 2021-07-19
        comment: added description
    v3:
        date: 2021-07-19
        comment: added wmaProg as actor 
    v4: 
        date: 28-07-28
        comment: resolved review issues
    v5:
        date: 2021-07-29
        comment: fundamental changes in order to better reflect the functional requirement
todo: 
---

## Beschreibung

Hier werden mögliche Interaktionen mit dem System dargestellt, die mit der Anforderung "Aussagekräftige Fehlermeldung"
in Verbindung stehen. 

Der Use Case "Aufgabe einreichen" wird vom Studenten ausgeführt. Wenn der Student sein Ergebnis comitet und pusht,
wird zunächst die lokale pom.xml mit der pom.xml aus dem hidden Repo verglichen (pom.xml überprüfen). Werden Änderungen 
festgestellt, wird das Compilieren der Aufgabe abgebrochen. Auf der Testseite wird eine Fehlermeldung ausgegeben, die den
Studenten darauf hinweist, dass er die Datei "pom.xml" verändert hat, dies aber nicht sollte. Es werden auch die Änderungen
angezeigt, die der Student rückgängig machen muss, damit die Aufgabe wieder compilieren kann

Wenn die Überprüfung der pomm.xml keine unzulässigen Veränderungen findet, wird die Aufgabe compiliert und die Tests
werden durchgeführt. Dem Studenten wird auf der Testseite angezeigt, ob die Tests bestanden wurden.

 Der Use Case "Hilfe anfordern" bildet ab, dass dem Studenten unter der Fehlermeldung Kontaktdaten angegeben werden, mit
 denen er menschliche Hilfe anfordern kann, wenn er das Problem nicht selbständig lösen kann.

