# myTischtennis API Dokumentation

[![Dokumentation](https://img.shields.io/badge/📖_Dokumentation-online-green)](https://notmycupofteetee.github.io/mytt-api/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> ⚠️ **Inoffizielle Dokumentation** – Erstellt durch Community-Analyse

**📖 [Interaktive Dokumentation ansehen](https://notmycupofteetee.github.io/mytt-api/)**

## Worum geht es?

Diese OpenAPI-Spezifikation dokumentiert die API-Endpunkte von [myTischtennis.de](https://www.mytischtennis.de).

MyTischtennis.de stellt keine offizielle API-Dokumentation bereit – obwohl alle hier dokumentierten Endpunkte für alle mit einem Browser öffentlich sichtbar sind (Entwicklertools → Network Tab).

## Warum diese Dokumentation?

### 🔍 Transparenz statt "Security by Obscurity"

Die fehlende Dokumentation schützt niemanden:
- Alle Entwickler*innen können die Endpunkte im Browser sehen
- Die Daten sind bereits öffentlich zugänglich
- Eine Dokumentation macht es nur transparenter, nicht unsicherer

### 🚀 Innovation ermöglichen

Mit einer dokumentierten API könnten Vereine und Entwickler*innen:
- **Vereins-Apps** bauen (Spielplan, Ergebnisse, TTR-Tracking)
- **Widgets** für Vereinswebsites erstellen
- **Benachrichtigungen** für Spielergebnisse implementieren
- **Analysetools** für Trainer*innen entwickeln

### 💬 Diskussion anstoßen

Vielleicht lässt sich hiermit eine Diskussion über **Open Data im deutschen Tischtennissport** anstoßen:
- Warum gibt es keine offizielle API?
- Wie könnten Vereine von offenen Daten profitieren?
- Welche Daten sollten (nicht) öffentlich sein?

## Dokumentation ansehen

**👉 [https://notmycupofteetee.github.io/mytt-api/](https://notmycupofteetee.github.io/mytt-api/)**

Oder lokal starten:

```bash
npm install
npm run preview
```

## Endpunkt-Kategorien

| Kategorie | Beschreibung | Auth erforderlich? |
|-----------|--------------|-------------------|
| **Suche** | Personen- und Vereinssuche | ❌ Nein |
| **Spieler*innen & TTR** | TTR-Werte, Profile, Ranglisten | Teilweise |
| **Ligen & Gruppen** | Tabellen, Spielpläne, Bilanzen | ❌ Nein |
| **Mannschaften** | Mannschaftsinfos, Aufstellungen | ❌ Nein |
| **Vereine** | Vereinsdaten, Kontakte | ❌ Nein |
| **Begegnungen** | Live-Ticker, Spieldetails | ❌ Nein |

## Disclaimer

- ⚠️ **Inoffiziell:** Keine Verbindung zum DTTB oder myTischtennis.de
- ⚠️ **Nutzung auf eigene Verantwortung:** Bitte respektiere die [AGB](https://www.mytischtennis.de/agb)
- ⚠️ **Rate Limiting:** Die API hat ein Limit von ~90 Requests/Stunde

## Wie wurde diese Dokumentation erstellt?

1. Browser-Entwicklertools öffnen (F12)
2. Network Tab auswählen
3. myTischtennis.de normal nutzen
4. Die sichtbaren API-Requests analysieren und dokumentieren

Alles hier Dokumentierte ist im normalen Browserbetrieb sichtbar.

## Mitmachen

Fehler gefunden? Endpunkt fehlt? Pull Requests sind willkommen!

## Lizenz

MIT License – Die Dokumentation selbst ist frei nutzbar.  
Die Daten auf myTischtennis.de unterliegen den dortigen Nutzungsbedingungen.

