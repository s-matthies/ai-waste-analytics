# BSR KI-Projekt für Müllabfuhr-Optimierung

## Projektbeschreibung
Dieses Projekt analysiert und optimiert die Müllabfuhr-Prozesse der Berliner Stadtreinigung (BSR) mithilfe von KI-Methoden. Basierend auf BSR-Datensätzen der letzten vier Jahre wurden Vorhersagen für das kommende Jahr entwickelt. Um die Prognosegenauigkeit zu verbessern, wurden verschiedene öffentlich zugängliche Datensätze in die Analyse einbezogen, darunter Wetterdaten, Schulferien, Feiertage und Wahlumfragen. Die detaillierten Ergebnisse und Analysen sind in der Projektdokumentation zusammengefasst.

## Projektstruktur
- `Daten/`: Enthält die Rohdaten und verarbeiteten Datensätze
- `notebooks_training/`: Jupyter Notebooks für das Training der KI-Modelle
- `Notebooks_vorverarbeitung/`: Jupyter Notebooks für die Datenvorverarbeitung
- `Dokumentation.pdf`: Ausführliche Projektdokumentation
- `Leitfragen_Bericht_PPT.pdf`: Präsentationsunterlagen und Leitfragen
- `Notizen.md`: Zusätzliche Projektnotizen und Datenbeschreibungen

## Datenstruktur
Das Projekt arbeitet mit folgenden Hauptdatensätzen:

### Basis-Daten
- **Monat, KW, Jahr, Datum**: Zeitliche Erfassung der Anlieferungen
- **Hof**: Zuordnung zu verschiedenen BSR-Höfen (VMF, VMG, VMN, VMM, VMWSF, VMWSM, VMWSN)
- **Schicht**: Arbeitszeiterfassung
- **Tour**: Tournummern mit rotierenden Routen (2-Wochen-Rhythmus)
- **Tonnage**: Abfallmenge in Tonnen
- **Abfallart**: Kategorisierung (BIO, HM, SPM)

### Zusätzliche Datensätze
- Wetterdaten
- Inflationsdaten
- Ausfallstatistiken
- Feiertagsdaten
- Wahldaten
- Tourismusdaten

## Installation und Nutzung
1. Repository klonen:
```bash
git clone https://gitlab.rz.htw-berlin.de/s0587519/bsr_ki.git
cd bsr_ki
```

2. Notebooks in der bevorzugten Jupyter-Umgebung öffnen
3. Daten entsprechend der Dokumentation verarbeiten

## Projektkontext
Das Projekt wurde als viertägiges Studienprojekt in einer vierköpfigen Gruppe in Zusammenarbeit mit der Berliner Stadtreinigung (BSR) durchgeführt. Es zielt darauf ab, die Effizienz der Müllabfuhr durch datengetriebene Entscheidungen zu verbessern.

## Autoren und Beteiligte
- Team aus 4 Studierenden der HTW Berlin
