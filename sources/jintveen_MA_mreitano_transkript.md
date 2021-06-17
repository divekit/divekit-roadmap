---
acronym: mreitano
type: literature reference
title: Interview Transkript Reitano
responsible: 
    - ako
    - kru
    - duz
publisher: none
source_url: none
history:
    v1:
        date: 2021-06-15
        comment: initially created

---

## Transkript des Interviews mit Marco Reitano 

Interviewpartner: Marco Reitano
Datum: 21.01.2021

## Inhalt

I: [00:02] Also wir fangen jetzt erst einmal ein bisschen auf einer höheren Ebene an. Was
sind deiner Meinung nach die wichtigsten Werkzeuge, die man braucht, wenn man jetzt
modernes Coding betreiben will?

B: [00:30] Auf jeden Fall Git, da gibt es mittlerweile keinen Weg drum herum. Irgendeine
Form von IDE und damit schließe ich eigentlich so ziemlich jede mit ein, die es gibt. Es
könnte z.B. Vim, VS Code, IntelliJ oder Eclipse sein, aber eben eine, in der man sich auskennt und in der man fluide ist. Für Programmieranfänger eignen sich meiner Meinung
nach eher leichtgewichtigere IDEs wie VS Code, da IDEs mit großem Funktionsumfang
oft eher verwirren und ablenken. Und wenn es nicht nur um Eigenentwicklungen zuhause
alleine geht: In irgendeiner Form Software Tools, die Teamarbeit unterstützen, also sowas
wie ein Kanban Board. Dann auch Absprache Tools im Sinne von einem Miró Board oder
einem Trello Board. Das hängt dann immer stark davon ab, wie das Team aufgebaut ist
und wie die Teamarbeit aussieht. Wenn das nicht vor Ort ist und kein Whiteboard zur
Verfügung steht, braucht man eben solche Tools. Es kommt immer auf das Feld an, in dem
man sich bewegt, beispielsweise Docker als grundlegendes Tool in der Backendentwicklung.

I: [02:02] Ich hätte da nochmal eine speziellere Frage, du hattest ja auch Git erwähnt.
Würdest du es eher bevorzugen, wenn die Leute Git auch von Anfang an über die Funktionen der IDE nutzen oder sollten sie das lieber über die Konsole machen?

B: [02:20] Ich habe es bis jetzt immer so gemacht, das auf jeden Fall in der Konsole beizubringen. Was sie später machen ist mir egal. Aber ich habe immer die Erfahrung gemacht,
dass es besser ist, das den Leuten in der Konsole beizubringen, weil die Konzepte, die dahinterstecken, klarer abgetrennt sind. Also es gibt in der IDE Tools, die teilweise allein
schon falsche Begrifflichkeiten nutzen. Also da hast du nicht gepusht, sondern Git Sync
ausgeführt. Und die IDEs verstecken teilweise Dinge. Also da muss man dann eben nicht
mehr Adden, Commiten und Pushen, sondern das wird mit einem Tastendruck für einen
erledigt. Und so fällt es den Studenten dann schwerer, die einzelnen Konzepte dahinter
zu verstehen. Und die Konzepte muss man verstehen, um nachher kompliziertere Aufgabenstellungen erledigen zu können. Ich denke da beispielsweise an Mergekonflikte oder an
das Zurückrollen auf einen alten Stand.

I: [03:23] Jetzt nochmal eine generelle Frage, und zwar: Was macht für dich modernes
Coding aus?

B: [03:43] Agilität, wenn man das unter Coding verstehen würde. Klein anfangen, sich
selbst überprüfen, iterativ arbeiten, kurze Feedback Loops haben. Ich antworte vielleicht
auch mit dem Gegenteil: Nicht modernes Coding heißt, sehr lange Dinge tun, die im Verborgenen liegen und dann am Ende in den meisten Fällen mit einem falschen Ergebnis
kommen. Und modernes Coding und moderne Entwicklung muss sein, dass man möglichst
schnell zu etwas kommt, was überprüfbar ist. Gleichzeitig muss auf eine hohe Qualität
geachtet werden und technische Schuld vermieden werden. Themen wie Refactoring und
TDD werden dann relevant. Modern bedeutet auch, dass moderne Softwareentwicklung
immer mehr ein People Problem und nicht ein technisches Problem ist. Also moderne
Softwareentwicklung hat immer mehr mit Kommunikation und Teamarbeit zu tun und
nicht nur mit der Frage, wie etwas technisch umzusetzen ist.

I: [05:47] Was fallen dir jetzt so spontan für Programmiersprachen ein, die viele Paradigmen vereinen, welche als modern gelten?

B: [06:50] Ich würde z.B. nicht JavaScript sagen. Wenn überhaupt, dann TypeScript, weil
JavaScript ist zwar modern, verachtet aber alles was davor war sozusagen. Also im Endeffekt unterstützen alle Programmiersprachen alles. Es ist eben immer nur eine Sache von
Syntactic Sugar und hängt mit der Frage zusammen, wie viel Code ich brauche, um etwas
umzusetzen.

I: [07:56] Was würdest du in der Lehre höher priorisieren: Ein Fokus auf weit verbreitete Programmiersprachen oder ein Fokus auf Programmiersprachen, welche auf modernen
Paradigmen aufbauen und das Potential aufweisen, auch einmal eine breite Anwendung
zu finden?

B: [08:11] Es muss relativ weit verbreitet sein, denn es sollte wie z.B. bei Java viel Material vorhanden sein, welches über das bereitgestellte Material von Dozenten hinausgeht.
Wenn man Java in Google eingibt, findet man eine Menge relativ hochqualitative Tutorials, Reference Guides und so weiter. Was JavaScript angeht, ist das mehr als ein großer
Schwachpunkt, weil bei JavaScript findet man auch viel, was qualitativ extrem durchmischt ist. Das reicht von absoluten Bad-Smell Anleitungen bis hin zu hoch qualitativem
Material. Deswegen weit verbreitet und relativ etabliert finde ich gut, weil es sich so ein
bisschen festgelegt hat, was denn jetzt gute Programmierung in dieser Programmiersprache ist und was nicht. Gleichzeitig aber auch modern, weil bestimmte Aspekte vielleicht
in modernen Programmiersprachen klarer umgesetzt sind. Also wenn man z.B. funktional
Programmieren beibringen möchte, würde ich nicht Java nehmen. Und das dritte, was eigentlich dazukommt, ist, dass die Programmiersprache bestimmte Prinzipien relativ klar
machen muss. Also ich kann z.B. keine Objektorientierung an JavaScript erklären, weil
JavaScript es sozusagen erlaubt, es falsch zu machen. Dadurch werden die Konzepte nicht
so klar und können nicht so klar rübergebracht werden. Das heißt, bestimmte Konzepte
müssen relativ klar unterstützt werden und so angeboten werden, dass es nicht fünf verschiedene Wege gibt, das Konzept zu umgehen und dadurch zu verfälschen.

I: [10:46] Vor allem am Anfang wissen Studenten ja noch nicht, wie man auch sauberen
Code schreibt. Wie kann man die Studenten denn dazu bringen, dass sie bestimmte Richtlinien einhalten, welche zu sauberem Code führen?

B: [11:09] Erstmal sollte man möglichst früh möglichst viel Feedback geben und die Studenten auch möglichst früh sauber arbeiten lassen. Man sollte also nicht dem Gedanken
verfallen: Ach, wir lassen die jetzt einfach nur machen und lassen die denken, dass es so
okay ist. Sondern dass man, wenn man die machen lässt und unsauber arbeiten lässt,
dann folgenden Hinweis mitgibt: Was ihr da macht ist nicht gut, aber das ist okay, weil
ihr es eben noch nicht besser wisst. Man sollte die Studenten auch möglichst früh den
Schmerz von schlechtem Code spüren lassen. Das hat bei uns in CE01 gut funktioniert.
Da haben wir die Leute erst einmal Spaghetti Code schreiben lassen und haben diesen
Code in einem extra Modul namens Clean Code nochmal aufgegriffen, um zu zeigen, wie
schlecht der Code eigentlich war, den sie da geschrieben haben, weil sie nach einem halben
Jahr überhaupt nichts mehr verstanden haben. Also an einigen Stellen muss man sie auch
den Schmerz spüren lassen und in die Probleme reinlaufen lassen, damit sie verstehen,
warum denn jetzt Clean Code zum Beispiel so wichtig ist.

I: [13:00] Du sagtest ja auch gerade, dass man möglichst früh den Leuten beibringen soll,
sauberen Code zu schreiben. Kennst du da praktikable Wege, wie man das in Übungsaufgaben auch erzwingen kann?

B: [13:47] Also alles was funktional ist, kann man automatisiert z.B. über Unit Tests
relativ gut einfach überprüfen. Problematisch wird es dann beispielsweise bei Variablenbenennungen, wenn es darum geht, ob ein Name intuitiv ist oder nicht. Das kann man
schlecht automatisch überprüfen. Deswegen muss man da wahrscheinlich auf Peer-Review
Taktiken zurückgreifen. Der Peer bewertet dann quasi nicht den Code und nicht funktional, sondern die Verständlichkeit des Codes. Also man simuliert sozusagen das, was
passieren würde, wenn jemand den Code abgibt in einer großen Firma oder ähnlichem.
Man könnte auch Übungen zu Refactoring im Live Coding machen, also dass man ihnen
vormacht, wie aus unleserlichem Code leserlicher Code wird.

I: [15:23] Jetzt würde ich mal in Richtung Domain Driven Design übergehen. Domain Driven Design stellt eine Herangehensweise zur Modellierung von komplexer Software dar,
wobei sich dieser Ansatz stark an der zu modellierenden Fachlichkeit orientiert. Was muss
man bei der Erstellung von Übungsaufgaben beachten, welche diesen Ansatz lehren sollen,
obwohl diese meist ein geringes Maß an Komplexität aufweisen?

B: [16:18] Es kommt darauf an, welchen Teil von Domain Driven Design man beibringen
möchte. Wenn es um die strategischen Entscheidungen geht, dann braucht man eine gewisse Grundmenge an Domäne. Die Domäne muss breit genug sein, damit man überhaupt
irgendwie Teile davon identifizieren kann. Ich glaube aber die taktischen Aspekte, also
z.B. Entities oder Value Objects, kann man auch beibringen, indem man in relativ kleinen Domänen unterwegs ist. Man muss nur Zeit darauf verwenden, zu iterieren und immer
wieder sich darauf einlassen, Kleinigkeiten mehrfach anzumerken und dabei pedantisch
zu sein. Zudem basiert DDD ja auch auf anderen Konzepten wie z.B. Objektorientierung.
Diese sollte man etwas sauberer und durchdachter beibringen, weil Domain Driven Design
ja eigentlich nur sehr saubere Objektorientierung ist. In der Lehre beobachte ich auch,
dass Studenten irgendwie immer nur in Daten und nicht in Verhalten denken. Das ist
sehr problematisch für die Objektorientierung und deswegen auch sehr problematisch für
Domain Driven Design.

I: [19:19] Ich würde jetzt nochmal zu einem anderen Bereich übergehen, und zwar in
Richtung Kooperation, Gruppenarbeit und Einzelarbeit. Würdest du eine Bearbeitung
von Programmieraufgaben eher in Gruppen oder in Einzelarbeit bevorzugen, wenn diese
dazu gedacht sind, bewertet zu werden?

B: [19:50] Generell gesprochen, auf jeden Fall in der Gruppe, weil das das einzig Realistische ist. Es gibt heutzutage kaum noch Probleme, welches man alleine sozusagen lösen
kann, dazu ist es einfach zu komplex geworden. Ich möchte nicht nur einfach Einzelarbeit
machen, weil ich diese dann besser bewerten kann. Ich möchte reale Dinge beibringen und
deswegen bevorzuge ich immer Gruppenarbeit. Und wenn man sozusagen einzelne Noten
haben möchte, dann muss man noch einen individuellen Anteil mit einbringen. Vielleicht
spricht man mit den einzelnen Personen dann nochmal über den Code und lässt sich ein
bisschen was erklären oder man beobachtet das Coding. Wenn man Studierenden allerdings gerade frisch das Programmieren beibringt, dann würde ich Einzelarbeit eher sehen.
Weil das muss eben jeder können und da bringt gegenseitiges Unterhalten und Kommunizieren nicht so viel. Das muss jeder für sich selber irgendwie verstehen und diesen Weg
kann man auch nicht so richtig erklären. Dazu muss man sich konzentrieren und selber
damit auseinandersetzen.

I: [22:46] Die Arbeitstechnik Pair-Programming beschreibt ein Verfahren, bei dem zwei
Personen abwechselnd jeweils Programmieren und Feedback geben. Welche besonderen
Vorteile siehst du hier in Abgrenzung zur Gruppenarbeit?

B: [22:51] Ich würde die Kombination aus Gruppenarbeit und Pair-Programming sehen.
Also so wie es auch in der Realität passiert. Ich habe dann irgendwie kleinere Teams, die
sich um bestimmte Bereiche kümmern. Häufig wird dann auch innerhalb dieser Gruppe
nochmal Pair-Programming betrieben. Die Gruppenarbeit hat eher so etwas höhere großflächigere Vorteile, dass man sich eben Arbeit aufteilen und diese parallelisieren kann.
Dazu kommt noch, dass man über bestimmte Konzepte während Planungen diskutieren kann und Lösungen aushandelt. Beim Pair-Programming geht es dann weniger um
die Architektur-Ebene, sondern mehr um die Code-Ebene. Pair-Programming löst eigentlich einfach nur das Problem, dass Programmierer Menschen sind und manchmal Fehler
machen und deswegen ist es eben besser, mit vier Augen anstatt mit zwei Augen zu programmieren. Außerdem kann das Abwechseln auch mal angenehm sein, wenn man gerade
nicht weiterkommt.

I: [25:26] Die Lernenden brauchen ja immer eine gewisse Motivation, um überhaupt
Übungsaufgaben zu bearbeiten. Um Lernenden den nötigen Druck bei der Aufgabenbearbeitung zu machen, gibt es verschiedene Ansätze. Zum einen kann Druck durch Noten
und Aufgabenindividualisierung geschaffen werden und zum anderen kann ein motivierendes Lernklima schon ausreichen. Unter welchen Umständen sollte deiner Meinung nach
welcher Ansatz bevorzugt werden?

B: [26:45] Ich glaube, dass die meisten Studenten anfänglich intrinsisch motiviert sind,
weil sie sich höchstwahrscheinlich aus einem Grund für Informatik entschieden haben.
Man muss eigentlich mehr darauf achten, diese intrinsische Motivation nicht zu zerstören.
Und ich glaube, dass es häufig der Fall ist, dass diese intrinsische Motivation zerstört wird,
indem z.B. die Arbeit der Studenten nicht ernst genommen wird oder ihnen widersprüchliches Feedback gegeben wird. Ich glaube Studenten kommen dann in so eine Situation,
dass sie nicht mehr motiviert sind, obwohl sie motiviert waren, weil sie merken, dass die
Arbeit, die sie reinstecken, für sie nicht lohnend oder erfüllend ist. Und wenn es so weit gekommen ist, dann sind auch Lehrende ganz oft der Meinung, dass sie mithilfe von Noten,
Deadlines oder Meilensteinen extrinsisch motivieren müssen. Manchmal schlägt bei den
Lehrenden auch eine gewisse Arroganz durch, in dem Sinne, dass die Lehrenden ja nichts
falsch machen und der Fehler bei den Studenten liegen muss. Oft wird nicht reflektiert,
das man als Lehrender vielleicht selber irgendwie an der Art des Bewertens oder an der
Art des Beibringens arbeiten muss, um die intrinsische Motivation zu erhalten. Wichtig
dabei ist eben, dass man als Lehrender den Studenten nichts Missverständliches oder zu
stark vereinfacht erzählt. Sonst läuft man Gefahr, dass wenn die Studenten Google aufmachen, dass sie dann andere Aussagen zu diesem Thema finden, die an der Sinnhaftigkeit
der Vorlesung oder Übung zweifeln lassen. Wenn sie etwas richtig machen, müssen sie
das auch relativ früh und eindeutig gesagt bekommen. Wenn man noch in die Richtung
Constructive Alignment geht, dann muss klar sein, was geprüft wird und was verlangt
wird. Um ein bisschen mehr in deine Richtung zu gehen: Man braucht kurze Feedback
Zyklen, schnelles Feedback z.B. mit Unit Tests, die automatisiert passieren können. Genau dadurch ist schon ausgeschlossen, dass sie mehrere Meinungen bekommen, denn die
Wahrheit liegt im Code. Entweder ist ein Test grün oder rot, da gibt es keine zwei Meinungen drüber.

I: [30:46] Wenn diese intrinsische Motivation jetzt aber doch nicht vorliegt, gibt es ja trotzdem verschiedene Möglichkeiten, wie man den Einzelnen dazu bewegt, dass er sich auch
mit der Aufgabe beschäftigt und nicht einfach nur z.B. Lösungen kopiert. Eine Möglichkeit
wäre natürlich, dass man Individualisierung betreibt. Was für Individualisierungsmethoden kennst du, mit denen man Aufgaben individualisieren kann, sodass eben das Kopieren
von Lösungen nicht mehr so einfach ist?

B: [31:24] Was ich aus meinem Studium her kenne, sind so etwas wie Varianten A und
B bei Klausuren, sodass ein Ablesen oder Abschreiben nicht möglich ist. Wenn es eher
um algorithmische Belange geht, kann man relativ einfach nur die Testdaten verändern.
Komplexer wird es dann, wenn man auch semantisch individualisiert, also dass man den
Kontext und die Domäne ändert und dadurch individualisiert. Das ist allerdings mehr
Aufwand und braucht ein Tooling. Wenn es aber darum geht, konkret zu testen, ob jemand etwas verstanden hat oder nicht, dann muss man in wirkliche Fachgespräche gehen
und nachhaken. Dies würde aber eher in Richtung Prüfungen gehen. Wir haben ja eben
über Motivation gesprochen, die wahrscheinlich früher passieren sollte und nicht erst in
der Prüfung. Da ist dann wahrscheinlich eher eine Individualisierung nötig oder möglich.

I: [33:28] Was wäre aus deiner Sicht wichtiger: Dass man einen sehr hohen Grad an Individualisierung hat oder dass man mehr Fokus legt auf die Geschichte, die den Aufgabenkontext bestimmt?

B: [34:29] Ich würde sagen, die Geschichte ist wichtiger. Also wenn es um Domain Driven
Design geht, dann bestimmt ja die Domäne und der Kontext wirklich das, was schlussendlich im Code steht. Und wenn man nur um der Individualisierung Willen diese Geschichte
und diese Domäne irgendwie unlogisch macht, dann verfehlt man sozusagen das Ziel. Man
nimmt dann den Studenten wirklich die Chance, ihre Alltagserfahrungen zu nutzen, um
daraus zu lernen und in Code zu überführen. Deswegen würde ich sagen, die Story darf
nicht verfälscht werden.

I: [35:24] Würdest du das anders sehen, wenn man jetzt mal an Programmieraufgaben für
Anfänger denkt beziehungsweise an den ersten Programmierkurs?

B: [35:42] Ich glaube, ich würde den ersten Programmierkurs relativ unabhängig von der
Domäne gestalten. Deswegen würde sich mir da die Frage gar nicht stellen. Zu Beginn
sind die Leute schon genug mit den grundlegenden Programmierkonzepten beschäftigt,
sodass man die Domäne erst einmal außen vor lassen sollte. Bei Code and Context hat es
gut funktioniert, nicht zu individualisieren, weil es jeder selber machen musste. Trotzdem
sind die Studenten teilweise an einigen Problemen gescheitert und dann sind sie in den
Austausch gekommen und haben sich gegenseitig geholfen. Das wäre dann ein Softskill,
den sie schon beim ersten Kurs lernen. Deswegen ist es an der Stelle gar nicht so wichtig,
dass das jeder selber gemacht hat, sondern einfach nur beteiligt war an der Lösungsfindung.

I: [38:32] Was wäre da deine Meinung zu abweichenden Schwierigkeitsgraden, die entstehen können, wenn man individualisiert?

B: [38:56] Ich glaube, das ist ein Punkt, auf dem man sehr stark achten muss, dass das
eben nicht zu sehr auseinander läuft bei der Individualisierung. Ich glaube, das lässt sich
aber manchmal nicht vermeiden, indem z.B. einfach bestimmte Kombinationen von Domänenobjekten entstehen, die nicht ganz so einleuchtend sind wie andere. An der Stelle
sollte man nochmal die Möglichkeit geben, dass da nochmal jemand drauf schaut. Dann
können eben solche schwierigen Kombinationen erkannt werden und dann kann z.B. eine
bessere Note gegeben werden.

I: [39:58] Wie viel mehr Aufwand würdest du persönlich investieren, um solche Aufgaben
zu erstellen, die auch individualisiert werden können?

B: [40:26] Also ich kann dir keine genaue Zahl sagen, aber ich glaube, ich wäre bereit,
sehr viel Arbeit reinzustecken, weil ich glaube, dass sich das auf lange Sicht lohnen wird.
Also die Individualisierung wird trotzdem irgendwann passieren. Ich höre immer wieder,
dass Prüfungen neu gestellt werden müssen, weil man bestimmte Aufgaben ja schon in
der letzten Klausur oder im Praktikum schon hatte. Das waren immer Argumente dafür,
dass eine Klausur neu geschrieben werden musste, sich neue Praktikumsaufgaben überlegt werden mussten und so weiter. Das ist eben auch eine Art der Individualisierung, nur
verteilt über mehrere Semester und Jahre. Und wenn man dann einmal am Anfang relativ
viel Arbeit reinsteckt, hat man sich das dann am Ende vielleicht gespart. Man muss es
vielleicht noch immer überprüfen, ausbauen und verbessern, aber man schmeißt weniger
weg.

I: [41:55] Ich würde jetzt mal in Richtung Automatisierung übergehen. Was muss eine
Übungsaufgabe für Eigenschaften aufweisen, damit man diese auch automatisch überprüfen kann?

B: [42:22] Einfach überprüfbar sind in den meisten Fällen nur funktionale Aspekte, wenn
es nur um reine Unit Tests geht. Wenn es um Architektonische Aspekte geht, wird es schon
schwieriger, weil bei architektonischen Aufgabenstellungen gibt es nicht unbedingt immer
eine Lösung, die richtig ist. Außer man verkauft das den Leuten so, was dann an sich
schon relativ schwierig ist. Also wenn man Domain Driven Design macht, dann kann es
z.B. fünf Domänenmodelle geben, die alle unterschiedlich sind. Manche sind besser, manche sind schlechter, aber grundlegend ist keine davon falsch, sondern einfach nur anders.
Und da wird es problematisch mit dem Überprüfen. Man müsste sich alle Kombinationen,
die halbwegs sinnvoll sind, überlegen und diese abprüfen. Das heißt, bei architektonischen
Themen wird es dann schon wieder schwieriger. Außer man gibt denen sehr starke Leitplanken dahingehend, was sie machen sollen und was nicht. Das ist im ersten Moment
vielleicht eine gute Empfehlung, aber wir sind im Software Design und Design heißt, es
gibt nicht einfach nur eine richtige Lösung gibt. Außer man ist bei dem funktionalen, wo
eben relativ klar definiert ist, 1+1 muss 2 ergeben. Also wenn man in die architektonische
Richtung gehen möchte, dann muss man diese Regeln relativ klar formulieren und nach
meiner Ansicht aber auch dazu sagen, dass diese klar formulierten Regeln manchmal nur
eine starke Empfehlung sind und deshalb nicht immer an jeder Stelle auch zutreffend sind.
Also ich könnte mir z.B. durchaus vorstellen, dass es an einer Stelle manchmal auch eine
Bidirektionale Beziehung sein darf aus bestimmten Gründen. Und wenn man das durch
einen Test ausschließt, obwohl ein Student eine gute Begründung hat, dann sollte man
den nicht einfach bestrafen.

I: [45:20] Hast du Ideen, wie Übungsaufgaben sowohl automatisch überprüfbar wären als
auch mit einer gewissen Freiheit in der Aufgabenbearbeitung zu lösen wären?

B: [45:24] Man muss sich erst einmal selber relativ klar werden, was jetzt feste Gesetze
sind, die nicht gebrochen werden dürfen und was eher Empfehlungen sind, die eventuell
situationsabhängig sind. Wenn man Schichten Architektur macht, ist es z.B. eine feste
Regel, dass ich Schichten beim Zugriff nicht überspringen darf. Das kann man leicht überprüfen. Anders ist es bei bidirektionalen Beziehungen im DDD, von denen meist stark
abgeraten wird, aber das ist kein ultimatives Gesetz. Das heißt, ich würde sagen, man
muss sich als Dozent oder auch als Softwareentwickler allgemein sehr stark überlegen,
ob das jetzt etwas ist, was auf keinen Fall gebrochen werden kann oder einfach nur eine
Empfehlung ist. Also man kann auch automatische Tests machen, welche ein bisschen
Kreativität zulassen. Die werden eben nur unglaublich komplex zu schreiben. Also nehmen wir mal an, man überprüft, ob eine Klasse sinnvoll benannt ist. Man kann einfach
überprüfen, ob die Klasse Car heißt oder man kann auch Fuzzy Überprüfung machen.
Kommt z.B. irgendwo das Wort Car vor und kommt auf keinen Fall das Wort Auto vor,
weil das deutsch wäre. Also man kann diese Überprüfung breiter anlegen und sozusagen
Kreativität voraussehen, aber das wird unglaublich aufwendig.

I: [47:53] Ich würde jetzt nochmal zu Tools übergehen. Hast du schon mal in der praxisorientierten Lehre Tools zur Aufgabenindividualisierung angewendet und was hast du da
für Erfahrungen gemacht?

B: [48:13] Nein, habe ich bisher noch nicht.

I: [48:41] Nochmal eine Frage zu automatischer Aufgabenüberprüfung mittels Tools. Inwieweit denkst du, kann Feedback von automatischen Aufgabenkorrekturen das Feedback
von manuell korrigierenden Lehrenden ersetzen?

B: [49:01] Bestimmte Bereiche lassen sich gut überprüfen, also alles, was funktional ist.
Teilweise lassen sich auch nicht funktionale Aspekte überprüfen. In der Algorithmik könnte man z.B. mithilfe der O-Notation das Laufzeitverhalten von verschiedenen Ansätzen
überprüfen und so entscheiden, ob auf Basis der richtigen Datenstrukturen die richtige Lösungsstrategie ausgewählt wurde. Das wird dann aber auch schon wieder aufwendig, denn
dann muss man irgendwie 1000 Durchläufe machen und den Mittelwert bilden und dann
auch überprüfen, dass der Server nicht gerade auf Volllast ist. Sobald es aber um Design,
um Architektur, um solche Sachen geht, dann sollte man auch mal jemand menschlichen
drüber schauen lassen, denn ich glaube, das ist nicht immer komplett automatisiert überprüfbar.

I: [51:10] Wenn man Studenten Übungsaufgaben geben will, dann muss man diese auf
irgendeine Art verteilen und vielleicht auch Lösungen einsammeln. Mit welchen Plattformen hast du Erfahrungen gemacht, wo sich eben das realisieren lässt?

B: [51:43] Also für Abgaben ist glaube ich Git das Beste, denn es ist versioniert und wenn
man es richtig einstellt, dann weiß man auf jeden Fall nicht nur, wer es am Ende rechtzeitig hochgeladen hat, sondern man kennt auch die Zwischenstände. Man weiß also, wie
der Student zur Lösung gekommen ist. Bei Mathematikklausuren schreibt man ja auch
nicht nur die Lösung hin, sondern auch den Weg. Verteilen kann man auch über Git, da
kommt es aber auf die Art der Aufgaben an. Mit Unit Tests versehene Aufgaben würde
ich über Git verteilen, aber wenn es z.B. um komplexere Domänen geht, werden auch andere (visuelle) Darstellungsformen nötig, die auf einer Website oder in einem Wiki besser
aufgehoben sind.

I: [52:45] Dann nochmal ein letztes Thema, und zwar Feedback und Beratung. Du hast
ja auch mehrmals erwähnt, dass Feedback nach wie vor wichtig ist, auch wenn man automatische Mechanismen mit integriert. Was hältst du von modernen Messengern als
Kommunikationsplattform zwischen Lehrenden und Lernenden?

B: [53:23] Gut und wichtig, weil es die Feedback Zyklen kleiner macht. Dazu kommt noch,
dass sich bestimmte Arten der Kommunikation für verschiedene Themen besser eignen
als für andere. Man kann z.B. Feedback über E-Mail geben, das dauert allerdings relativ
lange, sodass die Kommunikation und das Feedback einfach nicht so direkt sind. Wenn
man diese Richtung betrachtet, gibt es eine relativ klare Hierarchie, welche Kommunikationsart sich eignet, wenn man bestimmte Feedback Geschwindigkeiten haben will. Das
Beste ist face to face Kommunikation, vor dem Code sitzen und mit dem Studenten zusammen durchgehen, was ist gut und was ist falsch. Gerade jetzt funktioniert das nicht.
Und die nächstbessere Möglichkeit ist sozusagen dann im Videochat, weil dann eben auch
Mimik dabei ist. Dann kommt die Möglichkeit von irgendetwas Verbalem, also direkte
Kommunikation verbal über Voice Chats über z.B. Zoom oder Discord. Die nächste Möglichkeit ist dann sozusagen Instant Messaging, also textuell, aber dann sehr direkt, sodass
direkt und schnelle geantwortet wird. Das ist auf jeden Fall besser als Kommunikation
über E-Mail.