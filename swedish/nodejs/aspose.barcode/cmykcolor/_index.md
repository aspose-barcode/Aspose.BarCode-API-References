---
title: "CMYKColor"
linktitle: "CMYKColor"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Klass för CMYK‑färg."
type: docs
weight: 180
url: /sv/nodejs/aspose.barcode/cmykcolor/
---

## CMYKColor class

Klass för CMYK-färg. En null-instans betyder att CMYK inte används och standard‑RGB‑färg är i bruk.

```js
new CMYKColor(c, m, y, k)
```

Initierar en ny instans av CMYKColor‑klassen från CMYK‑värden. CMYK‑värden förväntas ligga i intervallet 0–100.

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | nummer | – Cyanvärde [0, 100] |
| m | nummer | – Magentavärde [0, 100] |
| y | nummer | – Gulvärde [0, 100] |
| k | nummer | – Svartvärde [0, 100] |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [parseCMYK(str)](#parsecmyk) *(static)* | Parsa en CMYK‑sträng på formen "C_M_Y_K" till en CMYKColor‑instans. |
| [formatCMYK()](#formatcmyk) | Formatera denna CMYKColor till en sträng "C_M_Y_K", multiplicera varje intern komponent (0–1) med 100 och avrunda. |
| [toString()](#tostring) | Valfri: en människoläsbar representation. |

### parseCMYK(str) (static) {#parsecmyk}

Parsa en CMYK‑sträng på formen "C_M_Y_K" till en CMYKColor‑instans.

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | string | – en sträng som "30_100_0_30" |

**Returns:** CMYKColor

### formatCMYK() {#formatcmyk}

Formatera denna CMYKColor till en sträng "C_M_Y_K", multiplicera varje intern komponent (0–1) med 100 och avrunda.

**Returns:** string — e.g. "30_100_0_30"

### toString() {#tostring}

Valfri: en människoläsbar representation.
