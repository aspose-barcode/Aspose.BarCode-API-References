---
title: "AztecExtCodetextBuilder"
linktitle: "AztecExtCodetextBuilder"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "مولد النص المشفر الموسع لباركودات Aztec لوضعية ExtendedCodetext في AztecEncodeMode. استخدم خاصية TwoDDisplayText في BarcodeGenerator لتعيين النص المرئي."
type: docs
weight: 50
url: /ar/nodejs/aspose.barcode/aztecextcodetextbuilder/
---

## AztecExtCodetextBuilder class

مولد النص المشفر الموسع لباركودات Aztec لوضعية ExtendedCodetext في AztecEncodeMode. استخدم خاصية TwoDDisplayText في BarcodeGenerator لتعيين النص المرئي وإزالة الأحرف الإدارية. يوضح هذا المثال كيفية استخدام AztecExtCodetextBuilder في الوضع الموسع.

```js
new AztecExtCodetextBuilder()
```

**Example:**

```js
//create codetext
     let textBuilder = new AztecExtCodetextBuilder();
     textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
     textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
     textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
     textBuilder.addPlainCodetext("Plain text");
     //generate codetext
     let codetext = textBuilder.getExtendedCodetext();
     //generate
     let generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
     generator.getParameters().getBarcode().getCodeTextParameters().setwoDDisplayText("My Text");
     generator.save("test.bmp", BarcodeImageFormat.BMP);
```

## طرق

| اسم | الوصف |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | ينشئ النص المشفر الموسع من قائمة النص المشفر الموسع. |

### getExtendedCodetext() {#getextendedcodetext}

ينشئ النص المشفر الموسع من قائمة النص المشفر الموسع.

**Returns:** Extended codetext as string
