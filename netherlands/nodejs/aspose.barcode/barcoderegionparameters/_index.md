---
title: "BarCodeRegionParameters"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Stelt de regio en hoek van de herkende barcode voor"
type: docs
weight: 100
url: /nl/nodejs/aspose.barcode/barcoderegionparameters/
---

## BarCodeRegionParameters class

Stelt de regio en hoek van de herkende barcode voor

```js
new BarCodeRegionParameters()
```

**Example:**

```js
//This sample shows how to get barcode Angle and bounding quadrangle values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Angle: " + result.getRegion().getAngle());
   console.log("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
}
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [equals(obj)](#equals) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven BarCodeRegionParameters-waarde. |
| [getAngle()](#getangle) | Haalt de hoek van de barcode op (0-360). Waarde: De hoek voor de barcode (0-360). |
| [getPoints()](#getpoints) | Haalt Points-array op die de barcode-regio begrenst Waarde: Retourneert Points-array die de barcode-regio begrenst |
| [getQuadrangle()](#getquadrangle) | Haalt Quadrangle op die de barcode-regio begrenst Waarde: Retourneert Quadrangle die de barcode-regio begrenst |
| [getRectangle()](#getrectangle) | Haalt Rectangle op die de barcode-regio begrenst Waarde: Retourneert Rectangle die de barcode-regio begrenst |
| [hashCode()](#hashcode) | Retourneert de hashcode voor deze instantie. |
| [toString()](#tostring) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze BarCodeRegionParameters. |

### equals(obj) {#equals}

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven BarCodeRegionParameters-waarde.

| Parameter | Beschrijving |
| --- | --- |
| obj | Een System.Object-waarde om te vergelijken met deze instantie. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getAngle() {#getangle}

Haalt de hoek van de barcode op (0-360). Waarde: De hoek voor de barcode (0-360).

### getPoints() {#getpoints}

Haalt Points-array op die de barcode-regio begrenst Waarde: Retourneert Points-array die de barcode-regio begrenst

### getQuadrangle() {#getquadrangle}

Haalt Quadrangle op die de barcode-regio begrenst Waarde: Retourneert Quadrangle die de barcode-regio begrenst

### getRectangle() {#getrectangle}

Haalt Rectangle op die de barcode-regio begrenst Waarde: Retourneert Rectangle die de barcode-regio begrenst

### hashCode() {#hashcode}

Retourneert de hashcode voor deze instantie.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Retourneert een menselijk leesbare tekenreeksrepresentatie van deze BarCodeRegionParameters.

**Returns:** A string that represents this BarCodeRegionParameters.
