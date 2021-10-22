# Coaching Unterlagen #

## Inhalt
- "Story"-Idee für den Edit-Bericht
- Status des Forschungsberichts & grundlegende Idee der Visualisierung
- hilfreiches theoretisches Konzept mit Erklärungspotenzial
- grundlegende Idee der Visualisierung (Vergleich, etc.)
- offene Fragen

# "Story"-Idee für den Edit-Bericht

Aufmacher der Story sind die "versteckten Riesen" des Bundesliga-Transfermarkts - also die Vereine, die eben nicht Bayern oder Dortmund heißen, aber dennoch viele und vor allem teure Trasnfers tätigen und somit zu den einflussreichsten Vereinen der Bundesliga zählen. Hiinzu kommt, dass diese Vereine häufig aus ziemlich kleinen Städten kommen: Hoffenheim, Wolfsburg, Leverkusen, Gelsenkirchen. Dabei zeigt sich bereits ein Muster. Die TSG Hoffenheim wollen wir uns seperat nochmal anschauen und zudem nochmal einen Überblick über das Gesamtnetzwerk liefern mit einem interessanten Teilsaspekt bspw. wie die Bundesliga - und insbesondere die Vereine auf die wir uns fokussieren - mit dem Ausland handeln. Wir suchen zudem noch nach einem Experten, der die Daten besser einordnen kann mit seinem Wissen des Transfermarkts. 

# Status des Forschungsberichts & grundlegende Idee der Visualisierung

Forschungsbericht befindet sich mitten in der Produktion. Wir versuchen die gesamte Bandbreite unserer großen Datenerhebung zu zeigen, in dem wir viele Teilnetzwerke bilden und versuchen unterschiedliche Aspekte herauszustellen. Diese liefern uns auch einzelne Erkenntnisse zu unserer Forschungsfrage "Welche Angewohnheiten und Muster der Bundesligavereine lassen sich aus ihrem Transfer-Verhalten der vergangenen zehn Jahre ableiten?". Teilnetzwerke sind auch wichtig für unsere Visualisierung, da die igraph-Objekte sonst zu unübersichtlich werden. Zusätzlich sollen eine sich an bspw. den Degree anpassende Knoten-Größe für eine klarere Aussage sorgen. 

# hilfreiches theoretisches Konzept mit Erklärungspotenzial

Die Ntzerwerkmechanismen von Fuhse liefern mehrere Erklärungspotenziale für die Bildung des Bundesliga-Transfernetzwerks. So lässt sich vor dem Hintergrund der Aktivitätsfoki erklären, warum die Bundesligavereine so viel untereinander handeln. Als Mitglieder derselben Liga kommen die Vereine und deren Verantwortlichen zwangsläufig in den Kontakt untereinander und den Spielern der Klubs. Dabei können sie geschäftliche Beziehungen vertiefen oder ein besseres Bild von potenziellen Neuzugängen erhalten. Schaut man sich beispielsweise das Teilnetzwerk der "versteckten Riesen" an, lässt sich aber auch erkennen, was der Netzwerkeffekt "Macht" - bei unserem Beispiel in Form von Geld - auslöst. Die dort besonders präsenten Vereine, werden mit einer Ausnahme von großen Unternehmen finanziert und haben entsprechend viele finanzielle Möglichkeiten, um Transfers zu tätigen und damit auch eine zentrale Position in dem Netzwerk einzunehmen. Dabei sei aber auch gesagt: Mehr Macht bzw. Geld ist nicht gleichbedeutend mit mehr Zentralität, sondern nur ein verstärkender Faktor.

# grundlegende Idee der Visualisierung (Vergleich, etc.)

Teilnetzwerke bilden die Grundlage unserer Visualisierung, da die igraph-Objekte sonst zu unübersichtlich werden. Diese werden teils mehrfach eingeschränkt und/oder verglichen - auch wenn Zweiteres eher selten ist. Zusätzlich sollen eine sich an bspw. den Degree anpassende Knoten-Größe für eine klarere Aussage sorgen. 

# offene Fragen

Wir arbeiten bei der Visualisierung gerne mit Degree, um die Vertex-Size zu manipulieren. Aufgrund der drastischen Degree-Unterschiede in unserem Netzwerk/den Teilnetzwerken sorgt das häufig für sehr extreme Ansichten, die bis auf bspw. eine Erkenntnis zum Knoten mit dem höchsten Degree-Wert wenig Erkenntnisse liefern. Deswegen unsere Frage: Kann man eine Mindest- und Maximalgröße für Knoten einstellen?

Kann man einem Teilnetzwerk nachträglich einzelne Knoten manuell hinzufügen?

Wie können wir Netzwerke in der Visualiserung auseinanderziehen und verhindern, dass Label sich überlappen?

Offene Fragen zu konkreten Code-Zeilen von uns sind im Fragen-Etherpad auf Moodle festgehalten.

##
