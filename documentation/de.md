<!-- ELUCENIA technical documentation · criterios-acr-eular-artrite-reumatoide · de · no clinical/professional/rights approval -->

# ACR/EULAR-Kriterien 2010 für rheumatoide Arthritis

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/criterios-acr-eular-artrite-reumatoide)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Gelenkbeteiligung (Schwellung oder Schmerz)

`artic`

- `0` — 1 großes Gelenk
- `1` — 2 bis 10 große Gelenke
- `2` — 1 bis 3 kleine Gelenke (mit oder ohne große Gelenke)
- `3` — 4 bis 10 kleine Gelenke (mit oder ohne große Gelenke)
- `5` — \> 10 Gelenke (mindestens 1 kleines Gelenk)

### Serologie (Rheumafaktor und Anti-CCP)

`soro`

- `0` — Beide negativ
- `2` — Mindestens ein niedrig-positiver Titer (bis zum 3-Fachen der Obergrenze)
- `3` — Mindestens ein hoch-positiver Titer (\> 3× die Obergrenze)

### Akutphaseparameter (CRP und BSG)

`fase`

- `0` — Beide normal
- `1` — CRP oder BSG erhöht

### Symptomdauer

`duracao`

- `0` — \< 6 Wochen
- `1` — ≥ 6 Wochen

## Fassung der Methode

ACR/EULAR 2010: 4 Domänen, gesamt 0–10, Grenze≥6; Kontext und Ausschlüsse erforderlich

## Dokumentierte Formel

Summe von vier Domänen (maximal 10): Gelenke (0–5), Serologie (0–3), Akutphaseparameter (0–1), Symptomdauer (0–1). ≥ 6 = gesicherte RA.

Große Gelenke: Schultern, Ellenbogen, Hüften, Knie, Sprunggelenke. Kleine: MCP, PIP, 2.–5. MTP, Daumen-IP und Handgelenke.

## Grenzen und Population

Die ACR/EULAR-Klassifikation 2010 erfordert vor Anwendung der Schwelle ≥6/10 eine bestätigte Synovitis in mindestens einem Gelenk und das Fehlen einer besser erklärenden alternativen Diagnose. Sie wurde für neu aufgetretene undifferenzierte entzündliche Synovitis entwickelt. Der Score allein bildet ohne diese Bedingungen die Klassifikationskriterien nicht ab.

## Referenzen

- [Aletaha D et al. 2010 Rheumatoid arthritis classification criteria: an American College of Rheumatology/European League Against Rheumatism collaborative initiative. Arthritis Rheum, 2010.](https://doi.org/10.1002/art.27584)

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
