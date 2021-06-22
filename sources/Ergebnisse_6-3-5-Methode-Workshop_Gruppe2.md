---
acronym: 6-3-5-No.2
type: literature reference
title: Ergebnisse_6-3-5-Methode-Workshop_Gruppe2
responsible: - tza
             - ngi
             - fgr
             - jsp
publisher: none
source_url: none
history:
    v1:
        date: 2021-06-06
        comment: initially created

---

**Schwerpunkt Interface:**

Es soll ein Darkmode für Divekit eingeführt werden. Mit der Einstellung „Systemfarbe“ kann automatisch überprüft werden, ob White oder Darkmode genutzt werden soll. Gewünscht wären auch verschiede Varianten wie IDE Theme, Solarized, Dracula, High Contrast und true black.
Vergangenes Feedback über Dropdown Menü anzeigen.

Sidebar mit allen Tests für Divekit. Aufteilung der Tests in Kategorien bestanden und nicht bestanden.

History über die bisherigen Abgaben ein- und ausklappbar machen.

Position in der Warteschlange anzeigen, wann der Student überprüft wird.

**Schwerpunkt Interaktion:**

Es soll benachrichtigt werden, sobald die Überprüfung der Aufgaben abgeschlossen wurde. Mögliche Ansätze dies umzusetzen wäre eine E-Mail über die TH-Adresse, eine persönliche Nachricht auf Diskord von einem Bot oder eine gitlab Issue, wo der Student Staff member ist. Sobald die Issue vom Kontrolleur geschlossen wird, wird der Student automatisch informiert. 
Um Zeit sparen zu können sollen an den Aufgaben mit Haken markiert werden können, welche Aufgabe kontrolliert werden sollen. 

Von den Kontrolleuren soll auch bei bestandenen Tests allgemeines Feedback gegeben werden, was ihnen beim Kontrollieren des Tests auffällt. Dieses kann zum Beispiel häufige Fehler oder schlechte Angewohnheiten beinhalten. Es sollen auch Fragen zur Aufgabenlösung gestellt werden können und bei folgenden Aufgabenstellungen Anmerkungen zu häufigen Fehler der gesamten Studierenden gegeben werden.
Das Feedback der vergangenen Aufgaben soll in einer History gespeichert werden. Um Zeit zu spenden kann auch anstatt der eigenen Meinung zum Code eine Bewertung über eine 5-Sterne-Skala gegeben werden.
Der Betreuer soll auch für die Betreuerschaft intern Kommentare erstellen können, um bei einer Übernahme anderer Prüfer den Prozess zu vereinfachen.

Über einen Trigger soll benachrichtigt werden, wenn man nach einer bestimmten Zeit die Aufgaben noch nicht abgegeben hat, weil diese Tests noch nicht fertig sind.
Die Prüfer sollen direkt von den Studenten über ihre Abgabe informiert werden können, ohne noch einmal auf Diskord gehen zu müssen. Das kann über einen Prefix in der Commit Message gelöst werden, welcher von einem Diskord Bot erkannt wird und zu einer Benachrichtigung des Prüfers führt, eine Seite für die Prüfer mit einer Übersicht der nächsten, prüfungsbereiten Studenten oder ein Button auf der Testseite.
Das Feedback soll direkt am Code sein und aufgeteilt nach Aufgabe. Falls es nicht direkt am Code geht, zumindest besser gegliedert mit Stichpunkten, Pfeilen, Code schnipseln oder ähnlichem. 
Falls vom Studenten jedoch ein kompaktes Feedback gewünscht ist, soll dies aber auch eingestellt werden können. 

Es sollen Fragen zu den Korrekturen gestellt werden können. Bei einem Diskord-Bot direkt als Antwort, ansonsten in eigenem Feedbacksystem.

Ein eigener Diskord-Bot für Fragen, der Standartfragen beantwortet. Alternativ eine FAQ Seite, auf die mit Emojis geantwortet werden kann.

Längeres Feedback zu den Aufgaben ist gewünscht, auf einer separaten Seite, auf die von den Aufgaben per Hyperlink zugegriffen werden kann.

Beim Feedback wenn möglich auf den passenden Vorlesungsinhalt oder andere passende Ressourcen verweisen.

Zu bestimmten Zeiten Meetings auf Diskord, wo Fragen an die Betreuer gestellt werden kann und für generelle Fragen auch Issues auf Git anlegen, wo der Betreuer dann drauf reagieren kann.

Agile Videochats Sprints zu den Aufgaben mit den Prüfern für eine Art Zwischenstand bei langen Projekten.

Commit Messages nach einem vorgegebenen Muster verfassen lassen, um die Prüfer zu entlasten.

Tools zur Förderung von Gruppenarbeiten wie Peer-Review oder auch studentische Förderung von Studenten mit Schwierigkeiten.

**Schwerpunkt Technik:**

Bessere Rückmeldung, wenn die Pipe gestorben ist, z.B. „Bitte ändere nicht deine om.xml“ anstatt nur eines Sterben der Testseite. Es soll bei solchen Problemen auch direkt ein Tutorial gegeben werden, mit dem dieses Problem gelöst werden kann.

Automatische Tests sollen schneller gehen als 5 bis 10 Minuten.

Es soll User Preferencen für Design der Seite, Art der Notifikation, etc. bereitgestellt werden.

Prüfungsanstoßung über Branches (wenn rein gemerged wird, kommen die Aufgaben in den Fragenpool) oder issues von den Betreuern anlegen. Wenn der Student sie gelöst hat, bekommt der Prüfer so direkt eine Benachrichtigung. 

Companion App mit Push-Benachrichtigungen, wenn Tests bewertet wurden und Einsicht in History

Schnellere Pipeline um, den Buildvorgang zu beschleunigen.

Die Tests in einem Docker Container ausführen lassen, damit kein Student die gesamte Projektstruktur zerstören kann.

Divekite sollte als Multiprozesssystem aufbauen.

Eine Erkennungssoftware für Betrugsversuche von Studenten einführen.

**Schwerpunkt Aufgaben:**

Aufgaben sollen auch lokal getestet werden können, ohne sie schon commiten zu müssen.

Automatisierte Erzeugung von komplexen Aufgabenstellungen über AI oder einen Pool mit Aufgaben gleicher Schwierigkeit. 

Aufgaben mehr so konzipieren, dass sie automatisch überprüfbar sind. Dazu automatisierte Tests die die Aufgaben auf Robustheit testen.

Ein Punktesystem für die Bewertung, anstatt nur richtig oder falsch zurückzugeben.

Ranking der Studenten nach Performance oder Clean Code. Falls dies bei den schlechten Studenten negative Auswirkungen hat alternativ Bonuspunkte, wenn der Code schnell läuft und innerhalb der ersten Woche abgegeben wurde oder sie Clean Code beinhaltet. Dies ist erst möglich, wenn das Thema Clean Code in vorrangegangen Modulen bereits gelehrt werden. Auch wer schnell fertig wird kann Bonuspunkte erwerben.

Gute Studenten können anbieten, Studenten zu helfen und so Bonuspunkte zu erlangen.

Unterschiedlichere Aufgaben wie Lückentext, Multiple Choice oder auch Performance- und Style-Optimierung von vorgegebenen Code.

Einheitlichen Style für Benennungen von Klassen und ähnlichem bei den Aufgaben fordern.

Kleine Aufgaben und Meilensteine, die aber zusammen ein großes Projekt ergeben.
