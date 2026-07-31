---
title: "BarcodeSettings.setStripFNC"
linktitle: "setStripFNC"
articleTitle: "setStripFNC"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false."
type: docs
weight: 90
url: /nodejs/aspose.barcode/barcodesettings/setstripfnc/
---

## setStripFNC(value)

Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false.

| Parameter | Description |
| --- | --- |
| value | Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```
