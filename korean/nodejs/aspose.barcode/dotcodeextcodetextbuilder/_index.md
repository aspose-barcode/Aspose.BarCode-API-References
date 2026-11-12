---
title: "DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "DotCodeEncodeMode의 ExtendedCodetext 모드를 위한 2D DotCode 바코드용 확장 코드텍스트 생성기"
type: docs
weight: 370
url: /ko/nodejs/aspose.barcode/dotcodeextcodetextbuilder/
---

## DotCodeExtCodetextBuilder class

DotCodeEncodeMode의 ExtendedCodetext 모드를 위한 2D DotCode 바코드용 확장 코드텍스트 생성기

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

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addFNC1FormatIdentifier()](#addfnc1formatidentifier) | 확장된 codetext 항목에 FNC1 형식 식별자를 추가합니다. |
| [addFNC3ReaderInitialization()](#addfnc3readerinitialization) | 확장된 codetext 항목에 FNC3 리더 초기화를 추가합니다. |
| [addFNC3SymbolSeparator()](#addfnc3symbolseparator) | 확장된 codetext 항목에 FNC3 심볼 구분자를 추가합니다. |
| [addStructuredAppendMode(barcodeId, barcodesCount)](#addstructuredappendmode) | 확장된 codetext 항목에 구조화된 추가 모드를 추가합니다. |
| [getExtendedCodetext()](#getextendedcodetext) | 확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다. |

### addFNC1FormatIdentifier() {#addfnc1formatidentifier}

확장된 codetext 항목에 FNC1 형식 식별자를 추가합니다.

### addFNC3ReaderInitialization() {#addfnc3readerinitialization}

확장된 codetext 항목에 FNC3 리더 초기화를 추가합니다.

### addFNC3SymbolSeparator() {#addfnc3symbolseparator}

확장된 codetext 항목에 FNC3 심볼 구분자를 추가합니다.

### addStructuredAppendMode(barcodeId, barcodesCount) {#addstructuredappendmode}

확장된 codetext 항목에 구조화된 추가 모드를 추가합니다.

| 매개변수 | 설명 |
| --- | --- |
| barcodeId | 바코드 ID |
| barcodesCount | 바코드 수 |

### getExtendedCodetext() {#getextendedcodetext}

확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다.

**Returns:** Extended codetext as string
