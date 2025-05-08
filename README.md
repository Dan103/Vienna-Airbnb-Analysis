# [Vienna-Airbnb-Analysis](https://public.tableau.com/app/profile/danylo.butynskyy/viz/ViennaAirbnbAnalysis/AirbnbDashboard) - [Dashboard Link](https://public.tableau.com/app/profile/danylo.butynskyy/viz/ViennaAirbnbAnalysis/AirbnbDashboard)


## Inhaltsverzeichnis
1. [Projektübersicht](#projektübersicht)  
2. [Motivation](#motivation)  
3. [Datenquellen](#datenquellen)  
4. [Methodik](#methodik)  
5. [Dashboard-Beschreibung](#dashboard-beschreibung)  
   - [Durchschnittspreis pro Schlafzimmeranzahl](#durchschnittspreis-pro-schlafzimmeranzahl)  
   - [Anzahl der Inserate pro Schlafzimmeranzahl](#anzahl-der-inserate-pro-schlafzimmeranzahl)  
   - [Monatliche Umsatzentwicklung](#monatliche-umsatzentwicklung)  
   - [Geografische Verteilung nach Bezirk](#geografische-verteilung-nach-bezirk)  
   - [Durchschnittspreis pro Bezirk](#durchschnittspreis-pro-bezirk)  
6. [Interpretation und Hintergründe](#interpretation-und-hintergründe)  
7. [Fazit](#fazit)  

## Projektübersicht
Dieses Projekt umfasst die Analyse und Visualisierung von Airbnb-Daten für die Stadt Wien. Das interaktive Dashboard in Tableau bietet Einblicke in Preisstruktur, Angebot und Nachfrage sowie räumliche Muster der Ferienwohnungen.

## Motivation
Ziel ist es, durch datengetriebene Erkenntnisse sowohl für Vermieter als auch für Stadtplaner und touristische Dienstleister Verständnis für Preisentwicklungen und Angebotsstrukturen zu schaffen. Besonders im Kontext der Debatte um Zweckentfremdung und Wohnungsmarktregulierung liefert diese Analyse wertvolle Impulse.

## Datenquellen
- **Open Data Wien**: Amtliche Bezirksgrenzen als Shapefile  
- **Airbnb API**: Inserate-Metadaten (Preise, Schlafzimmeranzahl, Buchungsdaten)  
- **Tourismusstatistik**: Monatliche Gästezahlen (sekundär zur Kontextualisierung)  

## Methodik
1. **Datenaufbereitung:** Bereinigung fehlender Werte, Harmonisierung der Bezirkscodes  
2. **Aggregationen:** Berechnung von Mittelwerten, Summen und Anzahl eindeutiger Inserate  
3. **Visualisierung:** Erstellung von Balkendiagrammen, Liniencharts und einer Kartendarstellung in Tableau  

## Dashboard-Beschreibung

### Durchschnittspreis pro Schlafzimmeranzahl
Ein Balkendiagramm zeigt, wie sich der durchschnittliche Preis pro Nacht mit wachsender Schlafzimmerzahl verändert. 1-Zimmer-Apartments beginnen bei etwa 85 EUR, steigen im Schnitt auf 178 EUR für Zwei-Zimmer-Angebote und erreichen über 600 EUR für exklusive Penthouses mit mehr als fünf Schlafzimmern. Die sukzessive Preiszunahme verdeutlicht eine oft überproportionale Aufzahlung für zusätzliche Räume, insbesondere ab drei Schlafzimmern. Dies lässt auf einen Markt für größere Gruppen und Familien schließen, die bereit sind, signifikant mehr zu zahlen. Zudem zeigt die relative Konsistenz der Preissprünge zwischen den Kategorien eine stabile Struktur im Premiumsegment.

### Anzahl der Inserate pro Schlafzimmeranzahl
Eine tabellarische Übersicht listet die Anzahl der verfügbaren Inserate je Schlafzimmerkategorie. Einbettzimmer und Studios (1–2 Schlafzimmer) dominieren das Angebot mit über 10 000 Einträgen, während große Apartments mit vier oder mehr Schlafzimmern zusammen weniger als 200 Inserate ausmachen. Diese Verteilung spiegelt eine starke Nachfrage nach kompakten Urlaubsunterkünften wider, die gleichzeitig vermieterseitig eine geringere Auslastungs- und Instandhaltungskostenstruktur bieten. Die Seltenheit großer Appartements deutet darauf hin, dass Investoren hauptsächlich kleinere Einheiten fokussieren, um eine konstant hohe Belegungsrate zu erzielen. Außerdem verdeutlicht der langsame Rückgang ab der Kategorie drei Schlafzimmern eine sinkende Marge bei größeren Objekten.

### Monatliche Umsatzentwicklung
Ein Linienchart stellt die prozentuale Veränderung des Umsatzes im Jahresverlauf dar. Deutlicher Rückgang im Februar (-9,68 %) ist auf Wintersaison und Karnevalsfeiern zurückzuführen, während im März ein Anstieg um 10,94 % zu verzeichnen ist. Die Frühjahrsmonate zeigen stabile Zuwächse von knapp 3–4 % bis in den Juni hinein, flankiert von konstanten Sommerwerten. Diese saisonale Dynamik unterstreicht das Zusammenspiel von Wetter, Ferien und lokalen Veranstaltungen. Die leichte Delle im September lässt sich durch das Schuljahresende und das Ende der Hochsaison erklären, gefolgt von einer Erholung durch den Wien-Herbst und Messeaktivitäten.

### Geografische Verteilung nach Bezirk
Eine farbkodierte Karte zeigt mittlere Preise pro Nacht in allen Wiener Bezirken. Innere Stadt und angrenzende Bezirke wie Josefstadt und Neubau weisen mit über 160 EUR die höchsten Preise auf, während periphere Bezirke wie Favoriten und Meidling unter 90 EUR liegen. Der Preiskorridor bildet damit die klassische Zentrum-Peripherie-Achse ab, die durch Infrastruktur- und Tourismusqualität getrieben wird. Bezirke mit guter U-Bahn-Anbindung und Sehenswürdigkeiten verzeichnen dabei stärker konzentrierte Premiumlagen. Gleichzeitig signalisiert die Karte aufstrebende Bezirke wie Floridsdorf, die im Mittelfeld liegen und durch Neubauprojekte und verbesserte Anbindung an Attraktivität gewinnen.

### Durchschnittspreis pro Bezirk
Ein Balkendiagramm ordnet Bezirke nach Preisniveau. Innere Stadt führt mit rund 195 EUR, gefolgt von Josefstadt (130 EUR) und Floridsdorf (122 EUR). Bezirke mit historischer Bausubstanz und starkem Geschäftsreisemarkt wie Mariahilf und Landstraße liegen im oberen Mittelfeld (110–116 EUR). Am unteren Ende finden sich Meidling und Favoriten mit 78–81 EUR, typisch für Wohngebiete mit weniger touristischer Attraktivität. Diese Rangliste verdeutlicht den Premiumcharakter zentraler Lagen und das Potenzial randstädtischer Bezirke, die durch infrastrukturelle Verbesserungen langfristig aufschließen können.

## Interpretation und Hintergründe

### Soziale Faktoren
- **Touristische Nachfrage und Urbanität:** Zentrale Bezirke wie Innere Stadt und Josefstadt bieten dichte Konzentrationen an Sehenswürdigkeiten, Gastronomie und Kultur. Das zieht international reisende Gäste an, die bereit sind, höhere Preise zu zahlen, weil sie Wege und Zeit sparen und das Stadtzentrum als Erlebnisraum wahrnehmen.  
- **Demografische Zielgruppen:** Alleinreisende und Paare bevorzugen kompakte, zentral gelegene Studios, um nach kurzem Aufenthalt rasch zu Fuß zu lokalen Angeboten zu gelangen. Familien und Gruppen buchen größere Apartments in Randbezirken, da dort Platz und Ruhe günstiger sind. Diese Nachfrage-Struktur erklärt die Häufung kleiner Inserate im Zentrum und größerer Objekte am Stadtrand.  
- **Wohnraummangel und Lokaler Widerstand:** In Stadtteilen mit hohem Tourismusdruck entwickelt sich Widerstand der Wohnungseigentümer und Mieter gegen Kurzzeitvermietung, da dies das Angebot für Langzeitmieter verknappt. Dies führt zu lokalen Bestrebungen, die Anzahl der kurzfristigen Vermietungen politisch zu beschränken, um soziale Kohäsion und leistbares Wohnen zu sichern.

### Politische Rahmenbedingungen
- **Zweckentfremdungsgesetz:** Durch Registrierungs- und Meldepflichten werden viele Privatinserate limitiert, weshalb Vermieter in stärker regulierten Bezirken formell angemeldete Objekte in weniger strikter Lage bevorzugen. Das dämpft das Angebot in stark kontrollierten Bezirken und verschiebt das Marktgewicht in die Peripherie.  
- **Regulierung von Neubauten:** Die restriktive Wohnbaupolitik der Stadt Wien bremst die Schaffung neuer Wohnungen. Investoren nutzen Ferienwohnungen als Renditeobjekte, weil sie kurzfristig höhere Einnahmen versprechen als langfristige Vermietung. Das führt zu einem Ungleichgewicht im Wohnungsmarkt und verstärkt Preisunterschiede zwischen den Bezirken.  
- **Kommunale Fördermaßnahmen:** Subventionen für geförderten Wohnbau in Randbezirken treiben deren Attraktivität mittelfristig nach oben. Gleichzeitig entstehen in etablierten Stadtvierteln Programme zur Erhaltung von leistbarem Wohnraum, die das Airbnb-Angebot in diesen Zonen relativ stabil halten.

### Wirtschaftliche Einflüsse
- **Angebotsknappheit und Preiselastizität:** In Hochpreislagen ist das verfügbare Angebot an Wohnraum begrenzt. Zusätzliche Schlafzimmer rechtfertigen überproportionale Preisaufschläge, da größere Gruppen und besondere Anlässe (z. B. Kongresse, Firmenevents) höhere Zahlungsbereitschaften mitbringen.  
- **Saisonalität und Eventökonomie:** Messen und Kongresse in Wien (z. B. Vienna Auto Show, European Economic Congress) finden meist im Frühjahr und Herbst statt und generieren kurzfristige Preisspitzen. In der kalten Jahreszeit sowie während weniger frequentierter Perioden (Februar) ziehen Preise ab, da Geschäftsreisende und Konferenzteilnehmer ausbleiben.  
- **Infrastruktur und Erreichbarkeit:** Bezirke mit direkter U-Bahn-Anbindung oder Nähe zum Flughafen erzielen höhere Preise, da Reisende auf schnelle Verbindungen und kurze Transferzeiten angewiesen sind. Großprojekte wie der Flughafenausbau und U-Bahn-Verlängerungen erhöhen langfristig den Wert angrenzender Bezirke und verschieben Nachfrage und Preisniveau.\

## Fazit
Das Metro- und Stadtbild Wiens prägt die Airbnb-Angebotsstruktur deutlich. Zentrumsnähe, politische Regulierung und saisonale Schwankungen bestimmen Preisniveau und Verteilung. Die gewonnenen Erkenntnisse unterstützen strategische Entscheidungen für Vermieter, Stadtplaner und touristische Akteure.
