---
title: "MaxiCodeCodetextMode2"
linktitle: "MaxiCodeCodetextMode2"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于对嵌入 MaxiCode 代码中模式 2 的文本进行编码和解码的类。"
type: docs
weight: 610
url: /zh/nodejs/aspose.barcode/maxicodecodetextmode2/
---

## MaxiCodeCodetextMode2 class

用于对嵌入 MaxiCode 代码中模式 2 的文本进行编码和解码的类。

```js
new MaxiCodeCodetextMode2()
```

**Example:**

```js
This sample shows how to encode and decode MaxiCode codetext for mode 2.
 //Mode 2 with standart second message
 let maxiCodeCodetext = new MaxiCodeCodetextMode2();
 maxiCodeCodetext.setPostalCode("524032140");
 maxiCodeCodetext.setCountryCode(056);
 maxiCodeCodetext.setServiceCategory(999);
 let MaxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
 MaxiCodeStandardSecondMessage.setMessage("Test message");
 maxiCodeCodetext.setSecondMessage(MaxiCodeStandardSecondMessage);
 let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
 complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getMode()](#getmode) | 获取 MaxiCode 模式。 |

### getMode() {#getmode}

获取 MaxiCode 模式。

**Returns:** MaxiCode mode
