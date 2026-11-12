---
title: "MaxiCodeSecondMessage"
linktitle: "MaxiCodeSecondMessage"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于对模式 4、5 和 6 的 MaxiCode 编码文本进行编码和解码的类。"
type: docs
weight: 660
url: /zh/nodejs/aspose.barcode/maxicodesecondmessage/
---

## MaxiCodeSecondMessage class

用于对模式 4、5 和 6 的 MaxiCode 编码文本进行编码和解码的类。

```js
new MaxiCodeSecondMessage()
```

**Example:**

```js
//Mode 4
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```
