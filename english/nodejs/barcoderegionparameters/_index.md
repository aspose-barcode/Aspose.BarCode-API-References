---
title: BarCodeRegionParameters Class
linktitle: BarCodeRegionParameters
articleTitle: BarCodeRegionParameters
second_title: Aspose.BarCode for Node.js via Java
description: Represents the recognized barcode's region and barcode angle.
type: docs
weight: 1330
url: /nodejs/barcoderegionparameters/
---
## BarCodeRegionParameters class

Represents the recognized barcode's region and barcode angle

```javascript
public class BarCodeRegionParameters : joint.BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [BarCodeRegionParameters](./barcoderegionparameters/#constructor)(*object*) | Initializes a new instance of the BarCodeRegionParameters class. |

## Methods

| Name | Description |
| --- | --- |
| [convertJavaPoints](./convertjavapoints/)(*object*) |  |
| [equals](./equals/)(*object*) | Returns a value indicating whether this instance is equal to a specified BarCodeRegionParameters value. |
| [getAngle](./getangle/) | Gets the angle of the barcode (0-360). Value: The angle for barcode (0-360). |
| [getPoints](./getpoints/) | Gets Points array bounding barcode region Value: Returns Points array bounding barcode region. |
| [getQuadrangle](./getquadrangle/) | Gets Quadrangle bounding barcode region Value: Returns Quadrangle bounding barcode region. |
| [getRectangle](./getrectangle/) | Gets Rectangle bounding barcode region Value: Returns Rectangle bounding barcode region. |
| [hashCode](./hashcode/) | Returns the hash code for this instance. |
| [init](./init/) |  |
| [toString](./tostring/) | Returns a human-readable string representation of this BarCodeRegionParameters. |

## Fields

| Name | Description |
| --- | --- |
| [points](./points/) |  |
| [quad](./quad/) |  |
| [rect](./rect/) |  |

## Examples

```javascript
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

### See Also

* assembly [Aspose.BarCode](../)

