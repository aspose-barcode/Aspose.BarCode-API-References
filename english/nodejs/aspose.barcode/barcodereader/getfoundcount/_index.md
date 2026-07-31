---
title: "BarCodeReader.getFoundCount"
linktitle: "getFoundCount"
articleTitle: "getFoundCount"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Gets recognized barcodes count"
type: docs
weight: 70
url: /nodejs/aspose.barcode/barcodereader/getfoundcount/
---

## getFoundCount()

Gets recognized barcodes count

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
Value: The recognized barcodes count
```
