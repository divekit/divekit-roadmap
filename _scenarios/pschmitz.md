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
    v4:
        date: 2021-07-28
        comment: rework scenarios addressing given todos
todo:
---

### Hauptszenario

Das Semester neigt sich dem Ende zu und die Klausuren stehen an. Aufgrund von Online Klausuren befürchtet Paul, dass die
Studierenden die Klausuraufgaben nicht selbstständig lösen. In der Vergangenheit hat er die Erfahrung gemacht, dass gerade die
Betrugsprävention bei Online-Klausuren sehr schwierig ist. Er sucht nun eine Möglichkeit, Klausuren zu individualisieren, um 
diesem Problem vorzubeugen.

Die Klausur dreht sich um die Erstellung eines Docker-Containers und dem anschließend automatischen Deployment 
in eine Cloudlösung. Während der Klausur sollen die Studierenden einen Docker Container erstellen und zum Laufen bringen.

Nach dem erfolgreichen Erstellen der Docker Container, werden die Images der Student*innen auf Github gepushed und alle automatisiert ausgeführt.
Einige vordefinierten Tests, welche den Zustand des Docker Containers überprüfen, liefern Paul bereits kurz nach der Klausur einen 
guten Überblick über die Leistungen der Student*innen, sodass er bereits kurz nach der Klausur zufrieden sein kann, dass viele Student*innen 
gut abgeschnitten haben. 

Eine Woche nach der Klausur pulled Paul alle eingereichten Klausurlösungen und überprüft diese manuell, da er sicher gehen will, dass eine 
faire Notenbewertung zu stande kommt. Sein erster positiver Eindruck der eingereichten Lösungen bestätigt sich. 

Paul möchte aufgrund der positiven Erfahrungen in Zukunft weiter auf das DiveKit zur Stellung von DevOps bezogenen Klausuraufgaben setzten und denkt darüber nach 
nicht nur die Erstellung von Docker Containern mithilfe des DiveKits in Klausuren zu prüfen. 

### Alternativszenario

Paul möchte, dass die Studierenden in den Übungen möglichst viel lernen. Allerdings hat er in der 
Vergangenheit oft die Erfahrung gemacht, dass einige Studierende die Lösung abschreiben und so schlecht für die Klausuren 
vorbereitet sind. Der Fokus der Aufgaben liegt dabei in der Erstellung eines Google Cloud Clusters. Konkret soll jede*r
Student*in ein eigenes Cluster aufsetzten und dabei individuelle Aspekte berücksichtigen.

Um Paul die Arbeit zu erleichtern, setzt er auf das DiveKit zur Erstellung, Individualisierung und der vollständig automatisierten Auswertung 
der Übungsaufgaben. 

Während der Übung erstellen alle Student*innen ihre Cluster und pushen die dazugehörigen Dateien in ihr individuelles Repository. 
Nach kurzer Zeit erhalten die Student*innen einen guten Überblick über ihren aktuellen Lernstatus. 

Da dies nur eine unbenotete Übung ist, verzichtet Paul explizit auf eine manuelle Überprüfung der eingereichten Lösungen, sondern nutzt
lediglich vordefinierte Tests, welche den Zustand des Google Cloud Clusters auf Vollständigkeit und Korrektheit validieren. 

Neben den Übungsaufgaben bietet Paul seinen Student*innen an, das DiveKit und die damit erstellten Aufgaben zur individuellen 
Prüfungsvorbereitung zu nutzen. Die Aufgaben werden nach dem Push in das DiveKit Repository automatisch mit den vorgegebenen Tests validiert
und anschließend automatisch auf eine zentrale Google Cloud der Hochschule deployt, sodass sich die Studierenden andere Lösungen anschauen können.

Paul hat in diesem Jahr besonders gute Klausurergebnisse nach der praxisnahen Vorbereitung erhalten und auch das Feedback der Student*innen 
ist sehr positiv ausgefallen.

Paul möchte auch in Zukunft auf das DiveKit setzten und seine bereits umgesetzten Aufgaben zu DevOps ausbauen. 




### Negativszenario

Die Student*innen arbeiten mitten in der Klausur an ihrer Aufgabe zum Aufsetzen eines Google Cloud Clusters. Neben dem Deployment einer kleinen Anwendung, sollen die Student*innen
eine Datenbank anbinden. 

Nach der Hälfte der Zeit läuft die Lizenz der Hochschule für das Google Cloud System aus und alle Student*innen können an den 
Aufgaben nicht mehr weiterarbeiten. 

Eine kurzfristige Erneuerung der Lizenz ist nicht möglich, sodass die Klausur für alle Teilnehmer*innen abgebrochen werden muss und 
zu einem neuen Termin erneut durchgeführt werden muss. 

Leider sind aufgrund dieses Vorfalls einige Student*innen verängstigt, dass ähnliche Vorfälle nochmals vorkommen können und 
das Vertrauen in das DiveKit sinkt. Einige Dozent*innen ziehen zudem nun in Betracht ihre Klausuren wieder auf eine klassische Klausur umzustellen und abstand 
vom Gebrauch des DiveKits zu nehmen.



