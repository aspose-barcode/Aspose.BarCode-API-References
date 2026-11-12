---
title: "AztecExtCodetextBuilder"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于 AztecEncodeMode 的 ExtendedCodetext 模式的 Aztec 条码扩展码文本生成器，使用 BarcodeGenerator 的 TwoDDisplayText 属性设置可见文本"
type: docs
weight: 50
url: /zh/nodejs/aspose.barcode/aztecextcodetextbuilder/
---

## AztecExtCodetextBuilder class

用于 AztecEncodeMode 的 ExtendedCodetext 模式的 Aztec 条码扩展码文本生成器，使用 BarcodeGenerator 的 TwoDDisplayText 属性设置可见文本并移除管理字符。此示例展示了如何在扩展模式下使用 AztecExtCodetextBuilder。

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

## 方法

| 名称 | 描述 |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | 从扩展码文本列表生成扩展码文本。 |

### getExtendedCodetext() {#getextendedcodetext}

从扩展码文本列表生成扩展码文本。

**Returns:** Extended codetext as string
