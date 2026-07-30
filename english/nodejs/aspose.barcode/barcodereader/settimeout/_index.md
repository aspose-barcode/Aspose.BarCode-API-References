---
title: "BarCodeReader.setTimeout"
linktitle: "setTimeout"
articleTitle: "setTimeout"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Sets the timeout of recognition process in milliseconds."
type: docs
weight: 140
url: /nodejs/aspose.barcode/barcodereader/settimeout/
---

## setTimeout(value)

Sets the timeout of recognition process in milliseconds.

| Parameter | Description |
| --- | --- |
| value | The timeout. |

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```
