---
title: "OneDExtendedParameters"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Lagrar speciella data för 1D‑igenkänd streckkod, såsom separat kodtext och kontrollsumma"
type: docs
weight: 720
url: /sv/nodejs/aspose.barcode/onedextendedparameters/
---

## OneDExtendedParameters class

Lagrar speciella data för 1D‑igenkänd streckkod, såsom separat kodtext och kontrollsumma

```js
new OneDExtendedParameters()
```

**Example:**

```js
//This sample shows how to get 1D barcode value and checksum
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.EAN_13);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Value: " + result.getExtended().getOneD().getValue());
   console.log("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals(obj)](#equals) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat OneDExtendedParameters‑värde. |
| [getCheckSum()](#getchecksum) | Hämtar kontrollsumman för 1D‑streckkoder. Värde: Kontrollsumman för 1D‑streckkod. |
| [getValue()](#getvalue) | Hämtar kodtexten för 1D‑streckkoder utan kontrollsumma. Värde: Kodtexten för 1D‑streckkoder utan kontrollsumma. |
| [hashCode()](#hashcode) | Returnerar hashkoden för detta objekt. |
| [isEmpty()](#isempty) | Testar om alla parametrar endast har standardvärden. Värde: Returnerar `true ` om alla parametrar endast har standardvärden; o |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av detta OneDExtendedParameters. |

### equals(obj) {#equals}

Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat OneDExtendedParameters‑värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | Ett System.Object-värde att jämföra med detta objekt. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCheckSum() {#getchecksum}

Hämtar kontrollsumman för 1D‑streckkoder. Värde: Kontrollsumman för 1D‑streckkod.

### getValue() {#getvalue}

Hämtar kodtexten för 1D‑streckkoder utan kontrollsumma. Värde: Kodtexten för 1D‑streckkoder utan kontrollsumma.

### hashCode() {#hashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Testar om alla parametrar endast har standardvärden. Värde: Returnerar `true ` om alla parametrar endast har standardvärden; annars, `false `.

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av detta OneDExtendedParameters.

**Returns:** A string that represents this OneDExtendedParameters.
