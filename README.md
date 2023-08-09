# Anand's Analytics Portfolio

# Projekt 1 - Sales Dashboard und Datawarehouse mit Produkt- und Kundenhierarchieebenen (https://github.com/anandjain55/Sales-Dashboard)

## Geschäftsfall :
In diesem Projekt müssen Sie mit den aktuellen Daten vieler Unternehmen arbeiten, die mit einer Vielzahl von Produkten handeln. Ihre Aufgabe ist es, die Daten aus der Hauptdatenbank mit Hilfe von SQL Server Integration Services (SSIS) zu extrahieren, einen Staging-Bereich zu erstellen und dann DataMart in SQL Server zu erstellen. Sie sollten die KPIs für den Verkauf verfolgen, kreative Diagramme erstellen, die die Verkäufe nach Monat und Jahr zeigen, hochwertige Kunden und Trends auf Produktebene analysieren.
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

## Details der Datenvisualisierung verwenden :
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
Sql Server Management Studio, Visual Studio, Power BI Desktop.

## Verwendete Techniken / Fertigkeiten / Software :
Sql Server Integration Services, Sql Server und Power BI, Datenvisualisierung, DAX.

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

## Geschäftsproblem und kontext :
Erstellung eines persönlichen Finanz-Trackers, der bei der Verwaltung und Kontrolle der finanziellen Ausgaben hilft. Der Zweck dieses Projekts ist es, schon in jungen Jahren Finanzwissen zu vermitteln und Analysen in das tägliche Leben einzubinden.

## Datenquelle :
Die Rohdaten der durchschnittlichen Ausgaben des Jahres 2022 aus Indien wurden in Excel erstellt.
Vorgehensweise - Die Rohdaten wurden in Excel erstellt und dann in Power BI importiert. ETL wurde für die Daten mit Power BI durchgeführt, und die bereinigten Daten wurden zur Erstellung eines Dashboards in Power BI verwendet.

## Abgeleitete Schlüsseleinblicke :
Aus dem Bericht können wir Erkenntnisse über das Nettovermögen, die Genauigkeit des Ausgabenmusters, den Status der Sparziele, die besten und schlechtesten finanziellen Monate in Bezug auf Ausgaben und Einsparungen gewinnen.

## Verwendete technische Tools : 
SQL Server Management Studio, MS Excel, Power BI Desktop.

## Verwendete Techniken / Fertigkeiten / Software :
Excel, Power BI, DAX, Datenvisualisierung.

### Überblick über das Executive Dashboard :
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Persönliche_Finanzen_Tracker_Dashboard.jpg)

# Tooltips :
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Tooltip-1.jpg),
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Tooltip-2.jpg),
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Tooltip-3.jpg),
![](Bilder_Persönliche_Finanzen_Tracker_Dashboard/Tooltip-4.jpg)



# Projekt 3 - AdventureWorks Bike-Bericht (https://github.com/anandjain55/AdventureWorks-Bike-Company-Report)

## Geschäftsproblem :
Sie wurden gerade von AdventureWorks, einem fiktiven globalen Produktionsunternehmen, das Fahrradausrüstung und -zubehör herstellt, als Business-Intelligence-Analyst eingestellt. Und Ihre Aufgabe besteht darin, dem Managementteam dabei zu helfen, seine KPIs wie Umsatz, Umsatz, Gewinn und Rendite zu verfolgen, die Leistung über Regionen hinweg zu vergleichen, Trends auf Produktebene zu analysieren und hochwertige Kunden zu identifizieren.

Aber alles, was Sie erhalten haben, ist ein Ordner mit CSV-Rohdateien, die Informationen zu Transaktions- und Retourendatensätzen, Produkten, Kunden und Vertriebsgebieten enthalten.

## Ziel erreicht :
Verwendete den Power BI-Desktop, um diese Rohdaten zu verbinden und zu transformieren, erstellte ein relationales Datenmodell, erstellte berechnete Spalten und Kennzahlen mit DAX und entwarf schließlich ein interaktives Dashboard, um die Visualisierung und Analyse dieser Daten zu unterstützen.

## Wichtige Schritte, die im Projekt (Verfahren) erreicht wurden :
1. Erstellen Sie die Executive Summary-Ansicht, die allgemeine KPIs (Umsatz, Gewinn, Bestellungen, Rücklaufquote), ein wöchentliches Umsatztrenddiagramm, coole interaktive Elemente wie Schieberegler zum Vergrößern bestimmter Zeiträume, benutzerdefinierte Tooltipps und einen vollständig benutzerdefinierten Filterbereich enthält .
2. Sie können einen Drilldown zu einem bestimmten Produkt durchführen, um zur Produktdetailansicht zu gelangen. Dadurch werden Dinge wie die Leistung eines Produkts im Vergleich zu seinem monatlichen Bestell-, Umsatz- oder Gewinnziel angezeigt.
3. Ich habe Dinge wie Parameter für die Was-wäre-wenn-Analyse verwendet. Wie verändert sich in diesem Fall der Preis und wirkt sich dies auf eine Kennzahl wie den Gesamtgewinn aus?
4. Ich habe Feldparameter untersucht, um diese Diagramme für Endbenutzer interaktiver und dynamischer zu gestalten.
5. Ich habe mir die Kartierungs- und Geodatentools von Power BI genauer angesehen und auch eine Ansicht auf Kundenebene erstellt, um die Leistung auf der Ebene einzelner Kunden genauer zu untersuchen und verschiedene Kundenprofile und -segmente aufzuschlüsseln.
6. Dieser gesamte Bericht wurde komplett von Grund auf neu erstellt und enthält lediglich einen Ordner mit rohen CSV-Dateien.

## Ergebnis und Schlussfolgerung :
Wir können KPIs (Umsatz, Umsatz, Gewinn, Rendite) verfolgen, die regionale Leistung vergleichen, Trends auf Produktebene und hochwertige Kunden analysieren.

## Verwendete technische Tools : 
Sql Server Management Studio, Power BI Desktop.

## Verwendete Techniken / Fertigkeiten / Software :
SQL Server und Power BI, Datenvisualisierung, DAX.

###  Überblick über das Executive Dashboard :
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Executive_Dashboard_der_AdventureWorks_Bike_Company.jpg)

###  Übersicht der Produktdetails :
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Produktdetails_der_AdventureWorks_Bike_Company.jpg)

###  Übersicht der Kundendaten :
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Kundendetails_der_AdventureWorks_Bike_Company.jpg)

###  Übersicht über die Kartenansicht :
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Karte_der_AdventureWorks_Bike_Company.jpg)

###  Übersicht über den Tooltip für die Kategorie :
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Tooltip_zur_Kategorie_AdventureWorks_Bike_Company.jpg)

###  Übersicht über benutzerdefinierte visuelle Elemente (animiertes Barrennen) :
![](Bilder_des_AdventureWorks_Bike_Company_Berichts/Benutzerdefiniertes_Visual_von_AdventureWorks_Bike_Company_(animiertes_Barrennen).jpg)



# Projekt 4 - HR Data Analytics Dashboard ([HR_Data_Analytics-Dashboard.jpg](https://github.com/anandjain55/Excel_HR_Analytics_Dashboard))
Dies ist das Projekt, das ich während meiner Kurse durchgeführt habe. Dabei werden die Daten zunächst in Excel verarbeitet und dann das Dashboard in Excel erstellt.

Die Daten stammen aus echten Unternehmensdaten.

## Verwendete technische Tools : 
MS Excel

## Verwendete Techniken / Fertigkeiten / Software :
Power Pivot, Datavisualisierung.

###  Überblick über das Executive Dashboard :
![](HR_Data_Analytics-Dashboard.jpg)



# Projekt 5 - Hotel Revenue Dashboard (https://github.com/anandjain55/SQL_Power-BI_Hotel-Revenue_Dashboard) 
Dies ist das Projekt, das ich während meiner Kurse durchgeführt habe. Die Daten werden zunächst in SQL Server verarbeitet und dann in Power BI importiert und ein Dashboard erstellt.

* Die Daten stammen aus echten Unternehmensdaten.

## Verwendete technische Tools : 
Sql Server Management Studio, Power BI Desktop, 

## Verwendete Techniken / Fertigkeiten / Software :
Sql Server und Power BI, Datenvisualisierung, DAX.

### Überblick über das Executive Dashboard :
![](Hotel_Revenue-Dashboard.jpg)



# Projekt 6 - Globale Supertstore_2016 Umsatz-Dashboard (https://github.com/anandjain55/Globale-Supertstore_2016-Umsatz-Dashboard)
Dabei werden zunächst die Daten in Power BI verarbeitet und anschließend das Dashboard ebenfalls in Power BI erstellt.

## Verwendete technische Tools : 
Sql Server Management Studio, Power BI Desktop. 

## Verwendete Techniken / Fertigkeiten / Software :
SQL Server und Power BI, Datenvisualisierung, DAX.

### Überblick über das Executive Dashboard :
![](Globale_Supertstore_2016_Umsatz-Dashboard.jpg)



