<!-- ELUCENIA technical documentation · indice-de-bishop · de · no clinical/professional/rights approval -->

# Bishop-Score

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/indice-de-bishop)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Dilatation

`dil`

- `0` — Geschlossen
- `1` — 1 bis 2 cm
- `2` — 3 bis 4 cm
- `3` — ≥ 5 cm

### Zervixverstreichen

`apag`

- `0` — 0 bis 30%
- `1` — 40 bis 50%
- `2` — 60 bis 70%
- `3` — ≥ 80%

### Höhenstand der Präsentation (De Lee)

`alt`

- `0` — −3
- `1` — −2
- `2` — −1 oder 0
- `3` — +1 oder +2

### Zervixkonsistenz

`cons`

- `0` — Fest
- `1` — Mittelwert
- `2` — Weich

### Zervixposition

`pos`

- `0` — Posterior
- `1` — Mittel
- `2` — Anterior

## Fassung der Methode

Bishop 1964: 5 Komponenten 0–13; prozentuales Verstreichen, keine Zervixlängen-Version

## Dokumentierte Formel

Summe von 5 vaginalen Befunden: Dilatation (0–3), Verstreichen (0–3), Höhenstand (0–3), Konsistenz (0–2), Zervixlage (0–2). Gesamt 0–13.

## Grenzen und Population

Der klassische Bishop beschreibt die Zervixreife anhand von fünf Untersuchungskomponenten und berechtigt allein nicht zur Geburtseinleitung. Der Artikel von 1964 untersuchte einen historischen Kontext von Mehrgebärenden ab 36 Schwangerschaftswochen; daraus ergibt sich keine aktuelle Indikation zur elektiven Einleitung in diesem Gestationsalter. Die konsultierte institutionelle ACOG-Empfehlung verlangt eine Prüfung der geburtshilflichen Indikationen und Kontraindikationen sowie keine elektive Einleitung vor 39 Wochen. Diese Version verwendet die Zervixverstreichung in Prozent, keine modifizierte Variante anhand der Zervixlänge.

## Referenzen

- [Bishop EH. Pelvic scoring for elective induction. Obstet Gynecol, 1964.](https://pubmed.ncbi.nlm.nih.gov/14199536/)

- [American College of Obstetricians and Gynecologists. ACOG Practice Bulletin No. 107: Induction of Labor. Obstet Gynecol, 2009.](https://doi.org/10.1097/AOG.0b013e3181b48ef5)

- [Bishop1964](https://epp.evidencio.com/uploads/files/models/files/1293/0bf17b-Bishop%20EH%2C%201964.pdf)

- [ACOG patient FAQ,current retrieval2026-10-04](https://www.acog.org/womens-health/faqs/labor-induction)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Ungünstiger Muttermund (≤ 6): vor Oxytocin eine Zervixvorbereitung angeben

Vorbereitungsmethoden: Misoprostol, Foley-Katheter oder Dinoproston, entsprechend dem Protokoll der Einrichtung und der Uterusnarbe.


### 2

Mittlerer Muttermund (7 bis 8)

Die Wahrscheinlichkeit einer vaginalen Entbindung nach der Einleitung ist geringer als bei einem günstigen Muttermund; die Zervixvorbereitung individuell anpassen.


### 3

Günstiger Muttermund (> 8): Wahrscheinlichkeit einer vaginalen Entbindung ähnlich wie bei spontanem Wehenbeginn

Kann mit Oxytocin und/oder Amniotomie eingeleitet werden.


### 4

Günstiger Muttermund (> 8): Wahrscheinlichkeit einer vaginalen Entbindung ähnlich wie bei spontanem Wehenbeginn

Kann mit Oxytocin und/oder Amniotomie eingeleitet werden.

