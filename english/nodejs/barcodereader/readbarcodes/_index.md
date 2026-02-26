---
title: "BarCodeReader.readBarCodes"
linktitle: "readBarCodes"
articleTitle: "readBarCodes"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Reads BarCodeResult from the image."
type: docs
weight: 150
url: /nodejs/barcodereader/readbarcodes/
---
## readBarCodes() {#readbarcodes}

Reads BarCodeResult from the image.

```javascript
readBarCodes()
```

### Return Value

Returns

array of recognized {

## Examples

```javascript
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode CodeText: " + result.getCodeText());
}
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
```

### See Also

* class [BarCodeReader](../)
* assembly [Aspose.BarCode](../../)

