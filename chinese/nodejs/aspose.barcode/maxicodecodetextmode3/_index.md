---
title: "MaxiCodeCodetextMode3"
linktitle: "MaxiCodeCodetextMode3"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于对模式 3 中嵌入的 MaxiCode 代码文本进行编码和解码的类。"
type: docs
weight: 620
url: /zh/nodejs/aspose.barcode/maxicodecodetextmode3/
---

## MaxiCodeCodetextMode3 class

用于对嵌入在 MaxiCode 代码中的文本进行编码和解码的类，适用于模式 3。此示例展示了如何对模式 3 的 MaxiCode 编码文本进行编码和解码。

```js
new MaxiCodeCodetextMode3()
```

**Example:**

```js
//Mode 3 with standart second message
 let maxiCodeCodetext = new MaxiCodeCodetextMode3();
 maxiCodeCodetext.setPostalCode("B1050");
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
