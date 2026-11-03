# Community Treffen – 19.11.2026

![Plakat Community Treffen](plakat.png)

KI-generiertes Einladungsplakat für das Community-Treffen der EEG Grünes Licht am 19.11.2026 im Weingut Herzog, Bad Vöslau.

Das Bild wurde lokal auf einem MacBook Pro erzeugt, ohne Cloud-Dienst. Die reine Rechenzeit lag bei rund 6½ Minuten.

## Dateien

| Datei | Inhalt |
|---|---|
| `prompt.txt` | Prompt, wie er in Draw Things eingegeben wurde |
| `config.json` | Vollständige Generierungs-Einstellungen aus Draw Things |
| `original.png` | Unbearbeitete Ausgabe von Draw Things, mit eingebetteten Metadaten (Prompt, Seed, Modell) |
| `plakat.png` | Verwendete Fassung mit einer Nachbearbeitung, siehe unten |
| `plakat.jpg` | Dieselbe Fassung als JPG, kleinere Datei zum Weitergeben |

## Einstellungen

| Parameter | Wert |
|---|---|
| Software | Draw Things (macOS) |
| Modell | FLUX.2 [dev], 8-bit (`flux_2_dev_q8p.ckpt`) |
| Modus | Text to Image (leere Leinwand, kein Referenzbild, kein Moodboard) |
| Größe | 1024 × 1024 |
| Steps | 28 |
| Text Guidance | 4,5 |
| Sampler | DDIM Trailing |
| Seed | 1877456384 |
| Seed Mode | Scale Alike |
| Shift | 3,158 (auflösungsabhängig) |
| LoRA | keine |
| Negative Prompt | leer |

## Reproduzieren

1. Draw Things für macOS installieren (Mac App Store).
2. In Draw Things das Modell **FLUX.2 [dev]** in der 8-bit-Variante herunterladen.
3. Eine leere Leinwand öffnen und den Modus **Text to Image** wählen.
4. Die Werte aus der Tabelle oben in den Einstellungen setzen. `config.json` enthält zusätzlich alle übrigen Parameter in Draw Things' eigenem Format.
5. Den Inhalt von `prompt.txt` ins Prompt-Feld kopieren.
6. Generieren.

Mit demselben Modell, Seed und denselben Einstellungen entsteht `original.png`. Bei anderen Draw-Things- oder Modellversionen sind kleine Abweichungen möglich.

## Nachbearbeitung

Das Modell hat das „ß“ in „SOOß“ nicht sauber gezeichnet. In `plakat.png` und `plakat.jpg` wurde nur dieses eine Zeichen durch ein gesetztes ß ersetzt (Schrift: Roboto Condensed). In `plakat.png` sind alle anderen Pixel identisch mit `original.png`; `plakat.jpg` ist daraus komprimiert.
