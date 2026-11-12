---
title: "MaxiCodeExtCodetextBuilder"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "مولد نص مشفر موسع لباركودات MaxiCode لوضع ExtendedCodetext في MaxiCodeEncodeMode. استخدم خاصية TwoDDisplayText في BarcodeGenerator لتعيين visibl"
type: docs
weight: 630
url: /ar/nodejs/aspose.barcode/maxicodeextcodetextbuilder/
---

## MaxiCodeExtCodetextBuilder class

مولد نص الترميز الموسع لباركودات MaxiCode لوضعية ExtendedCodetext في MaxiCodeEncodeMode استخدم خاصية TwoDDisplayText من BarcodeGenerator لتعيين النص الظاهر وإزالة الأحرف الإدارية. يوضح هذا المثال كيفية استخدام MaxiCodeExtCodetextBuilder في الوضعية الموسعة.

```js
new MaxiCodeExtCodetextBuilder()
```

**Example:**

```js
//create codetext
let textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");

//generate codetext
let codetext = textBuilder.getExtendedCodetext();

//generate
let generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
generator.save("test.bmp", BarcodeImageFormat.BMP);
```

## طرق

| اسم | الوصف |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | ينشئ النص المشفر الموسع من قائمة النص المشفر الموسع. |

### getExtendedCodetext() {#getextendedcodetext}

ينشئ النص المشفر الموسع من قائمة النص المشفر الموسع.

**Returns:** Extended codetext as string
