---
title: "BarCodeRegionParameters"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Represents the recognized barcode's region and barcode angle"
type: docs
weight: 100
url: /nodejs/aspose.barcode/barcoderegionparameters/
---

## BarCodeRegionParameters class

Represents the recognized barcode's region and barcode angle

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

## Methods

| Name | Description |
| --- | --- |
| [equals(obj)](#equals) | Returns a value indicating whether this instance is equal to a specified BarCodeRegionParameters value. |
| [getAngle()](#getangle) | Gets the angle of the barcode (0-360). Value: The angle for barcode (0-360). |
| [getPoints()](#getpoints) | Gets Points array bounding barcode region Value: Returns Points array bounding barcode region |
| [getQuadrangle()](#getquadrangle) | Gets Quadrangle bounding barcode region Value: Returns Quadrangle bounding barcode region |
| [getRectangle()](#getrectangle) | Gets Rectangle bounding barcode region Value: Returns Rectangle bounding barcode region |
| [hashCode()](#hashcode) | Returns the hash code for this instance. |
| [toString()](#tostring) | Returns a human-readable string representation of this BarCodeRegionParameters. |

### equals(obj) {#equals}

Returns a value indicating whether this instance is equal to a specified BarCodeRegionParameters value.

| Parameter | Description |
| --- | --- |
| obj | An System.Object value to compare to this instance. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getAngle() {#getangle}

Gets the angle of the barcode (0-360). Value: The angle for barcode (0-360).

### getPoints() {#getpoints}

Gets Points array bounding barcode region Value: Returns Points array bounding barcode region

### getQuadrangle() {#getquadrangle}

Gets Quadrangle bounding barcode region Value: Returns Quadrangle bounding barcode region

### getRectangle() {#getrectangle}

Gets Rectangle bounding barcode region Value: Returns Rectangle bounding barcode region

### hashCode() {#hashcode}

Returns the hash code for this instance.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Returns a human-readable string representation of this BarCodeRegionParameters.

**Returns:** A string that represents this BarCodeRegionParameters.
