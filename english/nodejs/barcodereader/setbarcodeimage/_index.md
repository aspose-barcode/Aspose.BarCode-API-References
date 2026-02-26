---
title: BarCodeReader.setBarCodeImage
linktitle: setBarCodeImage
articleTitle: setBarCodeImage
second_title: Aspose.BarCode for Node.js via Java
description: Sets bitmap image and areas for recognition. Must be called before ReadBarCodes() method.
type: docs
weight: 190
url: /nodejs/barcodereader/setbarcodeimage/
---
## setBarCodeImage(object, object) {#setbarcodeimage}

Sets bitmap image and areas for recognition. Must be called before ReadBarCodes() method.

```javascript
setBarCodeImage(imageResource, ...areas)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageResource | object | The image for recognition. |
| ...areas | object |  |

## Examples

```javascript
//This sample shows how to detect Code39 and Code128 barcodes.
let bmp = "test.png";
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
var img = new Image();
img.src = 'path_to_image';
width = img.width;
height = img.height;
reader.setBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, width, height) });
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode Type: " + result.getCodeTypeName());
console.log("BarCode CodeText: " + result.getCodeText());
}
```

### See Also

* class [BarCodeReader](../)
* assembly [Aspose.BarCode](../../)

