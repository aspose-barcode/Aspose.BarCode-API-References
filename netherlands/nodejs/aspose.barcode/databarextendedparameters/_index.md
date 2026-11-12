---
title: "Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Slaat extra informatie van DataBar van herkende barcode op"
type: docs
weight: 310
url: /nl/nodejs/aspose.barcode/databarextendedparameters/
---

## DataBarExtendedParameters class

Slaat extra informatie van DataBar van herkende barcode op

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

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [equals(obj)](#equals) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven DataBarExtendedParameters‑waarde. |
| [hashCode()](#hashcode) | Retourneert de hashcode voor deze instantie. |
| [is2DCompositeComponent()](#is2dcompositecomponent) | Haalt de DataBar 2D‑composite‑component‑vlag op. Standaardwaarde is false. |
| [toString()](#tostring) | Retourneert een menselijk leesbare tekenreeksrepresentatie van dit . |

### equals(obj) {#equals}

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven DataBarExtendedParameters‑waarde.

| Parameter | Beschrijving |
| --- | --- |
| obj | DataBarExtendedParameters‑waarde om te vergelijken met deze instantie. |

**Returns:** true if obj has the same value as this instance; otherwise, false .

### hashCode() {#hashcode}

Retourneert de hashcode voor deze instantie.

**Returns:** A 32-bit signed integer hash code.

### is2DCompositeComponent() {#is2dcompositecomponent}

Haalt de DataBar 2D‑composite‑component‑vlag op. Standaardwaarde is false.

**Returns:** The DataBar 2D composite component flag.

### toString() {#tostring}

Retourneert een menselijk leesbare tekenreeksrepresentatie van dit .

**Returns:** A string that represents this .
