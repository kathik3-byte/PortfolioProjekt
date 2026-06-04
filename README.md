# Analyse globaler Mikroplastik-Hotspots in den Weltmeeren 

> Analyse globaler NOAA-Messdaten zur Untersuchung der räumlichen Verteilung, zeitlichen Entwicklung und geografischen Konzentrationsmuster von Mikroplastik in den Weltmeeren.

## 📊 Projektübersicht

Mikroplastik stellt eine der größten Herausforderungen für marine Ökosysteme dar. Die winzigen Kunststoffpartikel gelangen über Flüsse, Küstenregionen und menschliche Aktivitäten in die Ozeane und können dort über lange Zeiträume verbleiben. Trotz zahlreicher Messprogramme ist die globale Verteilung von Mikroplastik komplex und regional sehr unterschiedlich.

Ziel dieses Projekts ist die Analyse eines internationalen NOAA-Datensatzes, um Belastungsschwerpunkte, zeitliche Entwicklungen und geografische Muster der Mikroplastikverschmutzung sichtbar zu machen.

**Ziel:** 
Im Rahmen dieses Projekts sollen folgende Forschungsfragen beantwortet werden:
 
1. Welche Regionen weisen die höchste Mikroplastikbelastung auf?

Analyse geografischer Hotspots und Vergleich verschiedener Ozeanregionen anhand von Konzentrationswerten.

2. Wie hat sich die Mikroplastikbelastung im Zeitverlauf verändert?

Untersuchung zeitlicher Trends und Entwicklungen der Mikroplastikverschmutzung über mehrere Jahrzehnte.

3. Welche geografischen Muster oder Cluster lassen sich erkennen?

Analyse räumlicher Verteilungen und möglicher Konzentrationscluster in den Weltmeeren.

**Methoden:** 

- Datenbereinigung und Datenvalidierung in Power Query
- Berechnung von Kennzahlen wie Median, Durchschnitt und Maximum
- Geografische Visualisierung von Messpunkten mittels Kartenvisualisierungen
- Zeitreihenanalyse zur Untersuchung langfristiger Entwicklungen
- Clusteranalyse anhand räumlicher Konzentrationsmuster
- Interaktive Dashboards mit Filtern nach Ozean, Jahr und Konzentrationsklasse

**Herausforderungen im Datensatz:** 

Während der Datenaufbereitung wurden mehrere Qualitätsprobleme identifiziert:

- Fehlende oder unvollständige Regionszuordnungen ("Unknown Region")
- Inkonsistente geografische Koordinaten
- Unterschiedliche Einheiten und Messmethoden innerhalb des Datensatzes
- Sehr starke Ausreißer bei einzelnen Messungen mit Konzentrationen von mehreren Milliarden Partikeln pro m³
- Teilweise fehlerhafte oder nicht eindeutig zuordenbare Regionsbezeichnungen

Um die Aussagekraft der Analyse zu erhöhen, wurden ungültige Koordinaten bereinigt und für viele Analysen robuste Kennzahlen wie der Median anstelle des Durchschnitts verwendet.

**Verwendete Daten:**

Quelle: NOAA Marine Microplastics Database

Zeitraum: 1972 – 2022

Anzahl analysierter Messungen: 15.530

Anzahl untersuchter Regionen: 72

Anzahl untersuchter Ozeane: 4

**Zentrale Erkenntnisse:**

- Die Mikroplastikbelastung ist weltweit sehr ungleich verteilt.
- Besonders hohe Belastungen treten in einzelnen regionalen Hotspots auf.
- Die zeitliche Analyse zeigt einen langfristig steigenden Trend der Mikroplastikbelastung.
- Räumliche Cluster konzentrieren sich vor allem im Nordatlantik, Mittelmeerraum und westlichen Pazifik.
- Sehr hohe Konzentrationen sind selten, treten jedoch lokal stark konzentriert auf.
