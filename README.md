# Anand's Analytics Portfolio

# Projekt 1 - Sales Dashboard und Datawarehouse mit Produkt- und Kundenhierarchieebenen (https://github.com/anandjain55/Sales-Dashboard)

## Geschäftsfall :
In diesem Projekt müssen Sie mit den Daten vieler Unternehmen arbeiten, die sich mit einer Vielzahl von Produkten beschäftigen. Ihre Aufgabe ist es, die Daten mit SSIS aus der Hauptdatenbank zu extrahieren, einen Staging-Bereich zu erstellen und dann DataMart in SQL Server zu erstellen. Sie sollten KPI für den Verkauf verfolgen, kreative Diagramme erstellen, die die Verkäufe nach Monat und Jahr zeigen, hochwertige Kunden und Trends auf Produktebene analysieren.
Außerdem sollten Sie in der Lage sein, für weitere Details auf Produkt- und Kundenebene aufzuschlüsseln. Ihr Bericht sollte einen Vergleich der Ist-Werte mit den Budgetwerten der Verkäufe enthalten.

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
7.	7.	Das Schaubild zeigt den Minimalwert als 0 und den Maximalwert als das Doppelte des Umsatzes, wobei der Abrufwert der tatsächliche Umsatz von 2019-2023 und der Zielwert der Budget-Umsatz (umsatz_plan) von 2021-2023 ist.
8.	Das Ausblenden des Slicer-Panels enthält den Vertriebsweg-Slicer, der hilft, die Umsatzwerte von Kunden und Produkten zu filtern. 

### Icons und Logos :
Beschreibende Icons werden verwendet, um von einer Seite zur anderen zu wechseln, wie z.B. Produkt, Kunde, Karte und exec Dashboard. Das Slicer-Logo wurde verwendet, um den Vertriebsweg-Slicer auszublenden, um den Platz auf der Seite zu sparen. 

### Produkt- und Kundenhierarchieseiten:
Die Produkt- und Kundenhierarchieseiten enthalten detailliertere Informationen über Kunden und Produkte. Von der Seite "Executive Dashboard" oder "Product" können wir auf die Seite "Product Hierarchy" gehen, um mehr Details über Produkte zu sehen, während wir von der Seite "Customer" auf die Seite "Customer Hierarchy" gehen können, um mehr Details über Kunden zu sehen.

## Verwendete technische Tools : 
Sql Server Management Studio, Visual Studio und Power BI Desktop, 

## Verwendete Techniken/Fähigkeiten :
SQL Server - Sql Server Integration Services, ETL, Datamart, Gespeicherte Prozeduren, Ansichten,
Power BI - DAX, Datenmodellierung, Datenvisualisierung.

###  Überblick über das Executive Dashboard 
![](Executive-Dashboard.jpg)

###  Übersicht der Produktdetails 
![](Produkt-Dashboard.jpg)

###  Übersicht über die Kundendaten 
![](Kunden-Dashboard.jpg)

###  Kartenansicht 
![](Karte.jpg)

###  Übersicht der Produkthierarchie-Ebene 
![](Produkthierarchie.jpg)

###  Übersicht der Kundenhierarchie-Ebene 
![](Kundenhierarchie.jpg)



# Projekt 2 - Personliche-Finanzen-Tracker-Dashboard (https://github.com/anandjain55/Personliche-Finanzen-Tracker-Dashboard)

## Geschäftsproblem und kontext
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
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Persönliche_Finanzen_Tracker_Dashboard.jpg)

### Tooltips 
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Tooltip-1.jpg),
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Tooltip-2.jpg),
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Tooltip-3.jpg),
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Tooltip-4.jpg)



# Projekt 3 - AdventureWorks Bike-Bericht (https://github.com/anandjain55/AdventureWorks-Bike-Company-Report)

## Geschäftsproblem :
Entwickeln Sie eine Datenbank zur Analyse und Visualisierung von Hotelbuchungsdaten und erstellen Sie dann mit Power BI ein Dashboard, das Sie Ihren Stakeholdern präsentieren können. Das Dashboard sollte die Trends der Einnahmen, des durchschnittlichen Tagessatzes pro Nacht, des durchschnittlichen Rabatts und der benötigten Parkplätze zeigen. Sie müssen die Frage beantworten, ob die Hoteleinnahmen und der durchschnittliche Tagessatz von Jahr zu Jahr steigen und ob wir die Größe unserer Parkplätze erhöhen sollten.

## Datenquelle:
Historische Hoteldaten von 2018-2020.


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

## Verwendete Techniken/Fähigkeiten :
Power BI -  Datenvisualisierung, DAX.

###  Überblick über das Executive Dashboard 
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Executive_Dashboard_der_AdventureWorks_Bike_Company.jpg)

###  Übersicht der Produktdetails 
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Produktdetails_der_AdventureWorks_Bike_Company.jpg)

###  Übersicht der Kundendaten 
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Kundendetails_der_AdventureWorks_Bike_Company.jpg)

###  Übersicht über die Kartenansicht 
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Karte_der_AdventureWorks_Bike_Company.jpg)

###  Übersicht über den Tooltip für die Kategorie 
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Tooltip_zur_Kategorie_AdventureWorks_Bike_Company.jpg)

###  Übersicht über benutzerdefinierte visuelle Elemente (animiertes Barrennen) 
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Benutzerdefiniertes_Visual_von_AdventureWorks_Bike_Company_(animiertes_Barrennen).jpg)



# Projekt 4 - HR Data Analytics Dashboard ([HR_Data_Analytics-Dashboard.jpg](https://github.com/anandjain55/Excel_HR_Analytics_Dashboard))

Dies ist das Projekt, das ich während meiner Kurse durchgeführt habe. Dabei werden die Daten zunächst in Excel verarbeitet und dann das Dashboard in Excel erstellt.

## Geschäftliches Problem
Sie arbeiten als Datenanalyst und müssen der Personalabteilung des Unternehmens einen interaktiven und dynamischen Bericht mit Excel zur Verfügung stellen, in dem die Beschäftigungsinformationen dargestellt werden. Die Personalabteilung möchte die Gesamtzahl der aktiven und ausscheidenden Mitarbeiter nach Geschlecht, Ausbildung, Funktion, Abteilung, Altersgruppe und Familienstand kennen, damit das Unternehmen Einblicke in die Beschäftigungssituation erhält. Die Personalabteilung möchte auch wissen, wie viele Mitarbeiter mit ihrer Arbeit zufrieden sind.

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
![](HR_Data_Analytics-Dashboard.jpg)



# Projekt 5 - Analyse historischer Hoteldaten (https://github.com/anandjain55/Analyse-historischer-Hoteldaten) 

## Geschäftsproblem :
Entwickeln Sie eine Datenbank zur Analyse und Visualisierung von Hotelbuchungsdaten und erstellen Sie dann mit Power BI ein Dashboard, das Sie Ihren Stakeholdern präsentieren können. Das Dashboard sollte die Trends der Einnahmen, des durchschnittlichen Tagessatzes pro Nacht, des durchschnittlichen Rabatts und der benötigten Parkplätze zeigen. Sie müssen die Frage beantworten, ob die Hoteleinnahmen und der durchschnittliche Tagessatz von Jahr zu Jahr steigen und ob wir die Größe unserer Parkplätze erhöhen sollten.

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



# Projekt 6 - Globale Supertstore_2016 Umsatz-Dashboard (https://github.com/anandjain55/Globale-Supertstore_2016-Umsatz-Dashboard)
Dabei werden zunächst die Daten in Power BI verarbeitet und anschließend das Dashboard ebenfalls in Power BI erstellt.

## Verwendete technische Tools : 
Sql Server Management Studio, Power BI Desktop. 

## Verwendete Techniken / Fertigkeiten / Software :
SQL Server und Power BI, Datenvisualisierung, DAX.

### Überblick über das Executive Dashboard 
![](Globale_Supertstore_2016_Umsatz-Dashboard.jpg)



