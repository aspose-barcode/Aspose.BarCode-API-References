---
title: "DataBarExtendedParameters"
linktitle: "DataBarExtendedParameters"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Lagrar extra information för DataBar för den igenkända streckkoden"
type: docs
weight: 310
url: /sv/nodejs/aspose.barcode/databarextendedparameters/
---

## DataBarExtendedParameters class

Lagrar extra information för DataBar för den igenkända streckkoden

```js
new DataBarExtendedParameters()
```

**Example:**

```js
let reader = new BarCodeReader("test.png", DecodeType.DATABAR_OMNI_DIRECTIONAL);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
}
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals(obj)](#equals) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat DataBarExtendedParameters-värde. |
| [hashCode()](#hashcode) | Returnerar hashkoden för detta objekt. |
| [is2DCompositeComponent()](#is2dcompositecomponent) | Hämtar flaggan för DataBar 2D-kompositkomponent. Standardvärdet är falskt. |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av detta. |

### equals(obj) {#equals}

Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat DataBarExtendedParameters-värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | DataBarExtendedParameters-värde att jämföra med detta objekt. |

**Returns:** true if obj has the same value as this instance; otherwise, false .

### hashCode() {#hashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code.

### is2DCompositeComponent() {#is2dcompositecomponent}

Hämtar flaggan för DataBar 2D-kompositkomponent. Standardvärdet är falskt.

**Returns:** The DataBar 2D composite component flag.

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av detta.

**Returns:** A string that represents this .
