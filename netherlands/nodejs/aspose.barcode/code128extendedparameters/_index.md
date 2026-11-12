---
title: "Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Slaat speciale gegevens van herkende Code128-barcode op. Vertegenwoordigt de regio van de herkende barcode en de barcode‑hoek."
type: docs
weight: 240
url: /nl/nodejs/aspose.barcode/code128extendedparameters/
---

## Code128ExtendedParameters class

Slaat speciale gegevens van herkende Code128-barcode op. Vertegenwoordigt de regio van de herkende barcode en de barcode‑hoek.

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

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [equals(obj)](#equals) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven Code128ExtendedParameters‑waarde. |
| [getCode128DataPortions()](#getcode128dataportions) | Haalt de Code128DataPortion‑array op van herkende Code128‑barcode. Waarde van de Code128DataPortion. |
| [hashCode()](#hashcode) | Retourneert de hashcode voor deze instantie. |
| [toString()](#tostring) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze Code128ExtendedParameters. |

### equals(obj) {#equals}

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven Code128ExtendedParameters‑waarde.

| Parameter | Beschrijving |
| --- | --- |
| obj | Een System.Object-waarde om te vergelijken met deze instantie. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCode128DataPortions() {#getcode128dataportions}

Haalt de Code128DataPortion‑array op van herkende Code128‑barcode. Waarde van de Code128DataPortion.

### hashCode() {#hashcode}

Retourneert de hashcode voor deze instantie.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Retourneert een menselijk leesbare tekenreeksrepresentatie van deze Code128ExtendedParameters.

**Returns:** A string that represents this Code128ExtendedParameters.
