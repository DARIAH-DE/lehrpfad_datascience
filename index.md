`- [Table of Contents \
](#table-of-contents-) \

- [1 Lehrpfad Data Science ](#lehrpfad-data-science-) \
- [2 Einleitung](#einleitung) \
    * [2.1 Ziele](#ziele) \
    * [2.2 Zielgruppe](#zielgruppe) \
    * [2.3 Übungsmaterialien und didaktisches Konzept](#übungsmaterialien-und-didaktisches-konzept) \
- [3 Programmieren für Geistes- und Kulturwissenschaftler*innen](#programmieren-für-geistes--und-kulturwissenschaftler*innen)
  \
    * [3.1 Welche Forschungsdaten habe ich?](#welche-forschungsdaten-habe-ich?) \
    * [3.2 Python ](#python-) \
    * [3.3 Welche Systemvoraussetzungen benötigt Python?](#welche-systemvoraussetzungen-benötigt-python?) \
    * [3.4 Hands on Python](#hands-on-python) \
- [4 Statistik für Geistes- und Kulturwissenschaftler*innen](#statistik-für-geistes--und-kulturwissenschaftler*innen) \
    * [4.1 Wie wahrscheinlich ist es, dass ich Statistik brauche?](#wie-wahrscheinlich-ist-es,-dass-ich-statistik-brauche?)
      \
    * [4.2 Grundlagen](#grundlagen) \
        + [4.2.1 Lagemaße](#lagemaße) \
        + [4.2.2 Streuung](#streuung) \
- [5 Lineare Algebra für Geistes- und Kulturwissenschaftler*innen](#lineare-algebra-für-geistes--und-kulturwissenschaftler*innen)
  \
- [6 Textanalyse](#textanalyse) \
    * [6.1 NLP](#nlp) \
    * [6.2 Stilometrie](#stilometrie) \
    * [6.3 Topic Modeling](#topic-modeling) \
    * [6.4 Sentiment Analysis](#sentiment-analysis) \
    * [6.5 Word Embeddings](#word-embeddings) \
      `

## **# 1 Lehrpfad Data Science **

## **# 2 Einleitung**

### ## 2.1 Ziele

Dieser Lehrpfad gibt einen Überblick über das interdisziplinäre Feld Data Science und stellt grundlegende Theorien,
Methoden und Werkzeuge im Kontext der quantitativen Textanalyse vor. Ziel dieses Lehrpfades ist es, Geistes- und
Kulturwissenschaftler*Innen für den Umgang mit heterogenen, materiellen und immateriellen Forschungsdaten zu
sensibilisieren und Forschende dabei zu unterstützen geeignete Methoden und Werkzeuge für ihr Forschungsvorhaben zu
finden.

### ## 2.2 Zielgruppe

Dieser Lehrpfad richtet sich an Promovierende und Post-Docs aus den Geistes- und Kulturwissenschaften, die noch keine
Erfahrung mit digitalen Methoden und digitalen Werkzeugen haben oder ihre Kenntnisse vertiefen möchten. Der Lehrpfad
kann jedoch nur zu Orientierung dienen und Empfehlungen für Einstiegsmöglichkeiten in die jeweiligen Thematiken geben.
Eine individuelle Abstimmung mit den jeweiligen Betreuern eines Forschungsprojektes kann dieser Lehrpfad nicht ersetzen.

### ## 2.3 Übungsmaterialien und didaktisches Konzept

Unter dem Begriff Data Science wird ein sehr weites und interdisziplinäres Feld subsumiert, das sich rapide
weiterentwickelt. Im Rahmen dieses Lehrpfades können nicht alle Methoden und Werkzeuge aus den unterschiedlichen
Fachdisziplinen vorgestellt werden. Stattdessen werden zugrundeliegende Konzepte erläutert und bekannte Probleme
thematisiert. Wenn möglich, werden darüber hinaus ausgewählte, fachspezifische Übungen, Einführungen und Tutorials aus
externen Quellen verlinkt sowie Empfehlungen zu weiterführender Literatur gegeben.

## **# 3 Programmieren für Geistes- und Kulturwissenschaftler*innen**

<p style="text-align: right">
<em>Nicht um meine Sprache zu verlernen, lerne ich andere Sprachen, sondern ich gehe bloß durch fremde Gärten, um für meine Sprache Blumen zu holen.      </em></p>

<p style="text-align: right">
<em>– Johann Gottfried Herder</em></p>

### ## 3.1 Welche Forschungsdaten habe ich?

Forschungsergebnisse resultieren aus Daten, die Gegenstand eines Forschungsvorhabens sind oder die im Rahmen eines
Forschungsprozesses erhoben und/oder generiert wurden. Aufgrund der materiellen und immateriellen Forschungsgegenstände
der jeweiligen Fachdisziplinen sind geistes- und kulturwissenschaftliche Forschungsdaten häufig sehr heterogen. Im Zuge,
der durch die Digitalisierung wachsenden Bestände, können Geistes- und Kulturwissenschaftler*innen zudem zunehmend
größer werdende Datenmengen bearbeiten und im Rahmen von interdisziplinären, kollaborativen Forschungsgruppen
multiperspektivisch erschließen. Je nach Forschungsfrage und den gewählten Forschungsmethoden liegen diese
Forschungsdaten in unterschiedlichen Typen (Umfrageergebnisse, Handschriften, Messreihen) sowie in unterschiedlichen
Dateiformaten (als Text-, Audio- oder Videodateien) vor. Die meisten Daten in den Geistes- und Kulturwissenschaften
gehören zu den unstrukturierten Daten, deren Informationsgehalt nicht in einer formalisierten Struktur vorliegt und die
daher spezielle Methoden benötigen, um sie zu erschließen.

    Weiterführend Literatur: **Forschungsdaten in den Geisteswissenschaften**:


    Peter Andorfer: "Forschungsdaten in den (digitalen) Geisteswissenschaften. Versuch einer Konkretisierung" DARIAH-DE Working Papers Nr.14. Göttingen: DARIAH-DE, 2015 URN: urn:nbn:de:gbv:7-dariah-2015-7-2  


    Christoph Schöch (2013): [„Big? Smart? Clean? Messy? Data in the Humanities“](https://www.google.com/url?q=http://journalofdigitalhumanities.org/2-3/big-smart-clean-messy-data-in-the-humanities&sa=D&source=editors&ust=1632886193780000&usg=AOvVaw07Ha26oPONYYKvMxefdFnZ) 


    Weiterführende Literatur:** Umgang mit Forschungsdaten**: 


    DFG, [Leitlinien zum Umgang mit Forschungsdaten](https://www.google.com/url?q=https://www.dfg.de/foerderung/antrag_gutachter_gremien/antragstellende/nachnutzung_forschungsdaten/&sa=D&source=editors&ust=1632886193781000&usg=AOvVaw1I_WhWiY_5mOzyL182j7KA)


    [Informationsportal zu Forschungsdatenmanagement](https://www.google.com/url?q=https://www.forschungsdaten.info/&sa=D&source=editors&ust=1632886193781000&usg=AOvVaw1ZYIQEhvBJT1S1RnMKZq0f)

Mit Hilfe von Computern können nicht nur monotone und wiederkehrende Arbeitsschritte, wie das Durchnummerieren mehrerer
hundert Bild- oder Audiodateien in einem Ordner konsistent und effizient erledigt werden. Digitale Tools und Methoden
können auch neue Zugänge zu Forschungsgegenständen sowie erweiterte Perspektiven auf Forschungsergebnissen ermöglichen.
Da das Verständnis von grundlegenden Konzepten der Programmierung die Automatisierung einfacher Arbeitsschritte, die
Anwendung digitaler Tools und quantitativer Forschungsmethoden sowie eine kritische Interpretation von (digitalen)
Forschungsergebnissen ermöglicht, erscheint es gerade für Geistes- und Kulturwissenschaftler*Innen sinnvoll zu sein,
eine Programmiersprache zu erlernen. Für Geistes- und Kulturwissenschaftler*Innen eignet sich insbesondere die
Programmiersprache Python, die im folgenden Kapitel vorgestellt wird.

    Weiterführende Literatur: **Automatisierung von Arbeitsschritten**


    Sweigart, Al. Automate the boring stuff with python: practical programming for total beginners. San Francisco: No Starch Press. 2015.

### ## 3.2 Python

Python ist eine universelle, interpretierte und einfach zu erlernende Programmiersprache, die über eine klare und
übersichtliche Syntax verfügt und mehrere Programmierparadigmen vereint. Python-Code ist - im Vergleich mit dem Code
anderer Programmiersprachen - stellenweise deutlich kürzer und daher einfacher zu erlernen. Mit
_                                      _ lassen sich wiederkehrende Bearbeitungsschritte einfach automatisieren. Zudem
verfügt Python über eine umfangreiche Standardbibliothek und zahlreiche Pakete ([PyPI](https://pypi.python.org/pypi)),
die viele, bereits vorgefertigte Funktionen für das Sammeln/Erheben, Bereinigen, Generieren sowie die Analyse und
Interpretation von geistes- und kulturwissenschaftlichen Forschungsdaten zur Verfügung stellen.

### ## 3.3 Welche Systemvoraussetzungen benötigt Python?

Python ist plattformunabhängig und kann daher sowohl mit den Betriebssystemen _Microsoft Windows_, _Apple OS X_ und _
Linux_ installiert werden. Für den Einstieg in das Programmieren empfiehlt sich die Verwendung des Webtools _Jupyter
Notebook_ oder der Entwicklungsumgebung _Anaconda_.

Mithilfe _Jupyter Notebooks_ kann Python-Code eingebettet im Browser interaktiv ausgeführt und getestet werden und
eignet sich damit besonders für das Erlernen der Sprache sowie das automatisieren von wiederkehrenden Aufgaben. Für
komplexere Aufgaben eignen sich die Entwicklungsumgebungen _Anaconda_ oder _PyCharm Edu,_ mit denen Python-Code nicht
nur experimentell entwickelt, sondern auch besser getestet (debugging) und modularisiert werden kann. Eine
deutschsprachige Schritt-für-Schritt-Anleitung für die Installation von _Jupyter Notebooks_, _Python_ und _Anaconda_
findet sich hier -> Tutorial jupyter

    Weiterführende Literatur: **Installation und Anwendung von Jupyter Notebooks**


    Quinn Dombrowski, Tassie Gniady, and David Kloster, "Introduction to Jupyter Notebooks," The Programming Historian 8 (2019), [https://doi.org/10.46430/phen0087](https://doi.org/10.46430/phen0087).


    Benjamin Pryke, Tutorial: Advanced Jupyter Notebooks

### ## 3.4 Hands on Python

Sprachen lernt man am Besten in der Praxis und mit Hilfe vieler Wiederholungen. Gleiches gilt für das Erlernen der
Syntax von Programmiersprachen. Ein für Geistes- und Kulturwissenschaftler konzipiertes Python-Tutorial mit praktischen
Übungen findet sich hier: Fotis Jannidis (2016) - Einführung in Python für Nicht-Informatiker

    Weiterführende Literatur: **Tutorien mit praktischen Übungen für den Einstieg in Python  **


    Folgert Karsdorp, Maarten van Gompel, Matt Munson (2014) - Python Programming for the Humanities


    Weiterführende Literatur: **Installation von Python-Modulen**


    Fred Gibbs, "Installing Python Modules with pip," The Programming Historian 2 (2013), https://doi.org/10.46430/phen0029.


    Weiterführende Literatur: **Visualisierung des eigenen Python-Codes**


    [Python Tutor](http://pythontutor.com/) ermöglicht durch die Live-Visualisierung der Ausführung von Python-Codes gerade Anfängern ein besseres Verständnis der zugrundeliegenden Funktionsweise sowie ein schnelleres Auffinden von Fehlern (Debugging) im Python-Code.

## **# 4 Statistik für Geistes- und Kulturwissenschaftler*innen**

### ## 4.1 Wie wahrscheinlich ist es, dass ich Statistik brauche?

Die Frage der Soziologie nach dem wechselseitigen Einfluss von einzelnen Akteuren und ihren sozialen Netzwerken, die
Frage der Linguistik nach der Bedeutung von Kopulaverben in unterschiedlichen Sprachen oder die Frage der
Literaturwissenschaft, nach der Bedeutung der Häufigkeitsverteilung von Replikenlängen in Dramen sind nur einige
Beispiele für den Raum, den die Statistik in der geistes- und kulturwissenschaftlichen Forschung einnimmt. Neben
fachspezifischen Fragestellung und dem Testen der eigenen Hypothesen ermöglicht das Verständnis statistischer Methoden
jedoch auch eine kritische Interpretation von visualisierten Forschungsergebnissen. Daher werden im Folgenden
grundlegende Begriffe und Konzepte der deskriptiven Statistik vorgestellt.

### ## 4.2 Grundlagen

Die Anzahl der Wörter, die Sätze eines Textes durchschnittlich enthalten, kann zunächst einfach dadurch berechnet
werden, indem die Anzahl der Wörter jedes Satzes in einem Textes zusammengezählt und diese Summe durch die Anzahl der
Sätze in dem entsprechenden Text geteilt wird. Der Durchschnitt (arithmetisches Mittel) zweier oder mehrer Zahlen ist
die Zahl, die von allen Zahlen gleichweit entfernt ist.

Sind in dem untersuchten Text jedoch viele kurze und einige sehr lange Sätze, vermittelt der Durchschnittswert (
arithmetisches Mittel) einen irreführenden Eindruck. Mit Hilfe weiterer Lagemaße können solche Unregelmäßigkeiten
normalisiert und so realistische Aussagen getroffen werden.

#### ### 4.2.1 Lagemaße

Median (geometrisches Mittel)

Zusätzlich zu dem Mittelwert kann der Median (Zentralwert) berechnet werden. Hier werden die Verse nach der Anzahl der
enthaltenen Wörter geordnet. Die erste Strophe des Gedichts “Mittelwert und Streuung” von P.H. List beispielsweise
enthält 8 Verse, die jeweils 5 bis 7 Wörter enthalten.

    **Mittelwert und Streuung**


    Ein Mensch, der von Statistik hört,


    denkt dabei nur an Mittelwert.


    Er glaubt nicht dran und ist dagegen,


    ein Beispiel soll es gleich belegen:


    Ein Jäger auf der Entenjagd


    hat einen ersten Schuß gewagt.


    Der Schuß, zu hastig aus dem Rohr,


    lag eine gute Handbreit' vor.


    Der zweite Schuß mit lautem Krach


    lag eine gute Handbreit' nach.


    Der Jäger spricht ganz unbeschwert


    voll Glauben an den Mittelwert:


    Statistisch ist die Ente tot!


    Doch wär er klug und nähme Schrot


    - dies sei gesagt ihn zu belehren -


    er würde seine Chancen mehren:


    Der Schuß geht ab, die Ente stürzt,


    weil Streuung ihr das Leben kürzt!


    P.H. List


    Professor für Pharmazeutische Technologie


    Marburg a.d. Lahn

Dementsprechend ergibt sich nach der Sortierung folgende Tabelle


<table>
  <tr>
   <td>Vers
   </td>
   <td>2
   </td>
   <td>5
   </td>
   <td>6
   </td>
   <td>8
   </td>
   <td>1
   </td>
   <td>4
   </td>
   <td>3
   </td>
   <td>7
   </td>
  </tr>
  <tr>
   <td>Wörter
   </td>
   <td>5
   </td>
   <td>5
   </td>
   <td>5
   </td>
   <td>5
   </td>
   <td>6
   </td>
   <td>6
   </td>
   <td>7
   </td>
   <td>7
   </td>
  </tr>
</table>


**Ungerade Anzahl:**

Liegt nach dem Ordnen eine ungerade Anzahl von Werten (Anzahl der Wörter) vor, entspricht der Median dem Wert in der
Mitte des Datensatzes.


<table>
  <tr>
   <td>Verse
   </td>
   <td>2, 5, 6, 8
   </td>
   <td>1, 4
   </td>
   <td>3, 7
   </td>
  </tr>
  <tr>
   <td>Wörter
   </td>
   <td>5
   </td>
   <td>6
   </td>
   <td>7
   </td>
  </tr>
</table>


**Gerade Anzahl:**

Liegt eine gerade Anzahl von Werten vor, dann wird der Median berechnet, indem die beiden Werte in der Mitte des
Datensatzes summiert und durch 2 dividiert werden. Der Median des Durchschnittsalters der Umfrageteilnehmer in der
nachfolgenden Tabelle liegt beispielsweise bei (27 + 34) : 2 = 61 : 2 = 30, 5.


<table>
  <tr>
   <td>Umfrageteilnehmer
   </td>
   <td>1
   </td>
   <td>2, 3
   </td>
   <td>4, 5
   </td>
   <td>6
   </td>
  </tr>
  <tr>
   <td>Alter
   </td>
   <td>16
   </td>
   <td>27
   </td>
   <td>34
   </td>
   <td>50
   </td>
  </tr>
</table>


Der Median ermöglicht eine Normalisierung der Daten, da sich wenige Verse mit vielen Wörtern bzw. wenige Teilnehmer in
einem höheren Alter durch die Verwendung des Medians weniger stark auf die durchschnittliche Anzahl der Wörter in einem
Text bzw. durchschnittliche Alter der Umfrageteilnehmer auswirken, als das arithmetische Mittel.

**Quantile**

Mit dem Median wird ein Datensatz in zwei Hälften unterteilt. Mithilfe eines p-Quantils kann ein Datensatz in zwei
Mengen unterteilt werden. Dabei gilt für eine Menge, dass p% der Werte kleiner oder gleich dem Quantil sind. Der Median
entspricht beispielsweise dem 50%-Quantil, da eine Hälfte der Datensätze über und die andere Hälfte der Datensätze unter
dem Median liegt.

Das 25%-Quantil teilt einen Datesatz beispielsweise in 25% und 75% der Datenpunkte, die über bzw. unter dem Wert des
25%-Quantils liegen. Das 25%-Quantil kann auch als 0,25-Quantil bezeichnet werden.

**Modalwert**

Die Anzahl der Wörter bzw. das Alter nennt man auch Merkmale oder Features. In den vorherigen Beispielen wurden Merkmale
mit ordinal skalierten Größen (Maßeinheiten), mit denen das arithmetische und geometrische Mittel berechnet werden
konnte. Bei Merkmalen mit nominal skalierten Größen (Labeln), wie beispielsweise „männlich, weiblich, divers“ kann nur
die Häufigkeit der Merkmalsausprägung ermittelt werden. Nehmen an einer Umfrage beispielsweise 35 weibliche, 19
männliche und 3 diverse Menschen teil, dann entspricht der Modalwert der häufigsten Merkmalsausprägung und beträgt in
diesem Beispiel also 35.

#### ### 4.2.2 Streuung

Lagemaße beschreiben Datensätze nur unvollständig. Entspricht die durchschnittliche Verslänge in einem Gedicht 5
Wörtern, sagt das arithmetische Mittel nichts darüber aus, ob die meisten Verse aus 5 Wörtern bestehen oder die Anzahl
der Wörter pro Verse beispielsweise zwischen 2 und 9 Wörtern variiert. Hierfür werden Streuung der Daten sowie deren
Standardabweichung (vom Median) berechnet.

Einen guten Überblick über grundsätzlichen Methoden der Statistik mit einem Fokus auf die typischen Aufgaben und
Probleme, die sich in geistes- und kulturwissenschaftlichen Forschung ergeben, vermittelt der
Kurs [Statistik für Digital Humanities (StatDH)](https://www.google.com/url?q=http://www.informatik.uni-leipzig.de/~jtiepmar/lehre/statdh20/&sa=D&source=editors&ust=1632886193788000&usg=AOvVaw2aeDTYSL_7ElBdSwu4971H)
sowie die dazugehörigen Übungsbeispiele.

Weiterführende Informationen
- [Examining Assumptions through Null Hypotheses - A Short Introduction to Analytical Statistics for (Digital) Humanists](https://github.com/DARIAH-DE/statistics_for_humanists)

## **# 5 Lineare Algebra für Geistes- und Kulturwissenschaftler*innen**

Tutorial Lineare Algebra für Geistes- und Kulturwissenschaftler*innen

## **# 6 Textanalyse**

_[TAToM: Text Analysis with Topic Models for the Humanities and Social Sciences](https://github.com/DARIAH-DE/tatom)_
ist eine Sammlung von Tutorials, die in die Grundlagen der quantitativen Textanalyse einführen. Die Tutorials wurden
speziell für Geistes- und Kulturwissenschaftler*innen entwickelt und behandeln die Aufbereitung und explorative Analyse
von Textkorpora.

### ## 6.1 NLP

Tutorial [Named Entity Recognition (NER)](https://fortext.net/routinen/methoden/named-entity-recognition-ner)

### ## 6.2 Stilometrie

In der digitalen Stilometrie werden Texte oder Textpassagen auf Grundlage statistischer Verteilungen (i. d. R. der
häufigsten Wörter) stilistisch miteinander verglichen. So lässt sich beispielsweise die stilistische Entwicklung oder
Differenzierung eines literarischen Textes, eines Œuvres, oder gar einer ganzen Epoche quantitativ nachvollziehen.
Insbesondere werden stilometrische Methoden bei Autorschaftsattributionen, Genreklassifikationen,
Epochendifferenzierungen oder auch in der forensischen Linguistik eingesetzt.

Online-Vorlesung
“[Einführung in die Stilometrie, die computergestützte Stilanalyse von Texte](https://www.youtube.com/watch?v=9eW7giYjObY)n”
mit Jun.-Prof. Dr. Manuel Burghardt

### ## 6.3 Topic Modeling

Topic Modeling ist ein auf Wahrscheinlichkeitsrechnung basierendes Verfahren zur Exploration größerer Textsammlungen.
Das Verfahren erzeugt statistische Modelle (Topics) zur Abbildung häufiger gemeinsamer Vorkommnisse von Wörtern.

<p style="text-align: right">
Topic modeling algorithms are statistical methods that analyze the words of the original texts to discover the themes that run through them, how those themes are connected to each other, and how they change over time.</p>


<p style="text-align: right">
 David M. Blei</p>


[Topic Modeling Tutorial ](https://dariah-de.github.io/TopicsExplorer/) von CLARIAH-DE

### ## 6.4 Sentiment Analysis

“Die Sentimentanalyse ist – oft als kommerzielle Dienstleistung – fester Bestandteil diverser Kommunikationsunternehmen
und gehört zum Methodenkanon der Sozialwissenschaften. Die Anwendungen betreffen u. a. die automatisierte Extraktion der
in sozialen Netzwerken vermittelten Gefühlslagen, die Überwachung von Internet-Foren sowie die Erkennung von negativen
Äußerungen (Flaming) und deren Entfernung oder die Analyse von Kundenfeedback und Online Reviews zur
Produktverbesserung (vgl. Ortner 2014; Liu 2015). Neben die analytische Funktion der Stimmungsanalyse tritt eine
prognostische: Sentimentanalysen werden ebenfalls eingesetzt, um Hypothesen über mögliche zukünftige menschliche
Reaktionen – z. B. auf ein Produkt oder zu einem bestimmten Thema – anstellen zu können (vgl. Liu 2015, 3). Als
spezifische Methode der Textanalyse ist die Sentimentanalyse in ein interdisziplinäres Forschungsfeld eingebettet, und
übernimmt Techniken aus den Bereichen Natural Language Processing und Data- bzw. Web-Mining (vgl. Zhang und Liu 2014).”
Marie Flüh (2019): „Sentimentanalyse“. In: forTEXT. Literatur digital erforschen.
URL: https://fortext.net/routinen/methoden/sentimentanalyse  [Zugriff: 29. September 2021].

[Tutorial „Sentimentanalyse“ forTEXT](https://fortext.net/routinen/methoden/sentimentanalyse)

### ## 6.5 Word Embeddings

[Semantic Word Representations - An Introductory Tutorial for Digital Humanists](https://github.com/DARIAH-DE/wordembeddings_tutorial)
