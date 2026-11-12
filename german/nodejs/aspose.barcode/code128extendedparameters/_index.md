---
title: "Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Speichert spezielle Daten des erkannten Code128-Barcodes. Stellt die Region des erkannten Barcodes und den Barcode-Winkel dar."
type: docs
weight: 240
url: /de/nodejs/aspose.barcode/code128extendedparameters/
---

## Code128ExtendedParameters class

Speichert spezielle Daten des erkannten Code128-Barcodes. Stellt die Region des erkannten Barcodes und den Barcode-Winkel dar.

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

| Name | Beschreibung |
| --- | --- |
| [equals(obj)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Code128ExtendedParameters-Wert entspricht. |
| [getCode128DataPortions()](#getcode128dataportions) | Liest das Code128DataPortion‑Array des erkannten Code128‑Strichcodes. Wert des Code128DataPortion. |
| [hashCode()](#hashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [toString()](#tostring) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses Code128ExtendedParameters zurück. |

### equals(obj) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Code128ExtendedParameters-Wert entspricht.

| Parameter | Beschreibung |
| --- | --- |
| obj | Ein System.Object-Wert zum Vergleich mit dieser Instanz. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCode128DataPortions() {#getcode128dataportions}

Liest das Code128DataPortion‑Array des erkannten Code128‑Strichcodes. Wert des Code128DataPortion.

### hashCode() {#hashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses Code128ExtendedParameters zurück.

**Returns:** A string that represents this Code128ExtendedParameters.
