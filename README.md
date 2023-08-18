# Anand Jain

# Datenanalyse-, Business-Analysten- und Business-Intelligence-Analyseprojekten


### Hinweis: 
Dieses Portfolio und die zugehörigen GitHub-Repositories werden von mir (Anand Jain) erstellt. Die Daten auf dieser Website und allen Repositories sind durch die Datenschutzrichtlinie geschützt und die hier erstellten Dashboards sollten nicht kopiert oder übertragen werden. Alle Regeln gelten gemäß der Datenschutzrichtlinie.




# Projekt 1 - Datamart-Erstellung und Analyse hierarchiebasierter Verkaufsdaten
[https://github.com/anandjain55/Datamart_Erstellung_und_Analyse_hierarchiebasierter_Verkaufsdaten](https://github.com/anandjain55/Datamart_Erstellung_und_Analyse_hierarchiebasierter_Verkaufsdaten)

## Geschäftsproblem und Kontext:

In diesem Projekt müssen Sie mit den Daten vieler Unternehmen arbeiten, die sich mit einer Vielzahl von Produkten beschäftigen. Ihre Aufgabe ist es, die Daten mit SSIS aus der Hauptdatenbank zu extrahieren, einen Staging-Bereich zu erstellen und dann DataMart in SQL Server zu erstellen. 

Sie sollten KPI für den Verkauf verfolgen, kreative Diagramme erstellen, die die Verkäufe nach Monat und Jahr zeigen, hochwertige Kunden und Trends auf Produktebene analysieren.Außerdem sollten Sie in der Lage sein, für weitere Details auf Produkt- und Kundenebene aufzuschlüsseln. Ihr Bericht sollte einen Vergleich der Ist-Werte mit den Budgetwerten der Verkäufe enthalten.

## Die wichtigsten Schritte während des Projekts sind folgende :
1. Der Staging-Bereich des Datawarehouse wurde mithilfe von SSIS erstellt und alle Rohdaten wurden in den SQL Server importiert.
2. In SQL Server wurde ein CORE-Layer für Dimensions- und Faktentabellen mithilfe von Stored Procedures erstellt.
3. StarSchema wurde aus diesen Tabellen generiert.
4. Ansichten wurden aus dem Core Layer generiert.
5. Power BI Dashboard mit Executive Dashboard, Customer und Product Level Dashboards wurde mit Hilfe von Views der Core Layer Daten erstellt.

## Die wichtigsten Erkenntnisse :
1.	Der Umsatz für das ganze Jahr beträgt 547 Mio. 
2.	Geshirrspüler hat höchsten Umsatz von 2019-2023.
3.	Metra hat höchsten Umsatz von 2019-2023.
4.	Kunde Corporate Express Deutschland hat höchsten umsatz von 547 M von 2019-2023.
5.	VL- Gebiet Müller ist der vertiebsleiter mit dem höchsten umsatz für alle Jahre.
6.	Donut Chart für UmsatzPlan vers umstzplan by Vertiebsweg zeigt, dass Kaüfhauser den höchsten umsatz von 2019-2023 hat.

## Ergebnis und Schlussfolgerung aus dem Dashboard :
1.	Umsatzdaten für alle Produkthierarchien aus den Jahren 2019 bis 2023 und umsatzplan Daten von 2021-2023
2.	Umsatz_Plan Karte zeigt den prognostizierten Umsatz für das ausgewählte Jahr von 2021-2023. Wir können den aktuellen und den vorhergesagten Umsatz aus beiden Karten vergleichen.
3.	Wir können den Monats- und Jahres-Slicer mit anderen Karten kombinieren, um das Produkt und den Kunden mit dem höchsten Verkaufswert pro Jahr und Monat zu filtern 
4.	Wir können die tatsächlichen und geplanten Verkaufswerte für Produkte und Kunden für alle 3 Hierarchieebenen der Produkt- und Kundenmatrix vergleichen.
5.	Wir können auch die Ist- und Budget-Verkaufswerte für die Top-Produkte und Top-Kunden vergleichen.
6.	Anhand des Guage-Diagramms können wir die Differenz zwischen Budget und tatsächlichem Verkaufswert für einen bestimmten Kunden ermitteln.
7.	Das Schaubild zeigt den Minimalwert als 0 und den Maximalwert als das Doppelte des Umsatzes, wobei der Abrufwert der tatsächliche Umsatz von 2019-2023 und der Zielwert der Budget-Umsatz (umsatz_plan) von 2021-2023 ist.
8.	Das Ausblenden des Slicer-Panels enthält den Vertriebsweg-Slicer, der hilft, die Umsatzwerte von Kunden und Produkten zu filtern. 

### Icons und Logos :
Beschreibende Icons werden verwendet, um von einer Seite zur anderen zu wechseln, wie z.B. Produkt, Kunde, Karte und exec Dashboard. 
Das Slicer-Logo wurde verwendet, um den Vertriebsweg-Slicer auszublenden, um den Platz auf der Seite zu sparen. 

### Produkt- und Kundenhierarchieseiten:
Die Produkt- und Kundenhierarchieseiten enthalten detailliertere Informationen über Kunden und Produkte. Von der Seite "Executive Dashboard" oder "Product" können wir auf die Seite "Product Hierarchy" gehen, um mehr Details über Produkte zu sehen, während wir von der Seite "Customer" auf die Seite "Customer Hierarchy" gehen können, um mehr Details über Kunden zu sehen.

## Verwendete technische Tools : 
Sql Server Management Studio, Visual Studio und Power BI Desktop, 

## Verwendete Techniken/Fähigkeiten :
SQL Server - Sql Server Integration Services, ETL, Datamart, Gespeicherte Prozeduren, Ansichten,
Power BI - DAX, Datenmodellierung, Datenvisualisierung.

###  Überblick über das Executive Dashboard 
![](Bilder-Analyse_des_Berichts_über_hierarchiebasierte_Verkaufsdaten/Executive-Dashboard.jpg)

###  Übersicht über das Dashboard auf Produktebene 
![](Bilder-Analyse_des_Berichts_über_hierarchiebasierte_Verkaufsdaten/Produkt_Ebene_Dashboard.jpg)

###  Übersicht über die Kundenebene_Dashboard
![](Bilder-Analyse_des_Berichts_über_hierarchiebasierte_Verkaufsdaten/Kunden_Ebene_Dashboard.jpg)

###  Kartenansicht 
![](Bilder-Analyse_des_Berichts_über_hierarchiebasierte_Verkaufsdaten/Karte_Ansicht.jpg)

###  Übersicht der Produkthierarchie-Ebene 
![](Bilder-Analyse_des_Berichts_über_hierarchiebasierte_Verkaufsdaten/Produkt_Hierarchiestufe_Details.jpg)

###  Übersicht der Kundenhierarchie-Ebene 
![](Bilder-Analyse_des_Berichts_über_hierarchiebasierte_Verkaufsdaten/Kunden_Hierarchiestufe_Details.jpg)



# Projekt 2 - Persönliche Finanz-Tracker Analyse 
[https://github.com/anandjain55/Personliche_Finanz-Tracker_Analyse](https://github.com/anandjain55/Personliche_Finanz-Tracker_Analyse)

## Geschäftsproblem und Kontext
Erstellung eines persönlichen Finanz-Trackers, der bei der Verwaltung und Kontrolle der finanziellen Ausgaben hilft. Das Ziel dieses Projekts ist es, schon in jungen Jahren finanzielle Kenntnisse zu vermitteln und die Analytik in das tägliche Leben einzubinden.

## Datenquelle:
Die Rohdaten der durchschnittlichen Ausgaben des Jahres 2022 aus Indien wurden in Excel erstellt.


## Befolgte Vorgehensweise : 
1.	Die Rohdaten wurden in Excel erstellt und dann in Power BI importiert. 
2.	ETL wurde für die Daten mit Power BI durchgeführt, und die bereinigten Daten wurden dann zur Erstellung eines Dashboards in Power BI verwendet.

## Abgeleitete Schlüsselerkenntnisse:
1.	Mit Hilfe der KPIs des Berichts erhalten wir Einblicke in das Nettovermögen, die Genauigkeit des Ausgabenmusters, den Status der Sparziele, die besten und schlechtesten Finanzmonate in Bezug auf Ausgaben und Einsparungen.
2. Slicer hilft, Daten nach Jahr und Monat zu filtern.
3.	Das Liniendiagramm hilft zu erkennen, ob Geld gespart oder ausgegeben wird im Vergleich zu dem, was verdient wird.
4.	Baumdiagramme geben Aufschluss über die Ausgaben in verschiedenen Bereichen und deren prozentualen Anteil.
5.	Balkendiagramme geben Aufschluss über den prozentualen Anteil des eingesparten Geldes in den einzelnen Bereichen.


## Ergebnis und Schlussfolgerung aus dem Dashboard:
1.	Das höchste Einkommen ist im Jahr 2020 und sein Wert ist 593K INR mit 17 % Gesamtersparnis (99 K INR)
2.	Die höchsten Ausgaben werden für die Wohnungsmiete getätigt, was etwa 37 % entspricht, und das meiste Geld, etwa 87 %, wurde in Investmentfonds gespart. 
3.	Der Prozentsatz der Ersparnisse im Jahr 2020 ist höher als der Prozentsatz der Ersparnisse aller Zeiten, während der Prozentsatz der Ausgaben niedriger ist als der Prozentsatz der Ausgaben aller Zeiten.
4. Die höchste Ersparnis von 27 % wurde im Jahr 2018 erreicht.
5.	Das Liniendiagramm zeigt, dass das Sparziel bis zum Jahr 2020 gut ist, dann aber wieder sinkt.
6.	Die Einsparung in % nimmt von 2018 bis 2020 ab, während sie von 2020 bis 2021 wieder ansteigt und die Ausgaben in % das umgekehrte Muster zeigen.

## Verwendete technische Tools : 
 MS Excel, Power BI Desktop.

## Verwendete Techniken / Fertigkeiten / Software :
Excel, 
Power BI- DAX, Datenvisualisierung.

### Überblick über das Executive Dashboard 
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Persönliche_Finanzen_Tracker-Dashboard.jpg)

### Tooltips 
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Tooltip-1.jpg),
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Tooltip-2.jpg),
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Tooltip-3.jpg),
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Tooltip-4.jpg)

# Projekt 3 - Datenanalyse der AdventureWorks Bike Company 
[https://github.com/anandjain55/Datenanalyse_der_AdventureWorks_Bike_Company](https://github.com/anandjain55/Datenanalyse_der_AdventureWorks_Bike_Company)

## Geschäftsproblem: 
Sie wurden gerade als Business Intelligence-Analyst von AdventureWorks eingestellt, einem fiktiven globalen Produktionsunternehmen, das Fahrradausrüstung und -zubehör herstellt. Ihre Aufgabe ist es, das Managementteam dabei zu unterstützen, die KPIs wie Absatz, Umsatz, Gewinn und Rendite zu verfolgen, die Leistung zwischen den Regionen zu vergleichen, Trends auf Produktebene zu analysieren und wichtige Kunden zu identifizieren.
Aber alles, was Ihnen zur Verfügung steht, ist ein Ordner mit rohen CSV-Dateien, die Informationen über Transaktionen und Retouren, Produkte, Kunden und Verkaufsgebiete enthalten.

## Ziel erreicht: 
Power BI Desktop verwendet, um diese Rohdaten zu verbinden und umzuwandeln, ein relationales Datenmodell erstellt, berechnete Spalten und Kennzahlen mit DAX erstellt und schließlich ein interaktives Dashboard entworfen, um die Daten zu visualisieren und zu analysieren.

## Abgeleitete Schlüsselerkenntnisse:
1. Die Übersichtsansicht enthält hochrangige KPIs (Umsatz, Gewinn, Aufträge, Rücklaufquote), ein wöchentliches Umsatztrenddiagramm, coole interaktive Elemente wie Schieberegler zum Heranzoomen bestimmter Zeiträume, benutzerdefinierte Tooltipps und einen vollständig benutzerdefinierten Filterbereich.
2. Man kann in ein bestimmtes Produkt bohren, um zur Produkt-Detailansicht zu gelangen. Dort wird z. B. angezeigt, wie sich ein Produkt im Vergleich zu seinem monatlichen Auftrags-, Umsatz- oder Gewinnziel verhält.
3. Die Verwendung von Parametern für die Was-wäre-wenn-Analyse zeigt, wie sich eine Preisänderung auf eine Kennzahl wie den Gesamtgewinn auswirkt.
4. Die untersuchten Feldparameter machen diese Diagramme für die Endbenutzer interaktiver und dynamischer.
5. Eine Ansicht auf Kundenebene hilft dabei, die Leistung auf der Ebene des einzelnen Kunden zu untersuchen und verschiedene Kundenprofile und -segmente aufzuschlüsseln.

## Ergebnis und Schlussfolgerung aus dem Dashboard:
1.	Von Dezember 2020 bis Juni 2022 stieg der Umsatz mit einigen Ausnahmen linear an.  Die Gesamteinnahmen betrugen $ 24,9 Mio., während der Gewinn $ 10,5 Mio. betrug. In diesem Zeitraum wurden 25,2 K Bestellungen aufgegeben und die Gesamtrücklaufquote betrug 2,2 %.
2.	Im Zeitraum von Januar 2020 bis Juni 2022 bestellten die Kunden am meisten Reifen und Schläuche, während das Produkt, das am häufigsten zurückgegeben wurde, Shorts waren.
3.	Von Januar 2020 bis Juni 2022 war Herr Maurice Shan der Kunde mit dem höchsten Umsatz mit einem Gesamtumsatz von 12.000 $ und 6 Bestellungen. Beruflich gesehen hatten die Fachleute die meisten Aufträge, während die Gruppe der Führungskräfte die geringste Anzahl von Aufträgen hatte. Die Gesamtzahl der Kunden stieg mit einigen Ausnahmen allmählich an, während der Umsatz pro Kunde mit einigen Ausnahmen allmählich zurückging.

## Verwendete technische Tools: 
Excel, Power BI Desktop.

## Verwendete Techniken/Fähigkeiten:
Power BI -  Datenvisualisierung, DAX.

Power Query Editor - Laden und Bereinigen von Daten 

###  Überblick über das Executive Dashboard 
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Executive-Dashboard.jpg)

###  Übersicht über das Dashboard auf Produktebene 
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Produkt_Ebene-Dashboard.jpg)

###  Übersicht über die Kundenebene_Dashboard
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Kunden_Ebene-Dashboard.jpg)

###  Übersicht über den Tooltip für die Kategorie 
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Kategorie_Tooltip.jpg)

###  Übersicht über benutzerdefinierte visuelle Elemente (animiertes Barrennen) 
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Benutzerdefiniertes_Bildmaterial_(Animierter_Balkenlauf).jpg)


# Projekt 4 - Humanressourcen Datenanalyse 
[https://github.com/anandjain55/Humanressourcen_Datenanalyse](https://github.com/anandjain55/Humanressourcen_Datenanalyse)

Dies ist das Projekt, das ich während meiner Kurse durchgeführt habe. Dabei werden die Daten zunächst in Excel verarbeitet und dann das Dashboard in Excel erstellt.

## Geschäftsproblem und Kontext:
Sie arbeiten als Datenanalyst und müssen der Personalabteilung des Unternehmens einen interaktiven und dynamischen Bericht mit Excel zur Verfügung stellen, in dem die Beschäftigungsinformationen dargestellt werden. 

Die Personalabteilung möchte die Gesamtzahl der aktiven und ausscheidenden Mitarbeiter nach Geschlecht, Ausbildung, Funktion, Abteilung, Altersgruppe und Familienstand kennen, damit das Unternehmen Einblicke in die Beschäftigungssituation erhält. Die Personalabteilung möchte auch wissen, wie viele Mitarbeiter mit ihrer Arbeit zufrieden sind.

## Abgeleitete Schlüsselerkenntnisse :
1.	Dieses Dashboard ist vollständig interaktiv und dynamisch.
2.	Die Personalabteilung kann Einblicke in die Leistung der Unternehmen in Bezug auf Bildungsbereiche, Abteilungen und Geschlecht erhalten.
3.	Dieses Dashboard konzentriert sich hauptsächlich auf die Fluktuation, d.h. auf die Mitarbeiter, die das Unternehmen verlassen. Die KPIs geben Aufschluss über die Gesamtleistung des Unternehmens und einen Gesamtüberblick über die Personalabteilung.
4.	Es veranschaulicht, wie viele Mitarbeiter das Unternehmen nach Alter, Geschlecht, Familienstand und Aufgabenbereich verlassen.
5.	Wir haben Slicer wie Bildungsbereich, Abteilung und Geschlecht, nach denen wir visuelle Darstellungen filtern und das Dashboard dynamisch betreiben können, und die Daten wurden entsprechend dem ausgewählten Bildungsbereich, der Abteilung und dem Geschlecht geändert.
6.	Oben rechts befindet sich die Bewertung der Arbeitszufriedenheit, die in einem kleinen Donut-Diagramm dargestellt ist.
7.	Kleine Donut-Diagramme und Formen wurden verwendet, um die Gesamtzahl der Mitarbeiter nach Geschlecht darzustellen.
8.	Das Tortendiagramm zeigt die Fluktuation in den einzelnen Abteilungen.
9.	Ein Baumdiagramm zeigt die Fluktuation nach Aufgabenbereich und deren Prozentsatz.
10.	Die Zuordnung nach Ausbildung wird in einem Balkendiagramm dargestellt, während die Fluktuation nach Gruppe in einem Säulen- oder Häufigkeitsdiagramm gezeigt wird.
11.	Ein Trichterdiagramm zeigt die Fluktuation bei geschiedenen, ledigen und verheirateten Mitarbeitern.

## Ergebnis und Schlussfolgerung aus dem Dashboard:
1.	Die Gesamtzahl der aktiven Mitarbeiter für alle Abteilungen und Bildungsbereiche beträgt 1233 und die Fluktuationsrate der Mitarbeiter liegt bei 16 % mit einer Bewertung der Arbeitszufriedenheit von 2,6 von 4. 
Die Gesamtzahl der Mitarbeiter ist 1,5-mal höher als die der Frauen, wobei die höchste Fluktuationsrate bei Junggesellen und Labortechnikern zu verzeichnen ist. 
Junge Mitarbeiter der F&E-Abteilung weisen die höchste Fluktuation auf (56,12 %). Bei Alter und Familienstand ist die höchste Fluktuation bei alleinstehenden Arbeitnehmern im Alter von 25-34 Jahren zu verzeichnen. 
2.	Die höchste Fluktuationsrate von 24 % der 100 aktiven Mitarbeiter mit technischem Hochschulabschluss steht im Gegensatz zur Zufriedenheit mit dem Arbeitsplatz, die mit 3,9 von 4 Punkten bewertet wird. 
Die meisten Mitarbeiter, die aus diesem Bereich ausscheiden, sind alleinstehende Männer im Alter von 25 bis 34 Jahren, die einen Bachelor-Abschluss haben und in der Rolle eines Wissenschaftlers arbeiten. 
Die höchste Fluktuation (62,5 %) ist in der Forschungs- und Entwicklungsabteilung in diesem Bildungsbereich zu verzeichnen.
3.	Mitarbeiter mit dem Bildungsbereich Marketing sind mit einer Bewertung von 1,8 von 4 am wenigsten zufrieden.
4.	In der Abteilung Vertrieb ist die Fluktuation mit 21 % am höchsten, während sie in der Abteilung Forschung und Entwicklung mit 14 % am niedrigsten ist.

## Verwendete technische Tools: 
MS Excel, MS Power Point.

## Verwendete Techniken/Fähigkeiten :
Power Query Editor, Datenvisualisierung (KPIs, Slicer, Diagramme und Schaubilder)

###  Überblick über das Executive Dashboard 
![](HR_Datenanalyse-Dashboard.png)



# Projekt 5 - Analyse Historischer Hoteldaten 
[https://github.com/anandjain55/Analyse_Historischer_Hoteldaten](https://github.com/anandjain55/Analyse_Historischer_Hoteldaten)

## Geschäftsproblem und Kontext:

Entwickeln Sie eine Datenbank zur Analyse und Visualisierung von Hotelbuchungsdaten und erstellen Sie dann mit Power BI ein Dashboard, das Sie Ihren Stakeholdern präsentieren können. 

Das Dashboard sollte die Trends der Einnahmen, des durchschnittlichen Tagessatzes pro Nacht, des durchschnittlichen Rabatts und der benötigten Parkplätze zeigen. 

Sie müssen die Frage beantworten, ob die Hoteleinnahmen und der durchschnittliche Tagessatz von Jahr zu Jahr steigen und ob wir die Größe unserer Parkplätze erhöhen sollten.

## Datenquelle:
Historische Hoteldaten von 2018-2020.

## Die wichtigsten Schritte im Projekt :
1. Aufbau einer Datenbank 
2. Analysieren und Abrufen von Daten mit SQL (Entwicklung einer SQL-Abfrage) 
3. Power BI mit einer Datenbank verbinden 
4. Daten in Power BI visualisieren
5. Unsere Ergebnisse zusammenfassen
   
## Key Insights abgeleitet:
1.	KPIs für Einnahmen, durchschnittliche Tagesraten, Gesamtübernachtungen, durchschnittliche Rabatte und benötigte Parkplätze helfen, einen Überblick über die Hoteldaten zu erhalten. 
2.	Datum, Hoteltyp und Land Slicer hilft, die Daten nach Bedarf zu filtern und auch KPI's wird geändert.
3.	Ein Liniendiagramm hilft, die Umsatzentwicklung beider Hotels für einen bestimmten Zeitraum zu vergleichen.
4.	Die Matrix zeigt einen Überblick über die Umsatzdaten und die benötigten Parkplätze, was uns hilft, unser Geschäftsproblem in Bezug auf die Größe des Parkplatzes zu lösen. Die blau markierten Linien zeigen die Zeile mit dem höchsten Wert.
   
## Ergebnis und Schlussfolgerung aus dem Dashboard :
1.	Die Hoteleinnahmen steigen von 2018 bis 2020. Der höchste Umsatz ist im Jahr 2019 zwischen 2018 und 2020 und sein Wert beträgt 26,63 Millionen Dollar für beide Hotels und alle Länder. Unter beiden Hotels ist der Wert 2019 für das Stadthotel am höchsten und beträgt 7,19 Mio. $ für alle Länder.
2.	Da der Prozentsatz der Parkplätze stagniert, haben wir nicht viele Anhaltspunkte, um zu entscheiden, ob wir einen Parkplatz bauen sollten oder nicht.
3.	Der adr steigt von 2018- 2020 . Der höchste durchschnittliche Tagessatz ist im Jahr 2019 zwischen 2018 und 2020 und sein Wert beträgt 119,86 Mio. $ für beide Hotels und alle Länder. Bei beiden Hotels ist der durchschnittliche Tagessatz auch im Jahr 2020 für das Stadthotel am höchsten und hat einen Wert von 123,02 Mio. $ für alle Länder.
   

## Verwendete technische Tools : 
Sql Server Management Studio, Power BI Desktop.

## Verwendete Techniken/Fertigkeiten :
Sql Server, 
Power BI - Datenvisualisierung, DAX, Power Query-Editor.

### Überblick über das Executive Dashboard 
![](Historische_Hoteldaten-Dashboard.jpg)




# Projekt 6 - Globale Superstore-Verkaufsdatenanalyse 
[https://github.com/anandjain55/Globale_Superstore_Verkaufsdatenanalyse](https://github.com/anandjain55/Globale_Superstore_Verkaufsdatenanalyse)

## Geschäftsproblem und Kontext:
Führen Sie ETL auf dem globalen Superstor_2016-Datensatz durch, der in csv-Dateien vorliegt, indem Sie ihn in Power BI importieren. Erstellen Sie ein interaktives Dashboard, um KPIs zu Verkäufen, verkauften Mengen, Liefertagen und zurückgesandten Produkten zu verfolgen, Verkäufe nach Segmenten und Märkten zu vergleichen, hochwertige Kunden und Trends auf Produktebene zu analysieren.

## Datenquelle:
 Open-Source-Datensatz Global Superstor_2016.

## Abgeleitete Schlüsselerkenntnisse : 
1.	Der Umsatz, die Menge der verkauften Artikel, die durchschnittliche Anzahl der benötigten Liefertage und die Anzahl der zurückgesandten Bestellungen wurden anhand von KPIs berechnet.
2.	Slicers hilft, die Daten nach Jahr zu filtern.
3.	Die Eignung der Region für den Verkauf von Produkten wurde durch eine Karte dargestellt, die bei Bedarf zur Verbesserung unseres Geschäfts beitragen kann.
4.	Das Tortendiagramm zeigt uns den Verkaufswert und seinen Prozentsatz nach Segment.
5.	Das Donut-Diagramm zeigt die Verkaufsdetails nach Markt.
6.	Die Filteroption "Top N" in Kombination mit den Balkendiagrammen hilft, die 10 besten Kunden und 10 besten Produkte mit den höchsten Gewinn- und Verlustwerten zu finden.

## Ergebnis und Schlussfolgerung aus dem Dashboard :
1.	Der Verkauf und die verkaufte Menge steigen von 2012 bis 2015 mit dem niedrigsten Wert im Jahr 2012 und dem höchsten Wert im Jahr 2015.
2.	Der insgesamt höchste Umsatz hat einen Wert von 12,64 Mio. $ und die verkaufte Menge beträgt 178.000 Stück in allen Jahren. Der höchste Verkaufswert ($ 4,3 Mio.) wurde 2015 erzielt und die höchste verkaufte Menge betrug 60,62 T. 
3.	Im Jahr 2015 verzeichnete das Verbrauchersegment den höchsten Umsatz (2,14 Mio. USD), was ungefähr der Hälfte des Gesamtumsatzes in diesem Jahr entspricht. Der asiatisch-pazifische Raum ist der größte Absatzmarkt (1,37 Mio. $) mit 31,93 % des Gesamtumsatzes.
4.	Tamara Chand ist der umsatzstärkste Kunde in den Jahren 2012-2015 und auch im Jahr 2015.
5.	Motorola smart phone full size hat den höchsten Gewinn im Jahr 2015 und Cannon imageCLASS 2200 Advance Copier hat den höchsten Gewinn zwischen 2012 -2015.
6. Das Produkt mit dem höchsten Verlust ist der Bewis-Computertisch komplett montiert im Jahr 2015 und auch in den Jahren 2012-2015. 

## Abgedeckte Schlüsselschritte : 
1. Verbinden der Datenbank mit Power BI Desktop. 
2. Analysieren der Tabellen und Beziehungen. 
3. Datenbereinigung mit Power Query Editor mit DAX (Datenanalyseausdrücke). 
4. Entwicklung eines interaktiven BI Dashboards / Berichts.

## Verwendete technische Tools: 
Excel, Power BI Desktop.

## Verwendete Techniken / Fertigkeiten :
Power BI - Datenvisualisierung, DAX, Power Query Editor.

### Überblick über das Executive Dashboard 
![](Globales_Superstore_Verkaufs-Dashboard.jpg)



# Projekt 7 - Skishop-Analyse_mit_Python 
[https://github.com/anandjain55/Skishop-Analyse_mit_Python](https://github.com/anandjain55/Skishop-Analyse_mit_Python)

## Geschäftsproblem und Kontext:
Dieses Projekt besteht aus zwei Teilen. Der erste Teil ist die Datenvorbereitung und der zweite Teil die Analyse. Der Excel-Experte ist seit drei Monaten auf Skiern unterwegs und muss nun die Verkaufsdaten für den Schwarzen Freitag analysieren. In der beigefügten Excel-Arbeitsmappe werden Sie sehen, dass Daten für Steuern und Summen fehlen. Sie müssen diese Datenzeilen mit Python? ausfüllen.

Im zweiten Teil geht es darum, durch Aggregation von Daten einige Schlüsselkennzahlen zu berechnen, die sehr hilfreich sind, um zu ermitteln, wie gut die Leistung während des Black Friday war.

Einige der Ziele in diesem Abschnitt sind die Definition einer Funktion, die Excel-Spalten summiert, die Nutzung eines Listenverständnisses, die Anwendung numerischer Funktionen zur Berechnung von KPIs, die Verwendung von Mengenoperationen, um eindeutige Elemente zu finden, die Erstellung eines Wörterbuchs mit verschachtelten Schleifen.

## Projektlösung Schritt für Schritt mit Beschreibung:
![](Bilder_der_Skishop-Analyse_mit_Python/Skishop-Analyse_mit_Python_page-0001.jpg) 
![](Bilder_der_Skishop-Analyse_mit_Python/Skishop-Analyse_mit_Python_page-0002.jpg)
![](Bilder_der_Skishop-Analyse_mit_Python/Skishop-Analyse_mit_Python_page-0003.jpg)
![](Bilder_der_Skishop-Analyse_mit_Python/Skishop-Analyse_mit_Python_page-0004.jpg)
![](Bilder_der_Skishop-Analyse_mit_Python/Skishop-Analyse_mit_Python_page-0005.jpg)
![](Bilder_der_Skishop-Analyse_mit_Python/Skishop-Analyse_mit_Python_page-0006.jpg)
![](Bilder_der_Skishop-Analyse_mit_Python/Skishop-Analyse_mit_Python_page-0007.jpg)
![](Bilder_der_Skishop-Analyse_mit_Python/Skishop-Analyse_mit_Python_page-0008.jpg)
![](Bilder_der_Skishop-Analyse_mit_Python/Skishop-Analyse_mit_Python_page-0009.jpg)
![](Bilder_der_Skishop-Analyse_mit_Python/Skishop-Analyse_mit_Python_page-0010.jpg)


# Project - 8  Arbeit an einem realen Projekt des COVID-19-Datensatzes mit Pandas, Matplotlib und Seaborn von Python. 

## Geschäftsproblem und Kontext:

Dieses Projekt basiert auf dem Covid-19-Datensatz.
Die hier verwendeten Daten sind bis zum 29-Apr-2020 und haben Datensätze ab dem 29-Apr-2020.
Diese Daten sind als CSV-Datei verfügbar, die von Kaggle heruntergeladen wurde.
Die Daten müssen analysiert werden, um die folgenden Fragen zu beantworten:

Q.1 ) Zeigen Sie die Anzahl der bestätigten, verstorbenen und wiedergefundenen Fälle in jeder Region.
Q2) Entfernen Sie alle Datensätze, bei denen die Zahl der bestätigten Fälle unter 10 liegt.
Q.3) In welcher Region wurde die höchste Anzahl an bestätigten Fällen verzeichnet?
Q.4) In welcher Region wurde die geringste Anzahl von Todesfällen registriert?
F.5) Wie viele bestätigte Fälle, Todesfälle und wiedergefundene Fälle wurden bis zum 29. April 2020 aus Indien gemeldet?
Q. 6-A ) Sortieren Sie die gesamten Daten nach der Anzahl der bestätigten Fälle in aufsteigender Reihenfolge.
Q. 6-B ) Sortieren Sie die gesamten Daten nach der Anzahl der wieder aufgetretenen Fälle in absteigender Reihenfolge.
## Projektlösung Schritt für Schritt mit Beschreibung:
![](Bilder_COVID-19_Datensatz_Analyse/COVID-19_Datensatz_Analyse_page-0001.jpg)
![](Bilder_COVID-19_Datensatz_Analyse/COVID-19_Datensatz_Analyse_page-0002.jpg)
![](Bilder_COVID-19_Datensatz_Analyse/COVID-19_Datensatz_Analyse_page-0003.jpg)
![](Bilder_COVID-19_Datensatz_Analyse/COVID-19_Datensatz_Analyse_page-0004.jpg)
![](Bilder_COVID-19_Datensatz_Analyse/COVID-19_Datensatz_Analyse_page-0005.jpg)
![](Bilder_COVID-19_Datensatz_Analyse/COVID-19_Datensatz_Analyse_page-0006.jpg)
![](Bilder_COVID-19_Datensatz_Analyse/COVID-19_Datensatz_Analyse_page-0007.jpg)
![](Bilder_COVID-19_Datensatz_Analyse/COVID-19_Datensatz_Analyse_page-0008.jpg)
![](Bilder_COVID-19_Datensatz_Analyse/COVID-19_Datensatz_Analyse_page-0009.jpg)
![](Bilder_COVID-19_Datensatz_Analyse/COVID-19_Datensatz_Analyse_page-0010.jpg)
![](Bilder_COVID-19_Datensatz_Analyse/COVID-19_Datensatz_Analyse_page-0011.jpg)

