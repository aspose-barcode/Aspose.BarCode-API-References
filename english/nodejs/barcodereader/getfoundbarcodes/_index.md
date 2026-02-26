---
title: BarCodeReader.getFoundBarCodes
linktitle: getFoundBarCodes
articleTitle: getFoundBarCodes
second_title: Aspose.BarCode for Node.js via Java
description: "Gets recognized BarCodeResult array."
type: docs
weight: 130
url: /nodejs/barcodereader/getfoundbarcodes/
---
## getFoundBarCodes() {#getfoundbarcodes}

Gets recognized BarCodeResult array

```javascript
getFoundBarCodes()
```

### Return Value

recognized

BarCodeResult array

## Examples

```javascript
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
console.log("BarCode CodeText: " +  reader.getFoundBarCodes()[i].getCodeText());
```

### See Also

* class [BarCodeReader](../)
* assembly [Aspose.BarCode](../../)

