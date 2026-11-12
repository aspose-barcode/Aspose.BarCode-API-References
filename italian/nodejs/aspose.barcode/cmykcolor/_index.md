---
title: "CMYKColor"
linktitle: "CMYKColor"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Classe per il colore CMYK."
type: docs
weight: 180
url: /it/nodejs/aspose.barcode/cmykcolor/
---

## CMYKColor class

Classe per il colore CMYK. Un'istanza null significa che il CMYK non è usato e il colore RGB predefinito è in uso.

```js
new CMYKColor(c, m, y, k)
```

Inizializza una nuova istanza della classe CMYKColor a partire dai valori CMYK. I valori CMYK sono attesi nell'intervallo 0–100.

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | numero | – Valore Cyan [0, 100] |
| m | numero | – Valore Magenta [0, 100] |
| y | numero | – Valore Giallo [0, 100] |
| k | numero | – Valore Nero [0, 100] |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [parseCMYK(str)](#parsecmyk) *(static)* | Analizza una stringa CMYK nel formato "C_M_Y_K" in un'istanza CMYKColor. |
| [formatCMYK()](#formatcmyk) | Formatta questo CMYKColor in una stringa "C_M_Y_K", moltiplicando ogni componente interno (0–1) per 100 e arrotondando. |
| [toString()](#tostring) | Opzionale: una rappresentazione leggibile dall'uomo. |

### parseCMYK(str) (static) {#parsecmyk}

Analizza una stringa CMYK nel formato "C_M_Y_K" in un'istanza CMYKColor.

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | string | – una stringa come "30_100_0_30" |

**Returns:** CMYKColor

### formatCMYK() {#formatcmyk}

Formatta questo CMYKColor in una stringa "C_M_Y_K", moltiplicando ogni componente interno (0–1) per 100 e arrotondando.

**Returns:** string — e.g. "30_100_0_30"

### toString() {#tostring}

Opzionale: una rappresentazione leggibile dall'uomo.
