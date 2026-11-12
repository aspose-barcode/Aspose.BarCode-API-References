---
title: "DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "ExtendedCodetext मोड के DotCodeEncodeMode के लिए 2D DotCode बारकोड के लिए विस्तारित कोडटेक्स्ट जेनरेटर"
type: docs
weight: 370
url: /hi/nodejs/aspose.barcode/dotcodeextcodetextbuilder/
---

## DotCodeExtCodetextBuilder class

ExtendedCodetext मोड के DotCodeEncodeMode के लिए 2D DotCode बारकोड के लिए विस्तारित कोडटेक्स्ट जेनरेटर

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

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addFNC1FormatIdentifier()](#addfnc1formatidentifier) | विस्तारित codetext आइटम्स में FNC1 फ़ॉर्मेट पहचानकर्ता जोड़ता है |
| [addFNC3ReaderInitialization()](#addfnc3readerinitialization) | विस्तारित codetext आइटम्स में FNC3 रीडर प्रारंभिककरण जोड़ता है |
| [addFNC3SymbolSeparator()](#addfnc3symbolseparator) | विस्तारित codetext आइटम्स में FNC3 प्रतीक विभाजक जोड़ता है |
| [addStructuredAppendMode(barcodeId, barcodesCount)](#addstructuredappendmode) | विस्तारित codetext आइटम्स में संरचित जोड़ मोड जोड़ता है |
| [getExtendedCodetext()](#getextendedcodetext) | Extended codetext सूची से Extended codetext उत्पन्न करता है। |

### addFNC1FormatIdentifier() {#addfnc1formatidentifier}

विस्तारित codetext आइटम्स में FNC1 फ़ॉर्मेट पहचानकर्ता जोड़ता है

### addFNC3ReaderInitialization() {#addfnc3readerinitialization}

विस्तारित codetext आइटम्स में FNC3 रीडर प्रारंभिककरण जोड़ता है

### addFNC3SymbolSeparator() {#addfnc3symbolseparator}

विस्तारित codetext आइटम्स में FNC3 प्रतीक विभाजक जोड़ता है

### addStructuredAppendMode(barcodeId, barcodesCount) {#addstructuredappendmode}

विस्तारित codetext आइटम्स में संरचित जोड़ मोड जोड़ता है

| पैरामीटर | विवरण |
| --- | --- |
| barcodeId | बारकोड का ID |
| barcodesCount | बारकोड गिनती |

### getExtendedCodetext() {#getextendedcodetext}

Extended codetext सूची से Extended codetext उत्पन्न करता है।

**Returns:** Extended codetext as string
