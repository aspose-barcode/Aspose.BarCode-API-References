---
title: "DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于 DataMatrixEncodeMode 的扩展代码文本模式的 2D DataMatrix 条形码生成器 //扩展代码文本模式 //创建代码文本 let textBuil"
type: docs
weight: 340
url: /zh/nodejs/aspose.barcode/datamatrixextcodetextbuilder/
---

## DataMatrixExtCodetextBuilder class

用于 DataMatrixEncodeMode 的扩展代码文本模式的 2D DataMatrix 条形码扩展代码文本生成器 //扩展代码文本模式 //创建代码文本 let textBuilder = new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.BYTES, "World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF_8, "犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C_40, "ABCDE"); //generate codetext let codetext = textBuilder.getExtendedCodetext(); //generate let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null, codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.BMP);

```js
new DataMatrixExtCodetextBuilder()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [addCodetextWithEncodeMode(encodeMode, codetext)](#addcodetextwithencodemode) | 向扩展代码文本项添加具有指定编码模式的代码文本 |
| [addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext)](#addecicodetextwithencodemode) | 使用扩展通道标识符和指定编码模式添加代码文本 |
| [getExtendedCodetext()](#getextendedcodetext) | 从扩展码文本列表生成扩展码文本。 |

### addCodetextWithEncodeMode(encodeMode, codetext) {#addcodetextwithencodemode}

向扩展代码文本项添加具有指定编码模式的代码文本

| 参数 | 描述 |
| --- | --- |
| encodeMode | 编码模式值 |
| codetext | 以 Unicode 形式的代码文本，用于添加为扩展代码文本项 |

### addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext) {#addecicodetextwithencodemode}

使用扩展通道标识符和指定编码模式添加代码文本

| 参数 | 描述 |
| --- | --- |
| ECIEncoding | 扩展通道标识符 |
| encodeMode | 编码模式值 |
| codetext | 以 Unicode 形式的代码文本，使用扩展通道标识符和指定编码模式添加为扩展代码文本项 |

### getExtendedCodetext() {#getextendedcodetext}

从扩展码文本列表生成扩展码文本。

**Returns:** Extended codetext as string
