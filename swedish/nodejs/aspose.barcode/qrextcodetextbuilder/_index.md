---
title: "QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Utökad kodtextgenerator för 2D QR-streckkoder för ExtendedCodetext-läge i QREncodeMode Använd egenskapen Display2DText i BarCodeBuilder för att sätta synlig text till rem"
type: docs
weight: 820
url: /sv/nodejs/aspose.barcode/qrextcodetextbuilder/
---

## QrExtCodetextBuilder class

Utökad kodtextgenerator för 2D QR-streckkoder för ExtendedCodetext Mode av QREncodeMode. Använd Display2DText‑egenskapen i BarCodeBuilder för att ange synlig text genom att ta bort hanterande tecken.

```js
new QrExtCodetextBuilder()
```

**Example:**

```js
//Example how to generate FNC1 first position for Extended Mode
 //create codetext
 const lTextBuilder = new QrExtCodetextBuilder();
 lTextBuilder.addFNC1FirstPosition();
 lTextBuilder.addPlainCodetext("000%89%%0");
 lTextBuilder.addFNC1GroupSeparator();
 lTextBuilder.addPlainCodetext("12345&lt;FNC1&gt;");
 //generate codetext
 const lCodetext = lTextBuilder.getExtendedCodetext();
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addCodetextWithCompactionMode(mode, codetext)](#addcodetextwithcompactionmode) | Lägger till kodtext med det angivna QR‑komprimeringsläget till de utökade kodtextobjekten. |
| [addFNC1FirstPosition()](#addfnc1firstposition) | Lägger till FNC1 i första positionen till de utökade kodtextobjekten |
| [addFNC1GroupSeparator()](#addfnc1groupseparator) | Lägger till grupseparator (GS - '\\u001D') till de utökade kodtextobjekten |
| [addFNC1SecondPosition(codetext)](#addfnc1secondposition) | Lägger till FNC1 i andra positionen till de utökade kodtextobjekten |
| [clear()](#clear) | Rensar utökade kodtextobjekt |
| [getExtendedCodetext()](#getextendedcodetext) | Genererar utökad kodtext från den utökade kodtextlistan. |

### addCodetextWithCompactionMode(mode, codetext) {#addcodetextwithcompactionmode}

Lägger till kodtext med det angivna QR‑komprimeringsläget till de utökade kodtextobjekten.

| Parameter | Beskrivning |
| --- | --- |
| läge | QR‑komprimeringsläge för kodtexten. |
| codetext | Kodtext i Unicode att lägga till som ett utökat kodtextobjekt. |

**Throws:** IllegalArgumentException The specified codetext cannot be encoded in the selected QR compaction mode.

### addFNC1FirstPosition() {#addfnc1firstposition}

Lägger till FNC1 i första positionen till de utökade kodtextobjekten

### addFNC1GroupSeparator() {#addfnc1groupseparator}

Lägger till grupseparator (GS - '\\u001D') till de utökade kodtextobjekten

### addFNC1SecondPosition(codetext) {#addfnc1secondposition}

Lägger till FNC1 i andra positionen till de utökade kodtextobjekten

| Parameter | Beskrivning |
| --- | --- |
| codetext | Värde för FNC1 i andra positionen |

### clear() {#clear}

Rensar utökade kodtextobjekt

### getExtendedCodetext() {#getextendedcodetext}

Genererar utökad kodtext från den utökade kodtextlistan.

**Returns:** Extended codetext as string
