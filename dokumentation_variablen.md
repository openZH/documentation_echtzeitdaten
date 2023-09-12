|**Variable**|**Inhalt**|**Format**|**Bemerkungen**|
|-|-|-|-|
|wahltag|Datum des Urnengangs|date "yyyy-mm-dd"| |
|timestamp|Zeitpunkt der letzten Aktualisierung|datetime "yyyy-mm-ddThh:mm:ss"|Werte, welche direkt aus der Übermittlungssoftware gespiesen werden, beinhalten kein Datum und werden im Format "hh:mm" ausgewiesen.|
|kantone|Liste der Kantone|list| |
|geoLevelnummer|Nummer der Verwaltungseinheit gemäss BFS|numeric|Bei Zählkreisen, also Untereinheiten von Gemeinden, setzt sich diese Nummer aus der Nummer des Auszählkreises, einer Null und der BFS-Nummer der Gemeinde zusammen|
|geoLevelname|Name oder bei Verwaltungseinheiten mit Geolevel 2 (Kantonen) die Abkürzung der Verwaltungseinheit gemäss BFS|character| |
|nochKeineInformation|Gibt an, ob bereits Informationen zum Geschäft vorliegen|logical| |
|vorlagen|Liste der Vorlagen|list| |
|geoLevelLevel|Geolevel der Verwaltungseinheit 0: Bund 1: Kanton 2: Bezirk 3: Gemeinde 4: Zählkreis|numeric|4 existiert de facto nicht, die Zählkreise werden anders verarbeitet (siehe Variable zaehlkreise)|
|vorlagenId|Eindeutiger Identifikator eines Geschäfts über sämtliche erfassten kommunalen und regionalen Geschäfte|numeric| |
|notfalltext|Liste der verschiedenen Sprachen, in denen ein Notfalltext angeboten wird|list|Wird vorläufig nicht verwendet|
|vorlagenTitel|Liste der Vorlagentitel in den angebotenen Sprachen|list| |
|langKey|Sprachcode für den Vorlagentitel de: deutsch fr: französisch it: italienisch rm: rätoromanisch|character| |
|text|Titel der Vorlage|character| |
|vorlageBeendet|Angabe, ob die Auszählung und Eingabe des gesamten Geschäfts (in allen daran beteiligten Verwaltungseinheiten) abgeschlossen ist|logical| |
|geschaeftsTypId|ID des Geschäftstyps|numeric|Siehe Tabellenblatt "Geschäftstypen"|
|geschaeftsTyp|Typ des Geschäfts|character|Siehe Tabellenblatt "Geschäftstypen"|
|geschaeftsSubTypId|ID des Geschäftssubtyps|numeric|Siehe Tabellenblatt "Geschäftstypen"|
|geschaeftsSubTyp|Subtyp des Geschäfts|character|Siehe Tabellenblatt "Geschäftstypen"|
|hauptvorlagenId|Indikator für die ID der Hauptvorlage, falls das Geschäft keine Hauptvorlage ist (geschaeftsSubTypId ≠ 1)|numeric| |
|annahmekriteriumTypId|(Code für das) Annahmekriterium des Geschäfts  1: Mehrheit der Stimmen 2: Mehrheit der Gemeinden 3: Alle Gemeinden 4: Mehrheit der Stimmen und der Gemeinden 5: Volks- und Ständemehr|numeric| |
|annahmekriteriumTyp| |character| |
|anzahlSitze|Gesamtzahl der in der Verwaltungseinheit im zu wählenden Organ enthaltenen Mandate|numeric| |
|bereitsGewaehlte|Anzahl Mandate, die schon vor der Wahl (beispielsweise in einem ersten Wahlgang oder in Stiller Wahl) vergeben wurden und bei der Wahl nicht besetzt werden|numeric| |
|zusatzInformationen|Zusätzliche Informationen zum Geschäft|list| |
|quelle|Quelle der Daten|character| |
|bemerkung|Bemerkungen zum Geschäft. Darin enthalten sein können unterschiedliche Attribute. Die Liste ist nicht abschliessend und auf die einzelnen Attribute wird nicht präziser eingegangen.|list| |
|stand|Informationen zum Auszählstand|list| |
|wahlAbgeschlossen|Angabe, ob die Wahl abgeschlossen ist|logical| |
|gemeindenZaehlkreiseTotal|Gesamtzahl der Auszählkreise für das Geschäft|numeric| |
|gemeindenZaehlkreiseAbgeschlossen|Zahl der Auszählkreise, in denen die Auszählung beendet ist|numeric| |
|gemeindenZaehlkreiseAbgeschlossenProzent|Anteil der Auszählkreise, in denen die Auszählung beendet ist in Prozent|numeric| |
|gemeindenZaehlkreiseNichtAbgeschlossen|Zahl der Auszählkreise, in denen die Auszählung noch nicht beendet ist|numeric| |
|gemeindenZaehlkreiseNichtAbgeschlossenProzent|Anteil der Auszählkreise, in denen die Auszählung noch nicht beendet ist in Prozent|numeric| |
|wahlkreiseTotal|Gesamtzahl der Wahlkreise der Wahl|numeric| |
|wahlkreiseAbgeschlossen|Zahl der Wahlkreise, in denen die Auszählung beendet ist|numeric| |
|wahlkreiseAbgeschlossenProzent|Anteil der Wahlkreise, in denen die Auszählung beendet ist in Prozent|numeric| |
|wahlkreiseNichtAbgeschlossen|Zahl der Wahlkreise, in denen die Auszählung noch nicht beendet ist|numeric| |
|wahlkreiseNichtAbgeschlossenProzent|Anteil der Wahlkreise, in denen die Auszählung noch nicht beendet ist in Prozent|numeric| |
|resultat|Liste der Resultatwerte|list| |
|gebietAusgezaehlt|Angabe, ob die Auszählung und Eingabe des Geschäfts in der betrachteten Verwaltungseinheit abgeschlossen ist|logical| |
|anzahlWahlberechtigte|Anzahl der Wahlberechtigten in der Verwaltungseinheit|numeric| |
|eingelegteWahlzettel|Anzahl der in der Verwaltungseinheit eingegangenen Wahlzettel|numeric| |
|gueltigeWahlzettel|Anzahl gültiger Wahlzettel in der Verwaltungseinheit|numeric|Die Summe der "veränderteWahlzettel" und "unveränderteWahlzettel" ist unter Umständen kleiner als "gültigeWahlzettel". Dies liegt daran, dass es möglicherweise Wahlzettel ohne Parteibezeichnung (WoP) gibt, die in beiden Kategorien nicht abgebildet werden. Die WoP unterscheiden sich von Wahlzetteln mit Parteibezeichnung dadurch, dass die leeren Zeilen nicht als Zusatzstimmen für eine Partei zählen, sondern verloren gehen. Entsprechend führt die Multiplikation von "gültigeWahlzettel" mit "anzahlSitze" auch nicht zwingend zum Wert von "listenStimmenTotal".|
|ungueltigeWahlzettel|Anzahl ungültiger Wahlzettel in der Verwaltungseinheit|numeric| |
|leereWahlzettel|Anzahl leerer Wahlzettel in der Verwaltungseinheit|numeric| |
|unveraenderteWahlzettel|Anzahl unveränderte Wahlzettel für die Proporzwahl in der Verwaltungseinheit|numeric| |
|veraenderteWahlzettel|Anzahl veränderte Wahlzettel (also Wahlzettel mit gestrichenen, kumulierten und/oder panaschierten Kandidierenden) für die Proporzwahl in der Verwaltungseinheit|numeric| |
|listenStimmenTotal|Total der Listen- oder Parteistimmen in der Verwaltungseinheit. Dieser Wert entspricht der Summe der Kandidatenstimmen aller Kandidierenden plus der Zusatzstimmen der Liste, also den leeren Zeilen von Wahlzetteln mit einer Listenbezeichnung.|numeric| |
|kandidatenStimmenTotal|Total der Kandidatenstimmen in der Verwaltungseinheit|numeric| |
|wahlbeteiligungInProzent|Wahlbeteiligung in Prozent als eingelegteWahlzettel / anzahlWahlberechtigte * 100|numeric| |
|wahlbeteiligungInProzentLetzteWahl|Wahlbeteiligung in Prozent der letzten Wahl für dasselbe Organs|numeric| |
|wahlbeteiligungVeraenderung|Differenz der Wahlbeteiligung von der letzten zu dieser Wahl dieses Organs in Prozentpunkten|numeric| |
|listen|Für diese Wahl antretende Listen|list| |
|listeNummer|Listennummer der Liste|numeric| |
|listeCode|Kurzbezeichnung der Liste|character| |
|waehler|Wählerzahl der Liste in der Verwaltungseinheit. In jedem Wahlkreis erhält man die Wählerzahl, indem die Parteistimmen einer Liste durch die im Wahlkreis zu vergebenden Mandate geteilt werden. Die einzelnen Wählerzahler aus den Wahlkreisen lassen sich anschliessend Summieren, wobei das Ergebnis die Wählerzahl einer Liste im gesamten Wahlgebiet ist.|numeric| |
|waehlerProzent|Anteil an der gesamten Wählerzahl in der Verwaltungseinheit in Prozent|numeric| |
|sitze|Anzahl der gewonnenen Mandate im Organ|numeric| |
|letzteWahlWaehlerProzent|Anteil an der gesamten Wählerzahl in der Verwaltungseinheit bei der letzten Wahl des Organs in Prozent|numeric| |
|letzteWahlSitze|Anzahl der gewonnenen Mandate bei der letzten Wahl des Organs|numeric| |
|gewinnWaehlerProzent|Differenz der Wählerzahl von der letzten zu dieser Wahl dieses Organs in Prozentpunkten|numeric| |
|gewinnSitze|Differenz der Anzahl gewonnener Mandate von der letzten zu dieser Wahl dieses Organs|numeric| |
|kandidaten|Zu dieser Wahl antretende Kandidierende|list| |
|kandidatenNummer|Für diese Wahl eindeutige Identifikationsnummer einer kandidierenden Person|character| |
|nachname|Nachname der kandidierenden Person|character| |
|vorname|Vorname der kandidierenden Person|character| |
|partei|Parteiangabe (Kurzform) der kandidierenden Person in den angebotenen Sprachen|list| |
|beruf|Angegebene Berufe der kandidierenden Person in den angebotenen Sprachen|list| |
|titel|Angegebene Titel der kandidierenden Person in den angebotenen Sprachen|list| |
|wohnort|Wohnort der kandidierenden Person|character| |
|geburtsjahr|Geburtsjahr der kandidierenden Person|numeric| |
|geschlecht|Geschlecht der kandidiereden Person. "M" für männlich, "W" für weiblich|character| |
|bisher|Angabe, ob die Person vor der Wahl dem Organ angehört hat|logical| |
|gewaehlt|Angabe, ob die Person bei der Wahl in das Organ gewählt wurde|logical| |
|stimmen|Anzahl erhaltener (Kandidierenden-)Stimmen bei der Wahl in der Verwaltungseinheit|numeric| |
|stimmenProzent|Anteil an der Gesamtzahl der Stimmen in der Verwaltungseinheit in Prozent|numeric| |
|prozentVomAbsolutenMehr|Anteil am absoluten Mehr der Stimmen in der Verwaltungseinheit in Prozent|numeric| |
|rangInListeInWahlkreis|Rang innerhalb der Liste in Wahlkreis anhand der erhaltenen Kandidierendenstimmen|numeric| |
|absolutesMehr|Höhe des absoluten Mehrs falls es sich um einen Wahlgang mit absoluten Mehr handelt|numeric| |
|weitererWahlgangNotwendig|Angabe, ob zur Besetzung sämtlicher offener Mandate ein weiterer Wahlgang notwendig ist|logical| |
|hochrechnungen|Liste der Hochrechnungswerte|list| |
|metadaten|Liste der zu der Hochrechnung gehörenden Metadaten|list| |
|text1|Liste der verschiedenen Sprachen, in denen ein Freitext angeboten wird|list| |
|text2|Liste der verschiedenen Sprachen, in denen ein Freitext angeboten wird|list| |
|infotext|Liste der verschiedenen Sprachen, in denen ein Infotext angeboten wird|list| |
|sitzeAnzeigen|Angabe, ob eine Hochrechnung zu den Sitzen vorhanden ist|logical| |
|vtlower|Obergrenze des 95%-Vertrauensintervalls|numeric| |
|vtupper|Untergrenze des 95%-Vertrauensintervalls|numeric| |
|sitzverteilung|Liste der Sitzverteilungsattribute|list| |
|sitzverteilungKanton|Liste der für die Wahl antretenden Listen|list| |
|sitzeProzent|Anteil der gewonnenen Mandate im Organ in Prozent|numeric| |
|listengruppenDivisor|Der Listengruppendivisor der Listengruppe|numeric|Weitere Informationen zum doppelproportionalen Sitzverteilungsverfahren im Kanton Zürich finden Sie unter https://www.zh.ch/de/politik-staat/wahlen-abstimmungen/kantons-regierungsratswahlen.html|
|sitzverteilungWahlkreise|Liste der Wahlkreise im Kanton|list| |
|wahlkreisNummer|Nummer des Wahlkreises|numeric| |
|wahlkreisBezeichnung|Bezeichnung des Wahlkreises|character| |
|wahlkreisDivisor|Wahlkreisdivisor des Wahlkreises|numeric|Weitere Informationen zum doppelproportionalen Sitzverteilungsverfahren im Kanton Zürich finden Sie unter https://www.zh.ch/de/politik-staat/wahlen-abstimmungen/kantons-regierungsratswahlen.html|
|listenImWahlkreis|Liste der im Wahlkreis zur Wahl antretenden Listen|list| |
|zeitreihen|Liste der Zeitreihenattribute|list| |
|hinweisZeitreihen|Hinweistext zu den Zeitreihendaten|character| |
|sitzeYYYY|Anzahl Sitze im Jahr YYYY|numeric| |
|waehlerProzentYYYY|Wählerzahl der Liste im Jahr YYYY|numeric| |
|bezirke|Liste der Bezirke in der Verwaltungseinheit, in denen ein Geschäft behandelt wird|list| |
|wahlkreise|Liste der Wahlkreise in der Verwaltungseinheit, in denen ein Geschäft behandelt wird|list| |
|stimmenProzentAufBasisDerListenStimmen|Anteil der Stimmen am Total der Listenstimmen in der Verwaltungseinheit|numeric|In Gemeinden, die aus mehreren Wahlkreisen bestehen (Stadt Zürich), ist darauf zu achten, dass diese Werte nicht zur Hierarchisierung von Kandidierenden aus verschiedenen Wahlkreisen verwendet werden kann, da die unterschiedliche Mandatszahl diese Werte verzerrt. Für solche Vergleiche sind ausschliesslich die Werte im Array "zaehlkreise" zu verwenden, wo die Anteile anhand der Gesamtzahlen (Listen- oder Kandidatenstimmen) in der Verwaltungseinheit, also im subkommunalen Zählkreis, berechnet werden.|
|stimmenProzentAufBasisDerKandidatenStimmen|Anteil der Stimmen am Total der Kandidatenstimmen in der Verwaltungseinheit|numeric| |
|gemeinden|Liste der Gemeinden, in welchen das Geschäft behandelt wird|list| |
|geoLevelParentnummer|Nummer der übergeordneten Verwaltungseinheit (geoLevelLevel -1) gemäss BFS|numeric| |
|bezirkeTotal|Gesamtzahl der Bezirke der Wahl|numeric| |
|bezirkeAbgeschlossen|Zahl der Bezirke, in denen die Auszählung beendet ist|numeric| |
|bezirkeAbgeschlossenProzent|Anteil der Bezirke, in denen die Auszählung beendet ist in Prozent|numeric| |
|bezirkeNichtAbgeschlossen|Zahl der Bezirke, in denen die Auszählung noch nicht beendet ist|numeric| |
|bezirkeNichtAbgeschlossenProzent|Anteil der Bezirke, in denen die Auszählung noch nicht beendet ist in Prozent|numeric| |
|zaehlkreise|Liste der subkommunalen Zählkreise einer Verwaltungseinheit|list| |
