---
title: "AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Arkiverar speciella data för Aztec‑igenkänd streckkod. Detta exempel visar hur man får Aztec‑råvärden let generator = new BarcodeGenerator(EncodeTypes.AZTEC, \"12345\"); "
type: docs
weight: 60
url: /sv/nodejs/aspose.barcode/aztecextendedparameters/
---

## AztecExtendedParameters class

Arkiverar speciella data för Aztec‑igenkänd streckkod. Detta exempel visar hur man får Aztec‑råvärden let generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345"); generator.save("test.png", BarcodeImageFormat.PNG);

```js
new AztecExtendedParameters()
```

**Example:**

```js
BarCodeReader reader = new BarCodeReader("test.png", null, DecodeType.AZTEC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode type: " + result.getCodeTypeName());
    console.log("BarCode codetext: " + result.getCodeText());
    console.log("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
    console.log("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
    console.log("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
    console.log("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
}
</pre>
</pre></blockquote></hr></p>
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals(obj)](#equals) | Returnerar ett värde som indikerar om detta objekt är lika med ett angivet `AztecExtendedParameters`‑värde. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Hämtar ID för Aztec strukturerade tilläggsläge‑streckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. D |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Hämtar antalet streckkoder för Aztec strukturerade tilläggsläge. Standardvärde är 0. Antalet måste vara ett värde mellan 1 och 26. Värde: The |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Hämtar fil‑ID för Aztec strukturerade tilläggsläge. Standardvärde är en tom sträng. Värde: The File ID of the Aztec stru |
| [hashCode()](#hashcode) | Returnerar hashkoden för detta objekt. |
| [isReaderInitialization()](#isreaderinitialization) | Indikerar om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av detta `AztecExtendedParameters`. |

### equals(obj) {#equals}

Returnerar ett värde som indikerar om detta objekt är lika med ett angivet `AztecExtendedParameters`‑värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | Ett System.Object-värde att jämföra med detta objekt. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Hämtar ID för Aztec strukturerade tilläggsläge‑streckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärde är 0. Värde: The barcode ID of the Aztec structured append mode.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Hämtar antalet streckkoder för Aztec strukturerade tilläggsläge. Standardvärde är 0. Antalet måste vara ett värde mellan 1 och 26. Värde: The barcodes count of the Aztec structured append mode.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Hämtar fil‑ID för Aztec strukturerade tilläggsläge. Standardvärde är en tom sträng. Värde: The File ID of the Aztec structured append mode.

### hashCode() {#hashcode}

Returnerar hashkoden för detta objekt.

**Returns:** 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Indikerar om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. Standardvärde är false.

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av detta `AztecExtendedParameters`.

**Returns:** A string that represents this `AztecExtendedParameters`.
