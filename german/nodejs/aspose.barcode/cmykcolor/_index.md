---
title: "CMYKColor"
linktitle: "CMYKColor"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Klasse für CMYK-Farbe."
type: docs
weight: 180
url: /de/nodejs/aspose.barcode/cmykcolor/
---

## CMYKColor class

Klasse für CMYK-Farbe. Eine Null-Instanz bedeutet, dass CMYK nicht verwendet wird und die Standard-RGB-Farbe verwendet wird.

```js
new CMYKColor(c, m, y, k)
```

Initialisiert eine neue Instanz der CMYKColor-Klasse aus CMYK-Werten. CMYK-Werte werden im Bereich 0–100 erwartet.

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | Zahl | – Cyan-Wert [0, 100] |
| m | Zahl | – Magenta-Wert [0, 100] |
| y | Zahl | – Gelb-Wert [0, 100] |
| k | Zahl | – Schwarz-Wert [0, 100] |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [parseCMYK(str)](#parsecmyk) *(static)* | Parsen Sie einen CMYK-String der Form "C_M_Y_K" in eine CMYKColor-Instanz. |
| [formatCMYK()](#formatcmyk) | Formatieren Sie diese CMYKColor in einen String "C_M_Y_K", indem Sie jede interne Komponente (0–1) mit 100 multiplizieren und runden. |
| [toString()](#tostring) | Optional: eine menschenlesbare Darstellung. |

### parseCMYK(str) (static) {#parsecmyk}

Parsen Sie einen CMYK-String der Form "C_M_Y_K" in eine CMYKColor-Instanz.

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | Zeichenkette | – ein String wie "30_100_0_30" |

**Returns:** CMYKColor

### formatCMYK() {#formatcmyk}

Formatieren Sie diese CMYKColor in einen String "C_M_Y_K", indem Sie jede interne Komponente (0–1) mit 100 multiplizieren und runden.

**Returns:** string — e.g. "30_100_0_30"

### toString() {#tostring}

Optional: eine menschenlesbare Darstellung.
