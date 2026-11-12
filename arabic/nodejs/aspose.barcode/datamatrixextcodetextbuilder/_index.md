---
title: "DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "مولد codetext الموسع لباركودات DataMatrix ثنائية الأبعاد لوضع ExtendedCodetext في DataMatrixEncodeMode //وضع codetext الموسع //إنشاء codetext let textBuil"
type: docs
weight: 340
url: /ar/nodejs/aspose.barcode/datamatrixextcodetextbuilder/
---

## DataMatrixExtCodetextBuilder class

مولد codetext الموسع لباركودات DataMatrix ثنائية الأبعاد لوضع ExtendedCodetext في DataMatrixEncodeMode //وضع codetext الموسع //إنشاء codetext let textBuilder = new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.BYTES, "World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF_8, "犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C_40, "ABCDE"); //generate codetext let codetext = textBuilder.getExtendedCodetext(); //generate let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null, codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.BMP);

```js
new DataMatrixExtCodetextBuilder()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [addCodetextWithEncodeMode(encodeMode, codetext)](#addcodetextwithencodemode) | يضيف codetext مع وضع الترميز المحدد إلى عناصر codetext الموسعة |
| [addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext)](#addecicodetextwithencodemode) | يضيف codetext مع معرف القناة الموسعة مع وضع الترميز المحدد |
| [getExtendedCodetext()](#getextendedcodetext) | ينشئ النص المشفر الموسع من قائمة النص المشفر الموسع. |

### addCodetextWithEncodeMode(encodeMode, codetext) {#addcodetextwithencodemode}

يضيف codetext مع وضع الترميز المحدد إلى عناصر codetext الموسعة

| معامل | الوصف |
| --- | --- |
| encodeMode | قيمة وضع الترميز |
| codetext | codetext بترميز Unicode لإضافته كعنصر codetext موسع |

### addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext) {#addecicodetextwithencodemode}

يضيف codetext مع معرف القناة الموسعة مع وضع الترميز المحدد

| معامل | الوصف |
| --- | --- |
| ECIEncoding | معرف القناة الموسعة |
| encodeMode | قيمة وضع الترميز |
| codetext | codetext بترميز Unicode لإضافته كعنصر codetext موسع مع معرف القناة الموسعة مع وضع الترميز المحدد |

### getExtendedCodetext() {#getextendedcodetext}

ينشئ النص المشفر الموسع من قائمة النص المشفر الموسع.

**Returns:** Extended codetext as string
