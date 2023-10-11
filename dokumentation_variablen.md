|**Variable**|**Inhalt**|**Format**|**Bemerkungen**|
|-|-|-|-|
|absolutesMehr|Höhe des absoluten Mehrs falls es sich um einen Wahlgang mit absoluten Mehr handelt|numeric| |
|abstimmtag|Datum des Urnenganges|date "yyyy-mm-dd"| |
|annahmekriteriumTyp|Annahmekriterium des Geschäfts <br />Mehrheit der Stimmen <br />Mehrheit der Gemeinden <br />Alle Gemeinden <br />Mehrheit der Stimmen und der Gemeinden <br />Volks- und Ständemehr|character| |
|annahmekriteriumTypId|Code für das Annahmekriterium des Geschäfts <br />1: Mehrheit der Stimmen <br />2: Mehrheit der Gemeinden <br />3: Alle Gemeinden <br />4: Mehrheit der Stimmen und der Gemeinden <br />5: Volks- und Ständemehr|numeric| |
|anzahlSitze|Gesamtzahl der in der Verwaltungseinheit im zu wählenden Organ enthaltenen Mandate|numeric| |
|anzahlStimmberechtigte|Anzahl der Stimmberechtigten in der Verwaltungseinheit|numeric| |
|anzahlWahlberechtigte|Anzahl der Wahlberechtigten in der Verwaltungseinheit|numeric| |
|bemerkungen|Bemerkungen zum Geschäft. Darin enthalten sein können unterschiedliche Attribute. Die Liste ist nicht abschliessend und auf die einzelnen Attribute wird nicht präziser eingegangen.|list| |
|bereitsGewaehlte|Anzahl Mandate, die schon vor der Wahl (beispielsweise in einem ersten Wahlgang oder in Stiller Wahl) vergeben wurden und bei der Wahl nicht besetzt werden|numeric| |
|beruf|Angegebene Berufe der kandidierenden Person in den angebotenen Sprachen|list| |
|bezirke|Liste der Bezirke in der Verwaltungseinheit, in denen ein Geschäft behandelt wird|list| |
|bezirkeAbgeschlossen|Zahl der Bezirke, in denen die Auszählung beendet ist|numeric| |
|bezirkeAbgeschlossen|Zahl der Bezirke, in denen die Auszählung beendet ist|numeric| |
|bezirkeAbgeschlossenProzent|Anteil der Bezirke, in denen die Auszählung beendet ist in Prozent|numeric| |
|bezirkeAbgeschlossenProzent|Anteil der Bezirke, in denen die Auszählung beendet ist in Prozent|numeric| |
|bezirkeNichtAbgeschlossen|Zahl der Bezirke, in denen die Auszählung noch nicht beendet ist|numeric| |
|bezirkeNichtAbgeschlossen|Zahl der Bezirke, in denen die Auszählung noch nicht beendet ist|numeric| |
|bezirkeNichtAbgeschlossenProzent|Anteil der Bezirke, in denen die Auszählung noch nicht beendet ist in Prozent|numeric| |
|bezirkeNichtAbgeschlossenProzent|Anteil der Bezirke, in denen die Auszählung noch nicht beendet ist in Prozent|numeric| |
|bezirkeTotal|Gesamtzahl der Bezirke der Wahl|numeric| |
|bezirkeTotal|Gesamtzahl der Bezirke der Wahl|numeric| |
|bisher|Angabe, ob die Person vor der Wahl dem Organ angehört hat|logical| |
|eingelegteStimmzettel|Anzahl der in der Verwaltungseinheit eingegangenen Stimmzettel|numeric| |
|eingelegteWahlzettel|Anzahl der in der Verwaltungseinheit eingegangenen Wahlzettel|numeric| |
|gebietAusgezaehlt|Angabe, ob die Auszählung und Eingabe des Geschäfts in der betrachteten Verwaltungseinheit abgeschlossen ist|logical| |
|geburtsjahr|Geburtsjahr der kandidierenden Person|numeric| |
|gemeinden|Liste der Gemeinden, in welchen das Geschäft behandelt wird|list| |
|gemeindenZaehlkreiseAbgeschlossen|Zahl der Auszählkreise, in denen die Auszählung beendet ist|numeric| |
|gemeindenZaehlkreiseAbgeschlossenProzent|Anteil der Auszählkreise, in denen die Auszählung beendet ist in Prozent|numeric| |
|gemeindenZaehlkreiseNichtAbgeschlossen|Zahl der Auszählkreise, in denen die Auszählung noch nicht beendet ist|numeric| |
|gemeindenZaehlkreiseNichtAbgeschlossenProzent|Anteil der Auszählkreise, in denen die Auszählung noch nicht beendet ist in Prozent|numeric| |
|gemeindenZaehlkreiseTotal|Gesamtzahl der Auszählkreise für das Geschäft|numeric| |
|geoLevelLevel|Geolevel der Verwaltungseinheit <br />0: Bund <br />1: Kanton <br />2: Bezirk <br />3: Gemeinde <br />4: Zählkreis|numeric|4 existiert de facto nicht, die Zählkreise werden anders verarbeitet (siehe Variable zaehlkreise)|
|geoLevelParentnummer|Nummer der übergeordneten Verwaltungseinheit (geoLevelLevel -1) gemäss BFS|numeric| |
|geoLevelname|Name oder bei Verwaltungseinheiten mit Geolevel ("geoLevelLevel") 1 (Kantonen) die Abkürzung der Verwaltungseinheit gemäss BFS|character| |
|geoLevelnummer|Nummer der Verwaltungseinheit gemäss BFS|numeric|Bei Zählkreisen, also Untereinheiten von Gemeinden, setzt sich diese Nummer aus der Nummer des Auszählkreises, einer Null und der BFS-Nummer der Gemeinde zusammen|
|geschaeftsArt|Bezeichnung der Geschäftsart|character|Siehe Datei [geschaeftstypen_geschaeftsarten.md](https://github.com/openZH/documentation_echtzeitdaten-am-wahltag/blob/main/geschaeftstypen_geschaeftsarten.md)|
|geschaeftsArtId|ID der Geschäftsart|numeric|Siehe Datei [geschaeftstypen_geschaeftsarten.md](https://github.com/openZH/documentation_echtzeitdaten-am-wahltag/blob/main/geschaeftstypen_geschaeftsarten.md)|
|geschaeftsSubTyp|Subtyp des Geschäfts|character|Siehe Datei [geschaeftstypen_geschaeftsarten.md](https://github.com/openZH/documentation_echtzeitdaten-am-wahltag/blob/main/geschaeftstypen_geschaeftsarten.md)|
|geschaeftsSubTypId|ID des Geschäftssubtyps|numeric|Siehe Datei [geschaeftstypen_geschaeftsarten.md](https://github.com/openZH/documentation_echtzeitdaten-am-wahltag/blob/main/geschaeftstypen_geschaeftsarten.md)|
|geschaeftsTyp|Typ des Geschäfts|character|Siehe Datei [geschaeftstypen_geschaeftsarten.md](https://github.com/openZH/documentation_echtzeitdaten-am-wahltag/blob/main/geschaeftstypen_geschaeftsarten.md)|
|geschaeftsTypId|ID des Geschäftstyps|numeric|Siehe Datei [geschaeftstypen_geschaeftsarten.md](https://github.com/openZH/documentation_echtzeitdaten-am-wahltag/blob/main/geschaeftstypen_geschaeftsarten.md)|
|geschlecht|Geschlecht der kandidiereden Person. "M" für männlich, "W" für weiblich|character| |
|gewaehlt|Angabe, ob die Person bei der Wahl in das Organ gewählt wurde|logical| |
|gewinnSitze|Differenz der Anzahl gewonnener Mandate von der letzten zu dieser Wahl dieses Organs|numeric|Dieser Wert wird bei Nationalratswahlen nur für aggregierte Parteien, nicht aber für einzelne Listen ausgegeben, da die Listen unter Umständen nicht mit denjenigen der letzten Wahl gematcht werden können|
|gewinnWaehlerProzent|Differenz der Wählerzahl von der letzten zu dieser Wahl dieses Organs in Prozentpunkten|numeric|Dieser Wert wird bei Nationalratswahlen nur für aggregierte Parteien, nicht aber für einzelne Listen ausgegeben, da die Listen unter Umständen nicht mit denjenigen der letzten Wahl gematcht werden können|
|gueltigeStimmen|Anzahl der gültigen Stimmen. Entspricht dem Total der eingegangenen Stimm- oder Wahlzettel, abzüglich den ungültigen und den leeren Stimm- oder Wahlzetteln (wobei diese Zahl bei Wahlen mit den zu vergebenden Mandaten multipliziert wird und wiederum ungültige und leere Stimmen, also Zeilen auf dem Wahlzettel, abgezogen werden)|numeric| |
|gueltigeWahlzettel|Anzahl gültiger Wahlzettel in der Verwaltungseinheit|numeric|Die Summe der "veränderteWahlzettel" und "unveränderteWahlzettel" ist unter Umständen kleiner als "gültigeWahlzettel". Dies liegt daran, dass es möglicherweise Wahlzettel ohne Parteibezeichnung (WoP) gibt, die in beiden Kategorien nicht abgebildet werden. Die WoP unterscheiden sich von Wahlzetteln mit Parteibezeichnung dadurch, dass die leeren Zeilen nicht als Zusatzstimmen für eine Partei zählen, sondern verloren gehen. Entsprechend führt die Multiplikation von "gültigeWahlzettel" mit "anzahlSitze" auch nicht zwingend zum Wert von "listenStimmenTotal".|
|hauptvorlagenId|Indikator für die ID der Hauptvorlage, falls das Geschäft keine Hauptvorlage ist (geschaeftsSubTypId ≠ 1)|numeric| |
|hinweisZeitreihen|Hinweistext zu den Zeitreihendaten|character| |
|hochrechnung|Liste der Hochrechnungswerte|list| |
|infotext|Liste der verschiedenen Sprachen, in denen ein Infotext angeboten wird|list| |
|jaStimmenAbsolut|Anzahl der Ja-Stimmen für das Geschäft in der Verwaltungseinheit|numeric| |
|jaStimmenInProzent|Anteil der Ja-Stimmen für das Geschäft in der Verwaltungseinheit in Prozent|numeric| |
|kandidatNummer|Für diese Wahl eindeutige Identifikationsnummer einer kandidierenden Person|character| |
|kandidaten|Zu dieser Wahl antretende Kandidierende|list| |
|kandidatenStimmenTotal|Total der Kandidatenstimmen in der Verwaltungseinheit|numeric| |
|kantone|Liste der Kantone|list| |
|langKey|Sprachcode für den Vorlagentitel <br />de: deutsch <br />fr: französisch <br />it: italienisch <br />rm: rätoromanisch|character| |
|leereWahlzettel|Anzahl leerer Wahlzettel in der Verwaltungseinheit|numeric| |
|letzteWahlSitze|Anzahl der gewonnenen Mandate bei der letzten Wahl des Organs|numeric|Dieser Wert wird bei Nationalratswahlen nur für aggregierte Parteien, nicht aber für einzelne Listen ausgegeben, da die Listen unter Umständen nicht mit denjenigen der letzten Wahl gematcht werden können|
|letzteWahlWaehlerProzent|Anteil an der gesamten Wählerzahl in der Verwaltungseinheit bei der letzten Wahl des Organs in Prozent, wobei für diesen Vergleich ebenfalls lediglich die aktuell ausgezählten Auszählkreise in Betracht fallen|numeric|Dieser Wert wird bei Nationalratswahlen nur für aggregierte Parteien, nicht aber für einzelne Listen ausgegeben, da die Listen unter Umständen nicht mit denjenigen der letzten Wahl gematcht werden können|
|listeCode|Kurzbezeichnung der Liste für diese Wahl|character| |
|listeNummer|Listennummer der Liste für diese Wahl|numeric| |
|listen|Für diese Wahl antretende Listen|list| |
|listenImWahlkreis|Liste der im Wahlkreis zur Wahl antretenden Listen|list| |
|listenOld|Aufzählung der bei der letzten Wahl für dieselbe Behörde angetretenen Listen, welche für einen Vergleich der Parteistärken unter der genannten Partei subsummiert werden|list| |
|listenStimmenTotal|Total der Listen- oder Parteistimmen in der Verwaltungseinheit. Dieser Wert entspricht der Summe der Kandidatenstimmen aller Kandidierenden plus der Zusatzstimmen der Liste, also den leeren Zeilen von Wahlzetteln mit einer Listenbezeichnung.|numeric| |
|listengruppenDivisor|Der Listengruppendivisor der Listengruppe|numeric|Weitere Informationen zum doppelproportionalen Sitzverteilungsverfahren im Kanton Zürich finden Sie unter https://www.zh.ch/de/politik-staat/wahlen-abstimmungen/kantons-regierungsratswahlen.html|
|metadaten|Liste der zu der Hochrechnung gehörenden Metadaten|list| |
|mutmasslichGewaehlt|Angabe, ob eine kandidierende Person gemäss der Hochrechnung voraussichtlich gewählt ist|logical| |
|nachname|Nachname der kandidierenden Person|character| |
|neinStimmenAbsolut|Anzahl der Ja-Stimmen für das Geschäft in der Verwaltungseinheit|numeric| |
|nochKeineInformation|Gibt an, ob bereits Informationen zum Geschäft vorliegen|logical| |
|notfalltext|Liste der verschiedenen Sprachen, in denen ein Notfalltext angeboten wird|list|Wird vorläufig nicht verwendet|
|partei|Parteiangabe (Kurzform) der kandidierenden Person in den angebotenen Sprachen|list| |
|parteiBezeichnung|siehe parteiCode|character| |
|parteiCode|Kurzbezeichnung der Partei für diese Wahl|character| |
|parteiIdKantonZH|siehe parteiNummer|numeric| |
|parteiNummer|Parteinummer der Partei für diese Wahl|numeric| |
|parteien|Zu dieser Wahl antretende Parteien|list| |
|prozentVomAbsolutenMehr|Anteil am absoluten Mehr der Stimmen in der Verwaltungseinheit in Prozent|numeric| |
|prozentanteilAmTotalEigeneListenstimmen|Anteil der Stimmen am Total der Listenstimmen der eigenen Liste (der Hochrechnung) in der Verwaltungseinheit in Prozent|numeric| |
|quelle|Quelle der Daten|character| |
|rangDifferenz|Differenz zwischen Rangierung aufgrund des Resultates (der Hochrechnung) innerhalb der Liste im Vergleich zum Listenplatz, wobei ein negativer Wert eine bessere Rangierung aufgrund des Resultats bedeutet|numeric|Grundsätzlich indiziert die Kandidierendennummer den ursprünglichen Rang auf der Liste. Dies ist beispielsweise relevant, wenn Kandidierende vorkummuliert sind. So bekleidet die Kandidatin XX.02 den ursprünglichen Rang 2 auf der Liste, selbst wenn Sie aufgrund einer vorkumulierung des Kandidaten XX.01 erst auf dem dritten Platz der Liste aufgeführt ist.|
|rangInListeInWahlkreis|Rang innerhalb der Liste in Wahlkreis anhand der erhaltenen Kandidierendenstimmen|numeric| |
|resultat|Liste der Resultatwerte|list| |
|sitze|Anzahl der gewonnenen Mandate im Organ|numeric| |
|sitzeAnzeigen|Angabe, ob eine Hochrechnung zu den Sitzen vorhanden ist|logical| |
|sitzeProzent|Anteil der gewonnenen Mandate im Organ in Prozent|numeric| |
|sitzeYYYY|Anzahl Sitze im Jahr YYYY|numeric| |
|sitzverteilung|Liste der Sitzverteilungsattribute|list| |
|sitzverteilungKanton|Liste der für die Wahl antretenden Listen|list| |
|sitzverteilungWahlkreise|Liste der Wahlkreise im Kanton|list| |
|stand|Informationen zum Auszählstand|list| |
|stimmbeteiligungInProzent|Stimmbeteiligung als Anteil gültiger Stimmen des Totals der Stimmberechtigten in der Verwaltungseinheit in Prozent|numeric| |
|stimmen|Anzahl erhaltener (Kandidierenden-)Stimmen bei der Wahl in der Verwaltungseinheit|numeric| |
|stimmenProzent|Anteil an der Gesamtzahl der Stimmen in der Verwaltungseinheit in Prozent|numeric| |
|stimmenProzentAufBasisDerKandidatenStimmen|Anteil der Stimmen am Total der Kandidatenstimmen in der Verwaltungseinheit in Prozent|numeric| |
|stimmenProzentAufBasisDerListenStimmen|Anteil der Stimmen am Total der Listenstimmen in der Verwaltungseinheit in Prozent|numeric|In Gemeinden, die aus mehreren Wahlkreisen bestehen (Stadt Zürich), ist darauf zu achten, dass diese Werte nicht zur Hierarchisierung von Kandidierenden aus verschiedenen Wahlkreisen verwendet werden kann, da die unterschiedliche Mandatszahl diese Werte verzerrt. Für solche Vergleiche sind ausschliesslich die Werte im Array "zaehlkreise" zu verwenden, wo die Anteile anhand der Gesamtzahlen (Listen- oder Kandidatenstimmen) in der Verwaltungseinheit, also im subkommunalen Zählkreis, berechnet werden.|
|text|Titel der Vorlage|character| |
|text1|Liste der verschiedenen Sprachen, in denen ein Freitext angeboten wird|list| |
|text2|Liste der verschiedenen Sprachen, in denen ein Freitext angeboten wird|list| |
|timestamp|Zeitpunkt der letzten Aktualisierung|datetime "yyyy-mm-ddThh:mm:ss"|Werte, welche direkt aus der Übermittlungssoftware gespiesen werden, beinhalten kein Datum und werden im Format "hh:mm" ausgewiesen.|
|titel|Angegebene Titel der kandidierenden Person in den angebotenen Sprachen|list| |
|ungueltigeWahlzettel|Anzahl ungültiger Wahlzettel in der Verwaltungseinheit|numeric| |
|unveraenderteWahlzettel|Anzahl unveränderte Wahlzettel für die Proporzwahl in der Verwaltungseinheit|numeric| |
|veraenderteWahlzettel|Anzahl veränderte Wahlzettel (also Wahlzettel mit gestrichenen, kumulierten und/oder panaschierten Kandidierenden) für die Proporzwahl in der Verwaltungseinheit|numeric| |
|vorlageAngenommen|Angabe, ob die Vorlage in der Verwaltungseinheit angenommen wurde. Der Wert ist "null", so lange die Auszählung noch nicht abgeschlossen wurde|logical| |
|vorlageAngenommenGesamtbetrachtung|Gibt an, ob ein Geschäft in seiner Gesamtbetrachtung, also auch unter Berücksichtigung von Resultaten verbundener Geschäfte, angenommen wurde|logical|Dieses Attribut wird momentan nicht abgefüllt und enthält flächendeckend "null"|
|vorlageBeendet|Angabe, ob die Auszählung und Eingabe des gesamten Geschäfts (in allen daran beteiligten Verwaltungseinheiten) abgeschlossen ist|logical| |
|vorlagen|Liste der Vorlagen|list| |
|vorlagenId|Eindeutiger Identifikator eines Geschäfts über sämtliche erfassten Geschäfte|numeric| |
|vorlagenTitel|Liste der Vorlagentitel in den angebotenen Sprachen|list| |
|vorname|Vorname der kandidierenden Person|character| |
|vtlower|Obergrenze des 95%-Vertrauensintervalls|numeric| |
|vtupper|Untergrenze des 95%-Vertrauensintervalls|numeric| |
|waehler|Wählerzahl der Liste in der Verwaltungseinheit. In jedem Wahlkreis erhält man die Wählerzahl, indem die Parteistimmen einer Liste durch die im Wahlkreis zu vergebenden Mandate geteilt werden. Die einzelnen Wählerzahler aus den Wahlkreisen lassen sich anschliessend Summieren, wobei das Ergebnis die Wählerzahl einer Liste im gesamten Wahlgebiet ist.|numeric| |
|waehlerProzent|Anteil an der gesamten Wählerzahl in der Verwaltungseinheit zum aktuellen Auszählzeitpunkt in Prozent|numeric| |
|waehlerProzentYYYY|Wählerzahl der Liste im Jahr YYYY|numeric| |
|wahlAbgeschlossen|Angabe, ob die Wahl abgeschlossen ist|logical| |
|wahlbeteiligungInProzent|Wahlbeteiligung in Prozent als eingelegteWahlzettel / anzahlWahlberechtigte * 100|numeric| |
|wahlbeteiligungInProzentLetzteWahl|Wahlbeteiligung in Prozent der letzten Wahl für dasselbe Organs|numeric| |
|wahlbeteiligungVeraenderung|Differenz der Wahlbeteiligung von der letzten zu dieser Wahl dieses Organs in Prozentpunkten|numeric| |
|wahlkreisBezeichnung|Bezeichnung des Wahlkreises|character| |
|wahlkreisDivisor|Wahlkreisdivisor des Wahlkreises|numeric|Weitere Informationen zum doppelproportionalen Sitzverteilungsverfahren im Kanton Zürich finden Sie unter https://www.zh.ch/de/politik-staat/wahlen-abstimmungen/kantons-regierungsratswahlen.html|
|wahlkreisNummer|Nummer des Wahlkreises|numeric| |
|wahlkreise|Liste der Wahlkreise in der Verwaltungseinheit, in denen ein Geschäft behandelt wird|list| |
|wahlkreiseAbgeschlossen|Zahl der Wahlkreise, in denen die Auszählung beendet ist|numeric| |
|wahlkreiseAbgeschlossenProzent|Anteil der Wahlkreise, in denen die Auszählung beendet ist in Prozent|numeric| |
|wahlkreiseNichtAbgeschlossen|Zahl der Wahlkreise, in denen die Auszählung noch nicht beendet ist|numeric| |
|wahlkreiseNichtAbgeschlossenProzent|Anteil der Wahlkreise, in denen die Auszählung noch nicht beendet ist in Prozent|numeric| |
|wahlkreiseTotal|Gesamtzahl der Wahlkreise der Wahl|numeric| |
|wahltag|Datum des Urnengangs|date "yyyy-mm-dd"| |
|weitererWahlgangNotwendig|Angabe, ob zur Besetzung sämtlicher offener Mandate ein weiterer Wahlgang notwendig ist|logical| |
|wohnort|Wohnort der kandidierenden Person|character| |
|zaehlkreise|Liste der subkommunalen Zählkreise einer Verwaltungseinheit|list| |
|zeitreihen|Liste der Zeitreihenattribute|list| |
|zusatzInformationen|Zusätzliche Informationen zum Geschäft|list| |
