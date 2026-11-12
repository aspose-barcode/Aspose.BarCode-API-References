---
title: "BarCodeRegionParameters"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Stellt die Region und den Winkel des erkannten Barcodes dar"
type: docs
weight: 100
url: /de/nodejs/aspose.barcode/barcoderegionparameters/
---

## BarCodeRegionParameters class

Stellt die Region und den Winkel des erkannten Barcodes dar

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

| Name | Beschreibung |
| --- | --- |
| [equals(obj)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen BarCodeRegionParameters-Wert entspricht. |
| [getAngle()](#getangle) | Liefert den Winkel des Barcodes (0-360). Wert: Der Winkel für den Barcode (0-360). |
| [getPoints()](#getpoints) | Liefert das Points-Array, das den Barcode-Bereich begrenzt. Wert: Gibt das Points-Array zurück, das den Barcode-Bereich begrenzt. |
| [getQuadrangle()](#getquadrangle) | Liefert das Quadrangle, das den Barcode-Bereich begrenzt. Wert: Gibt das Quadrangle zurück, das den Barcode-Bereich begrenzt. |
| [getRectangle()](#getrectangle) | Liefert das Rectangle, das den Barcode-Bereich begrenzt. Wert: Gibt das Rectangle zurück, das den Barcode-Bereich begrenzt. |
| [hashCode()](#hashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [toString()](#tostring) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieser BarCodeRegionParameters zurück. |

### equals(obj) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen BarCodeRegionParameters-Wert entspricht.

| Parameter | Beschreibung |
| --- | --- |
| obj | Ein System.Object-Wert zum Vergleich mit dieser Instanz. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getAngle() {#getangle}

Liefert den Winkel des Barcodes (0-360). Wert: Der Winkel für den Barcode (0-360).

### getPoints() {#getpoints}

Liefert das Points-Array, das den Barcode-Bereich begrenzt. Wert: Gibt das Points-Array zurück, das den Barcode-Bereich begrenzt.

### getQuadrangle() {#getquadrangle}

Liefert das Quadrangle, das den Barcode-Bereich begrenzt. Wert: Gibt das Quadrangle zurück, das den Barcode-Bereich begrenzt.

### getRectangle() {#getrectangle}

Liefert das Rectangle, das den Barcode-Bereich begrenzt. Wert: Gibt das Rectangle zurück, das den Barcode-Bereich begrenzt.

### hashCode() {#hashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Gibt eine menschenlesbare Zeichenkettenrepräsentation dieser BarCodeRegionParameters zurück.

**Returns:** A string that represents this BarCodeRegionParameters.
