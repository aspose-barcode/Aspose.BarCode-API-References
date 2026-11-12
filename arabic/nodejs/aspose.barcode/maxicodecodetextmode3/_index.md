---
title: "MaxiCodeCodetextMode3"
linktitle: "MaxiCodeCodetextMode3"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "فئة لتشفير وفك تشفير النص المضمن في رمز MaxiCode للأنماط 3."
type: docs
weight: 620
url: /ar/nodejs/aspose.barcode/maxicodecodetextmode3/
---

## MaxiCodeCodetextMode3 class

فئة لتشفير وفك تشفير النص المضمن في رمز MaxiCode للأوضاع 3. يوضح هذا المثال كيفية تشفير وفك تشفير نص MaxiCode للوضعيّة 3.

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

## طرق

| اسم | الوصف |
| --- | --- |
| [getMode()](#getmode) | يحصل على وضع MaxiCode. |

### getMode() {#getmode}

يحصل على وضع MaxiCode.

**Returns:** MaxiCode mode
