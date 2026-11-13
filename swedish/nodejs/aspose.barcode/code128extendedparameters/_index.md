---
title: "Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Lagrar specialdata för igenkänd Code128‑streckkod. Representerar den igenkända streckkodens region och vinkel."
type: docs
weight: 240
url: /sv/nodejs/aspose.barcode/code128extendedparameters/
---

## Code128ExtendedParameters class

Lagrar specialdata för igenkänd Code128‑streckkod. Representerar den igenkända streckkodens region och vinkel.

```js
new Code128ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get code128 raw values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.CODE_128);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("Code128 Data Portions: " + result.getExtended().getCode128());
}
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals(obj)](#equals) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat Code128ExtendedParameters-värde. |
| [getCode128DataPortions()](#getcode128dataportions) | Hämtar Code128DataPortion-array av igenkända Code128-streckkodsdata. Värde för Code128DataPortion. |
| [hashCode()](#hashcode) | Returnerar hashkoden för detta objekt. |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av detta Code128ExtendedParameters. |

### equals(obj) {#equals}

Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat Code128ExtendedParameters-värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | Ett System.Object-värde att jämföra med detta objekt. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCode128DataPortions() {#getcode128dataportions}

Hämtar Code128DataPortion-array av igenkända Code128-streckkodsdata. Värde för Code128DataPortion.

### hashCode() {#hashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av detta Code128ExtendedParameters.

**Returns:** A string that represents this Code128ExtendedParameters.
