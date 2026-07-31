---
title: "BarCodeReader.readBarCodes"
linktitle: "readBarCodes"
articleTitle: "readBarCodes"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Reads BarCodeResult from the image."
type: docs
weight: 100
url: /nodejs/aspose.barcode/barcodereader/readbarcodes/
---

## readBarCodes()

Reads BarCodeResult from the image.

**Returns:** Returns array of recognized `BarCodeResult`s on the image. If nothing is recognized, zero array is returned.

**Example:**

```js
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
