---
acronym: n.n. WMA 4
type: literature reference
title: Interview Transkript n.n. WMA 4
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

## Transkript des Interviews mit n.n. WMA 4

Durchgeführt durch Jann Intveen\
Tätigkeitsfeld: Wissenschaftlicher Mitarbeiter\
Datum: 17.12.2020

## Inhalt

I: [00:01] Was sind deiner Meinung nach die wichtigsten Werkzeuge, welche man im Rahmen von modernem Coding benötigt und deshalb auch lehren sollte?

B: [00:13] Also es kommt immer darauf an, was man darunter versteht.

I: [00:23] Ich meine die essenziellen Werkzeuge, die man zum Coden braucht.

B: [00:28] Ja, die Entwicklungsumgebung, klar. Wobei da würde ich eher sagen, mir fällt da Maven ein. Das ist komplett unabhängig von der Entwicklungsumgebung. Es wäre sinnvoll, wenn man den Lernenden da die Wahl lassen würde. Im Rahmen des Hochschulstudiums wäre es natürlich sinnvoll, wenn man sich auf eine Entwicklungsumgebung einigen würde. Weil dann ist die Betreuung viel einfacher. Wenn man z.B. sagen würde, man nimmt Eclipse oder was auch immer, dann kann man auch besser Leitfaden schreiben und auch die Lernenden besser unterstützen. Aber im Prinzip wäre ein offenes Framework eine gute Wahl, welches unabhängig von der IDE ist. Im Java Umfeld ist das klassisch Maven. Also du brauchst jetzt nicht unbedingt eine IDE. Es reicht auch eine Konsole zum entwickeln. Wichtig meiner Meinung nach ist auch Continuous Integration, sei es jetzt Bamboo oder Jenkins, dann natürlich auch Versionsverwaltung z.B. Git.

I: [01:42] Das heißt, du würdest so etwas wie Build Umgebungen auch sehr früh lehren?

B: [01:48] Ja auf jeden Fall. Also das ist das, was mir permanent auffällt, auch hier im Studium. Die Studierenden lernen nicht, am Ende auch ein fertiges Produkt auszuliefern. Also es werden oft Schnipsel gecoded, vielleicht paar Tests dazu, aber so wirklich von Null auf zu sagen, dass man mal ein Produkt aufsetzt und dieses ausliefert, gehört einfach dazu. Und auch so etwas wie einen Jenkins aufzusetzen. Also über Infrastructure lässt sich drüber streiten? Muss man das jetzt machen in der heutigen Zeit oder nutzt man irgendwelche Cloud Lösungen? Aber ich finde das gar nicht verkehrt, wenn man das auch selber aufsetzen könnte.

I: [02:41] Dann würde ich mal zur nächsten Frage übergehen. Findest du es sinnvoller, wenn man Lernende Werkzeuge zur Versions Verwaltung direkt über Funktionen der IDE bedienen lässt? Oder sollten die Lernenden die Konsole benutzen?

B: [02:58] Beides würde ich sagen. Ich würde erstmal weg von der IDE gehen und sagen, lernt erstmals tatsächlich mithilfe der Konsole Versionsverwaltung zu nutzen. Dann versteht man auch, was da passiert. Die IDE macht ja nichts anderes, nur dass man die Befehle nicht kennt. Ich meine, ich bin ja jetzt ein bisschen älter und ich habe damals auch C++ selber kompiliert und Make-Files geschrieben und klar, die IDE übernimmt viele Tätigkeiten für dich. Und das funktioniert auch ganz gut. Also auch wenn man im Java Umfeld programmiert und ein Maven Projekt importiert in die IDE, dann ist alles schon vorkonfiguriert. Der Class Path ist gesetzt und so weiter. Alle Libraries sind schon irgendwie angebunden und man bekommt gar nicht mit, was da passiert im Hintergrund. Also im Prinzip wie eine Black-Box. Schön und gut, aber wenn man das dann irgendwann mal selber machen muss und nachvollziehen muss, was wie zusammenhängt, dann bekommt man das nicht mit. Und daher würde ich sagen am Anfang auf jeden Fall die Basics selber kennenlernen. Und später, wenn man das z.B. im Berufsleben einsetzt und das schneller geht mit einer IDE, dann würde ich sagen, dann macht es schon Sinn, auch die Features, welche die IDE bietet, auch einzusetzen.

I: [04:20] Mal eine ganz generelle Frage. Was macht für dich modernes Coding aus?

B: [04:29] Für meine Begriffe macht modernes Coding aus, dass man sich nicht irgendwie auf eine Programmiersprache oder auf bestimmte Tools konzentriert, sondern auch mal links und rechts guckt und schaut, was gibt es aktuell auf dem Markt? Wie kann man etwas beschleunigen? Wo kann man irgendwelche Frameworks einsetzen, welche dir zum Teil die Arbeit abnehmen? Was sind die aktuellen Standards? Das eine ist die Frage, wie komme ich schnell zu einer Lösung? Da kann ich dann bestimmte Libraries einsetzen, um Code generieren zu lassen, der aber auch qualitativ hochwertig ist. Time to Market ist jetzt ein Thema. Sei es auch Continuous Integration, was bewirkt, dass ich nicht immer permanent alles lokal kompilieren und testen muss. Damals hatten wir diese Tools nicht gehabt. Man musste permanent alles bauen und lokal testen und wenn da mal ein Bug war, musste man den erstmal fixen. Heute hat man einen Developer Branch, auf den man committen kann und im Hintergrund wird dann gebaut und getestet, sodass man einfach weitercoden kann. Aber im Wesentlichen bedeutet modern, dass man aktuelle Technologien verwendet und auch links und rechts schaut. Wenn man aber schnell produktiv gehen möchte, dann würde man eher auf erprobte und bewährte Technologien setzen, wo auch die Unterstützung da ist. Aber wie gesagt, man sollte auch links und rechts schauen und im Einzelfall entscheiden, was die richtige Technik oder Methodik ist.

I: [06:40] Wenn man sich jetzt mal eine Ebene darunter anschaut. Was für Programmiersprachen fallen dir ein, die auch so moderne Paradigmen vereinen?

B: [06:50] Darunter würde Go fallen. Welches aber im Vergleich zu Java viel weniger Unterstützung bietet. Also es gibt schon viele Open Source Projekte dazu und Frameworks. Diese werden aber oft halbherzig betreut. Also klar, Java ist da unschlagbar. Eine andere Programmiersprache wäre da noch Kotlin. Wobei das sehe ich so ähnlich wie bei der Frage mit der Versionsverwaltung. Da würde ich auch sagen, wir haben erstmal Java als Programmiersprache und dann lernt man später auch die Vorteile von Kotlin. Weil da ist auch vieles Magie, was man auf den ersten Blick nicht sieht.

I: [07:42] Nochmal eine andere Frage zu Programmiersprachen. Was würdest du in der Lehre höher priorisieren. Ein Fokus auf weit verbreitete Programmiersprachen oder ein Fokus auf Programmiersprachen, welche auf modernen Paradigmen aufbauen und das Potential aufweisen, auch einmal eine breite Anwendung zu finden? 

B: [07:59] Beides. Also hauptsächlich vor allem hier an der Technischen Hochschule bilden wir ja schon Handwerker aus, welche nach einem abgeschlossenen Studium auch meistens coden können. Und da gehört dazu, dass man aktuell gängige Programmiersprachen kennenlernt. Aber man sollte natürlich auch Fokus auf Neuerungen haben. Es gibt bestimmte Programmiersprachen, Konzepte oder Frameworks, die für bestimmte Anwendungen eher geeignet sind als andere. Die sollte man auch kennenlernen. 

I: [08:33] Das heißt, du würdest den Fokus sehr verteilt setzen und nicht explizit auf eines der beiden? 

[08:41] Auf jeden Fall verteilt und wichtig ist, dass man tatsächlich ein Handwerk beherrscht. Dass man mit dem Studium fertig ist und sagen kann, dass man jetzt auch mit einer bestimmten Programmiersprache oder bestimmten Methodik und Konzepten wirklich ein Produkt am Ende umsetzen kann. Dieses auch zu deployen und nutzbar zu machen. Das Wesentliche besteht ja darin, sich weiterzubilden. Also wenn ich zurückdenke an meine Zeiten. Als ich damals angefangen hatte mit Versionsverwaltung, war das damals noch CVS. Dann kam Subversion, dann kam Mercure. Dann kam Git und so weiter. Und diese Lernkurve wird sehr flach, wenn man davor schon die Konzepte kennenlernt. Also so stark unterscheiden die sich nicht. Also der wesentliche Vorteil von Versionsverwaltung ist dann klar. Da kommen ein paar Features hinzu, der Code liegt mittlerweile eben verteilt und nicht mehr zentral vor. Und das ist meiner Meinung nach das Wichtigste, dass man auch lernt, sich weiterzubilden und die Grundkonzepte kennenlernt.

I: [09:59] Gehen wir mal zu einem etwas tieferen Bereich über, und zwar: Viele Lernende können ja noch nicht gut coden und da entsteht manchmal Code, den man vielleicht nicht als sehr lesbar bezeichnen würde. Und jetzt die Frage, wie kann man denn die Lernenden dazu bringen, sich an bestimmte Richtlinien zu halten, die zu sauberen Code oder auch Clean Code führen?

B: [10:27] Ja, es gibt Style-Guides, die auch teilweise de facto Standard sind, welche man sich anschauen kann. Ich würde dann viele Beispiele liefern, diese erklären und auch Gegenbeispiele zeigen. Ich beobachte, dass viele auch nicht mit fremdem Code klarkommen. Also das muss man auch beibringen, auch mal Code zu lesen und zu überarbeiten und nicht nur eigene Lösungen zu entwickeln. Ich denke mal, das würde auf jeden Fall helfen. Und wenn man dann ein schlechtes Beispiel vorstellt und sagt, da existiert ein Bug und der soll gefixt werden, dann kann man daraus auch Lehren ziehen. Wenn der Code eben schlecht umgesetzt wurde und nicht lesbar ist, dann werden die Studenten schon selber draufkommen, wo das Problem liegt.

I: [11:26] Welche praktikablen Wege würden dir einfallen, wenn man die Studenten dazu zwingen will, sich an diese Richtlinien zu halten? Also das nicht nur einfach gesagt werden soll, dass man sich daranhalten soll, sondern das irgendwie auch erzwingen will.

B: [11:39] Da gibt es ja zahlreiche technische Lösungen, die das auch schon unterstützen z.B. für Jenkins gibt es Plugins, mit denen man Code Check-Styles durchführen kann. Also ich hatte ein Open-Source-Projekt im Bereich Smart Room betreut, da haben wir auch ein Binding entwickelt für Open Hub und wir hatten auch automatisierte Code Überprüfung, sei es Länge der Zeilen usw. Das gab es als Vorgabe und das konnte man in der IDE einbinden und automatisch durchchecken lassen. Das ist so ähnlich wie Tests, welche erstmal durchlaufen werden müssen und dann wird Code eventuell nicht akzeptiert. Das wäre eine Möglichkeit, die relativ einfach umzusetzen ist.

I: [12:39] Was wären denn konkrete Richtlinien, die du besonders wichtig finden würdest?

B: [12:52] Ich würde da jetzt wirklich auf die gängigen de facto Standards beim Code Style verweisen. Wichtig ist vielleicht einheitliche Sprache zu nutzen, dass da jetzt nicht z.B. Englisch und Deutsch vermischt wird. Dann generell auch, dass Code auch dokumentiert ist, wo es nötig ist. Wichtig ist auch, wie die Methodennamen gewählt sind, wie generell die Struktur von dem Projekt aussieht und so weiter.

I: [13:30] Ich habe noch eine Frage zu Domain Driven Design, und zwar ist das ja eine Herangehensweise zur Modellierung von meist sehr komplexer Software. Und wir lehren das ja auch bei uns. Die Frage ist, was muss man da beachten, wenn man das in Übungsaufgaben verpackt, die ja oft von der Komplexität eher geringer ausfallen?

B: [13:52] Also, wenn man zu große Aufgaben wählt, die zu komplex sind, dann läuft man die Gefahr, dass die Studenten damit nicht klarkommen oder die Zeit einfach nicht ausreicht. Wenn man die Aufgaben zu einfach gestaltet, dann kommt das eigentliche Lernziel nicht zum Tragen. Da muss man eine Lösung in der Mitte finden. Was ich sehr oft beobachte, ist, dass es sich manche Lehrende einfach machen und sich einen Anwendungsfall überlegen und diesen permanent weiter einsetzen. Das kann man machen, aber es wäre sinnvoll, wenn man das in der Retrospektive nochmal betrachtet und verbessert. Man kann schlecht von vornherein alles komplett richtig machen. Man muss eben jedes Jahr oder jedes Semester evaluieren und schauen, was könnte man anders machen und wie kann man das verbessern?

I: [14:58] Das heißt, die Ideen ist, sich einfach schrittweise ranzutasten?

B: [15:05] Genau das hatten wir auch mal in dem Modul Künstliche Intelligenz. Da haben wir drei Semester lang ein Framework entwickelt und immer weiter ausgebaut. Das ist machbar. Wenn man sich eine Aufgabe mitsamt einer Musterlösung nur einmal überlegt, dann macht das auch keinen Spaß.

I: [15:33] Jetzt geht es mal in die Richtung Gruppenarbeit oder auch die Motivation von Studierenden. Die erste Frage wäre, würdest du bei der Bearbeitung von Übungsaufgaben eher Gruppenarbeit oder Einzelarbeit bevorzugen, wenn man davon ausgeht, dass die Arbeit auch bewertet wird nachher?

B: [15:51] Es kommt drauf an. Man kann da jetzt nicht pauschal ja oder nein sagen. Also ist es je nach Modul und je nach Aufgabe anders zu bewerten. Zum Beispiel beim Projektmanagement ist das Lernziel tatsächlich Teamarbeit auch zu fördern. Und die müssen das auch gemeinsam bearbeiten. Da würde ich jetzt auch nicht drauf verzichten wollen. Also bei den Programmieraufgaben, würde ich sagen, tendiere ich mittlerweile auch eher weniger zu Gruppenarbeit. Also zumindest mal am Anfang. Also vielleicht sollte eine Mischform da rauskommen, dass man sagt die Basics, die ersten Programmieraufgaben setzt jeder halt für sich allein um. Und dann gibt es vielleicht eine komplexere Aufgabe, wo man auch gemeinsam im Team eine Lösung entwickelt. Also man kennt das aus den Praktika, du kennst das wahrscheinlich auch, dass die Studenten versuchen, das irgendwie aufzuteilen. Einer macht Datenbanken, der andere Softwaretechnik und der dritte eben MCI. Und das ist nicht unser Ziel. Es soll jeder die Methodik kennenlernen und auch anwenden können.

I: [17:02] Und in Abgrenzung dazu nochmal existiert ja auch Pair-Programming. Wie würdest du das einordnen in Abgrenzung zur Gruppenarbeit?

B: [17:10] Das ist auf jeden Fall sinnvoll, aber vielleicht nicht am Anfang. In der jetzigen Zeit ist es schwierig, Studenten dazu zu bewegen, sich zusammenzusetzen. Wenn man das nicht wörtlich nimmt, dass man nebeneinandersitzt und einer programmiert, der andere zuschaut und kommentiert, kann man das sicherlich auch Remote machen. Dann braucht man eben entsprechende Tools dafür. Also das finde ich auf jeden Fall sinnvoll.

I: [17:58] Würdest du das dann der Gruppenarbeit vorziehen oder wären das nochmal zwei getrennte Anwendungsbereiche für dich?

B: [18:08] Das sind schon getrennte Bereiche. Und ja, ich würde jetzt eher eine Mischform bevorzugen. Zum einen sollte man auch alleine coden können. Man sollte aber auch die Vorteile von Pair-Programming kennenlernen. In größeren Projekten sind dann auch mal viele Entwickler involviert, mit dieser Situation sollte man auch Erfahrungen machen. Weil das kann man allein nicht lernen. Wenn man z.B. etwas eingecheckt hat und dann irgendwas kaputt geht, muss man schauen, wer dafür zuständig ist und so weiter. Solche Aspekte würde man allein nicht erfahren. Daher würde ich sagen, dass man das alles kombinieren sollte.

I: [19:15] Gehen wir mal in den Bereich Motivation über. Oft muss man Lernenden ein bisschen Druck machen, dass diese die Aufgaben überhaupt bearbeiten oder auch mit einer gewissen Motivation darangehen. Und da fallen mir zwei Ansätze ein. Einer ist eben Druck durch Noten oder Individualisierung, also dass die Lernenden gar nicht die Möglichkeit haben, zu kopieren oder diese Lerngruppen zu bilden, von denen du gesprochen hast. Und die andere Möglichkeit wäre, dass man ein motiviertes Lernklima schaffen kann, sodass die Lernenden Lust auf die Aufgaben haben und vielleicht dieser Druck durch Noten oder Individualisierung gar nicht nötig ist. Die Frage ist, unter welchen Umständen meinst du ist welcher Ansatz der richtige oder kann überhaupt funktionieren?

B: [20:10] Also ich finde die Noten sowieso das Schlimmste, was es geben kann. Also ich behaupte mal, dass wir auch ohne Noten klarkommen würden. Für mich gibt es da nur zwei Seiten, entweder beherrscht jemand ein Werkzeug oder eine Methodik oder er beherrscht es nicht. Daher würde ich die Noten an sich, wenn ich es könnte, komplett abschaffen und am Ende nur einen Schein ausstellen, der bescheinigt, dass eine Methodik beherrscht wird oder nicht. Und wie diese Kompetenz zustande kommt oder wie lange man dafür braucht, spielt eigentlich gar keine Rolle. Die Anforderung ist also, dass ich etwas können muss und eine bestimmte Qualität liefern kann. Dies ist aber leider nicht möglich, obwohl es so viele wissenschaftliche Untersuchungen dazu gab, die besagen, dass es eigentlich nicht förderlich ist, durch Noten zu motivieren. Ich würde trotzdem versuchen, einen Kompromiss zu machen. Also es gibt sicherlich Studenten, die sich motivieren lassen. Das hängt auch von den Lehrenden ab. Also wie die Lehrenden ihr Modul gestalten. Es gibt so etwas wie agile Hochschuldidaktik. Das Buch kann ich nur empfehlen. Da geht es darum, dass man auch in der Lehre agil vorgeht und gemeinsam Ziele erarbeitet und der Lehrende dann in die Richtung der Ziele lenkt. Man kann dann den aktuellen Lernstand ermitteln und gemeinsam schauen, wie das Ziel erreicht werden kann. Das funktioniert bei einigen, wenn man das richtig umsetzt. Wenn das nicht funktioniert, dann muss man anders vorgehen. Es gibt immer noch Trittbrettfahrer, die einen Schubs brauchen. Wichtig ist meiner Meinung nach, klare Ziele zu formulieren. Was sind die Lernziele? Und wenn man die erreicht hat, dann kommt man auch weiter. Also unabhängig von Noten hat man z.B. Meilensteine und um jetzt weiter gehen zu können oder um zur Klausur zugelassen zu werden, muss man dann ein Praktikum bestehen. Da sind klare Qualitätskriterien definiert z.B. Definition of Done. Wenn einzelne Aufgaben erreicht werden, dann kommt man eben weiter. Wenn man das vollautomatisiert, dann muss man auch nicht wirklich in Kontakt mit Studierenden treten. Man muss das nur rechtzeitig kommunizieren und zeigen, wie das ablaufen kann. Dann würde man beispielsweise sehen, dass alle Tests auf grün sind, die Aufgabe somit erledigt ist und man kommt weiter. Es gibt auch Modelle, bei denen das Praktikum eine Teilnote ergibt und die Klausur dann als Individualleistung zählt. Dies ist zum Beispiel in unserem Modul Projektmanagement der Fall.

I: [23:29] Jetzt geht es etwas in Richtung Individualisierung. Was sind dir für Individualisierungsmethoden bekannt, die das Kopieren von Lösungen verhindern können?

B: [23:45] Die einfachste Lösung wäre, einfach mal die Testdaten zu individualisieren. Das würde schon mal dazu führen, dass man nicht so einfach kopieren kann. Die beste Lösung wäre natürlich, je nach Lernziel, wenn man unterschiedliche Aufgaben aus unterschiedlichen Domänen definieren würde. Dann müsste man sich quasi in die Domäne hineinversetzen, um die Aufgabe zu lösen. Da dies aber natürlich sehr aufwendig ist, glaube ich, dass die einfachste Variante wäre, individuelle Testdaten zur Verfügung zu stellen.

I: [24:48] Was wäre dann aus deiner Sicht wichtiger, dass man einen sehr hohen Grad an Individualisierung hat oder doch mehr Fokus legt auf die Geschichte bzw. Domäne, welche diese Aufgabe bestimmt?

B: [25:06] Es kommt darauf an, was man damit bezwecken will. Wenn man die Teamarbeit fördern will, dann macht es natürlich keinen Sinn unterschiedliche Domänen zu wählen. Wenn man jetzt einfaches Kopieren verhindern will, dann macht es schon Sinn, dass man dann mehr individualisiert. Aber ich kenne das auch aus eigener Erfahrung. Eigentlich sollte man tatsächlich mehr Pair-Programming fördern, sodass man sich gemeinsam Sachen anschaut, denn dabei lernt man viel mehr. Viele können das allerdings noch nicht, weil man das nie gelernt hat.

I: [25:59] Wie wäre denn deine Meinung zu abweichenden Schwierigkeitsgraden aufgrund von Individualisierung?

B: [27:34] Es gibt ja Vorgaben, dass Aufgaben, die benotet werden sollen, auch vergleichbar sein sollen. Daher muss man da schauen, dass es von der Komplexität relativ ähnlich ist.

I: [27:53] Wie viel Mehraufwand wärst du bereit zu investieren, wenn es darum geht, individualisierbare Aufgaben zu erstellen im Vergleich zu normalen Aufgaben?

B: [28:04] Ich scheue da keinen Aufwand. Je nachdem, wenn man jetzt ein Einzel Praktikum mit Studenten betrachtet, wird das schon problematisch. Aber wenn man das automatisieren kann, dann ist das denke ich mal auch kein Problem.

I: [28:27] Das heißt, du würdest auf jeden Fall diesen Mehraufwand betreiben, wenn du dadurch mit den positiven Aspekten von Individualisierung leben könntest?

B: [28:36] Auf jeden Fall. Ja.

I: [28:41] Du hattest eben auch automatische Überprüfung angesprochen. Und zwar, was muss deiner Meinung nach eine Übungsaufgabe für Eigenschaften aufweisen, damit man diese überhaupt automatisch überprüfen kann?

B: [28:59] Dann muss man schon gewisse Vorgaben machen können. Sei es z.B. Interfaces vorgeben, dass man dazu automatisierte Tests erstellen kann. Weil anders wird das nicht funktionieren, sonst müsste man das alles händisch prüfen. Es wäre auch möglich, dass die Studenten erstmal Test-Driven vorgehen und auch Tests implementieren. Das wäre auch eine Möglichkeit. Man könnte dann durch Individualisierung eine kleine Anzahl unterschiedlicher Aufgaben erstellen und dann jeweils ein Team Tests schreiben lassen und ein Team die Aufgabe auf Basis dieser Tests lösen lassen.

I: [30:07] Du sagtest eben, man müsste dann bestimmte Vorgaben machen, damit das automatische Überprüfen mittels Tests überhaupt geht. Das Problem dabei ist, dass dies die Freiheit der Studenten beim Lösen dieser Aufgabe einschränkt. Hast du Ideen, wie man da einen Mittelweg gehen könnte oder wie man das vereinen könnte, sodass die Aufgaben auf der einen Seite automatisch überprüfbar sind, und auf der anderen Seite Studenten aber noch Freiheiten haben?

B: [30:37] Da würde ich mich auf die Algorithmen zur Wegsuche Dijkstra und A* beziehen. Für die Algorithmen an sich kann man die wichtigsten Funktionen mithilfe von Pseudocode vorgeben. Diese könnte man somit auch automatisiert testen lassen. Das integrieren des Algorithmus in verschiedene individuelle Domänen würden wir dann den Studierenden überlassen und so Freiheit schaffen. Die Studierenden könnten dann auch für die jeweilige Domäne spezifische Anwendungstests schreiben. Das wäre ein Kompromiss, bei dem man nicht alles komplett vorgibt und die Studierenden im Design auch Freiheit haben.

I: [31:15] Dann geht es mal in Richtung Tools. Hast du schon mal Tools zur Aufgabenindividualisierung angewendet in der praxisorientierten Lehre? Und was für Erfahrungen hast du gemacht?

B: [31:29] Leider noch nicht, aber wir wären jetzt dabei. Aber das macht jetzt hauptsächlich einer meiner Kollegen und ich weiß gar nicht, wie weit er gekommen ist. In diesem Semester bin ich tatsächlich nur mit dem Modul Projektmanagement beschäftigt. Wobei ich da auch langsam an dem Punkt angekommen bin, dass man das auch ziemlich gut unterstützen kann durch Tools. Also nicht nur im Bereich des Codings, sondern auch im Projektmanagement. Es gibt viele Lösungen zu Testdatenindividualisierung, welche man einsetzen kann. Wenn man konkret weiß, welche Testdaten man braucht, kann man sich zufällig genügend Datensätze generieren. Aber das ist jetzt nicht wirklich Individualisierung, sondern es handelt sich bloß um andere Testdaten.

I: [32:31] Was kennst du denn für Tools, mit dem man das auch in einem sehr großen Stil machen kann? Man hat ja oft mehrere hundert Studenten in einem Modul. Würde das in die Richtung gehen, was du gerade angesprochen hattest.

B: [32:42] Das weniger, also das sind eben nur unterschiedliche Testdaten, die man zufällig generieren kann. Aber das ist jetzt nicht wirklich die Lösung für das Problem. Da würde ich schon eher in die Richtung gehen, die ihr momentan einschlagt.

I: [33:03] Ein anderes Problem ist, dass wenn man dieses automatische Feedback von Tests betrachtet, ist das ja immer noch ein Unterschied zu dem Feedback von Betreuern, wenn diese eine Aufgabe korrigieren oder mit jemandem mal die Aufgabe durchgehen. In wie weit meinst du kann automatisch generiertes Feedback, das Feedback von Betreuern ersetzen?

B: [33:30] Meiner Meinung nach ist das schwierig, das würde man wahrscheinlich nicht so hinkriegen. Also man bekommt über automatische Tests schon konkretes Feedback, wenn man das Feedback vernünftig auf eine bestimmte Fehlermeldung reduziert. Aber man bekommt so kein Feedback zu dem eigentlichen Code. Es geht also um Feedback, welches auf Erfahrungen von Lehrenden basiert. Was man auch machen könnte, ist, dass man sowas wie ein Peer-Review Verfahren einbaut. Auch wenn alle Tests grün sind und alles wunderbar läuft, wird der Code nochmal durch ein anderes Team angeschaut, sodass es dann nochmal Feedback gibt. Als Lehrender würde man dann gewisse Qualitätskriterien vorgeben, wonach man den Code untersuchen sollte. Das wäre eine Möglichkeit und kann auch als Lernziel angesehen werden. Es gibt ja auch Tools, welche solche Verfahren unterstützen.

I: [35:45] Mit was für Plattformen hattest du bisher Kontakt, über die man generell Aufgaben an Studierende verteilen kann und auch später wieder Lösungen einsammeln kann?

B: [35:55] Ja, über Ilias, damit haben wir viel gemacht. Funktioniert tatsächlich auch ganz gut. Also wenn es jetzt nicht um Code geht, sondern um irgendwelche Abgaben. Dort gibt es Übungsmodule, wo man ziemlich feingranular einstellen kann, wann abgegeben werden soll, wer abgeben soll und was abgegeben werden soll. Für Source Code haben wir im Modul Algorithmik mal einen GitBucket verwendet. Da kann man dann nur ein Repository anlegen und schauen, dass die Studierenden das dann dort hochladen. Automatisierte Tests waren da aber auch nicht dabei. Früher haben wir die Aufgabenstellung an sich für Projekte im Master über Confluence und Jira verwaltet. Dass man das irgendwie automatisiert verteilt oder auch automatisiert Lösungen bekommt ist eben schwierig umzusetzen. Als ich hier anfing hatten wir damals eine Continuous Integration Lösung und Subversion eingesetzt. Da mussten damals schon die Studenten Maven nutzen und ihre Lösung commiten. Das hat nicht vielen gefallen, aber es wurde viel dabei gelernt.

I: [38:08] Eine Frage noch, und zwar Kommunikation zwischen den Lernenden und Lehrenden ist ja auch eine wichtige Komponente. Was ist deine Meinung zu modernen Messengern zur Kommunikation?

B: [38:26] Am besten sowas in Richtung Slack, dass man tatsächlich auch mal die Integration zu den Tools hat, aber dass man auch mitbekommt, wenn da irgendetwas gebaut wurde. Das ist etwas, was bei uns an der Hochschule wirklich fehlt. Momentan haben wir da Cisco Jabber, aber das ist eigentlich nur für die Lehrenden gedacht. Man kommt da an die Studenten nicht ran. Jetzt haben wir Zoom, darüber kann man auch kommunizieren. Es gibt einfach ziemlich viel an Tools und das wünsche ich mir unabhängig auch vom Coden, dass man irgendwie eine Lösung hätte für die Hochschule, welche auch Studierende mit einschließt. Diese kommunizieren nämlich ständig über Lösungen wie Discord, WhatsApp oder Facebook Messenger und müssen dann auch deren Daten freigeben. Dies muss nicht unbedingt sein, denn jeder hat einen Hochschul-Account und ich würde das auch trennen, auch aus Datenschutzgründen. Also meine Handynummer kennt auch schon fast jeder, aber ich wünschte mir, dass ich dann auch zuhause mal abschalten kann. Aber das fehlt wirklich noch bei uns. Ich würde mir das sehr wünschen, wenn es möglich wäre, dass man auch Integration über z.B. Chat Bots zu bestimmten Plattformen hat. Und dass man da vielleicht pro Modul auch separate Chats hat. Es gibt zwar das Ilias mit Forum. Aber dann bekommst du nicht direkt die Benachrichtigung. Das müsste man sich extra einschalten, dann bekommt man das per Mail. Da muss man sich dann einloggen und nochmal anschauen. Da ist natürlich Discord oder Slack ideal, aber leider noch nicht vorhanden für die Hochschule.
