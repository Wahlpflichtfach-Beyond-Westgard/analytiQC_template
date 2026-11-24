# analytiQC_template
# Qualitätskontrolle im medizinischen Labor mit R, Git und GitHub

Willkommen im Projektrepository Ihrer Arbeitsgruppe.

In diesem Projekt analysieren Sie Qualitätskontrolldaten aus dem medizinischen Labor und entwickeln einen reproduzierbaren Workflow zur Qualitätssicherung mit R. Gleichzeitig lernen Sie die kollaborative Arbeit mit Git und GitHub kennen.

---

# Lernziele

Nach Abschluss des Projekts können Sie:

- Qualitätskontrolldaten in R einlesen und verarbeiten
- Mittelwert, Standardabweichung, Variationskoeffizient und Bias berechnen
- Levey-Jennings-Diagramme erstellen
- Westgard-Regeln programmatisch prüfen
- typische Fehlerquellen im Labor erkennen
- Git und GitHub für die Zusammenarbeit nutzen
- Analyseergebnisse reproduzierbar dokumentieren

---

# Projektstruktur

```text
.
├── data/
│   └── qc_daten.csv
│
├── R/
│   ├── 01_daten_einlesen.R
│   ├── 02_auswertung.R
│   ├── 03_levey_jennings.R
│   └── 04_westgard.R
│
├── docs/
│   ├── arbeitsprotokoll.md
│   └── bericht.md
│
├── output/
│   ├── grafiken/
│   └── berichte/
│
├── .gitignore
└── README.md
```

---

# Team

Bitte ergänzen Sie die Namen Ihrer Gruppe.

| Name | GitHub-Username | Verantwortungsbereich |
|--------|----------------|------------------------|
| | | |
| | | |
| | | |
| | | |

---

# Arbeitsaufträge

## Aufgabe 1: Daten einlesen

Datei:

```text
R/01_daten_einlesen.R
```

Ziele:

- CSV-Datei einlesen
- Datentypen prüfen
- Datenstruktur dokumentieren

---

## Aufgabe 2: Grundlegende Qualitätskennzahlen

Datei:

```text
R/02_auswertung.R
```

Berechnen Sie:

- Mittelwert
- Standardabweichung
- Variationskoeffizient (CV%)
- Bias

Dokumentieren Sie die Ergebnisse in:

```text
docs/bericht.md
```

---

## Aufgabe 3: Levey-Jennings-Diagramm

Datei:

```text
R/03_levey_jennings.R
```

Erstellen Sie:

- Mittelwertlinie
- ±1 SD
- ±2 SD
- ±3 SD

Speichern Sie die Grafik in:

```text
output/grafiken/
```

---

## Aufgabe 4: Westgard-Regeln

Datei:

```text
R/04_westgard.R
```

Implementieren Sie folgende Regeln:

- 1-2s
- 1-3s
- 2-2s
- R-4s
- 4-1s
- 10x

Dokumentieren Sie:

- welche Regel verletzt wurde
- mögliche Fehlerursachen
- notwendige Maßnahmen

---

# GitHub-Workflow

## Vor Arbeitsbeginn

```bash
git pull
```

Aktuellen Stand vom Repository abrufen.

---

## Änderungen speichern

```bash
git add .
git commit -m "Kurze Beschreibung der Änderung"
```

Beispiel:

```bash
git commit -m "Levey-Jennings-Diagramm ergänzt"
```

---

## Änderungen hochladen

```bash
git push
```

---

# Arbeiten mit Branches

Für neue Funktionen verwenden Sie eigene Branches:

```bash
git checkout -b feature-westgard
```

Nach Abschluss:

```bash
git push origin feature-westgard
```

Erstellen Sie anschließend einen Pull Request auf GitHub.

---

# Dokumentation der Zusammenarbeit

Jedes Teammitglied dokumentiert seine Beiträge in

```text
docs/arbeitsprotokoll.md
```

Beispiel:

```markdown
## Max Mustermann

- Datenimport erstellt
- Mittelwert berechnet
- Pull Request #2 bearbeitet
```

---

# Qualitätskriterien

Bei der Bewertung werden folgende Aspekte berücksichtigt:

| Kriterium | Gewichtung |
|------------|-------------|
| Korrekte Datenanalyse | 30 % |
| Umsetzung der Westgard-Regeln | 25 % |
| Dokumentation | 15 % |
| GitHub-Nutzung | 15 % |
| Zusammenarbeit im Team | 15 % |

---

# Abgabe

Die Abgabe erfolgt über den Link zu Ihrem GitHub-Repository.

Folgende Dateien müssen vorhanden sein:

✅ README.md

✅ daten.csv

✅ Analyse-Skripte

✅ Levey-Jennings-Diagramm

✅ Implementierte Westgard-Regeln

✅ Arbeitsprotokoll

✅ Abschlussbericht

---

# Ehrenkodex

Alle Gruppenmitglieder verpflichten sich, ihre Beiträge transparent zu dokumentieren und die Regeln guter wissenschaftlicher Praxis einzuhalten. Die Versionshistorie des Repositories dient als Nachweis der individuellen Mitarbeit.

Viel Erfolg bei der Analyse Ihrer Qualitätskontrolldaten!
