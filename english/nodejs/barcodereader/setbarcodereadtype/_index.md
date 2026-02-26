---
title: BarCodeReader.setBarCodeReadType
linktitle: setBarCodeReadType
articleTitle: setBarCodeReadType
second_title: Aspose.BarCode for Node.js via Java
description: "Sets SingleDecodeType type array for recognition. Must be called before readBarCodes() method."
type: docs
weight: 200
url: /nodejs/barcodereader/setbarcodereadtype/
---
## setBarCodeReadType(object) {#setbarcodereadtype}

Sets SingleDecodeType type array for recognition. Must be called before readBarCodes() method.

```javascript
setBarCodeReadType(...types)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ...types | object |  |

## Examples

```javascript
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.setBarCodeImage("test.png");
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

