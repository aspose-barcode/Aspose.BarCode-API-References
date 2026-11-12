---
title: "AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "AustraliaPost 解码参数。"
type: docs
weight: 30
url: /zh/nodejs/aspose.barcode/australiapostsettings/
---

## AustraliaPostSettings class

AustraliaPost 解码参数。包含影响 AustraliaPost 符号已识别数据的参数。

```js
new AustraliaPostSettings()
```

AustraliaPostSettings 构造函数

## 方法

| 名称 | 描述 |
| --- | --- |
| [getCustomerInformationInterpretingType()](#getcustomerinformationinterpretingtype) | 获取 AustralianPost BarCode 的客户信息解释类型。默认是 CustomerInformationInterpre |
| [getIgnoreEndingFillingPatternsForCTable()](#getignoreendingfillingpatternsforctable) | 在解码期间，强制 AustraliaPost 解码器忽略客户信息字段中最后填充模式的标志 |
| [setCustomerInformationInterpretingType(value)](#setcustomerinformationinterpretingtype) | 设置 AustralianPost BarCode 的客户信息解释类型。默认是 CustomerInformationInterpre |
| [setIgnoreEndingFillingPatternsForCTable()](#setignoreendingfillingpatternsforctable) | 在解码期间，强制 AustraliaPost 解码器忽略客户信息字段中最后填充模式的标志 |

### getCustomerInformationInterpretingType() {#getcustomerinformationinterpretingtype}

获取 AustralianPost BarCode 的客户信息解释类型。默认是 CustomerInformationInterpretingType.OTHER。

**Returns:** The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode

### getIgnoreEndingFillingPatternsForCTable() {#getignoreendingfillingpatternsforctable}

在解码期间，使用 CTable 方法时，强制 AustraliaPost 解码器忽略客户信息字段中最后填充模式的标志。CTable 编码方法在编码表中没有任何间隙，填充模式序列 "333" 被解码为字母 "z"。

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeType());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setCustomerInformationInterpretingType(value) {#setcustomerinformationinterpretingtype}

设置 AustralianPost BarCode 的客户信息解释类型。默认是 CustomerInformationInterpretingType.OTHER。

| 参数 | 描述 |
| --- | --- |
| 值 | AustralianPost BarCode 客户信息的解释类型（CTable、NTable 或 Other） |

### setIgnoreEndingFillingPatternsForCTable() {#setignoreendingfillingpatternsforctable}

在解码期间，使用 CTable 方法时，强制 AustraliaPost 解码器忽略客户信息字段中最后填充模式的标志。CTable 编码方法在编码表中没有任何间隙，填充模式序列 "333" 被解码为字母 "z"。

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeType());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```
