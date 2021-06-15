---
acronym: ckohls
type: literature reference
title: Interview Transkript Kohls
responsible: 
    - ako
publisher: none
source_url: none
history:
    v1:
        date: 2021-06-15
        comment: initially created

---

## Transkript des Interviews mit Prof. Dr. Christian Kohls

Interviewpartner: Prof. Dr. Christian Kohls
Datum: 18.12.2

## Inhalt

I: [00:00] Zuerst einmal hätte ich eine sehr generelle Frage. Ein bisschen von oben drauf
geschaut, was findest du sind die wichtigsten Werkzeuge, die man braucht, wenn man
modernes Coding betreiben will?

B: [00:22] Natürlich auf alle Fälle eine integrierte Entwicklungsumgebung kennenlernen,
im besten Fall auch mal zwei. Ich persönlich würde IntelliJ bevorzugen. Nicht nur, weil
es Android unterstützt, sondern weil die von JetBrains einfach richtig gut sind. Eclipse
ist auch ok, aber eben doch auch recht schwerfällig. Wenn man modern programmieren
möchte, sollte man IntelliJ mal kennengelernt haben. Wenn man diese Entwicklungsumgebungen kennenlernt, muss man aber noch darauf eingehen, dass da ja viele Tools noch
integriert sind, d. h. der Debugger wird von vielen Studierenden gar nicht mehr genutzt
und auch da muss man als Student lernen, damit effektiv umzugehen. Auch die Building
Tools sollte man verstehen. Und man muss eben auch verstehen, wie man visuelle Oberflächen baut, Libraries einbindet, diese ganzen Sachen muss man einmal gemacht haben.
Dann natürlich Versionierung, dass man mit Git einmal gearbeitet hat. Dann sollte man
im späteren Verlauf des Studiums auch Projektmanagement kennengelernt haben, ob das
jetzt mit Trello, Miró oder Jira ist, spielt keine Rolle. Aber irgendwie müsste man es mal
kennengelernt haben oder zumindest irgendwo einen Einblick in ein Backlog mit Features
gehabt haben, die man abarbeiten muss. Und man sollte aus meiner Sicht auch einmal
gelernt haben, wie man Klassendiagramme ordentlich skizziert. Ich finde Skizzen immer
besser, als alles formal darzustellen, weil es andere formale Notationsformen gibt, die dafür besser geeignet sind. Aber die Strukturdiagramme, die muss man irgendwo zeichnen
können, entweder mit Online Werkzeugen oder mit Visio, meinetwegen auch Powerpoint.
Auch das geht, wenn ein Student keine Tools zur Verfügung hat. Aber man muss eben
sowas kennengelernt haben.

I: [02:33] Du hattest eben Git erwähnt. Meinst du, es reicht, wenn man einfach sagt, benutzt Git mal über die IDE und die Magie dahinter sehen die Studenten dann gar nicht
oder bist du der Meinung, man sollte vor allem am Anfang auch sagen, nimmt mal die
Konsole und vielleicht können die Studenten dann die Funktionsweise auch besser durchdringen?

B: [02:53] Ja, ich glaube, man muss beides haben. Also vielleicht ist es zu Anfang ohne
die Konsole gut. Ich habe früher die Konsole bei der Versionsverwaltung nicht so gerne
gehabt, aber man muss das, glaube ich, einmal gesehen haben, um das zu verstehen. Ich
habe in den ersten Semestern damals auch gezeigt, wie man mit Java per Hand eine Datei
kompiliert, um die Magie dahinter zu sehen. Ich mache das aber inzwischen nicht mehr,
weil es auch ein bisschen komplexer geworden ist. Also da lenkt man auch zu sehr ab,
weil man mehr konfigurieren muss, wenn man per Hand kompiliert. Es kann so komplexer
werden, als das, was eigentlich dahintersteckt. Also insofern ist es schwierig, da kann ich
kein ja oder nein sagen. Pragmatisch mache ich es nicht, dass ich das zeige, weil ich denke,
erst einmal geht es darum, überhaupt das Programmieren zu lernen. Und das ist schon
Urwald genug. Und wenn man das draufhat, dann glaube ich, kann man sich auch so ein
bisschen anschauen, was die Magie dahinter ist.

I: [04:04] Dann hätte ich mal eine ganz generelle Frage. Was macht für dich modernes
Coding aus?

B: [04:16] Ich bin immer sehr orientiert an Entwurfsmustern und schaue, dass man von
guten Praktiken anderer lernt. Das ist der eine Punkt, der wichtig ist. Der zweite Punkt
ist, dass man eigentlich selbst dokumentierend programmiert. Man also gar nicht so viele
Kommentare schreiben muss, sondern dass der Code so aufgebaut ist, dass eigentlich ganz
klar ist, was damit gemeint ist. Dann ist für mich die lose Kopplung ganz wichtig, welche
sich in vielen Entwurfsmustern widerspiegelt. Dass man also möglichst wenig Abhängigkeiten hat. Also dass es, wenn man ein System in seine Bestandteile zerlegt, möglichst
wenig Abhängigkeiten gibt und dass man versteht, wie man ordentlich abstrahiert. Man
fragt sich, wie kann ich mich denn von konkreten Erweiterungen unabhängig machen. Wie
abstrahiere ich von Objekten auf Klassen ist das eine, aber das andere ist, wie abstrahiere
ich auch von verschiedenen Implementierungen, sodass ich mich nicht mehr für die konkreten Implementierungen interessieren muss. Das muss man auf alle Fälle lernen. Dann
ist Testen ein großes Thema, dass man also weiß, wie man testet. Man muss sich mit der
Fehlerbehandlung mithilfe von Exceptions beschäftigen und dies auch verstehen. Wofür
das ist und wie man das auch gut designt. Das man z.B. Nicht alles auffängt, sondern dass
es manchmal auch gut ist, wenn ein Fehler geworfen wird. Code Sparsamkeit ist glaube ich
eine ganz wichtige Sache. Einige Sprachen wie z.B. Kotlin unterstützen das. Es ist wirklich ein großer Unterschied zu anderen Sprachen, weil man viel schneller erkennt, was da
eigentlich passiert. Aber auch wenn man dann Code schreibt. Ein klassisches Beispiel sind
11Anweisungen wie z.b. if true return true else return false. Du glaubst gar nicht, was für
umständlichen Code ich in Klausuren manchmal sehe. Also alles was richtig ist, bekommt
volle Punktzahl. Aber ich habe teilweise jetzt Aufgaben drin, wo ich schlechten Code zeige
und es Punkte dafür gibt, Eleganz einzubringen und zu vereinfachen. Ein Unterschied zur
klassischen Objekt-Orientierung ist, dass dort immer ganz viel darauf geguckt wird, wie
man Vererbungshierarchien aufbauen kann. Dort ist also Vererbung etwas Gutes. Und ich
glaube, bei modernen Sprachen versucht man Vererbung zwar zuzulassen, aber zu vermeiden. Dass man da also ein bisschen mehr Bewusstsein hat, wo es Seiteneffekte geben
kann. Und zwar nicht auf Ebene der Funktionen, sondern auf Klassenebene. Was auch
noch wichtig ist, ist funktionale Programmierung. Vor Jahren gab es das auch schon,
aber hat noch nicht so eine große Rolle gespielt. Ich glaube, da kommt man heute einfach
nicht drum herum, sich damit zu beschäftigen.

I: [07:58] Ja, du hast ja jetzt schon viele moderne Paradigmen genannt. Da wäre meine
Frage, was fallen dir da für Programmiersprachen ein, die viele dieser modernen Paradigmen vereinen?

B: [08:09] Kotlin habe ich ja schon genannt. Also der Grund, warum wir auf Kotlin gewechselt sind, ist, dass eigentlich alle diese Paradigmen dort enthalten sind und dass
Kotlin als Lehrsprache super ist, aber auch weil es industrienah ist. Scala ist eine Programmiersprache, die zwar ein bisschen akademischer ist, aber auch trotzdem sehr gut
ist. Python halte ich auch für eine gute Sprache, um einige Konzepte darzustellen. Allerdings bin ich der Meinung, aber das ist wirklich so eine Weltanschauung, das typsichere
Sprachen besser sind im Studium, auch, um Typen zu verstehen. Bis heute hat mich keiner überzeugen können, wofür man nicht typsichere Sprachen braucht. Ich glaube, eine
interessante, aber auch gruselige Sprache ist JavaScript, weil sie viele Konzepte beinhaltet. An JavaScript kann man sich wirklich gut Konzepte anschauen, weil da z.B. auch
funktionale Programmierung mit dabei ist. Also solche Konzepte sollte man kennen. Man
muss den Unterschied zwischen funktionaler, objektorientierter und einfacher iterativen
oder prozeduralen Programmierung kennen.

I: [09:38] Was würdest du in der Lehre höher priorisieren? Und zwar, wenn man den Fokus auf weit verbreitete Sprachen setzt oder eben auf modernere Sprachen, die vielleicht
auch das Potenzial aufweisen, mal eine breite Anwendung zu finden? Du hattest ja auch
Kotlin genannt, was ja schon in eine der beiden Richtungen geht. Aber was sagst du da
so generell zu?

B: [09:59] Also man muss beides haben, man muss schauen, wie die Sprache verbreitet
ist. Wie praxisrelevant ist die Sprache heute und wie praxisrelevant ist sie in fünf bis
zehn Jahren. Und Kotlin ist da ein schönes Beispiel. Ich habe lange darüber nachgedacht,
warum ich von Java auf Kotlin wechsle, weil einfach viel Java Code existiert. Aber ich
habe gemerkt, dass man als Anfänger den Wald vor lauter Bäumen in Java Code nicht
sieht. Und ich merke das wirklich beim Erklären. Es geht mit Kotlin viel besser. Also man
lernt eigentlich mit Kotlin so zu programmieren, wie man in Java programmieren sollte,
aber nie macht. Dass man mit Konstanten arbeitet, dass man Klassen final macht, nicht
offen lässt und man keine RuntimeExceptions hat. Ich wäre nicht umgestiegen, wenn ich
nicht wüsste, dass es ein Industriestandard ist. In dem Sinne, dass Google sagt, macht
Kotlin und nichts anderes mehr. Kotlin ist also nicht eine empfohlene Sprache, sondern
die empfohlene Sprache. Und ich glaube, selbst wenn man dann später nicht mit Kotlin
entwickelt, lernt man damit richtig programmieren. Python wäre ein anderes Beispiel und
ist insofern relevant, weil es im Bereich des Machine-Learning eine wichtige Sprache geworden ist. Ich behandle das ja im Modul Paradigmen der Programmierung, wo man mal
andere Sprachen kennenlernt, aber nicht in der Tiefe durchdringt. Und das ist, glaube ich,
auch wichtig, dass man ein bis zwei Sprachen richtig gut beherrscht, aber auch weiß, was
es für andere Konzepte gibt. Also eine Sprache muss drei Faktoren gerecht werden. Die
Sprache muss modern sein, nicht fancy modern, sondern eigentlich Konzepte aufgreifen,
die etabliert sind. Sie muss zweitens eine Relevanz in der Industrie haben und sie muss
drittens didaktisch geeignet sein. Wenn es alles zusammenfällt, dann landet man bei Kotlin. Aber das sind Überlegungen, die man an der Hochschule haben muss. Gerade Python
und JavaScript sind auch tolle Sprachen und die sind super Industrie relevant, aber sie
verführen auch zu schlechtem Code. Gerade JavaScript.

I: [12:30] Du hast dich eben schon mal für Clean Code ausgesprochen. Meine Frage ist,
wie kann man Lernende dazu bringen, dass sie sich auch an bestimmte Richtlinien halten,
welche zu sauberem Code führen?

B: [12:46] Im Idealfall machen sie das ja von vornherein. Aber ich glaube, man muss auch
ein bisschen in die Probleme reinlaufen, um zu verstehen, warum sauberer Code wichtig
ist. Es gibt so ein didaktisches Muster, das heißt “Feel the Pain“. Also man muss schon
einmal gefühlt haben, warum komplexe Systeme zusammenkrachen, wenn man zu viel
Abhängigkeiten hat. Dann kann man verstehen, warum ich mit Entwurfsmustern anfange. Wenn ich mit diesen Konzepten gleich zu Anfang anfange, dann verstehen die meisten
nur Bahnhof. Ja, also das Einführen von Interfaces ist schon so eine Sache, wo viele fragen,
warum mache ich denn das eigentlich? Da muss man viel Zeit für darauf verwenden, um
das zu erklären, warum man diese Konzepte benötigt, welche ja alle erst Relevanz haben,
und das ist das Gemeine, wenn ich komplexe Systeme bauen soll. In der Lehre habe ich
aber typischerweise keine komplexen Systeme. Das heißt, ich muss eigentlich auch Aufgaben designen, wo Studierende den Code verbessern können. Und da muss man natürlich
auch beim Code Review so Basic Sachen machen. Das fängt an bei Code Konventionen,
dass man eben Klassennamen großschreibt und nicht klein oder wo man Sachen kürzer
schreiben kann. Ich glaube, das kann man wirklich nur individuell mit Feedback machen.
Das kann man nicht im Frontalunterricht vermitteln, das muss man korrigieren, bei dem,
was die Studierende machen.

I: [14:22] Gibt es denn da für dich praktikable Wege, wie man diese Richtlinien auch erzwingen kann? Also dass man das nicht erst im Feedback sagt, sondern schon bei Übungsaufgaben sauberen Code ohne manuelle Korrekturen erzwingt?

B: [14:38] Du meinst, dass es automatisiert wird?

I: [14:39] Ja.

B: [14:41] Du kannst natürlich vorgeben, wie viele Klassen gebaut werden müssen, also
wie die Vererbungsstruktur ist. Du kannst Vorgaben machen, dass eine Klasse final sein
soll. Man kann eine Vorgabe machen: Setzen Sie alles, was nicht veränderbar oder zugreifbar sein soll, auf private. Bei Aufgabenstellungen von uns sind das Anforderungen.
Also was ist die Vererbungshierarchie? Was soll private sein? Welche Eigenschaften sollen
berechnet sein oder welche Eigenschaften sollen zu Anfang schon gesetzt werden? Also da
kann man einfach Requirements definieren. Dass kommentiert werden muss und Konventionen eingehalten werden, ist auch klar. Was ich bisher nicht gemacht habe, ist zu sagen,
ihr müsst in einer geringen Anzahl von Lines of Code zurechtkommen, könnte man ja
auch machen. Es dürften dann z.B. nur zehn Zeilen Code sein und dann gibt es eigentlich
nur eine bestimmte Form, wie man es lösen kann. Eine Sache, die man machen kann,
um das auch zu vergleichen, ist, dass man sagt, implementiert denselben Algorithmus auf
unterschiedliche Weise. Sodass man auch die Vor- und Nachteile abwägen kann. Also z.B.
einmal rekursiv und einmal iterativ. Einmal zeigen, was passiert, wenn ich eine Funktion
habe, die zwei Objekte übergeben bekommt, im Vergleich zu, ich habe ein Objekt, wo
es eine Methode gibt, wo ein weiteres Objekt übergeben wird. Man muss also die gleiche
Methode zweimal oder mehrfach zeigen, um die Unterschiede zu sehen. Ich will einfach
zeigen, welche Möglichkeiten gibt es eigentlich? Und wie sind da die Zusammenhänge? Ein
Beispiel wäre eine Liste, dessen Größe ich berechnen möchte. Speichere ich das in einer Eigenschaft, habe dann zur Laufzeit aber Seiteneffekte oder berechne ich das jedes Mal? Und
das miteinander zu vergleichen, welche Vor- und Nachteile das hat, ist auch ein guter Weg.

I: [17:06] Du hast ja auch schon einige Richtlinien genannt, die man Clean Code zuordnen
kann. Was wären denn da besonders Wichtige, die man unbedingt überprüfen sollte?

B: [17:33] Ich muss noch mal ganz kurz auf Kotlin zurückkommen. Einer der Gründe,
warum ich Kotlin damals eingeführt habe, ist, dass Kotlin als Sprache dazu führt, dass
ich saubereren Code schreibe. Denn Kotlin zwingt mich zu bestimmten Sachen, welche
ich bei anderen Sprachen überprüfen müsste. Also ich kann z.B. keine NullPointer verwenden, außer ich mache es explizit und prüfe dann, ob der Wert nicht vielleicht null
ist. Ja, das ist ein häufiger Fehler, dass Variablen nicht initialisiert werden oder vergessen
werden. Der nächste Punkt ist, dass es auch häufig Seiteneffekte gibt. Also man muss ganz
stark gucken, dass keine Seiteneffekte auftauchen, weil man von beliebigen Methoden auf
irgendwelche globale Variablen zugreift. Und wenn man aus dem Modul APnoch weiß,
dass globale Variablen nicht gut sind, nutzt man sie spätestens in dem Modul APdann
doch wieder. Die Studenten meinen dann, nur weil es Variablen innerhalb irgendwelcher
Objekte sind, auf die jeder zugreifen kann, ist es dann plötzlich nicht mehr global. Aber
ich muss es eben in einem Objekt oder in einer Klasse schützen und diese Zugriffe kapseln, was eigentlich ganz wichtig ist. Also wenn ich jetzt von einer Objektorientierung
spreche, muss man schauen, ob ordentlich abstrahiert ist. Also ob ich verstehen kann,
was die wesentlichen Eigenschaften sind. Da muss ich gucken, wie ich komplexe Objekte
zusammensetze und auch in einer Klasse das zusammenfasse, was zusammengehört. Also,
dass ein Element richtig auseinandergenommen wird. Bei einem Auto z.B. nimmt man
nicht den halben Reifen weg, sondern betrachtet den ganzen Reifen als einen Teilnehmer.
Die Kapselung als Konzept zu verstehen ist glaube ich ganz wichtig. Und dann zu schauen, wofür man die Unterscheidung zwischen Schnittstellen und Umsetzungen braucht.
Entwurfsmuster finde ich immer ganz gut geeignet, weil diese viele von den Clean Code
Prinzipien integrieren. Ein ordentliches Muster ist ja gerade eines, welches einen sauberen
Code abbildet. Da kann man ganz gut dran erklären, was die Designentscheidungen sind,
die man gegeneinander abwägt. Wenn man z.B. in einer bestimmten Situation bestimmte
Anforderungen und Einflussfaktoren hat, dann kann ich diese mithilfe von Mustern unter
einen Hut bringen, muss dann aber mit den Konsequenzen leben. Das Abwägen ist ganz
wichtig und sollte man trainieren. So kann man wirklich versuchen, eine Balance herzustellen. Das ist, glaube ich, ein ganz wichtiger Punkt.

I: [20:51] Ich hätte da noch eine Frage zu Domain Driven Design. Und zwar ist DDD
ja ein Ansatz, mit dem man sehr komplexe Software modellieren möchte und dabei sehr
fachlich vorgeht. Wenn man das allerdings lehren möchte, hat man dann das Problem,
dass Übungsaufgaben ja eine gewisse Beschränktheit haben, weil die können ja nicht so
komplex sein. Und die Frage ist, was muss man da beachten, wenn man Übungsaufgaben
erstellt, die solche Ansätze lehren sollen?

B: [21:28] Also das ist ja insofern auch interessant, weil man ja auf einer ganz anderen
Ebene ist am Anfang der Ausbildung. Man möchte ja trainieren, dass man etwas anhand
einer Spezifikation umsetzen kann. Da brauche ich dann aber noch kein DDD, weil ich
dann schon Vorgaben habe. Was dann ja spannend ist, ist die Domäne zu modellieren
und zu schauen, was ich für Events beachten muss oder welche Datenmodelle ich brauche.
Und ich glaube, das ist etwas, was man anhand einfacher Domänen erproben kann, mit
denen die Studierenden eigentlich schon vertraut sind. Die Frage ist auch, welchen Aspekt
von DDD man eigentlich vermitteln will. Also dass ich entweder in eine Domäne gehe,
wo ich eben kein Domänenexperte bin und erst verstehen muss, wie die Domäne funktioniert und deshalb auch Methoden kennen muss, mit denen ich das Wissen aus anderen
herauskitzeln kann. Und andersherum glaube ich aber, dass es auch hilfreich ist, sich die
Methoden anzuschauen, die man braucht, wenn man eigentlich selber schon Experte ist
und trotzdem immer schaut, wie kann ich z.B. ein ordentliches Glossar aufbauen. Ich habe
das bisher noch nicht gemacht, muss ich gestehen. Ich weiß ja, dass der Erstbetreuer von
der Arbeit viel mit DDD macht und ich war tatsächlich letztes Jahr auch auf der DDD
Konferenz. Ich bin am überlegen, ob ich das nicht bei Social Computing mit einbinde.
Also das ist ein Kurs, den ich gebe, wo es eigentlich um soziotechnische Systeme geht.
Da könnte man, obwohl es nicht ums Programmieren geht, trotzdem DDD mal anwenden
und ausprobieren. DDD ist natürlich auch für den Bachelor schon sehr ambitioniert, das
wäre im Master ein bisschen einfacher.

I: [25:07] Und dann hätte ich mal ein paar Fragen konkret zur Organisation von einem
Praktikum oder solchen Aufgaben. Und zwar würdest du da eher Programmieraufgaben
in Gruppenarbeit bevorzugen oder Einzelarbeit, wenn es darum geht, diese Aufgaben auch
zu bewerten im Nachhinein?

B: [25:28] Eigentlich eine Kombination, so haben wir das auch gemacht. Also erstmal
sind Gruppen sehr unterschiedlich. Es gibt die Gruppe, wo nur einer was macht und der
andere schaut zu. Das ist für den, der schwächer ist, wirklich ein Lernhindernis, weil es
bequem ist und der, der gut ist, will ja was machen. Der hat dann keine Geduld und
macht dann ganz schnell. Das ist der negative Fall vom gemeinsamen Arbeiten. Der positive Fall ist natürlich, dass beide gerne wirklich programmieren wollen. Der eine kann
es z.B. schon und erklärt es dem anderen und wird durch das Erklären auch nochmal
ein Level hochgehoben, andersherum genauso. Insofern war da mein Modell zu sagen, ihr
dürft zwar in Gruppen entwickeln, aber abgeben und erklären muss jeder einzeln. So kann
man sicherstellen, dass wirklich jedes Gruppenmitglied auch wirklich alles kann. Ab dem
dritten Semester lasse ich dann sogar größere Gruppen zu. Da muss dann jeder nur ein
kleines Stückchen erklären und dann bin ich auch ein bisschen toleranter, wenn es nicht
jedes Gruppenmitglied kann, weil das dann deren Verantwortung ist. Die ersten beiden
Semester bin ich noch bereit, streng zu sein und danach muss es eigenverantwortlich sein
und zur Not erst in der Prüfung knallen.

I: [27:18] Dazu hätte ich nochmal eine Frage. Wie würdest du im Vergleich dazu PairProgramming einordnen? Also nochmal in Abgrenzung zur Gruppenarbeit?

B: [27:27] Also bei Pair-Programming können es ja eigentlich beide, deswegen ist es das
bessere Modell als wirklich größere Gruppenarbeiten. Also gerade nachher dann bei Gruppenarbeit in höheren Semestern geht es ja auch darum, dass man Aufgaben verteilt. Und
bei Pair-Programming stelle ich sicher, dass wirklich beide jede Zeile Code gemeinsam angefasst haben. Und wenn man das tatsächlich etablieren könnte, dass die Studenten sich
auch abwechseln und jeder mal die Tastatur in der Hand hat, halte ich das für eine sehr
gute Möglichkeit. Leider ist das aber nicht das, was ich beobachte im Praktikum. Wenn
ich da die Gruppen sehe, dann ist derjenige, der schneller tippen kann, an der Tastatur.
Also an sich finde ich das Konzept supergut, aber in dem Bewusstsein, dass das von den
Studierenden so umgesetzt wird, wie man sich das eigentlich wünschen würde. Man kann
sie ja auch nicht dazu zwingen, man kann sie ja nur ermuntern.

I: [28:32] Thema Motivation: Man muss den Studierenden auch oft so ein bisschen Druck
machen, dass sie die Aufgaben überhaupt bearbeiten oder mit einer bestimmten Motivation bearbeiten. Und da gibt es ja verschiedene Arten, wie man diesen Druck generieren
kann. Also einmal kann man natürlich Noten einführen oder Aufgabenindividualisierung
schaffen, wo das Kopieren dann gar nicht mehr möglich ist. Oder man hat irgendwie ein
sehr motivierendes Lernklima, wo die Leute gar nicht das Bedürfnis haben, abzuschreiben, zu kopieren und die Aufgabe somit selber lösen möchten. Die Frage ist, unter welchen
Umständen meinst du, funktioniert überhaupt welcher Ansatz oder sollte auch bevorzugt
werden?

B: [29:13] Also ich kann ja mal erzählen, wie ich das gemacht habe und was ich vielleicht
anders machen möchte. Also bisher war das so: Ich habe tatsächlich als extrinsische Motivation Bonuspunkte vergeben für diejenigen, die ein bisschen mehr gemacht haben. Oder
ansonsten mussten bei der Abnahme Live-Aufgaben gelöst werden. Ob Code kopiert ist,
darauf habe ich aber eigentlich nicht geachtet. Also die Ansage war eigentlich, ihr dürft
kopieren. Also das überprüfen wir nicht, empfehlen tun wir das aber nicht. Das ist eine
sinnlose Diskussion zu sagen: Ist das jetzt kopiert oder nicht kopiert? Weil man muss
den Studenten schon klarmachen, wenn ihr da Code kopiert, betrügt ja nicht mich als
Dozent, sondern ihr betrügt euch ja selber. Ihr seid ja hier, um zu lernen, ihr habt euch
ja selber dafür entschieden, herzukommen und programmieren zu lernen. Und wenn ihr
unsere Hilfe nicht in Anspruch nehmt, dann habe ich das so zu akzeptieren. Dann müsst
ihr euch überlegen, ob ihr hier richtig seid oder nicht. Und diese Diskussion, kopiert oder
nicht kopiert, die führen wir gar nicht. Das Einzige, was wir machen, ist zu sagen, hier
habt ihr eine kleine Aufgabe, ändert mal den Code. Wenn ihr das nicht könnt, dann gibt
es da keine Punkte für. Also damit ist diese Aufgabe eben nicht bestanden, weil wir sehen
können, das hat nicht funktioniert. Ob ich Bonuspunkte vergebe, weiß ich noch nicht.
Ich möchte das Modell ein wenig umbauen. Bisher war das so, dass ein Praktikum aus
mehreren Aufgaben besteht, meistens so drei bis vier im Laufe des Semesters. Wenn du
also bei der dritten oder vierten Praktikums Aufgabe nicht mehr dabei bist und es nicht
mehr schaffst, dann ist das gesamte Praktikum nicht bestanden. Was dazu führt, dass da,
wo es eigentlich schwieriger wird, also da, wo man eigentlich hinkommen will, wir mehr
Augen zudrücken. Ja, denn die sind ja dann schon bis zur dritten oder vierten Aufgabe
gekommen und dann will man sie nicht durchfallen lassen, weil da müssen sie ein Jahr
warten. So die Idee, die wir alle haben, ist so ein bisschen Gamification orientiert. Wenn
ich z.B. ein Spiel habe und ich ein Level nicht schaffe, dann musstest du früher auch bei
den alten Arcade Spielen wieder von vorne anfangen. Das ist echt frustrierend. Wenn du
dir heute Spiele anschaust und ein Level nicht schaffst, dann kannst du auf dem gleichen
Level weitermachen. Und das ist eigentlich die Idee, zu sagen, wir haben vier Aufgaben,
die vier Aufgaben sind vier Level. Wenn du Aufgabe eins bzw. Level eins nicht geschafft
hast, musst du nochmal Level eins machen und das kann man öfter anbieten, also mehrfach im Semester, alle vier Level. Und wenn man dann Level zwei geschafft hat, geht man
ins Level drei. Wenn man Level drei nicht schafft, falle ich nicht wieder auf null zurück,
sondern Level eins und Level zwei bleiben geschafft. Damit wollen wir motivieren und betonen, dass schon zwei Level geschafft wurden. Wir vermitteln dann, dass die Studenten
dann schon so weit gekommen sind und das dritte Level fast geschafft haben und es mit
ein bisschen Zeit auch schaffen können. Wie wir das vom Zeitrahmen her organisieren, ob
wir eine Woche Level eins machen, dann Level zwei in den nächsten Wochen, dann Level
drei oder ob wir sagen: Jeden Montag ist Level eins, jeden Dienstag ist Level zwei und
so weiter. So kann man, wenn man will, in einer Woche oder über einen längeren Zeitraum das Praktikum bestehen. Das müssen wir nochmal überlegen. Die Idee dahin ist,
das ganzjährig anzubieten und den Stress rauszunehmen. Momentan ist leider folgende
Denkweise sehr präsent: Wenn ich jetzt diese Aufgabe nicht abgenommen bekomme, dann
habe ich das Praktikum nicht bestanden und dann fange ich von vorne an. Es geht also
nur um dieses Bestehen, Bestehen, Bestehen. Und bei dem anderen Modell würde man
halt versuchen zu sagen: Erreicht, erreicht, erreicht. Man erreicht also immer mehr, das
wird dir nicht weggenommen und dann kann man daran arbeiten, aufs nächste Level zu
kommen. Da versuchen wir die intrinsische Motivation mehr anzusprechen.

I: [33:55] Wie du schon sagtest, das geht jetzt in Richtung Gamification, Motivation von
den Studierenden. Ich würde jetzt aber trotzdem mal ein paar Fragen zur Individualisierung stellen. Also wenn man wirklich verhindern will, dass Leute kopieren, was man da
machen kann. Und da würde ich erst einmal fragen: Was kennst du da für Individualisierungsmethoden, welche wirklich dafür sorgen, dass einfaches Kopieren von Lösungen
nicht möglich ist oder eben erschwert wird?

B: [34:20] Also das, was wir gemacht haben, ist zu sagen: Du kannst deinen Code meinetwegen sogar kopieren. Aber es gibt eine live Aufgabe und von den Live Aufgaben haben
wir ganz viele und es wird zufällig eine ausgewählt.

I: [34:31] Also quasi ein Aufgabenpool?

B: [34:33] Genau und durch die elektronischen Prüfungen jetzt in Corona-Zeiten musste
ich Pools an Fragen aufbauen für die Prüfung. Das geht eigentlich ganz gut. Das kann ich
mir auch in Zukunft für die Praktika vorstellen. Wenn man dieses Gamification Modell
hat, dann gehst du in Level eins rein, startest Ilias und dir wird eine von Aufgaben
zugeteilt. Und wenn jetzt jemand sagt, er sei so gut, dass er sich Lösungen kopiert
und das organisieren kann, ist das ja auch eine Leistung. Aber ich glaube, das bekommt
man mit dieser Randomisierung ganz gut hin. Und wenn man dann nochmal randomisiert
und kombiniert Aufgaben mit anderen Themen, dann hast du mal Aufgaben Typen. Das kann kein Mensch kopieren, das Ziel wäre dann, sehr individualisierte
Aufgaben zu basteln.

I: [35:42] Ich hätte dazu nochmal eine Frage: Was findest du da wichtiger, dass man einen
sehr hohen Grad an Individualisierung hat, was das Kopieren immer schwerer macht, oder
sollte man doch mehr Fokus legen auf die Geschichte, welche den Aufgabenkontext bestimmt?

B: [35:59] Ja, beides muss wichtig sein. Das ist tatsächlich die Herausforderung. Bisher
habe ich das so gehabt, dass Aufgabe eins bis vier aufeinander aufbauen. Die Aufgabe
wird immer komplexer. Und das macht das ganze natürlich schwieriger. Und da weiß ich
noch nicht, wie man das abbilden kann, dass man beides hat, also randomisierte Aufgaben und aufeinander aufbauende Aufgaben. Und ich glaube schon, dass wichtig ist, dass
der Schwierigkeitsgrad immer größer wird, aber das das bisher Erreichte irgendwie weiter
verwendet wird. Also ist die Struktur der Aufgabe auch superwichtig. Und die sind eigentlich auch immer gleich. Also ich habe in den ganzen letzten Jahren immer die gleichen
Aufgaben abgefragt mit verschiedenen Aufgaben Typen. Also man muss irgendwo immer
Objekte miteinander verbinden, verknüpfen, erzeugen, durchlaufen, irgendeine Vererbung
mit drin haben, irgendwo eine Methode überschreiben. Also die Sachen sind tatsächlich
auf einer abstrakteren Ebene immer dieselben, die man in vielen Variationen durchlaufen
kann.

I: [37:12] Wie wäre denn da deine Meinung zu abweichenden Schwierigkeitsgraden? Wenn
du sagst, du hast ja ein Pool aus Aufgaben, können die ja teilweise sehr stark variieren.

B: [37:27] Das wird man nie prozentig genau hinkriegen. Die Problematik hatte ich
aber in den elektronischen Prüfungen noch viel stärker, weil wenn man da eine Varianz
der Aufgabe hat und der Schwierigkeitsgrad sehr voneinander abweicht, dann wäre es
wirklich unfair, wenn man dieselbe Prüfung betrachtet. Also man muss ganz stark darauf
aufpassen, dass die ungefähr gleich vom Umfang her sind. Man wird sie nicht eindeutig
gleich hinbekommen. Da muss man mit leben, das ist einer von den Nachteilen. Aber
vielleicht der kleinere Nachteil.

I: [38:00] Das ist natürlich auch immer mit einem gewissen Mehraufwand verbunden, wenn
man diese Art von Aufgaben erstellt. Wie viel Mehraufwand wärst du da bereit zu investieren für den Zweck der Individualisierung?

B: [38:14] Dadurch, dass ich denke, dass man das einmalig aufbauen muss und das dann
richtig gut funktioniert, habe ich eigentlich für das nächste Semester geplant, auch ein
bisschen Zeit reinzustecken. Und die andere Sache ist ja auch, dass man einen Pool ja
auch stückweise aufbauen kann. Man muss ja nicht sofort den gesamten Pool haben, weil
die Studenten beim ersten Durchlauf z.B. noch keine alten Lösungen haben. Wenn man
den Pool aber erweitert, dann hat man nachher irgendwann ganz viele.

I: [38:46] Jetzt würde ich mal ein bisschen Richtung Automatisierung übergehen. Was
müsste für dich eine Übungsaufgabe für Eigenschaften aufweisen, damit man diese auch
automatisch prüfen kann?

B: [39:13] Also damit man automatisch prüfen kann, muss natürlich das Ergebnis eindeutig prüfbar sein. Das ist die Herausforderung. Aber mich interessiert ja nicht nur der
Output oder die Objekt Struktur, sondern ich möchte ja teilweise auch prüfen, ob die
richtigen Variablen angelegt sind oder ob die eigentlich Klassenstruktur richtig ist. Also
wenn ich z.B. fünf mal eins rechne, dann ist fünf das richtige Ergebnis, aber ich möchte
keinen Algorithmus haben, der fünf Mal um eins inkrementiert. Und so etwas müsste man
irgendwo auch überprüfen können. Ich muss mir also vorher überlegen, was könnten typische Fehlkonzepte sein. Also wenn ich z.B. eine Liste von Zahlen habe und es sollte der
Durchschnittswert berechnet werden, dann muss man sich überlegen, was da passieren
kann. Vielleicht wird dann vergessen, durch die Anzahl der Elemente zu teilen. So kann
man besseres Feedback geben, als einfach zu sagen, dass etwas nicht stimmt. Oder man
prüft z.B. ob das letzte Element nicht mitgezählt worden ist. Man muss einfach auch aus
den bisherigen Prüfungen überlegen, was typischerweise falsch gelaufen ist und das in der
Automatisierung abbilden.

I: [40:57] Du sagtest eben, dass man bestimmte Vorgaben macht. Allerdings nimmt das
den Leuten auch eine gewisse Freiheit weg in der Aufgabenbearbeitung. Die Frage lautet:
Wie kann man denn gewährleisten, dass Aufgaben sowohl automatisch überprüfbar sind,
aber auch die Studenten trotzdem Freiheiten haben in der Aufgabenbearbeitung?

B: [41:40] Also im Prinzip hat man bei der automatisierten Prüfung ja immer ein bisschen Freiheit, weil man ja nicht alles automatisiert prüfen kann, es sei denn natürlich
man parst den Code Zeile für Zeile. Ich glaube, es gibt zwei Ebenen. Man kann natürlich
schon automatisiert testen, was allerdings nicht mehr ganz so gut funktioniert, ist eben
das Feedback, wie man den Code verbessern kann. Also was man natürlich schon auch
automatisiert machen kann, ist zu sagen: Warum ist das nicht private oder warum ist
diese Klasse nicht final, wenn es keine Ableitungen gibt? Vieles davon machen auch gute
Entwicklungsumgebungen schon, geben Warnhinweise, die man berücksichtigen sollte und
am besten mit einbezieht. Man könnte z.B. sagen: Ihr dürft machen, was ihr wollt, aber
verwendet nichts, was deprecated ist. Oder man versucht auch automatisiert zu schauen,
ob man auf interne Eigenschaften einer Klasse zugreifen kann. Man könnte ja auch so eine
Art Attacke machen: Dein Ergebnis stimmt nicht, warum nicht? Ja, weil ich habe Zugriff
darauf gehabt und ich habe einfach mal eine fünf eingesetzt. Aber das wird natürlich
schon komplexer.

I: [43:21] Ich würde dann mal in Richtung Tools übergehen, mit denen einiges, was wir
jetzt auch so besprochen haben, umsetzbar ist oder diese Tools zumindest unterstützend
wirken. Hast du schon mal Tools zur Aufgabenindividualisierung genutzt? Was für Erfahrungen hast du damit gemacht? Du sagtest ja eben, du hast das mit Ilias und Pools mal
ausprobiert. Hast du da auch noch was anderes ausprobiert?

B: [43:43] Ich habe tatsächlich dafür nur Ilias verwendet und bei einer anderen Möglichkeit, die ich mal angewendet habe, mussten sich die Lernenden selber eine Aufgabe
individualisieren. Da hatte ich einfach eine Seite mit 1Themen und das Thema eines
jeden einzelnen hat sich einfach aus den letzten drei Ziffern der Matrikelnummer ergeben.
Zum Beispiel baue eine Hierarchie aus drei Klassen, eine Oberklasse, zwei Unterklassen
zum Thema Fischerei oder zum Thema Politik. Und auf welcher Ebene das Thema interpretiert wird, ist mir dann eigentlich relativ egal, aber Hauptsache es passt irgendwie
zu dem Themenfeld. Jemand, der das Thema Hotel hat, kann dann relativ schlecht von
jemand kopieren, der das Thema Politik hat. Und das war so eine Möglichkeit, wie man
auch relativ einfach automatisieren kann.

I: [44:53] Kennst du da noch zusätzliche Tools, mit denen man das auch im großen Stil
betreiben kann? Wenn man jetzt sagt, man hat irgendwie Studierende und will für
diese Aufgaben individualisieren. Das kannst du mit dem Pool natürlich auch machen
und auch jetzt mit dieser zweiten Variante, aber gibt es da noch etwas, was dir einfällt?

B: [45:09] Leider nicht, aber ich habe da auch nicht gezielt recherchiert.

I: [45:16] Ich würde dann mal zu anderem Tooling übergehen, und zwar hatten wir ja
eben über automatische Aufgabenüberprüfung geredet. Und daraus resultiert natürlich
ein anderes Feedback, wie das Feedback von Betreuern, welche auch Aufgaben manuell
korrigieren und auch nochmal mit Studenten Gespräche führen. Inwiefern meinst du, kann
automatisches Feedback das Feedback von Betreuern ersetzen?

B: [45:42] Also ich glaube, es handelt sich dabei um eine Art First Level Support. Ich
glaube, wenn etwas funktioniert, ist ja erstmal alles gut. Auch da, wo es Fehler gibt, kann
ganz viel automatisiert werden. Dann hat man tatsächlich auch mehr Zeit, sich auch auf
einer höheren Ebene mit Problemen zu beschäftigen. Das sind einfach verschiedene Level von Support. Also wenn man sagt, man fängt vielleicht mit der Automatisierung an,
und dann kann man einen Betreuer fragen. Und ich glaube durchaus, dass einige Sachen
auch ganz ohne Betreuer abgebildet werden könnten. Die wertvolle Ressource Zeit, die
man miteinander hat, kann ich vielleicht eher damit verbringen, nochmal zu erklären,
wie Klassenstrukturen aufgebaut sind, statt nochmal zu erklären, wie man einen Durchschnittswert berechnet.

I: [46:46] Ich würde jetzt mal zur nächsten Frage übergehen. Jetzt geht es mir um die
automatische Verteilung von Aufgaben und das Abgeben von Lösungen. Was hast du da
für Plattformen genutzt, um dies zu gewährleisten, vielleicht auch neben Ilias?

B: [47:08] Da habe ich neben Ilias leider noch keine anderen genutzt.

I: [47:31] Kennst du denn in dem Bereich noch andere oder hast du welche im Visier, die
du interessant findest?

B: [47:45] Also was ich interessant finde, ist der ganze Bereich der Kotlin Koans. Also
da habe ich auch gerade eine Bachelorarbeit zu am Laufen. Das sind genau solche Programmier Challenges, bei denen man über Tests festlegt, ob die Aufgabe richtig gelöst ist
oder nicht. Und man kann eben Feedback geben, warum etwas richtig gelöst ist oder nicht.

I: [48:22] Werde ich mir auf jeden Fall mal anschauen. Ich hätte noch eine letzte Frage zu
Feedback und Beratung. Was hältst du von modernen Messengern als Kommunikationsplattform zum Austausch zwischen Lehrenden und Lernenden.

B: [48:39] Ja, finde ich supergut. Aber ich kenne noch keine, die das erfüllen, was man
eigentlich braucht. Nämlich Gruppen bilden und sagen können, dass man mal nicht für
einen Studenten verfügbar ist. Denn ich sag mal so, mit WhatsApp habe ich ein Datenschutzproblem. Ich mache mit allen gerne WhatsApp, aber nicht mit Studierenden. Ich
möchte da in beide Richtungen keine Mobilfunknummern austauschen. Ich möchte auch
niemanden ausschließen, der nicht WhatsApp nutzt. Also Skype ist auch so ein schönes Beispiel, wenn dann Skype bei mir lief, dann bekommt man auch mal schnell eine
Nachricht von einem Studenten. Und du hast bei Instant Messaging immer die Erwartungshaltung, dass du sofort antwortest. Das geht aber nicht. Bei Freunden oder dem
Arbeitsteam gerne, aber nicht bei Studenten. Das geht also nach hinten und wird dann
unabsichtlich ignoriert. Anders als bei einer E-Mail, die ich irgendwann abarbeite. Und
das ist glaube ich die Herausforderung, dass man sich überlegt, wie kann eine gute Plattform aussehen. Also Discord ist zum Beispiel ein gutes Tool, das wäre von der Art und
Weise her eine gute Möglichkeit, mit Channels zu arbeiten und so weiter. Ist aber auch
noch nicht unbedingt etwas, was man in der Lehre einsetzen kann, auch aus Datenschutzgründen. Ich kann ja niemanden dazu zwingen. Aber prinzipiell finde ich so Messenger
Lösungen gut, da würde ich mir nur eine Art Status wünschen, durch den ich zeigen kann,
dass ich erreichbar bin oder nicht. Oder dass sogar Nachrichten gesammelt werden, die
ich dann später abarbeiten kann.