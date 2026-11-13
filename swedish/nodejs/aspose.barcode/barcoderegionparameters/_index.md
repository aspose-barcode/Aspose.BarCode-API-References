---
title: "BarCodeRegionParameters"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Representerar den igenkända streckkodens region och streckkodsvinkel"
type: docs
weight: 100
url: /sv/nodejs/aspose.barcode/barcoderegionparameters/
---

## BarCodeRegionParameters class

Representerar den igenkända streckkodens region och streckkodsvinkel

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals(obj)](#equals) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat BarCodeRegionParameters‑värde. |
| [getAngle()](#getangle) | Hämtar vinkeln på streckkoden (0-360). Värde: Vinkeln för streckkoden (0-360). |
| [getPoints()](#getpoints) | Hämtar Points‑array som avgränsar streckkodsområdet Värde: Returnerar Points‑array som avgränsar streckkodsområdet |
| [getQuadrangle()](#getquadrangle) | Hämtar Quadrangle som avgränsar streckkodsområdet Värde: Returnerar Quadrangle som avgränsar streckkodsområdet |
| [getRectangle()](#getrectangle) | Hämtar Rectangle som avgränsar streckkodsområdet Värde: Returnerar Rectangle som avgränsar streckkodsområdet |
| [hashCode()](#hashcode) | Returnerar hashkoden för detta objekt. |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av detta BarCodeRegionParameters. |

### equals(obj) {#equals}

Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat BarCodeRegionParameters‑värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | Ett System.Object-värde att jämföra med detta objekt. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getAngle() {#getangle}

Hämtar vinkeln på streckkoden (0-360). Värde: Vinkeln för streckkoden (0-360).

### getPoints() {#getpoints}

Hämtar Points‑array som avgränsar streckkodsområdet Värde: Returnerar Points‑array som avgränsar streckkodsområdet

### getQuadrangle() {#getquadrangle}

Hämtar Quadrangle som avgränsar streckkodsområdet Värde: Returnerar Quadrangle som avgränsar streckkodsområdet

### getRectangle() {#getrectangle}

Hämtar Rectangle som avgränsar streckkodsområdet Värde: Returnerar Rectangle som avgränsar streckkodsområdet

### hashCode() {#hashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av detta BarCodeRegionParameters.

**Returns:** A string that represents this BarCodeRegionParameters.
