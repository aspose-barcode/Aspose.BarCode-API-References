---
title: BarCodeReader.getFoundCount
linktitle: getFoundCount
articleTitle: getFoundCount
second_title: Aspose.BarCode for Node.js via Java
description: "Gets recognized barcodes count."
type: docs
weight: 140
url: /nodejs/barcodereader/getfoundcount/
---
## getFoundCount() {#getfoundcount}

Gets recognized barcodes count

```javascript
getFoundCount()
```

## Examples

```javascript
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
Value: The recognized barcodes count
```

### See Also

* class [BarCodeReader](../)
* assembly [Aspose.BarCode](../../)

