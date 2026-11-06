# KI-Bilder der EEG Grünes Licht

Hier liegen die Prompts und Einstellungen zu allen KI-generierten Bildern, die die Erneuerbare-Energie-Gemeinschaft Grünes Licht (Bad Vöslau / Flugfeld / Sooß) verwendet.

## Warum

- **Offenlegung:** Wir kennzeichnen KI-generierte Bilder und zeigen, wie sie entstanden sind.
- **Souveränität:** Die Bilder entstehen lokal auf einem eigenen Rechner mit einem offenen Modell. Es gibt keine Cloud-Dienste, keine Konten, und keine Daten verlassen den Rechner.
- **Energiesparsamkeit:** Ein Bild braucht einige Minuten Rechenzeit auf einem Laptop statt einer Anfrage an ein Rechenzentrum.
- **Nachvollziehbarkeit:** Mit Prompt, Seed und Einstellungen lässt sich jedes Bild mit [Draw Things](https://drawthings.ai) selbst erzeugen.

## Bilder

| Datum | Bild | Modell |
|---|---|---|
| 05.11.2026 | [Equal Pay Day](2026-11-05_equal-pay-day/) | FLUX.2 [dev] |
| 19.11.2026 | [Community Treffen](2026-11-19_community-treffen/) | FLUX.2 [dev] |

## Aufbau

Jedes Bild hat einen eigenen Ordner `JJJJ-MM-TT_kurzname/` mit:

- `README.md`: Beschreibung, Einstellungen, Anleitung zum Reproduzieren
- `prompt.txt`: der Prompt
- `config.json`: vollständige Draw-Things-Einstellungen
- `original.png`: unbearbeitete Ausgabe mit eingebetteten Metadaten
- `plakat.png` (oder ähnlich): verwendete Fassung, falls nachbearbeitet
- `plakat.jpg`: dieselbe Fassung als kleinere JPG-Datei
