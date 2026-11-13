---
title: "DotCodeExtendedParameters"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Lagrar specialdata för igenkänd DotCode‑streckkod. Detta exempel visar hur man får DotCode‑råvärden"
type: docs
weight: 380
url: /sv/nodejs/aspose.barcode/dotcodeextendedparameters/
---

## DotCodeExtendedParameters class

Lagrar specialdata för igenkänd DotCode‑streckkod. Detta exempel visar hur man får DotCode‑råvärden

```js
new DotCodeExtendedParameters()
```

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
generator.save("test.png", BarCodeImageFormat.PNG);

let reader = new BarCodeReader("test.png", null, DecodeType.DOT_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    print("BarCode type: " + result.getCodeTypeName());
    print("BarCode codetext: " + result.getCodeText());
    print("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
    print("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
}
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals(obj)](#equals) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `DotCodeExtendedParameters`-värde. |
| [getDotCodeIsReaderInitialization()](#getdotcodeisreaderinitialization) ~~(deprecated)~~ | Indikerar om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | Hämtar ID för DotCode strukturerade append-läge streckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | Hämtar antalet streckkoder i DotCode strukturerade append-läge. Standardvärde är -1. Antalet måste vara ett värde mellan 1 och 35. Värde: |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Hämtar ID för DotCode strukturerade append-läge streckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | Hämtar antalet streckkoder i DotCode strukturerade append-läge. Standardvärde är -1. Antalet måste vara ett värde mellan 1 och 35. Värde: |
| [hashCode()](#hashcode) | Returnerar hashkoden för detta objekt. |
| [isReaderInitialization()](#isreaderinitialization) | Indikerar om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av detta `DotCodeExtendedParameters`. |

### equals(obj) {#equals}

Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `DotCodeExtendedParameters`-värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | Ett System.Object-värde att jämföra med detta objekt. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDotCodeIsReaderInitialization() {#getdotcodeisreaderinitialization}

> **Deprecated.** See method description for replacement.

Indikerar om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. Standardvärde är false.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

Hämtar ID för DotCode strukturerade append-läge streckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärde är -1. Värde: ID för DotCode strukturerade append-läge streckkod.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

Hämtar antalet streckkoder i DotCode strukturerade append-läge. Standardvärde är -1. Antalet måste vara ett värde mellan 1 och 35. Värde: Antalet streckkoder i DotCode strukturerade append-läge.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Hämtar ID för DotCode strukturerade append-läge streckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärde är -1. Värde: ID för DotCode strukturerade append-läge streckkod.

**Returns:** the ID of the DotCode structured append mode barcode.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

Hämtar antalet streckkoder i DotCode strukturerade append-läge. Standardvärde är -1. Antalet måste vara ett värde mellan 1 och 35. Värde: Antalet streckkoder i DotCode strukturerade append-läge.

**Returns:** the DotCode structured append mode barcodes count.

### hashCode() {#hashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Indikerar om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. Standardvärde är false.

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av detta `DotCodeExtendedParameters`.

**Returns:** A string that represents this `DotCodeExtendedParameters`.
