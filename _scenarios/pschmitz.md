---
type: scenario
acronym: pschmitz
title: Aufgabe zu DevOps
persona: pschmitz
scenarioTypes: 
    - main
    - alternative
    - negative
responsible: 
    - jlü
source: 
    - [interview, nnProf3]
history:
    v1:
        date: 2021-06-17
        comment: initially created
    v2:
        date: 2021-07-12
        comment: Hinzufügen von Szenarien
    v3:
        date: 2021-07-23
        comment: refactor regarding the issues from the review
todo:
    - (sbe) interessante, detailreiche Szenarien, allerdings brechen die irgendwie "mittendrin ab" - finden Sie da noch einen Abschluss?
    - (sbe) worin besteht die "Alternative" beim Alternativszenario?
    - (sbe) die abbrechende Internetverbindung ist so ähnlich wie ein Stromausfall, da kann das Tool eigentlich nichts machen. (Wir sagen den Studies dann, dass sie eine Support-Email des ISP einreichen sollen.) Sinnvoller fände ich sowas wie "Cloud-Lizenz mitten in der Klausur revoked" oder so.
---

### Hauptszenario

Das Semester neigt sich dem Ende zu und die Klausuren stehen an. Aufgrund von Online Klausuren befürchtet Paul, dass die
Studierenden die Klausuraufgaben nicht selbstständig lösen. In der Vergangenheit hat er die Erfahrung gemacht, dass gerade die
Betrugsprävention bei Online-Klausuren sehr schwierig ist. Er sucht nun eine Möglichkeit, Klausuren zu individualisieren, um 
diesem Problem vorzubeugen.

Die Klausur dreht sich um die Erstellung eines Docker-Containers und dem anschließend automatischen Deployment 
in eine Cloudlösung. Während der Klausur sollen die Studierenden einen Docker Container erstellen und zum Laufen bringen.

### Alternativszenario

Paul möchte, dass die Studierenden in den Übungen möglichst viel lernen. Allerdings hat er in der 
Vergangenheit oft die Erfahrung gemacht, dass einige Studierende die Lösung abschreiben und so schlecht für die Klausuren 
vorbereitet sind. Der Fokus der Aufgaben liegt dabei in der Erstellung eines Google Cloud Clusters. Konkret soll jede*r
Student*in ein eigenes Cluster aufsetzten und dabei individuelle Aspekte berücksichtigen.


### Negativszenario

Während der Klausur bricht die Internetverbindung eines Studenten ab. Dieser ist nicht mehr in der Lage
seine Lösungen zu einer Aufgabe mit Docker Containern zu deployen, zu testen und einzureichen, sodass er durch die Klausur durchfällt.


