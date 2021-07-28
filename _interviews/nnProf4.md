---
acronym: nnProf4_interview
type: interview
responsible:
    - cpo
    - aha
stakeholder: nnProf4
date: 2021-05-10
duration: 00:54:22
location: BigBlueButton-Meeting
transcriptUrl:
history:
    v1:
        date: 2021-07-28
        comment: initially created
    v2:
        date: 2021-07-28
        comment: corrections
todo:
---
## Interviewleitfaden

### Teilnehmer:
* Interviewer: I
* Protokollant: P
* Interviewpartner: B

### Modalitäten
* Dauer: 1 Stunde
* Datum: 10. Mai 2021
* Uhrzeit: 10:00 Uhr
* Ort: BigBlueButton

### Ziel
Wünsche und Bedürfnisse an ein digital gestütztes, individualisiertes Lerntool

### Begrüßung/Eröffnung
* Abklären, ob Du oder Sie verwendet werden soll
* Vorstellung der Interviewer & des Moduls / Kurses / Zwecks 
* Einholen des Einverständnis für die Aufnahme bzw. das Anfertigen eines Transkriptes 
* Vorstellung des zu Interviewpartners


### Fragenkatalog
1. Welche Aufgabenarten stellen Sie Ihren Studenten in Ihren Veranstaltungen?

2. Welche digitalen Lernmethoden kommen bei Ihnen bereits zum Einsatz?

   2.1. Wie würden Sie deren Effektivität bewerten?

   2.2. Gibt es etwas, das Sie auch nach Corona beibehalten möchten?

   2.3. Gibt es etwas, das Sie sich noch zusätzlich vorstellen könnten, zu digitalisieren?

   2.4. Gibt es etwas, das Sie weiterhin ausschließlich nicht-digital machen möchten? 

3. Gibt es für Ihre Veranstaltungen jetzt schon das Interesse daran, viele individualisierte Übungsaufgaben bereitzustellen?

    3.1. Wenn ja, in welchem Umfang?

   3.2. Könnten Sie sich den Einsatz einer digitalen Toolunterstützung vorstellen, um ihre Aufgaben zu individualisieren?

4. Erfolgt die Kontrolle der Aufgaben bisher schon teil-automatisiert oder digital-unterstützt?

   4.1. Wünschen Sie sich eine stärkere Automatisierung oder bessere Hilfsmittel?

   4.1.1. Wenn ja, was könnten Sie sich vorstellen, noch zu automatisieren?

   4.1.2. Gibt es etwas, das Sie weiterhin ausschließlich manuell machen möchten, obwohl es automatisierbar wäre?

5. Welche möglichen Anwendungszwecke könnte eine digitale Toolunterstützung für Sie übernehmen?

   5.1. Wären Sie daran interessiert, sie in Ihren Veranstaltungen zu verwenden?

   5.2. Welche Kriterien müsste das Tool erfüllen, damit es für Ihren Einsatz interessant wäre? Was würde zum Ausschluss führen?

6. Sehen Sie mögliche Bedenken, Gefahren oder Probleme, die durch den Einsatz des DiveKits oder ähnlicher Software entstehen könnte?

7. Glauben Sie, dass Ihre Kolleginnen und Kollegen auch Interesse an einer Software wie DiveKit haben könnten?

8. Haben Sie sonstige Anmerkungen / Hinweise? Möchten Sie noch etwas Ergänzen? 


## Transkript
## [Transkript des Interviews](../sources/nnPro4_transkript.md)

## Ergebnisprotokoll

#### Frage 1: Welche Aufgabenarten stellen Sie Ihren Studenten in Ihren Veranstaltungen? [00:04:54]
* Programmieraufgaben (Java, Shell, PHP, usw.)
* Systemintegrationsaufgaben in höheren Semestern:
  * Virtuelle Maschinen aufsetzen
  * Vernetzen
  * Automatisieren
  * Datensicherung
  * Parser-Integration
  * Eine komplette Pipeline zusammenbauen im Semester

#### Frage 2: Welche digitalen Lernmethoden kommen bei Ihnen bereits zum Einsatz? [00:07:25]
* Infrastruktur: ILIAS, Big Blue Button, Livestream in Kombination mit Matrix-Server
* Von Anfang an Kommandozeile und Shell-Programmierung mit Git
* Git Hooks schreiben
* Automatisierte Prozessketten (z.B. Commit, Parser im Backend, automatischer Testcode)
* KEINE automatisierten Prüfungen

**Effektivität [00:11:41]:**
* Setup mit zwei Webcams und einem Monitor
  * Chat beobachten
  * Abgefilmte Tafel
  * Wacom-Tablet
* Veranstaltung in Kleingruppen (20 bis 30 Leute)
   * Veranstaltung beobachtbar abhalten
   * Offen für Gespräche
   * In Kleingruppen zusammensitzen
   * Funktioniert sehr gut
* Live-Streaming
  * Für größere Veranstaltungen
  * Mehr Input vom Professor
  * Verzögerung von 10 bis 15 Sekunden
  * Funktioniert auch recht gut, wenn Professor den hauptsächlichen Input macht
* Aufgezeichnete Videos
  * Wird oft von den Studierenden gewünscht
  * Wird sich meistens nicht angeschaut, von denjenigen, die sich es wünschen
* Interaktive klassische Lehrveranstaltungen vor Ort funktionieren am besten
  * Live Coding
* Digitale Umsetzung nimmt die Hemmschwellen, beim Über-die-Schulter-Schauen, kein Zu-nahe-Treten
  * Professor programmiert vor, Studierende programmieren nach
  * 3, 4 Leute coden zusammen
  * Am Ende Gespräch mit den Gruppen
* Vorbereitete Lernvideos
  * Funktionieren gut
  * Aufwand zum Vorbereiten ist sehr enorm
* Verteilen von Aufgabenzetteln
  * Funktioniert nicht so gut

**Nach Corona beibehalten [00:16:51]:**
* Gemeinsames Coding in Kleingruppen mit Jitsi/Big Blue Button
* Einzelgespräche mit Studierenden über digitale Räume

**Noch zusätzlich digitalisieren [00:18:19]:**
* Automatisierung von Prozessketten für das Selber-Üben
* Git und Co. stärker einsetzen

**Weiterhin ausschließlich nicht-digital [00:23:30]:**
* Veranstaltungen mit seminarischem Charakter
* Veranstaltung zur Technikfolgenabschätzung

#### Frage 3: Gibt es für Ihre Veranstaltungen jetzt schon das Interesse daran, viele individualisierte Übungsaufgaben bereitzustellen? [00:24:36]
* So wird bereits viel gearbeitet
* Aufgaben-Pool, der angepasst wird
* Script verwendet Accountname als Seed und generiert individuelle Aufgabenstellung

**Umfang [00:26:37]:** 
* Kollege hat komplette Veranstaltung mit dem individualisierten Lerntool gemacht:
  * Schwer, Aufgaben klausurtauglich zu machen
* Interviewpartner verwendet es nur in der Alltagspraxis
  * Es kann besprochen werden, wenn die Aufgaben nicht den richtigen Schwierigkeitsgrad haben             

**Digitale Toolunterstützung [00:27:51]:**
* wird bereits gemacht
* möchte lieber seine eigenen Scripte verwenden, statt einem fremden Tool
* Aufgabenpools von ILIAS zu behäbig
* Fertiges Tool könnte für Lehrende aus anderen Fachbereichen interessant sein

#### Frage 4: Erfolgt die Kontrolle der Aufgaben bisher schon teil-automatisiert oder digital-unterstützt? [00:31:18]
**Stärkere Automatisierung oder bessere Hilfsmittel gewünscht [00:31:42]:**
* Feedback zu Umsetzungen des Visitor Pattern gerne visualisiert als Graph
* War bisher schlecht umsetzbar

**Weiterhin ausschließlich manuell machen, obwohl automatisierbar [00:34:59]:**
* Wenn Noten vergeben werden sollen
* Professor mag Benotungen grundsätzlich nicht gerne
* Im Zweifel gerne mit Studierenden über Note diskutieren
* Wenn jemand etwas verstanden hat, kann er darüber reden

#### Frage 5: Welche möglichen Anwendungszwecke könnte eine digitale Toolunterstützung für Sie übernehmen? [00:36:22]
* Codewars: Wettbewerb, bei dem man zu bestimmten Aufgaben Lösungen entwickelt und diese gegen Tests laufen lässt, Punkte sammeln, Schweregrad frei bestimmbar
* Mag nicht dessen elitären Charakter
* In der Veranstaltung gerne als Variante mit weniger Wettbewerb, Gamification Coding

**Voraussetzungen oder Ausschlusskriterien [00:43:16]:**
* Wenn es nur Fremdlernkontrolle gäbe und keine Eigenkontrolle
  * Tool müsste anonym nutzbar sein
* Tool müsste "Orthogonal zu den Werkzeugen sein"
  * IDE frei wählbar, es wird keine aufgezwungen
  * Am besten mit einem eleganten GitLab

#### Frage 6: Sehen Sie mögliche Bedenken, Gefahren oder Probleme, die durch den Einsatz des DiveKits oder ähnlicher Software entstehen könnte? [00:43:16]
* Datenschutz
* Fokus wird zu sehr auf Überprüfbarkeit eingeschränkt, anspruchsvolle und komplexe Aufgaben werden vernachlässigt
  * Einem fehlt der Blick fürs große Ganze

#### Frage 7: Glauben Sie, dass Ihre Kolleginnen und Kollegen auch Interesse an einer Software wie DiveKit haben könnten? [00:46:05]
* Professor baut solche Sachen gerne für sich selber, kann sich aber vorstellen, dass andere Lehrende Interesse am Tool haben könnten

#### Frage 8: Haben Sie sonstige Anmerkungen / Hinweise? Möchten Sie noch etwas Ergänzen? [00:49:04]
* Software muss Open Source sein, damit sie überhaupt infrage käme (00:48:06)
* Um eine richtige Entscheidung treffen zu können, müsste man das Tool erstmal in Ausführung sehen
* Möchte nach Corona mehr Kooperationen machen