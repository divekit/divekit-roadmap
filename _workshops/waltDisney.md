---
acronym: waltDisney
type: workshop
responsible: 
    - 
goals: 
date: 
time: 
method: 
stakeholderRole: student
history:
    v1:
        date: 
        comment: 
todo:
    - füllen       
---

## Ablauf

TODO

## Liste

1. Es wäre wünschenswert, Anfragen an den Kontrolleur stellen zu können, um Feedback einzuholen. Dies könnte mittels Kontaktfeld realisiert werden. Allerdings kann dies einen deutlichen Mehraufwand verursachen.
2. Es wäre wünschenswert, bei einem Hardcrash des Tests einen Link zu einer Google oder Stakeoverflow Seite/Suche für den Fehler bereitzustellen. Dieser Link könnte automatisch auf Basis des Fehlers erstellt werden. Allerdings müsste der Fehler sinnvoll für die Suche aufbereitet werden, damit die Suche nicht ins Leere läuft.
3. Es wäre wünschenswert, wenn alle Tests ausschließlich automatisch ausgewertet würden.
4. Es wäre wünschenswert, alle Meilensteine direkt nacheinander zu bearbeiten. Dafür müssten alle Aufgaben vorbereitet sein. Könnte aber auch problematisch bei zu manuell kontrollierende Aufgaben oder aufeinander aufbauenden Aufgaben sein.
5. Es wäre wünschenswert, die Testseite direkt in die IDE einzubinden, um die Hidden-Tests lokal auszuführen und somit die Pipeline zu entlasten. Dafür müsste ein Plugin für die jweilige IDE entwickelt werden. Allerdings sollen die Tests vor dem User verborgen bleiben, weshalb dies den Sinn und Zweck des Divekits ad absurdum führen würde.
6. Es wäre wünschenswert eine manuelle Überprüfung durch KI zu ermöglichen, um Wartezeiten zu reduzieren. Dafür würden KI Entwickler benötigt. Allerdings besteht ein hoher Trainingsaufwand für individuelle Aufgaben.
7. Es wäre wünschenswert einen Darkmode im Divekit bereitzustellen. Dies wäre schnell durch eine neue CSS Datei machbar.
8. Es wäre wünschenswert, wenn automatische Benachrichtungen an die Nutzer und Betreuer zu versenden. Dafür müsste eine Benachrichtigungsoption eingefügt werden, in der die Person angeben kann, wo bzw. wie sie benachrichtigt werden möchten. Ebenso könnte dies in der Commit-Nachricht eingefügt werden. Allerdings muss dafür der Datenschutz beachtet werden.
9. Es wäre wünschenswert, wenn nicht auf eine Korrektur bzw. die Pipeline gewartet werden müsste.
10. Es wäre wünschenswert, wenn eine Vorhersage über die Dauer über das Ende des Tests gegeben werden könnte.
11. Es wäre wünschenswert, wenn Divekit auf für andere Fächer (z. B. DB1, Algo, AP1, AP2, PP) eingsetzt werden würde. Dafür müsste Divekit verschiedene Aufgabentypen die zu den jeweiligen Fächern passen abbilden.
12. Es wäre wünschenswert, wenn es Bonuspunkte für Commits gäbe. Diese könnten automatisiert überprüft werden. Allerdings bedarf es eine faire Bewertungsmaßstab, der Missbrauch verhindert.










13. Direktes Feedback in der IDE anstatt im Browser
    * Mit den Entwicklern der IDE in Verbindung setzen um die Integration besser zu ermöglichen
    * Helfer- Klasse im Repo hinzufügen, welche die Tests Remote ausführt
    * Automatischen git Pull
        * IDE eventuell nicht Open Source oder ohne Plugin Möglichkeiten
        * Es müssten im sich besser Optimalfall mehr als eine IDE supported werden um den Studenten immernoch die Wahl der IDE zu lassen

14. Automatische Korrektur auch für Diagramme
    *  Eine oder mehrere feste Musterlösungen die mit Image Recognition verglichen werden müssen.
        * Aufwändig. Argumentationspotenzial für verschiedene Ansichten geht dabei verloren.
        * Spielraum der Betreuer bei kleinen Syntaxfehlern geht verloren

15. Testseite in einer App für bessere Zugänglichkeit + Usability
    * Man würde mind. einen Entwickler für iOS sowie einen Entwickler für die Android App benötigen um jedem Studenten Zugriff auf die App zu gewähleisten
    * Es gibt auch Möglichkeiten zur Cross- Plattform- Entwicklung für iOS und Android
    * Einfache Anzeige des Browsers in der App
    * Verbindung über den Benutzernamen in Git
        * App Entwicklung kostet viel Zeit, und benötigt Leute die es können. Zudem kann es sein das die App einfach von niemandem genutzt wird.

16. Studenten können andere Studenten kontrollieren und Bonuspunkte sammeln
    * Implementierung eines geeigneten Belohnungssystems ggf. auf Basis von Fehlerfreien Commits oder sauberer Commit History
    * Reviewsystem wird benötigt
    * Zusätzliche Testseite.
        * Studenten könnten falsches Feedback geben, da sie es nicht besser wissen und selber noch lernen
        * Studenten cheated Es müssten im sich besser
        * Studenten geben sich absichtlich besseres Feedback

17. Bei fehlgeschlagenen Tests sollte man Tipps zur Lösung bekommen
    * Hinterlegen einer Musterlösung um Tipps geben zu können
    * Ausgabe der Tipps, die zum jeweiligen Fehler passen.
        * Führt zu Trial and Error Verhalten, was mit Hidden Tests eigentlich verhindert werden soll

18. Bonuspunkte nach Geschwindigkeit, also 1-3 Tage nach Begin 2 BP 4-6 Tage 1BP
    * 24/7 Schichten haben damit jede Manuelle Prüfung sofort durchgeführt werden kann
    * Geeignetes Belohnungssystem implementieren
        * Unfair gegenüber Studenten welche auch Arbeiten nebenbei um sich das Studium zu finanzieren und nicht direkt Zeit für die Aufgabe haben
        * Könnte zu generell schlechterem Code führen da Studenten unter "Zeitdruck" arbeiten
        * Studenten mit Vorwissen haben Vorteile
        * Es würde eventuell eine "Black Market" geben in dem Lösungen von Erfahrenen Studente verkauft werden
        * we gonna get money yeah

19. Die Ergebnisseite übersichtlicher gestalten um schneller sehen zu können wo das Problem liegt
    * Überarbeitung der Testseite im Design und in der Struktur.
        * Erstellung von Design und neuer Struktur bedeutet wieder mehr Aufwand. Finde zudem persönlich ist die Testseite selber soweit übersichtlich.

20. Eine Warteschlange, in der man sehen kann, wann die manuelle Prüfung meiner Tests ansteht
    * Einfache Anzeige, die zeigt an welcher Stelle man steht.
    * Feste Arbeitszeiten der Kontrolleure festlegen und eine durchschnittliche Kontrolldauer für jede Aufgabe ermitteln
        * Sind nicht unbedingt immer zu festen Zeiten verfügbar.
        * Schwierig, da die Diagramme unterschiedlich gut sind und die Kontrolle pro Student unterschiedlich lange dauert
        * Problematisch, da am Anfang eines Meilensteins fast kein Arbeitsaufwand für die Betreuer besteht, während sie 2 Tage vor der Deadline dann überrannt werden. 
        -> Vermutlich bezogen auf die Leute die auf den letzten Drücker warten. Das gibt dann n Problem für die Zeitplanung der Betreuer.
        -> Das ist ja aber eher ein generelles Problem und keiner einer Warteschlangenanz eige
        -> Klar. Aber Realistkarte geht halt von den festen Arbeitszeiten für die Umsetzung aus. Deshalb schon eTwAs problematisch

21. Bessere Individualisierung der Aufgaben. Auch ausweitbar auf andere Module wie z.B. Mathe.
    * Dozenten/ Betreuer müssen neue Aufgaben passend zum Divekit erstellen
        * Dozenten sind nur sehr schwer zu überzeugen von ihrem gewohnten System wegzugehen und ein neues zu verwenden ( siehe Umstellung auf Online auf Grund von Corona. War eine absolute Katastrophe in 90% der Fächer )

22. Integrierter Chat auf Testseite, damit ggf. vorheriges Feedback bei einem Betreuertausch für den nächsten ebenfalls vorhanden ist, oder das der Student spezielle Fragen stellen kann, um den Nachrichtenfluss in Discord zu minimieren.
    * Einbindung einer Chatbox. Integrierbar auf der Testseite.
    * Chat per IRC Protokoll (wie Twitch) umsetzen
        * Es müsste immer jemand im Chat verfügbar sein

23. Anzeigen einer Musterlösung nach erfolgreichem Bestehen des Tests
    * Anfertigen der Individuellen Musterlösungen durch die Betreuer
        * Hoher Zeitaufwand für die Betreuer, außer, die Lösungen werden Automatisch von einer Musterlösung Abgeleitet, da die Aufgaben sich eh fast nur in Variablennamen und Szenarien Unterscheiden.
        * Problematisch bei Aufgaben mit vielen Umsetzungsmöglichkeiten





24. Es wird sich gewünscht, dass die Studierenden schneller benachrichtigt werden, wenn die Korrektur einer Aufgabe abgeschlossen ist. Als Vorschlag werden Discord-Bots genannt, die Bescheid geben. Es wird gewarnt, sich nicht zu stark von Discord abhängig zu machen.
25. Es wird sich gewünscht, das es eine Meldung/Notification für abgeschlosses Feedback gibt. Es wird vorgeschlagen, den Nutzern mehrere Benachrichtigunsmittel anzubieten, welche dann frei gewählt werden können. Als Kritik wird angemerkt, dass das Berücksichtigen aller Nutzerpräferenzen sehr aufwendig wäre.
26. Es wird sich gewünscht, dass Notifcations versendet werden, wenn sich die Testseite ändert. Es wird vorgeschlagen, E-Mails zu versenden. Auch wurde vorgeschlagen, dass man beim Commit angeben können sollte, ob man sich so eine Notification überhaupt wünscht. Als Kritik wird angemerkt, dass so eine Erweiterung (Erweiterung der Pipe, Mailserver, Templates...) evtl. sehr aufwendig sein könnte, falls Gitlab so eine Funktionalität nicht bereits anbietet.
27. Es wird sich gewünscht, dass Abschreiben komplett unterbunden wird. Dazu müssten Vergeleiche für die implementierten Mehoden eingeführt werden. Es wird kritisiert, dass dies zum einen sehr aufwendig wäre und zum anderen auch bedacht werden muss, dass bei ähnlichen Aufgaben ähnliche oder gleiche Methoden entstehen.
28. Es wird sich gewünscht, dass mehr Funktionalitäten von Gitlabverwendet werden. Dazu wurde angemerkt, dass man dafür evtl. die Aufgabenstellungen erleichtern müsste, wobei dieser Einwand auch infrage gestellt wurde. Ein andere Einwand ist, dass man so Kenntnisse über Gitlab vorraussetzen können müsste und unklar ist, welche Funktionen sich genau gewünscht wurden.
29. Es wird sich gewünscht, dass Aufgaben ohne großen Arbeitsaufwand kontrolliert werden können. Dazu wurde angemerkt, dass dies eine vereinfachung der Aufgabenstellungen erfordern würde und evtl. nicht alle Aspekte richtig und komplett getestet werden könnten. Ein weiterer Kritikpunkt ist, dass evtl. nicht alle Anforderungen deutlich vermittelt weden können.
30. Es wird sich gewünscht, das zusammen mit der Aufgabe auch eine Musterlösung erzeugt wird. Es wird vorgeschlagen, dies mit Maschienenlernen und Tools zur automatischen Codegenerierung zu lösen. Es gibt Befürchtungen, dass sie sehr Fehleranfällig sein könnte oder dadurch die Variationsmöglichkeiten für die Aufgabenerstellung leiden könnte. 
31. Es wird sich gewünscht, dass jeder Teilnehmer eine komplett eigene Aufgabe erzeugt, die sich nur in ihrer Art und Schwierigkeit unterscheiden. Es wird kritisiert, dass dies sehr aufwendig sein würde. 
32. Es wird sich gewünscht, dass je nach Arbeitsfortschritt Hints/Tipps gegeben werden. Es wird kritisiert, dass dies einen sehr hochen Arbeitsaufwand bei dem Veranstalter Team erzeugen würde.
33. Es wird sich gewünscht, dass Bonuspunkte für schnelöle und fehlerfreie Abgaben vergeben werden. Es wurde aich vorgeschlagen, zu zählen, wie oft eine Aufgabe kontrolliert wurde. Dies wird aber dafür kritisiert, dass so Studierende bestraft werden, wenn sie die Aufgaben später macehn.
34. Es wird sich eine komplette Automatisierung des Feedbacks gewünscht. Es Vorschlag wurede ergänzt, dass die Studireden sich selbst eine manuelle Überprüfung wünschen könnten. Kritisiert wird der Vorschlag dafür, dass viele Sachen nicht komplett automatisiert werden können.

Mert...

46.	Das System soll es ermöglichen, Feedback zum gesamten Code zu geben.
    Das System soll es ermöglichen, Feedback zum gesamten Code zu erhalten.
47.	Das System soll eine Chatfunktion bieten, mit der auf direktem Weg Fragen zu den korrigierten Aufgaben gestellt werden können.
48.	Das System soll eine Chatfunktion für direkte Kommunikation über das Feedback bieten.
49.	Das UI des Systems soll für eine bessere Optik überarbeitet werden.
50.	Das UI des Systems soll einen Dark Mode bieten.
51.	Das System soll die Möglichkeit bieten, auch das Feedback auf die vorherigen Tests zu sehen. (wird z.Zt. mit dem neuen Test überschrieben)
52.	Das System soll es ermöglichen, auch zu bestandenen Tests Feedback zu geben.
    Das System soll es ermöglichen, auch zu bestandenen Tests Feedback zu erhalten. 
53.	Das System soll spontane Änderungen des Praktika-Konzepts unterbinden.
54.	Das System soll einen Link oder Button für den schnellen Zugriff auf die Testseite erhalten.
55.	Das System soll für häufig auftretende Fehler mehr Informationen bereitstellen.
56.	Das System soll alle Aufgaben automatisch prüfen und keine manuellen Reviews mehr benötigen.



## Kategorien

Anforderungen an das Divekit für den Stakeholder _Student:innen_, wurde im Rahmen der Kreativmethode _Walt Disney_ ermittelt. Die Methode ist gut geeignet um Leistungs- und Begeisterungsfaktoren zu ermitteln.


Kategorisieren in _Interface, Interaktion, Technik, Aufgaben, Usability, Responsibility_ vornehmen.

Im folgenden werden die einzelnen Wünsche zusammengetragen.





* Responsivity (schnellere Ergebnisse, Automatische Hinweise, automatische Korrektur für alles, Musterlösung bei bestandener Abgabe)
* Usability (bessere Feedback Seite, Feedback schon in der IDE, manuelle Prüfungswarteschlange, direkter Kontakt in Test seite)




















