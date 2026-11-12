---
title: "MaxiCodeCodetextMode2"
linktitle: "MaxiCodeCodetextMode2"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "فئة لتشفير وفك تشفير النص المضمن في رمز MaxiCode للأوضاع 2."
type: docs
weight: 610
url: /ar/nodejs/aspose.barcode/maxicodecodetextmode2/
---

## MaxiCodeCodetextMode2 class

فئة لتشفير وفك تشفير النص المضمن في رمز MaxiCode للأوضاع 2.

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

## طرق

| اسم | الوصف |
| --- | --- |
| [getMode()](#getmode) | يحصل على وضع MaxiCode. |

### getMode() {#getmode}

يحصل على وضع MaxiCode.

**Returns:** MaxiCode mode
