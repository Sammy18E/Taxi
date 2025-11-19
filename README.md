# Excel-Dashboard: Analyse der NYC Taxi-Tourdaten

Dieses Projekt entstand im Rahmen des Moduls **Excel – Datenanalyse & Visualisierung**.  
Ziel war es, einen realen Taxidatensatz aus New York City auszuwerten und Erkenntnisse mithilfe von  
Pivot-Tabellen, Diagrammen und einem interaktiven Dashboard sichtbar zu machen.

---

## Projektziele

- Strukturierte Analyse des Datensatzes *2020624_Praxisprojekt_Datensatz_Taxis.csv*  
- Erstellung eines interaktiven Excel-Dashboards  
- Einsatz von Pivot-Tabellen, Diagrammen, Filtern und Slicern  
- Untersuchung relevanter Fragestellungen rund um Passagiere, Wochentage, Uhrzeiten und Zahlungsmethoden  
- Präsentation der wichtigsten Erkenntnisse in einer separaten Excel-Datei

---

## Analysierte Fragestellungen

Das Projekt beantwortet u. a. folgende Fragen:

- Wie ist die **Verteilung der Anzahl der Passagiere**? (Fahren die meisten Touren mit 1, 2 oder 3 Gästen?)
- An welchen **Wochentagen** wird am meisten Taxi gefahren zu welchen **Tageszeiten**?  
- Gibt es einen Zusammenhang zwischen der **Tourlänge** und den **Wochentagen**?  
- Wie ist die Verteilung der **Zahlungsarten**? Gibt es hier einen Zusammenhang zwischen **Tourlänge** oder **Wochentag**?  
- In welchen **Stadtteilen** beginnen bzw. enden die meisten Touren?  
- Gibt es einen Zusammenhang zwischen der **Zahlungsmethode** und der **Höhe des Trinkgeldes**, die ein Fahrer bekommt?
- Gibt es einen Zusammenhang zwischen der Anzahl der **Passagiere** und der **Tourlänge** oder des **Wochentages**? 

---

## Meine individuellen Aufgaben

Im Rahmen der Gruppenarbeit war ich für folgende Analysebereiche verantwortlich:

- **Analyse der Passagierverteilung:**  
  Untersuchung, wie viele Personen durchschnittlich pro Fahrt mitfahren (1, 2, 3 oder mehr Passagiere).

- **Analyse der Wochentage und Tageszeiten:**  
  Ermittlung der Tage und Uhrzeitbereiche mit dem höchsten Taxiaufkommen.

- **Analyse der Start- und Zielbezirke:**  
  Identifikation der Stadtteile, in denen besonders viele Fahrten beginnen bzw. enden.

---

## Vorgehensweise

### **1. Datenimport und Aufbereitung**
- Import des CSV-Datensatzes  
- Umwandlung von Zeitstempeln in Wochentage und Uhrzeitgruppen  
- Prüfung auf fehlende oder unplausible Werte

### **2. Pivot-Tabellen**
- Gruppierung nach Wochentag, Tageszeit und Passagieranzahl  
- Analyse der Fahrtdistanzen  
- Vergleich von Zahlungsmethoden und Trinkgeldern  
- Ermittlung regionaler Muster

### **3. Diagramme**
- Balken- und Säulendiagramme  
- Liniendiagramme  
- Kreisdiagramme  
- Kombinierte Diagramme  
- Nutzung von Farben und Layouts für Übersichtlichkeit

### **4. Dashboard**
Ein interaktives Dashboard zeigt die wichtigsten Metriken auf einen Blick, inkl.:

- Fahrten pro Tag / Stunde  
- Passagierverteilung  
- Bezirke mit den meisten Fahrten  
- Zahlungstypen und Trinkgelder  
- Vergleich von Distanz, Zeit und Fahrtverhalten  

---

## Dateien im Repository
```text
Taxi-Excel-Projekt/
│
├── 2020624_Praxisprojekt_Datensatz_Taxis.csv
│   → Originaldatensatz (NYC Taxi Tourdaten)
│
├── 20241218_Praxisprojekt_Datensatz_Taxis_pickupsdropoffs_SammyEhl.xlsx
│   → Persönliche Analyse- und Arbeitsdatei
│
└── Präsi_Datei_FINAL_Fanni_Laura_Sammy.xlsx
    → Gemeinsame Abschlusspräsentation (3er-Team)
```

---

## Verwendete Excel-Tools

- Pivot-Tabellen
- Slicer (Filterelemente)
- Diagramme & Charts
- Gruppierungen (Zeit & Datum)
- Bedingte Formatierung
- Dashboard-Gestaltung
- Layout-Formatierungen

---

## Zusammenfassung

Dieses Projekt zeigt, wie sich große reale Datensätze vollständig in Excel analysieren und visualisieren lassen.
Das erstellte Dashboard bietet einen verständlichen Überblick über das Fahrverhalten in New York City und unterstützt datenbasierte Entscheidungen.
