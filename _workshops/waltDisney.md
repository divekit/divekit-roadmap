---
acronym: waltDisney
type: workshop
responsible: 
    - aha
    - cpo
    - hbu
    - psc
goals: Sammeln von Ideen für Weiterentwicklung des DiveKit aus Studenten-Sicht
date: 2021-05-19
time: 13:00
method: Walt Disney Methode
stakeholderRole: student
history:
    v1:
        date: 2021-06-01
        comment: Initially created
    v2:
        date: 2021-06-07
        comment: Added Ablauf and rough list of ideas
todo:
    - füllen       
---

## Ablauf

1. Begrüßung
2. Einführung (ca. 15 Minuten)
	1. Bereitstellung des Miroboards (https://miro.com/app/board/o9J_lER6fao=/)
	2. Vorstellung des DiveKit-Szenarios und
	3. Vorstellung der Methode _Walt-Disney_
		1. Die Rolle _Träumer_
		2. Die Rolle _Realist_
		3. Die Rolle _Kritiker_
3. Workshop (ca. 45 Minuten)
	1. Hineinversetzen in die Rolle _Träumer_ (ca. 15 Minuten)
	2. Hineinversetzen in die Rolle _Realist_ (ca. 15 Minuten)
	3. Hineinversetzen in die Rolle _Kritiker_ (ca. 15 Minuten)
4. Reflexion der Methode und der Ergebnisse (ca. 15 Minuten)
5. Feedback und Verabschiedung

## Liste der Idden/Vorschläge

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

13. Es wird sich gewünscht, Feedback direkt in der IDE anstatt erst im Browser zu sehen. Als Vorschlag wurde eine Helfer-Klasse oder die Kontaktaufnahme mit den Entwicklern der IDE genannt. Es wird gewarnt, dass die IDE evtl. nicht open-source sei oder dass mehrere IDEs supported werden müssten.

14. Es wird sich gewünscht, dass auch Diagramme automatisch korrigiert werden. Als Vorschlag wurde eine Bilderkennung zwischen Muster- und Studentenlösung genannt. Es wird gewarnt, dass es zu aufwändig sei und dass der Argumentationsspielraum für verschiedenen Lösungen verloren geht.

15. Es wird sich gewünscht, die Testseite in einer App zugänglich zu machen. Als Vorschlag wurde die Entwicklung auf Android und iOS oder die Cross-Platform Entwicklung einer App vorgeschlagen. Der Browser könnte auch als Anzeige verwendet werden. Es wird gewarnt, dass die Entwicklung der App viel Zeit und Geld kosten würde und die App evtl. sogar kaum benutzt werden könnte.

16. Es wird sich gewünscht, dass Studenten andere Studenten kontrollieren können um Bonuspunkte zu sammlen. Als Vorschlag wurde die Implementierung eines Belohnungs- und Reviewsystems genannt. Es wird gewarnt, dass Studenten falschen Feedbach geben könnten und nicht immer richtig korrigieren. Studenten könnten sich auch gegenseitig gut bewerten und das müsste dann wieder kontrolliert werden.

17. Es wird sich gewünscht, automatisch Tips bei falscher Lösung zu bekommen. Als Vorschlag wurde die Hinterlegung einer Musterlösung und die Ausgabe von Tips die zum jeweiligen Fehler passen genannt. Es wird gewarnt, dass damit ein trial-and-error Ansatz zur Lösung der hidden Tests führen kann.

18. Es wird sich gewünscht, Bonuspunkte für die schnelle Lösung der Aufgaben zu bekommen. Als Vorschlag werden 24/7 Arbeitsschichten der manuelle Kontrollen und ein geeignetes Belohnungssystem genannt. Es wird gewarnt, dass dieser Ansatz unfair gegenüber arbeitenden Studenten sei. Studenten mit Vorwissen haben evenfalls einen Vorteil. Die Codequalität könnte auch darunter leiden und im schlimmsten Fall könnte es einen Handel für die Lösungen der individualisierten Aufgaben geben (Echtgeld gegen Bonuspunkte).

19. Es wird sich gewünscht, die Ergebnisseite übersichtlicher zu machen. Als Vorschlag wird eine Überarbeitung der Testseite genannt. Es wird gewarnt, dass die Überarbeitung zu mehr Aufwand führt.

20. Es wird sich gewünscht, einsehbar zu machen, in welcher Warteschlagenposition man bei der manuelle Korrektur ist. Als Vorschlag wurde eine Anzeige der Position genannt. Es wird gewarnt, dass Kontrollen unterschiedliche lange dauern und durch verschiedene Arbeitszeiten der Mitarbeiter keine genaue Aussage dazu getroffen werden kann. Oft ist es auch so, dass am Ende eines Meilensteins viele Leute gleichzeitig abgeben und daruch ein Engpass entsteht.

21. Es wird sich gewünscht, die Aufgaben weiter zu idividualisieren und das DiveKit auf anderen Module zu erweitern. Als Vorschlag dazu die Erstellung von neuen Aufgaben passend zu den Module genannt. Es wird gewarnt, dass Dozenten nur schwer von dem System überzeugt werden können und eine Umstellung eine Katastrophe sein könnte (wie die Umstellung auf Online auf Grund von Corona - War eine absolute Katastrophe in 90% der Fächer).

22. Es wird sich gewünscht, ein Chatsystem auf der Testseite zu haben um direkt mit dem Betreuer in Kontakt zu treten. Als Vorschlag wurde dafür die Endingung einer Chatbox mit IRC Protokoll auf der Testseite genannt. Es wird gewarnt, dass es immer jemand für den Chat verfügbar sein muss.

23. Es wird sich gewünscht, eine Musterlösung angezeigt zu bekommen nachdem man die Aufgabe erfolgreich gelöst hat. Als Vorschlag wurde die Anfertigung einer individuellen Musterlösung durch den Beteuer genannt. Es wird gewarnt, dass dies zu hohem Zeitaufwand für den Betreuer führen würde.

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





## Miro-Workshops














