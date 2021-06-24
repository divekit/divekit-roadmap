---
acronym: 6-3-5-No.1
type: literature reference
title: Ergebnisse_6-3-5-Methode-Workshop_Gruppe1
responsible: 
    - tza
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

Es soll ein Darkmode für das Divekit eingeführt werden. Zudem ein Optionsmenü mit weiteren Anpassungsmöglichkeiten der Oberfläche wie Themes.

Benutzerfreundliche Oberfläche wo bestandene Tests eingeklappt werden und nicht bestandene ausgeklappt bleiben. Anzeige der Betreuer, welche korrigiert haben, falls es Rückfragen gibt.

Zur Barrierefreiheit sollten Symbole statt roter und grüner Farbe verwendet werden.

Ein Loading indikator and den Test, um anzuzeigen, wenn diese noch nicht durchgelaufen sind.

Zeitangabe für Ergebnisse richtet sich nach lokaler Zeit des Users.

Manuelle Überprüfung extra kennzeichnen und mit Button ausstatten, sodass darüber die manuelle Überprüfung direkt angestoßen werden kann.

Notizenfeld, um sich nebenbei Fragen und Anmerkungen zu Aufgaben aufschreiben zu können.

Komplette Anzeige des Fehlers mit visueller Unterscheidung von Programmabsturz, Exceptions und falschem Wert.

Countdown bis zur Deadline.

Anzeige von News, wenn Professor dringende Anmerkungen zu einer Aufgabe machen möchte

**Schwerpunkt Interaktion:**

Feedback bekommen, auch wenn man besteht und Lösungsvorschläge was man noch verbessern soll oder direkt eine Musterlösung. Dabei sollten auch Screenshots und Kommentare zur eigenen Lösung gezeigt werden können.

Emailbenachrichtigung, sobald man die Manuelle Kontrolle eines Betreuers abgeschlossen ist und wenn man noch Aufgaben erledigen muss für die nächste Abgabe (Erinnerungsmail). Zudem Benachrichtigung, wenn Ergebnis zwar lange commited ist, aber noch nicht zur Überprüfung freigegeben wurde. Optional kann es über einen Discord Bot gelöst werden.

Feste Korrekturzeiten, sodass die Studenten wissen wann das Ergebnis kommt.

Benachrichtigung wenn Gesamtergebnis eines Tests feststeht und darin Info ob bestanden oder nicht.

Anstoß einer manuellen Kontrolle über Tag im Commit. Abgabe wandert dann in eine Warteschlange, aus dieser bei Änderungswünschen auch erstmal wieder rausgenommen werden kann. Nachricht wie viele Abgab noch vor einem dran sind mit der Kontrolle.

Ein Zeitfenster zeigt an, wann Betreuer Korrekturen vornehmen.

Bei Fehlschlägen von Tests genaue Fehlermeldungen.

Bei Härtefällen Rückmeldung mit Beispiellösung oder Hinweis auf Folien.


**Schwerpunkt Technik:**

Direkte Einbindung in Git. Test können dann per „git pull“ geholt werden. Das gesamte Projekt ist dann in einem Ordner.  Informationen zu dem bestandenen Test werden per Textdatei mitgeteilt.

Website nach jedem push updaten, um die Ergebnisse der Test direkt eingesehen werden können.

Anmeldung mit der CampusID anstatt der UUID, damit schneller eingeloggt werden kann.

Tests sollten auch in der eigenen Entwicklungsumgebung ausführbar sein (remote tests). Damit können Ergebnisse auch überprüft werden, ohne sie dafür jedes Mal erst hochladen zu müssen. 

Adminpanel, welche Test alle manuell sind und wie viele Tests einer Person noch fehlerhaft sind.

Einbindung eines Discord-Logins zur schnelleren Kontaktaufnahme mit Betreuern

Eine App mit der man Testseiten einsehen und verwalten kann. Dazu Zugriff auf Vorlesungen und Chat zu dem Modul. 

**Schwerpunkt Aufgaben:**

Unterscheidung der Aufgaben im Konzept und nicht nur der Wörter

Bonuspunkte über extra Aufgaben, besonders schnelles Abgeben, Vorstellung des Projekts in der Vorlesung, wenige Commits (kein rumprobieren) oder eine „Vorkontrolierung“ der Studenten von den Aufgaben ihrer Kommilitonen. Es wird markiert als studentisch überprüft und wird von den Betreuern noch einmal überprüft.

Neben Aufgabe Verlinkung der entsprechenden Videos der Vorlesung

FAQ und Hilfevideos für häufige Fehler bei einer Abgabe

Anzeige wie viele Studenten mit einer Aufgabe schon fertig sind und bei einem bestimmten Prozentsatz auch früheres freischalten der nächsten Aufgaben

Extraseite mit Statistiken zu den Aufgaben und den Lösungen, für Leute die sowas interessiert (wie viele wie schnell gelöst etc.) 

Teilpunkte für Lösungen

Wenn eine Abgabe im ersten Durchlauf funktioniert hat, bekommt man einen Freifahrtschein für weitere Meilensteine.

Aufgaben die man nicht komplett gelöst bekommen muss, um komplexere Aufgaben zu erlauben.

Bei jedem Meilenstein gleichen Kontrolleur oder im Falle eines Wechsels automatische Bereitstellung des Chatverlaufs  und der Verbesserungsvorschläge an den neuen Betreuer.

