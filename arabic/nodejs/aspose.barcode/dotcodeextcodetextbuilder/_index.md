---
title: "DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "مولد النص المشفر الموسع لباركود DotCode ثنائي الأبعاد لوضعية ExtendedCodetext في DotCodeEncodeMode"
type: docs
weight: 370
url: /ar/nodejs/aspose.barcode/dotcodeextcodetextbuilder/
---

## DotCodeExtCodetextBuilder class

مولد النص المشفر الموسع لباركود DotCode ثنائي الأبعاد لوضعية ExtendedCodetext في DotCodeEncodeMode

```js
new DotCodeExtCodetextBuilder()
```

**Example:**

```js
//Extended codetext mode
//create codetext
let textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");
textBuilder.addFNC3SymbolSeparator();
textBuilder.addFNC3ReaderInitialization();
textBuilder.addPlainCodetext("Reader initialization info");
//generate codetext
let codetext = textBuilder.getExtendedCodetext();
//generate
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
generator.save("test.bmp", BarCodeImageFormat.BMP);
```

## طرق

| اسم | الوصف |
| --- | --- |
| [addFNC1FormatIdentifier()](#addfnc1formatidentifier) | يضيف معرف تنسيق FNC1 إلى عناصر النص المشفر الموسعة. |
| [addFNC3ReaderInitialization()](#addfnc3readerinitialization) | يضيف تهيئة قارئ FNC3 إلى عناصر النص المشفر الموسعة. |
| [addFNC3SymbolSeparator()](#addfnc3symbolseparator) | يضيف فاصل رمز FNC3 إلى عناصر النص المشفر الموسعة. |
| [addStructuredAppendMode(barcodeId, barcodesCount)](#addstructuredappendmode) | يضيف وضع الإلحاق الهيكلي إلى عناصر النص المشفر الموسعة. |
| [getExtendedCodetext()](#getextendedcodetext) | ينشئ النص المشفر الموسع من قائمة النص المشفر الموسع. |

### addFNC1FormatIdentifier() {#addfnc1formatidentifier}

يضيف معرف تنسيق FNC1 إلى عناصر النص المشفر الموسعة.

### addFNC3ReaderInitialization() {#addfnc3readerinitialization}

يضيف تهيئة قارئ FNC3 إلى عناصر النص المشفر الموسعة.

### addFNC3SymbolSeparator() {#addfnc3symbolseparator}

يضيف فاصل رمز FNC3 إلى عناصر النص المشفر الموسعة.

### addStructuredAppendMode(barcodeId, barcodesCount) {#addstructuredappendmode}

يضيف وضع الإلحاق الهيكلي إلى عناصر النص المشفر الموسعة.

| معامل | الوصف |
| --- | --- |
| barcodeId | معرف الباركود. |
| barcodesCount | عدد الباركودات |

### getExtendedCodetext() {#getextendedcodetext}

ينشئ النص المشفر الموسع من قائمة النص المشفر الموسع.

**Returns:** Extended codetext as string
