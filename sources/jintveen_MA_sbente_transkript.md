---
acronym: sbente
type: literature reference
title: Interview Transkript Bente
responsible: 
    - ako
publisher: none
source_url: none
history:
    v1:
        date: 2021-06-15
        comment: initially created

---

## Transkript des Interviews mit Prof. Dr. Stefan Bente 

Interviewpartner: Prof. Dr. Stefan Bente
Datum: 29.12.2020

## Inhalt

1 I: [00:01] Was sind deiner Meinung nach die wichtigsten Werkzeuge, die man braucht,
wenn man modernes Coding betreibt?

B: [00:16] Also du musst vertraut sein mit einer modernen IDE, also üblicherweise IntelliJ
oder VS Code. Du musst vertraut sein mit Git, mit den wichtigsten Kommandos zumindest. Wir haben das im Kollegenkreis mal diskutiert und ich habe mich da überzeugen
lassen, dass die Verwendung von der Git Bash eine gute Sache ist, weil man dadurch
nochmal ein bisschen besser versteht, wie Git eigentlich funktioniert. Docker sollte man
sicherlich kennen. Generell sollte man eine CI / CD Pipeline einrichten können. Man sollte sich mit einer Plattform wie GitHub oder GitLab auskennen, was über die reinen Git
Befehle hinaus geht. Diese Dienste bieten dann zum Teil auch an, dass man die Build
Pipeline dann dort konfiguriert oder dass man z.B. sowas wie die GitHub oder Gitlab
pages benutzt, also saubere Dokumentationsgenerierung. Das wäre so die Tool Chain, die
im Groben aus meiner Sicht zentral ist für modernes oder aktuelles Coding. So etwas
wie Spring habe ich jetzt rausgelassen, weil ich nicht weiß, ob du das als Werkzeug sehen
würdest.

I: [01:50] Ja, ich hatte da schon in die Richtung gedacht, die du auch eingeschlagen hattest.

B: [01:57] Gut, ich finde das auch nochmal relativ zentral, aber vielleicht kommt das noch
in einer anderen Frage.

I: [02:08] Du hattest eben modernes Coding erwähnt. Was macht denn aus deiner Sicht
überhaupt modernes Coding aus?

B: [02:24] Also, dass man seinen Code so schreibt, dass er nachhaltig ist und von einem
selber, aber auch von Kollegen oder sonstigen Mitarbeitenden noch einen Monat nach Erstellung, ein halbes Jahr nach Erstellung oder auch zwei Jahre nach Erstellung verstanden
werden kann. Das hat unmittelbar etwas mit der Wartbarkeit des Codes zu tun. Das hat
aber auch damit zu tun, dass der Code auf der untersten, atomaren Ebene, letztlich zu
einer guten und auch nachhaltig wartbaren Architektur beiträgt.

I: [03:16] Du gehst also in die Richtung von Qualitätskriterien und machst das daran fest?

B: [03:26] Was mich am meisten überzeugt aus der Literatur sind die Ansätze von Bob
Martin aus dem Clean Code, dass man nämlich so ein paar leicht merkbare einsichtige Regeln für guten Code definiert. Ich finde auch so einen Ansatz wie Test-Driven Development
sehr sinnvoll und gut, bei dem man im Prinzip die Funktionalität, die man implementiert,
erst mal in Form von Tests abbildet, damit man nachher in kleinen Schritten gegen diesen Test implementieren kann. Wenn ich TDD mache, verlagere ich also Iterationen von
Fachlichkeit zur Implementierung in ganz kleine Schleifen. Das empfinde ich als ein sehr
sinnvolles Vorgehen und ich mache das auch selber, wenn ich programmiere. Und dann
könnte man noch folgendes ergänzen, denn du hattest ja gefragt, was modernes Coding
ist: Ich würde sagen, auf der etwas höheren Warte gehört für mich auch dazu, nach einem
Ansatz wie dem Domain Driven Design vorzugehen. Dass man also die Prinzipien einhält,
die das TDD fordert, also primär versucht, die Fachlichkeit angemessen zu durchdringen und zu verstehen. Dass man auch versucht, die Fachlichkeit in abgegrenzte Kontexte
zu zerteilen, sodass man dann ohne wahnsinnig viel Absprache autark arbeiten kann als
kleines Team. Dazu gehört auch, dass man akzeptiert, dass man in Iterationen arbeiten
muss. Also dieses Paradigma “Getting it right the first time“ als Paradigma von gestern
wahrnehme und einfach eher davon ausgehe, ich muss mehrere Iterationen machen, ich
muss die schnell hintereinander machen. So hat man mehr Zeit, ein Problem mehrfach zu
durchdenken, bis man es dann wirklich verstanden hat.

I: [05:57] Ich hätte eine generelle Frage, auf Programmiersprachen bezogen. Es gibt ja viele
Programmiersprachen, die auch als modern gelten, deswegen wäre meine Frage, was für
Programmiersprachen fallen dir ein, welche viele Paradigmen vereinen, die sehr modern
sind?

B: [06:22] Die Diskussion, die ich eigentlich mit Kollegen immer habe, wenn es darum
geht, wie mache ich Basis Coding Kurse, ist dann eher die Frage, ob wir es in Java oder in
Kotlin machen. Das sind eigentlich so die beiden Pole, die mir da im Moment am ehesten
einfallen. Ich nehme wahr, dass eine große Menge von JVM basierten Sprachen existieren,
die alle so ihre Meriten haben. Also ich habe vor 15 Jahren mal ein größeres Projekt in
Groovy gemacht, war da auch ein großer Fan von, weil Groovy einer der ersten Vertreter
von diesen JVM Sprachen war, kompatibel zu Java, aber ohne diesen ganzen Boilerplate
Ansatz, den man bei Java so hat. Mich hat das sehr überzeugt und es hat mir sehr viel
Spaß gemacht. Von daher verstehe ich auch die Faszination für Kotlin. Ich finde, dass
die Leute, wenn sie von uns weggehen, auf jeden Fall Java können müssen, denn immer
noch ein Großteil der Projekte, die gemacht werden, werden in Java gemacht. Und ich
finde auch, dass man sich sozusagen eine Haltung angewöhnen sollte, dass man nicht nur
einfach Sprache X oder Sprache Y kann, sondern dass sozusagen das Erlernen und Ausprobieren neuer Sprachen, abhängig auch von der Problemstellung, essentiell zum guten
Codieren dazugehört. Man sollte also eine Sprache wie Rust auch mal auf dem Schirm
haben und schauen, ob die Sprache z.B. gut funktioniert, wenn man etwas performantes
braucht. Oder vielleicht gibt es mal eine Anwendung, die ich vielleicht in Django machen
möchte, um zu schauen, ob das richtig schön ist. Also ich finde, das ist eine Haltung, die
auch zum Codieren dazugehört.

I: [08:26] Du sagtest, Kotlin ist eine moderne schöne Sprache. Java lehrt man eher, weil
es sehr weit verbreitet ist. Was würdest du aber jetzt höher priorisieren in der Lehre?
Würdest du eher Sprachen lehren, die sehr weit verbreitet sind oder eher Sprachen lehren,
die ebenso wie Kotlin sehr modern sind?

B: [08:47] Ich bin schon ein großer Java Fan. Ich wurde früher mit Turbo Pascal sozialisiert, so alt bin ich dann schon. Das ist das erste, was ich im Studium gelernt habe,
dann kam Modula zwei. Danach musste ich harte Jahre von Fortran erleiden, also auch
die Objektorientierung von Fortran in Richtung Fortran 90. Das war eher halbgar und
dann kam schon Java. Ich war nie so ein Microsoft Mensch, diese C# Richtung habe
ich nie aktiv gemacht. Das heißt also, ich habe mehr oder weniger mein ganzes aktives
Programmiererleben und die Zeit, die ich als Architekt verbracht habe, wo ich dann nicht
mehr so viel programmiert habe, nur in Java programmiert. Von daher bin ich da schon
ein Fan und finde Java auch nicht unmodern. Es hat eben ein paar Schwächen. Es ist halt
sehr groß und manchmal auch sehr umständlich. Diese moderneren Sprachen sind dann
eleganter in bestimmter Hinsicht. Und deswegen finde ich es auch schön und sinnvoll, sich
damit zu beschäftigen. Also wie gesagt, Groovy hat mir wahnsinnig viel Spaß gemacht,
ich fand das ganz toll. Ich finde es auch jetzt immer noch toll, mal was Neues auszuprobieren. Auch wenn man bestimmte Sprachen nicht so richtig gut findet, sollte man sie
sich trotzdem, wenn man die Zeit und die Gelegenheit hat, mal anschauen. Ich denke da
z.B. an sowas wie Python, weil es im ganzen Machine Learning Umfeld weit verbreitet
ist. Der Ansatz “Keeping an open mind“ wäre mir an dieser Stelle sehr wichtig, auch für
mich selber. Mit Blick auf Leere würde ich aber schon priorisieren, dass die Leute mit der
aktuellen Brot und Butter Sprache definitiv auch am meisten konfrontiert werden. Das
ist im Moment nach wie vor Java. Oder z.B. auch C#, wenn man sagt, wir bilden die
Leute für einen Microsoft Weg aus. Und daneben vermittelt man die Haltung, dass wenn
man eine Sprache kann, dann kann man auch ganz viele oder man kann sie sich schnell
beibringen.

I: [11:12] Als ich eben gefragt hatte, was für dich modernes Coding ist, hattest du Clean
Code erwähnt. Und zwar meine Frage wäre jetzt, wie kann man denn Lernende dazu
bringen, dass sie sich auch an Richtlinien halten, welche zu sauberen Code führen?

B: [11:32] Indem man es zum Thema macht. Ich bin eigentlich nach wie vor sehr glücklich
damit, wie wir das in Code & Context gemacht haben. Einige Kollegen und ich führen
diesen Studiengang sehr Werkstatt orientiert und sehr Hands on. Bei Clean Code habe
ich die gerade berufene Professur für Agile Coding vertreten und wir haben letztlich das
Programmierbeispiel wieder aufgenommen, was wir bei Coding Essentials zwei gemacht
haben, wo du auch mit dabei warst. Da haben die Studierenden ja zum Schluss ein Text
Adventure geschrieben, und da kamen irgendwie so 10 Texte Adventures dabei raus. Und
in Clean Code sind wir dann natürlich die Inhalte durchgegangen, kleine Übungen gemacht, und haben ihnen dann die Aufgabe gegeben: Jetzt nehmt euch nochmal euren
Code von vor einem halben Jahr vor und schaut ihn euch nochmal kritisch an und überarbeitet den mit dem, was ihr hier gelernt habt. Beachtet also mal die Regeln aus dem
Clean Code und versucht dabei mal TDD anzuwenden. Das war total effektiv. Von den
Studierenden kam ganz viel Feedback, dass diese jetzt sehen, dass sie ihren eigenen Code
nicht mehr verstanden haben und jetzt sehen, was jetzt besser ist als vor einem halben
Jahr. Solche Veranstaltungen würde ich mir gerne mehr wünschen. Das hat im Moment
in dem Informatik Bachelorstudiengang bei uns nicht richtig eine Heimat. Das finde ich
sehr schade.

I: [13:35] Du meinst quasi, man macht es in extra Fächern zum Thema und zeigt den
Leuten, was es bringt und was man daraus lernen kann. Kennst du praktikable Wege,
wie man das in Aufgaben, die die Studenten lösen, auch erzwingen kann, wenn man jetzt
nicht diese Kapazitäten hat, das in extra Fächer zu verpacken?

B: [13:59] Man kann es natürlich versuchen als Inhalte in die existierenden Fächer reinzubauen. Wir hätten ja Fächer, wo man das durchaus zum Thema machen kann oder
vielleicht wird es auch teilweise schon zum Thema gemacht. Ich kann da jetzt für die
Kollegen nicht sprechen. Also vielleicht ist es bei Algorithmen und Programmierung oder
bei Paradigmen der Programmierung zum Teil mit drin. Jetzt hast du gefragt, wie man
das erzwingen kann. Man kann es wie gesagt ein bisschen zum Thema machen und dann
kann man natürlich versuchen, den Weg zu gehen, den wir hier ja auch in Softwaretechnik
beschritten haben. Dass man eben versucht, den Code automatisch zu prüfen. Also erst
mal überhaupt die Studierenden im Praktikum Code schreiben lässt und den Code nicht
mehr manuell nachguckt, sondern automatisch nachprüfen lässt. Einfach damit es effizient ist und damit man sich nicht in Arbeit verliert. Und dann kann man natürlich auch
hingehen und mit SonarQube bestimmte Qualitätsmetriken aufstellen. Manches wird da
leichter sein, manches wird nicht so leicht sein. Z.B. eine Methodenlänge oder eine Klassenlänge zu bewerten wird gehen, aber die Vergabe von sinnvollen Methodennamen und
Variablennamen wird wahrscheinlich schwierig automatisch zu prüfen sein.

I: [15:57] Jetzt hast du ja schon mal ein paar Richtlinien genannt? Was wären denn da
konkrete Richtlinien, die du besonders wichtig finden würdest, dass man diese überprüft,
wenn es denn möglich ist?

B: [16:26] Also die Methodenlänge wäre schon mal definitiv ein Punkt. Das wäre wahrscheinlich relativ leicht rauszukriegen, wenn man nochmal über die einzelnen Bestandteile
des Clean Code Ansatzes drüber geht und schaut, was man denn mit vertretbarem Aufwand umsetzen kann. Und vielleicht auch schauen, was schon in dem Standard Regelsatz
von SonarQube enthalten ist. Das wäre jetzt eher eine Fleißarbeit, finde ich. Das fällt mir
aus dem Stehgreif ein bisschen schwer.

I: [17:19] Du hattest eben auch nochmal Domain Driven Design erwähnt und wie wichtig das ist. Aber Domain Driven Design ist ja auch eine Herangehensweise für eigentlich
komplexere Software, die man auch gut in einzelne Bereiche zerteilen kann. Wenn man
das jetzt aber lehren möchte, hat man oft das Problem, dass die Übungsaufgaben von der
Komplexität ja eher geringer ausfallen, weil man auch einfach diese Kapazität nicht hat.
Wie kann man denn dann durch diese Übungsaufgaben trotzdem einen guten Lerneffekt
erzielen?

B: [18:07] Ich denke, dass man beim Tactical Design eher noch ein leichteres Spiel hat als
beim Strategic Design. Die Building Blocks lehren wir ja auch jetzt schon. Man kann die
Unterscheidung zwischen Entity und Value Object abfragen. Man kann die Studierenden
trainieren, in sowas wie einer Ubiquitous Language zu denken und mit Begriffen sehr genau umzugehen. Auch das machen wir jetzt schon, indem wir quasi ein fachliches Glossar
erstellen lassen. Mit den jetzigen Mitteln könnten wir auch automatisch prüfen lassen,
ob das Glossar die richtigen Begriffe enthält. Ich würde die Aufgabenbeschreibung etwas
länger machen als sie es jetzt bei uns war. Jetzt war sie ungefähr eine halbe Seite lang und
da habe ich an den Rückfragen der Studierenden sehr oft gemerkt, dass da zu viel Gewicht
auf einzelnen kurzen Formulierungen war. Dies ist zu anfällig für Missverständnisse. Wenn
man die Studierenden ein bisschen mit der Nase drauf stoßen will, was ist denn z.B. jetzt
an Value Object oder ein Entity, dann sollte man das schon ein bisschen ausführlicher
beschreiben, sonst ist es einfach wirklich zu schwierig. Und wenn man zum Beispiel die
Studierenden dazu bringen will, Aggregatgrenzen festzulegen, dann muss man auch da
eigentlich mehr Text haben. Wenn ich in Richtung Strategic Design gehe, also z.B. einen
Bounded Context Schnitt mache, dann habe ich das Gefühl, dass das im Rahmen von
Vorlesungen wirklich sehr schwierig ist. So etwas wird man auch nicht mehr gut automatisch abprüfen können. Da wäre ich eher der Ansicht, dass man den Schnitt eher vorgibt.
Meine Lehre funktioniert im Moment so, dass ich diesen Teil eher im Master mache und
auch da häufig diesen ersten Schritt des Schnitts aus Zeitgründen nicht mache. Dabei fällt
generell dieses iterative Prinzip des DDD mehr oder weniger komplett über Bord, weil
man dafür nicht die Zeit hat. Also eigentlich müsste ich ja sagen, ich werfe etwas einmal
weg, zweimal weg, dreimal weg, mache es dreimal neu und habe eine Fachseite, die so
geduldig ist, dass sie immer wieder alle Fragen beantwortet. Ich wüsste nicht, wie das in
der Lehre zu realisieren wäre.

I: [21:12] Aber das ist ja schon mal ein Ansatz, dass man einfach gewisse Vorgaben macht.
Man ist zwar ein bisschen eingeschränkt, aber hat trotzdem die Möglichkeit, überhaupt
Übungen zum Tactical Design zu machen. Ich würde jetzt mal in Richtung Kooperation
und Organisation von Praktika übergehen. Wenn man jetzt davon ausgeht, man würde
Übungsaufgaben auch bewerten, würdest du da eher Einzelarbeit oder Gruppenarbeit bevorzugen?

B: [21:47] Da habe ich eine ganz klare Haltung mittlerweile zu entwickelt. Ich möchte
Gruppenarbeit, aber einzelne Abgaben haben. Und dann würde ich sehr gerne an dem
Thema der Individualisierung noch weiterarbeiten. Wir haben jetzt ein Maß an Individualisierung zwischen den verschiedenen Varianten, das doch noch relativ leicht durchschaubar ist. Das ist schon mal nicht schlecht, aber das hätte ich gerne noch ein bisschen
besser. Also der eine Gedanke ist: Ich möchte keine Gruppenarbeiten mehr. Ich bin so
verbrannt von Abgaben in diesen herkömmlichen Praktika. Da hast du immer einen Wortführer, der immer alles für die ganze Gruppe erzählt und dann versuchst du irgendwie
ganz mühsam Sonderregeln einzuführen, dass z.B. jetzt auch mal jemand anders vorstellen
muss. Man merkt dann ganz deutlich, dass derjenige sich das eine Viertelstunde vor dem
Praktikumstermin mal eben angeschaut hat und kann so gerade die wesentlichen Dinge
erklären. Eigentlich müsstest du ihm das rechts und links um die Ohren hauen, aber das
machst du eben nicht, weil es dann auch nicht wirklich quantifizierbar ist. Du hast zwar
das Gefühl, wirklich tief bohren kann ich hier nicht, aber er hat eigentlich formal die Anforderungen erfüllt, die du gestellt hast. Ich habe da einfach keine Lust mehr drauf und
das ist nicht effektiv. Ich verstehe, dass die Leute dazu neigen, arbeitsteilig vorzugehen.
Das Studium sorgt zwar für eine große Belastung, aber trotzdem ist das Ergebnis der
Studenten oft überhaupt nicht zufriedenstellend. Deswegen finde ich das Prinzip, so wie
wir es jetzt fahren, deutlich besser. Also die müssen alle ihre individuelle Lösung abgeben,
aber natürlich arbeiten die in Gruppen zusammen und wir ermutigen sie auch, das zu tun.
Die sollen diskutieren und auch gerne ihre Lösungen vergleichen und dann sehen sie eben
die Ähnlichkeiten. Aber sie müssen es immer noch selber umsetzen, weil sie sonst keine
grünen Tests bekommen. Und ich glaube, das ist so der der Weg, der sinnvoll ist. Und
gerne hätte ich noch eine Individualisierung, die dieses Storytelling bei der Aufgabenstellung noch ein bisschen vereinfacht. Wenn man z.B. Beziehungstypen individualisiert, ist
es dennoch sehr schwierig, dies vernünftig in den Aufgabentext zu transportieren. Man
möchte ja eine Story erstellen, die konsistent bleibt, egal ob eine Beziehung jetzt 1 zu n
oder n zu m ist. Wenn wir so weit sind, dann wäre ich wirklich zufrieden.

I: [24:45] Zusammenfassend findest du auf jeden Fall Gruppenarbeit super, aber hast
trotzdem lieber einzelne Abgaben. Was würdest du denn da von Pair-Programming in
Abgrenzung zu Gruppenarbeit halten?

B: [24:59] Ich finde, das ist auch ein sehr spannender Ansatz. Wir haben bei Code &
Context ein paar Mal versucht, die Leute zu Pair-Programming zu animieren. Die Leute
haben sich dann in Peers zusammengefunden und wir haben ihnen dann die Regeln für
Pair-Programming erklärt. Das hat bei Code & Context relativ gut funktioniert. Bei Code
& Context haben wir eine Gruppe von ca. 20 Personen im ersten Jahrgang, die als Gruppe
gut funktioniert haben. Da war also so ein gewisses Maß an Gruppendruck da und die
haben sich gegenseitig auch ein bisschen dazu animiert, solche Vorgaben auch einzuhalten. Das ist in der allgemeinen Informatik bei uns alles ein bisschen anonymer und da
müsste man noch mal einen Weg finden, wie man sowas wie Pair-Programming tatsächlich
erzwingen kann in der Bearbeitung. Da sehe ich im Moment nicht wirklich einen Weg,
wie ich das aktiv gestalten kann. Wenn ich ein Setting definieren könnte, wo 90 Prozent
oder 80 Prozent der Leute dabei mitmachen, wäre ich auch schon zufrieden. Dann müsste
ich es gar nicht erzwingen. Aber auch da wüsste ich nicht, wie ich das machen sollte.
Wenn ich einfach nur sage, wir machen 50 Sprachkanäle auf und geht mal bitte auf die 
Sprachkanäle, dann weiß ich nicht, wie viele von denen das wirklich mitmachen würden.
Da müsste man glaube ich noch ein bisschen mehr aktive Hinführung betreiben.

I: [26:47] Man hört ja heraus, dass man Studenten oft Druck machen muss, damit diese
eben auch mal was machen. Es gibt ja verschiedene Arten, diesen Druck zu erzeugen. Eine
Möglichkeit wäre ja, den Druck durch Individualisierung, Noten oder durch bestanden,
nicht bestanden zu erzeugen. Aber auf der anderen Seite kann man auch manchmal ein
motivierendes Lernklima erzeugen, bei dem man diesen künstlichen Druck vielleicht nicht
braucht. Die Frage ist jetzt, unter welchen Umständen meinst du, kann welcher Ansatz
funktionieren und sollte dann auch verfolgt werden?

B: [27:34] Das ist wirklich die absolute Schlüsselfrage. Also bei Code & Context merken
wir, dass es mit dem ersten Jahrgang ganz ordentlich funktioniert hat. Wir sind jetzt im
zweiten Jahrgang, da sind es jetzt ca. vierzig Personen. Ich habe einen Kurs mit denen
zusammen gemacht, das war Computational Thinking und das hat auch ganz gut funktioniert. Das ist jetzt so ein Datenpunkt und reicht natürlich noch nicht wirklich für eine
Bewertung. Also da spielt so dieser Werkstatt Charakter eine Rolle und der Fakt, dass
die als ein geschlossener Jahrgang immer durch diese einzelnen Blöcke durchgehen. Die
verbringen eigentlich viel mehr Zeit immer in der gleichen Konstellation als das unsere
Studierenden tun. Man könnte auch sagen, das Maß an Verbindlichkeit ist viel höher.
Nicht durch zwangsweise Vorgaben, sondern einfach dadurch, dass wir eine Tagesstruktur
definieren und die Studierenden dann einfach mitgehen, weil sie sozusagen diese Tagesstruktur einfach akzeptieren und annehmen. Also wenn wir es hier in der allgemeinen
Informatik auch schaffen würden, mehr im Block zu arbeiten, wäre ich sehr zuversichtlich, dass wir es auch schaffen würden, so ein Lernklima stärker herzustellen. Ich bin durch
Code & Context, aber vorher auch schon, wirklich bestärkt worden, dass Block Lehre richtig gut ist. Es tut einfach gut, mal weg von Task-Switching zu gehen und stattdessen mal
für längere Zeit in einem Thema zu bleiben.

I: [29:28] Du hattest ja eben das Thema Individualisierung angesprochen. Was sind dir
denn so für Individualisierungsmethoden bekannt, mit denen man Aufgaben in einem Maß
individualisieren kann, sodass ein einfaches Kopieren gar nicht mehr möglich ist?

B: [29:41] Also Ilias liefert ja zum Beispiel diese Fragenpools, wo du dann irgendwie eine
Menge an Aufgaben definierst und diese dann zufällig den einzelnen Personen zugeordnet
werden. Das würde definitiv gehen. Darüber hinaus habe ich tatsächlich nicht groß recherchiert, was es sonst noch an fertigen Lösungen gegeben hätte. Als wir darüber nachgedacht
haben, wie wir das machen können für Softwaretechnik, da ergab sich aus meiner Sicht
relativ schnell, dass wir eine ziemlich spezielle Aufgabenstellung vor uns hatten. Ich hätte
nicht gewusst, wo man da was hätte suchen können. Ich denke, den Ansatz, den wir da
gewählt haben, der ist schon ganz gut angepasst auf das, was wir in dieser Veranstaltung
machen wollen. Diese Mischung umfasst fachliche Analyse, die ein bisschen vom Geist des
DDD geprägt ist, Modellierung und andererseits die Umsetzung dessen in Code. Dafür
brauchst du glaube ich schon eine maßgeschneiderte Lösung und ich finde, da sind wir
auf einem ganz guten Weg mit der Implementierung dieser Lösung.

I: [31:15] Was wäre aus deiner Sicht wichtiger: Dass man schaut, dass man wirklich einen
hohen Grad an Individualisierung schafft oder dass man trotzdem noch eine sehr konsistente Geschichte hat. Du sagtest ja eben, du würdest auch lieber längere Aufgabentexte
haben. Ich würde das aber trotzdem gerne mal fragen: Welcher Ansatz von den beiden
wäre also für dich wichtiger?

B: [31:38] Ich glaube, ich würde die Konsistenz der Geschichte höher bewerten, weil es
absolut mein Anspruch ist, dass die Leute in meinen Modulen ST1 und ST2 vom gesprochenen Wort anfangen. Sie sollen bei den Anforderungen anfangen und nicht sofort bei
der Technik ansetzen. Es zieht sich ja wirklich eigentlich durch alles durch, was ich mit
Studierenden mache, dass ich bei der Fachlichkeit ansetze. Und wenn ich dann nur so eine
Sammlung von technisch geprägten Aussagen habe, dann ergibt sich kein fachliches Bild.
Die allererste Version bei ST2 war ja so geprägt, dass wir das sehr technisch formuliert
haben. Und damit bekommt man diesen ersten Schritt von der Fachlichkeit zur Technik
nicht hin. Schön wäre es natürlich, um es nochmal zu sagen, wenn man beides hinkriegen
könnte.

I: [33:05] Auch wenn man beides will, hat man leider immer einen kleinen Zielkonflikt
zwischen den zwei Sachen. Also selbst wenn man den Zielkonflikt weitestgehend auflösen
würde, hätte man wahrscheinlich doch mehr Möglichkeiten, wenn man die Fachlichkeit
außen vor lässt.

B: [33:19] Also dann würde ich da gerne noch etwas anschließen. Also für die Weiterentwicklung des Toolings auf längere Sicht würde ich mir wünschen, dass wir da das Schreiben
von Ausgangstexten etwas erleichtern. Durch Platzhalter zur Individualisierung in Form
von Variablen werden zum Beispiel die Texte fast unlesbar im Rohformat. Und ich glaube,
dass man da durchaus nochmal nach Ansätzen schauen könnte. Da würde ich auch nochmal ein bisschen in die Recherche gehen, was es da so sonst noch so gibt an irgendwelchen
Markup Sprachen, die einfach dieses Schreiben von Geschichten leichter machen. Also ich
weiß, dass mir persönlich das ganz gut liegt. Ich kann ganz gut so Geschichten schreiben,
die dann in Aufgaben münden. Ich denke mir auch sehr gerne Geschichten aus, die man
dann in Code umwandeln könnte. Und da würde ich mir gerne mehr Potential wünschen,
die Kreativität austoben zu lassen. Weil dann kannst du komplexere Geschichten erzählen. Und wenn sie dann noch ein bisschen stärker individualisierter sind, ist das gut, aber
wenn nicht, sind diese zumindest erst einmal so komplex, dass sie der Wirklichkeit näher
kommen.

I: [34:45] Jetzt würde ich mal zu einem Problem von Individualisierung übergehen. Es
kann ja sein, dass durch Individualisierung der Schwierigkeitsgrad abweicht zwischen einzelnen Aufgaben, die verschiedene Lernende bekommen. Wie ist deine Meinung dazu?

B: [34:58] Das ist natürlich blöd. Bei Softwaretechnik 1 und 2 hatten wir mal ein RestaurantManagementsystem als Beispiel. Da haben wir dann verschiedene Bounded Contexte definiert und diese haben wir dann den einzelnen Praktikumsgruppen zugeteilt. Und das
war dann doch sehr unterschiedlich schwer. Die eine Gruppe hatte im Statusdiagramm
dann z.B. zwei Status und die andere Gruppe hatte acht Status, das waren so die Extreme. Dafür war das dann aber bei anderen Aspekten der Aufgabenstellung wieder anders
gemischt. Richtig zufrieden hat mich das nicht gemacht. Also da hätte ich gerne eine
etwas höhere Konsistenz und da habe ich das Gefühl, dass der Ansatz, den wir jetzt fahren, besser ist. Also dass jeder quasi eine wirklich auf ihn oder sie selbst zugeschnittene
Aufgabe bekommt. Weil dann hat man wirklich eine relativ homogene Verteilung des
Schwierigkeitsgrade, natürlich mit dem Preis, dass die einzelnen Lösungen eben nicht so
stark voneinander abweichen. Und wenn dann jemand mit kritischem Blick drauf guckt,
wird er verstehen, wie die Individualisierungen zustande kommen und Lösungen kopieren können. Auf der anderen Seite würde ich damit dann im Zweifel leben, weil dann
heißt es immer noch, dass ich mir die Lösung von jemand anders anschauen, diese verstehen und dann auf meine Lösung übertragen muss. Damit hätte ich schon einen Grad
an Mindestverständnis garantiert, was mir als Praktikums Ergebnis schon genügen würde.

I: [37:10] Du hast eben erwähnt, dass das Schreiben von Aufgabentexten sehr schwierig
sein kann, wenn es um eine Aufgabe geht, die auch individualisiert werden kann. Wie viel
Mehraufwand wärst du bereit zu investieren, eben solche Texte zu schreiben im Vergleich
zu Texten von einfachen ganz normalen Aufgaben?

B: [37:33] Also ich habe das bis jetzt schon zwei Mal gemacht. Einmal für die ST2 Klausur und einmal für ST1, das war jedes Mal ein Gesamtkunstwerk. Das schwierige ist, dass
du eine Geschichte von hinten erdenken musst. Also insofern, dass man überlegt, welche
Aspekte will ich am Ende noch alle drin haben. Ich fange letztlich bei der Musterlösung
an. Erstelle also eine Art generische Musterlösung und entwickle die dann von hinten nach
vorne, bis ich dann dazu einen Aufgabentext schreiben kann. So ein Entwicklungsprozess
ist aufwendig, aber das ist aus meiner Sicht gut investierte Zeit. Weil mir würde kein
besserer Weg einfallen, um am Ende den Studierenden eine Aufgabenstellung zu präsentieren, die relativ nah an dem ist, was man dann später bei einem richtigen Kunden auch
zu Gesicht bekommen würde in Form eines Anforderungsdokuments.

I: [38:54] Ich würde jetzt mal in Richtung Automatisierung übergehen. Zuerst einmal eine
ganz generelle Frage: Was müssen Übungsaufgaben für Eigenschaften aufweisen, damit
man diese überhaupt automatisch überprüfen kann?

B: [39:23] Man braucht eine gewisse Eindeutigkeit der Antwort. Dazu zählen Fragen wie
z.B. “Was ist ein Entity, was ist ein Value Objekt?“ oder “Welche Klassen sind im logischen Datenmodell noch enthalten?“. Dann müsste ich sicherstellen, dass ich sinnvolle
Fehlermeldungen gebe. Da ist das Tooling, was wir jetzt haben z.B. an einer Stelle noch
nicht gut genug. Wenn quasi nur die Meldung zurückkommt, die Tabelle stimmt so nicht,
irgendwo ist ein Fehler, dann ist dieses Feedback so nicht ausreichend. Das ist einfach
ein Punkt, wo wir weiter dran arbeiten müssten, sodass man an dieser Stelle einen Weg
findet, auf das Problem hinzuweisen, ohne jetzt zu viel zu verraten. Die Leute sollen ja
auch nicht mit “Trial and Error“ nach zehn Minuten die Lösung gefunden haben. Das
ist dann eine Herausforderung, der man sich stellen muss. Was z.B. nicht so gut geht,
ist die Bewertung eines Modells, welches die Leute als UML Diagramm hochladen. Da
wüsste ich tatsächlich im Moment noch nicht, wie man mit den jetzigen Mitteln sinnvoll
automatisch prüfen könnte. In ST2 konnten wir tatsächlich komplett automatisch testen.
In ST1, wo es sehr stark noch um diese Anforderungsermittlung und das Aufstellen von
Domainmodellen geht, hätten wir wahrscheinlich den manuellen Aufwand auf sagen wir
mal 20 bis 30 Prozent drücken können. Im Moment war der manuelle Aufwand leider viel
höher, aber wir sind ja in der Entwicklung.

I: [41:32] Ein anderes Problem von automatischer Überprüfbarkeit ist ja, dass man eine
gewisse Eindeutigkeit braucht und deshalb auch gewisse Dinge verlangt, welche die Freiheit von Lernenden einschränken, die Übungsaufgaben lösen sollen. Hast du da Ideen, wie
man das ein bisschen vereinen kann?

B: [42:27] Man muss schon schauen, dass man eher in Richtung von Contract basiertem
Testen geht. Also wenn man mal Rest API’s als Beispiel nimmt, da geht das finde ich
richtig gut. Ich erwarte dann von dem API, dass es mir auf diese Anfrage jene Antwort zurück liefert. Dann könnte ich den Leuten in der Umsetzung erstmal komplett überlassen,
wie sie es machen. Dann könnte ich mit gewissen Sonarqube basierten Mitteln vielleicht
nochmal überprüfen, ob sie z.B. einen Application Service implementieren. Wenn wir also
sagen, also nach DDD gibt es eben diesen Application Layer und implementiere bitte
immer einen Application Service und gib z.B. kein Entity nach draußen und so weiter.
Das kann man wiederum ganz gut überprüfen. Und wie sie es im Detail machen, könnte
man ihnen überlassen.

I: [43:40] Das heißt also, dass man gewisse Vorgaben macht, aber den Rest frei lässt.

B: [43:47] Genau, ich meine Contract basiertes Testing oder auch Black-Box Testing, was
so das Testen von Schnittstellen angeht. Dazu würde man noch das Einhalten von Design
Prinzipien und Clean Code abtesten. Dann könnte man diese SOLID Prinzipien von Bob
Martin dann auch noch mit reinnehmen. Man würde dann diese Black-Box Tests, also
diese Contract basierten Tests, um Tests anreichern, welche Architekturprinzipien abdecken. Wenn wir sagen, es ist uns wichtig in der Veranstaltung, dass die Studierenden an
dieser Stelle dieses und jenes einhalten, dann gibt es dann da einen Test für.

I: [44:41] Jetzt geht es noch ein bisschen Richtung Tooling. Das deckt dann auch automatisches Testing und Individualisierung ab. Hast du schon mal Tools zur Aufgabenindividualisierung in der praxisorientierten Lehre angewendet? Du hast ja schon ein paar
genannt, aber fallen dir noch ein paar ein, die du verwendet hast?

B: [45:14] Ich habe das tatsächlich noch nie vorher gemacht. Dass ich bei Software Technik
die Leute auch Coden lasse, ist relativ neu. Ich mache sonst keine Coding Ausbildung,
das machen andere Kollegen. Mit diesen Ilias Ansätzen habe ich mal kurz experimentiert,
fand diese aber ein bisschen einengend und unkreativ. Ich fand dann eine maßgeschneiderte Lösung irgendwie attraktiver. Aber wie gesagt, richtig systematisch recherchiert habe
ich das tatsächlich nicht, weil mir der Glaube gefehlt hat, dass sich so eine Recherche
lohnt und dass man da was von der Stange findet, was dann so gut auf die eigene Lehrveranstaltung passt.

I: [46:05] Wir haben ja eben auch viel über automatische Überprüfung gesprochen. Inwieweit meinst du, kann Feedback von automatischer Überprüfung das Feedback von
manueller Korrektur oder Lehrenden ersetzen?

B: [46:21] Ich glaube, dass es das nicht ersetzen kann. Also man sollte unbedingt solche automatisch abgenommenen Praktikumsleistungen flankieren mit Beratungsstunden.
Auch da bin ich eigentlich wieder ganz zufrieden mit diesen Discord Sessions, die wir
gemacht haben. Wo wir dann gesagt haben, wir sind einfach als Betreuungsteam da und
machen vielleicht nochmal so kurze Impulse von Sachen, die man öfter mal sieht und die
falsch gemacht wurden. Oder man macht gezielt Übungen zu neuen Inhalten. Und dann
gibt es aber auch eine Phase, wo sich die Leute einfach in diesen Sprachgruppen treffen
können und das Betreuungsteam herbeirufen, sodass man Probleme mit denen bespricht
und inhaltliche Fragen klärt. Das funktioniert aus meiner Sicht online wirklich mehr oder
weniger genauso gut wird es live funktionieren würde. Also live würde man ebenso einen
großen Raum nehmen, wo sich die Leute an verschiedene Tische setzen können. Oder sie
sitzen in verschiedenen kleinen Räumen in Kleingruppen zusammen. Ob man nun virtuell
sozusagen von Team zu Team geht oder in einem physischen Raum von Team zu Team
geht, ist fast egal. Das funktioniert glaube ich beides ganz gut.

I: [47:41] Wir haben jetzt viel über Übungsaufgaben gesprochen und diese müssen auch
erstmal irgendwie an Studenten verteilt werden und am Ende muss man ja die Lösung
auch wieder einsammeln. Und wenn man dann eine ganze Menge an Studenten hat, kann
das echt viel Aufwand sein. Das heißt, dass man ja oft eine Plattform hat, über die das
abläuft. Mit was für Plattformen hast du da Erfahrungen gemacht, über die man das
realisieren kann?

B: [48:05] Also eigentlich mit Ilias und dann das, was wir selber machen, das also auf
Gitlab basieren. Damit bin ich total zufrieden. Das würde ich gar nicht anders haben
wollen. Also erst einmal funktioniert es einfach gut. Man bekommt dahingehend viel von
der Stange, hat aber andererseits einen großen Teil der Toolchain auch unter eigener Kontrolle. Also wenn man irgendwas ändern will, dann geht das sehr gut. Und zum zweiten
trainiert man den Leuten schon frühzeitig an, wie sie professionelle Software entwickeln.
Das ist ein Nebeneffekt, den würde ich gar nicht unterschätzen. Siehe der Anfang des Interviews, wo wir über notwendiges Tooling für modernes Coding gesprochen haben. Dass
man nicht mehr Dateien auf dem C-Drive ablegt oder irgendwie durch die Gegend schickt,
sondern eben mit einem VCS arbeitet. So etwas gehört auch dazu, dass man eben sein
Handwerkszeug beherrscht, wenn man rausgeht aus der Hochschule.

I: [49:10] Du hast ja eben auch mal Discord angesprochen. Das lag jetzt vor allem auch
an Corona, dass wir auf Discord umgestiegen sind. Was hältst du generell von modernen
Messengern als Kommunikationskanal auch außerhalb von Corona Bedingungen?

B: [49:27] Ich bin total angetan davon, wie leichtgängig das funktioniert. Also erstmal
passt es super zu der Altersgruppe, da würde ich quasi die Betreuer noch mit reinnehmen. Also die Leute, die so ganz grob zwischen 16 und 29 sind, sind glaube ich total mit
Discord sozialisiert. Und andererseits bekomme ich es ja bei den Kollegen aus dem ArchiLab auch noch mit, da geht die Altersspanne ja doch bis über 30 und auch da scheint
Discord völlig selbstverständlich zu sein. Also “jeder“ ist mehr oder weniger “immer“ da
unterwegs. Ein Plus von Discord ist, dass vieles ganz einfach geht. Also ich kann ganz
einfach einen Sprachkanal definieren. Ich kann ganz einfach einem Video Call beitreten
und bin auch ganz schnell wieder raus. Das macht es unheimlich leichtgewichtig, was
ganz toll ist für solche Beratungsleistungen. Also ich könnte mir auch für die Zukunft
vorstellen, wenn diese Corona-Pandemie Geschichte ist, dass man einfach Lehrveranstaltungen hybrid aufsetzt. Also sagen wir mal, man macht Kickoff-Veranstaltungen durchaus
persönlich, damit man sich auch mal gesehen hat und die Gesichter zuordnen kann und
dann aber durchaus solche Sessions auch über Discord macht. Weil das einfach gut funktioniert und ich das Gefühl habe, dass es zumindest meiner Arbeitsweise sehr entgegen
kommt, weil ich keine Regelstunden habe. Also es kann sein, dass ich mal nachmittags
was anderes mache, dafür dann aber abends vor dem Rechner sitze. Ich habe auch bei den
wissenschaftlichen Mitarbeitern das gleiche Gefühl, dass sie nämlich ähnlich ticken und
auch in ihrer Mehrzahl nicht unbedingt an einem “Nine to Five“ Job interessiert sind,
sondern das gerne dann machen, wenn es für sie passt. Und auch dafür finde ich das eine
super Sache, dass man sagt, wenn die Mitarbeiter das auch okay finden, dann machen wir
eben weniger feste Beratungstermine und beantworten sonst so, wie es gerade passt. Das
Feedback der Studierenden lässt ganz deutlich darauf schließen, dass sie das gut finden.