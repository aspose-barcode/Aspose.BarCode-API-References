---
title: BarCodeResult Class
linktitle: BarCodeResult
articleTitle: BarCodeResult
second_title: Aspose.BarCode for Node.js via Java
description: "Stores recognized barcode data like SingleDecodeType type, string codetext, BarCodeRegionParameters region and other parameters."
type: docs
weight: 1320
url: /nodejs/barcoderesult/
---
## BarCodeResult class

Stores recognized barcode data like SingleDecodeType type, `string` codetext, BarCodeRegionParameters region and other parameters

```javascript
public class BarCodeResult : joint.BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [BarCodeResult](./barcoderesult/#constructor)(*object*) | Initializes a new instance of the BarCodeResult class. |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](./deepclone/) | Creates a copy of BarCodeResult class. |
| [equals](./equals/)(*object*) | Returns a value indicating whether this instance is equal to a specified BarCodeResult value. |
| [getCodeBytes](./getcodebytes/) | Gets the encoded code bytes Value: The code bytes of the barcode. |
| [getCodeText](./getcodetext/)(*object*) | Gets the code text with encoding. |
| [getCodeType](./getcodetype/) | Gets the barcode type Value: The type information of the recognized barcode. |
| [getCodeTypeName](./getcodetypename/) | Gets the name of the barcode type Value: The type name of the recognized barcode. |
| [getConfidence](./getconfidence/) | Gets recognition confidence level of the recognized barcode Value: BarCodeConfidence.Strong does not have fakes or misrecognitions, BarCodeConfidence.Moderate could sometimes have fakes or incorrect codetext because this confidence level for barcodews with weak cheksum or even without it... |
| [getExtended](./getextended/) | Gets extended parameters of recognized barcode Value: The extended parameters of recognized barcode. |
| [getReadingQuality](./getreadingquality/) | Gets the reading quality. Works for 1D and postal barcodes. Value: The reading quality percent. |
| [getRegion](./getregion/) | Gets the barcode region Value: The region of the recognized barcode. |
| [hashCode](./hashcode/) | Returns the hash code for this instance. |
| [init](./init/) |  |
| [toString](./tostring/) | Returns a human-readable string representation of this BarCodeResult. |

## Fields

| Name | Description |
| --- | --- |
| [extended](./extended/) |  |
| [region](./region/) |  |

## Examples

```javascript
//This sample shows how to obtain BarCodeResult.
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode Type: " + result.getCodeTypeName());
console.log("BarCode CodeText: " + result.getCodeText());
console.log("BarCode Confidence: " + result.getConfidence());
console.log("BarCode ReadingQuality: " + result.getReadingQuality());
console.log("BarCode Angle: " + result.getRegion().getAngle());
}
```

### See Also

* assembly [Aspose.BarCode](../)

