---
title: "CMYKColor"
linktitle: "CMYKColor"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Klasse voor CMYK-kleur."
type: docs
weight: 180
url: /nl/nodejs/aspose.barcode/cmykcolor/
---

## CMYKColor class

Klasse voor CMYK-kleur. Een null‑instantie betekent dat CMYK niet wordt gebruikt, en de standaard RGB‑kleur wordt toegepast.

```js
new CMYKColor(c, m, y, k)
```

Initialiseert een nieuw exemplaar van de CMYKColor-klasse vanuit CMYK-waarden. CMYK-waarden worden verwacht in het bereik 0–100.

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| c | nummer | – Cyaanwaarde [0, 100] |
| m | nummer | – Magentawaarde [0, 100] |
| y | nummer | – Geelwaarde [0, 100] |
| k | nummer | – Zwartwaarde [0, 100] |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [parseCMYK(str)](#parsecmyk) *(static)* | Ontleed een CMYK-tekenreeks van de vorm \"C_M_Y_K\" naar een CMYKColor-exemplaar. |
| [formatCMYK()](#formatcmyk) | Formateer deze CMYKColor naar een tekenreeks \"C_M_Y_K\", waarbij elk intern component (0–1) met 100 wordt vermenigvuldigd en afgerond. |
| [toString()](#tostring) | Optioneel: een menselijk leesbare weergave. |

### parseCMYK(str) (static) {#parsecmyk}

Ontleed een CMYK-tekenreeks van de vorm \"C_M_Y_K\" naar een CMYKColor-exemplaar.

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | string | – een tekenreeks zoals \"30_100_0_30\" |

**Returns:** CMYKColor

### formatCMYK() {#formatcmyk}

Formateer deze CMYKColor naar een tekenreeks \"C_M_Y_K\", waarbij elk intern component (0–1) met 100 wordt vermenigvuldigd en afgerond.

**Returns:** string — e.g. "30_100_0_30"

### toString() {#tostring}

Optioneel: een menselijk leesbare weergave.
