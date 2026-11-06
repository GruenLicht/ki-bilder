# Equal Pay Day – 05.11.2026

![Cartoon Equal Pay Day](original.png)

KI-generierter satirischer Cartoon zum Equal Pay Day 2026 in Österreich.

Das Bild wurde lokal auf einem MacBook Pro erzeugt, ohne Cloud-Dienst. Die reine Rechenzeit lag bei rund 3¼ Minuten.

## Idee

Zwei gleiche Schreibtische, gleiche Laptops, gleiche Aktenberge. Beim Mann prasseln Münzen ins volle Glas, bei der Frau kommen nur noch Herzerl und „DANKE!“-Kärtchen aus dem Rohr. In ihrem Glas liegen unten Münzen, oben Dankeschön: Ab dem Equal Pay Day arbeiten Frauen rechnerisch für Dank statt Lohn. Die Schnecke mit der rot-weiß-roten Mappe „LOHNTRANSPARENZ“ steht für das österreichische Lohntransparenzgesetz, das noch fehlt.

## Fakten dahinter

- Der Equal Pay Day 2026 fiel in Österreich auf den 5. November. Ab diesem Tag arbeiten Frauen rechnerisch 57 Tage bis Jahresende „gratis“.
- Grundlage ist der Einkommensunterschied von 15,5 % zwischen ganzjährig vollzeitbeschäftigten Frauen und Männern (Bruttojahresbezüge, Lohnsteuerstatistik 2024 der Statistik Austria).
- Die EU-Lohntransparenzrichtlinie hätte bis 7. Juni 2026 in nationales Recht umgesetzt werden müssen. In Österreich ist das noch nicht geschehen.

## Dateien

| Datei | Inhalt |
|---|---|
| `prompt.txt` | Prompt, wie er in Draw Things eingegeben wurde |
| `config.json` | Vollständige Generierungs-Einstellungen aus Draw Things |
| `original.png` | Unbearbeitete Ausgabe von Draw Things, mit eingebetteten Metadaten (Prompt, Seed, Modell) |
| `bild.jpg` | Dasselbe Bild als JPG, kleinere Datei zum Weitergeben |

## Einstellungen

| Parameter | Wert |
|---|---|
| Software | Draw Things (macOS) |
| Modell | FLUX.2 [dev], 8-bit (`flux_2_dev_q8p.ckpt`) |
| Modus | Text to Image (leere Leinwand, kein Referenzbild, kein Moodboard) |
| Größe | 896 × 1152 |
| Steps | 28 |
| Text Guidance | 4,5 |
| Sampler | DDIM Trailing |
| Seed | 2935351773 |
| Seed Mode | Scale Alike |
| Shift | 3,124 (auflösungsabhängig) |
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

Keine. `bild.jpg` ist nur eine komprimierte Fassung von `original.png`.

## Energiebedarf (Abschätzung)

Die Rechenzeit für dieses Bild lag laut den eingebetteten Metadaten bei 197 Sekunden. Bei einer angenommenen Leistungsaufnahme des Laptops von 40 bis 100 Watt während der Berechnung sind das rund **2 bis 5½ Wattstunden**.

Bis zum fertigen Motiv waren acht Durchgänge nötig, zusammen etwa 35 Minuten Rechenzeit. Das ergibt insgesamt rund **25 bis 60 Wattstunden**, ungefähr so viel wie zwei bis vier volle Smartphone-Ladungen.

Die Werte sind geschätzt, nicht gemessen.
