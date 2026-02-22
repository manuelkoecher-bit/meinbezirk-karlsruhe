# MeinBezirk Karlsruhe

**Kommunale Transparenz für Bürger:innen** — Was der Gemeinderat entscheidet, was Sie betrifft.

MeinBezirk Karlsruhe bereitet Gemeinderatsbeschlüsse verständlich auf und filtert sie nach dem, was für verschiedene Lebenslagen relevant ist: Eltern, Mieter:innen, Radfahrer:innen, Gewerbetreibende, Senior:innen.

> Inspiriert von [MeinBezirk Berlin](https://igorschwarzmann.com/meinbezirk/) von Igor Schwarzmann.

## Features

- Filtert Beschlüsse nach **Lebenslage**, **Stadtteil** und **Anlass**
- Verständliche Zusammenfassungen statt PDF-Amtsdeutsch
- Quellenangaben zu Gemeinderatssitzungen und Ausschüssen
- Responsives Design für Mobile und Desktop

## Lokale Entwicklung

Das Projekt besteht aus einer einzelnen HTML-Datei ohne Build-Prozess:

```bash
# Repository klonen
git clone https://github.com/manuelkoecher-bit/meinbezirk-karlsruhe.git
cd meinbezirk-karlsruhe

# Im Browser öffnen
open index.html
# oder mit einem lokalen Server:
python3 -m http.server 8000
```

## Datenquellen

Die Einträge basieren auf dem öffentlichen [Ratsinformationssystem der Stadt Karlsruhe](https://sitzungskalender.karlsruhe.de/db/ratsinformation/start).

## Status

Prototyp — Februar 2026. Die Daten sind exemplarisch und werden manuell gepflegt.

## Lizenz

MIT
