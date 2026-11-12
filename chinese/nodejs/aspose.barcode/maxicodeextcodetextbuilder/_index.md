---
title: "MaxiCodeExtCodetextBuilder"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于 MaxiCode 条形码的扩展文本生成器，适用于 MaxiCodeEncodeMode 的 ExtendedCodetext 模式。使用 BarcodeGenerator 的 TwoDDisplayText 属性设置可见"
type: docs
weight: 630
url: /zh/nodejs/aspose.barcode/maxicodeextcodetextbuilder/
---

## MaxiCodeExtCodetextBuilder class

用于 MaxiCode 条形码的扩展文本生成器，适用于 MaxiCodeEncodeMode 的 ExtendedCodetext 模式。使用 BarcodeGenerator 的 TwoDDisplayText 属性设置可见文本以删除管理字符。此示例展示了如何在扩展模式下使用 MaxiCodeExtCodetextBuilder。

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

## 方法

| 名称 | 描述 |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | 从扩展码文本列表生成扩展码文本。 |

### getExtendedCodetext() {#getextendedcodetext}

从扩展码文本列表生成扩展码文本。

**Returns:** Extended codetext as string
