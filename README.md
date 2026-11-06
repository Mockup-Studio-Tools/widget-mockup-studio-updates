# Widget-Mockup Studio – Versionsinfo

Diese Datei liest der Update-Hinweis der Erweiterung. Hier steht nur die aktuelle Versionsnummer, kein Code.

## version.json

| Feld | Pflicht | Bedeutung |
|---|---|---|
| `version` | ja | Neueste Version, Format `1.2.3` |
| `minVersion` | nein | Ältere installierte Versionen sehen einen roten Hinweis, der sich nicht ausblenden lässt |
| `date` | nein | Datum, Format `JJJJ-MM-TT` |
| `notes` | nein | Bis zu 10 Änderungstexte, je max. 200 Zeichen, nur reiner Text |

Andere Felder ignoriert die Erweiterung. Der Download-Link ist fest in der Erweiterung hinterlegt.

## Reihenfolge bei einem neuen Release

1. Code-Repo: Version im Manifest erhöhen, committen, pushen.
2. Release mit ZIP im Code-Repo anlegen.
3. Erst danach hier `version.json` aktualisieren.

Keine Kundennamen oder internen Adressen in die Änderungstexte – dieses Repo ist öffentlich.
