---
title: "DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于 DotCodeEncodeMode 的 ExtendedCodetext 模式的 2D DotCode 条形码的扩展 codetext 生成器"
type: docs
weight: 370
url: /zh/nodejs/aspose.barcode/dotcodeextcodetextbuilder/
---

## DotCodeExtCodetextBuilder class

用于 DotCodeEncodeMode 的 ExtendedCodetext 模式的 2D DotCode 条形码的扩展 codetext 生成器

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

## 方法

| 名称 | 描述 |
| --- | --- |
| [addFNC1FormatIdentifier()](#addfnc1formatidentifier) | 向扩展的代码文本项添加 FNC1 格式标识符 |
| [addFNC3ReaderInitialization()](#addfnc3readerinitialization) | 向扩展的代码文本项添加 FNC3 读取器初始化 |
| [addFNC3SymbolSeparator()](#addfnc3symbolseparator) | 向扩展的代码文本项添加 FNC3 符号分隔符 |
| [addStructuredAppendMode(barcodeId, barcodesCount)](#addstructuredappendmode) | 向扩展的代码文本项添加结构化追加模式 |
| [getExtendedCodetext()](#getextendedcodetext) | 从扩展码文本列表生成扩展码文本。 |

### addFNC1FormatIdentifier() {#addfnc1formatidentifier}

向扩展的代码文本项添加 FNC1 格式标识符

### addFNC3ReaderInitialization() {#addfnc3readerinitialization}

向扩展的代码文本项添加 FNC3 读取器初始化

### addFNC3SymbolSeparator() {#addfnc3symbolseparator}

向扩展的代码文本项添加 FNC3 符号分隔符

### addStructuredAppendMode(barcodeId, barcodesCount) {#addstructuredappendmode}

向扩展的代码文本项添加结构化追加模式

| 参数 | 描述 |
| --- | --- |
| barcodeId | 条形码的 ID |
| barcodesCount | 条码计数 |

### getExtendedCodetext() {#getextendedcodetext}

从扩展码文本列表生成扩展码文本。

**Returns:** Extended codetext as string
