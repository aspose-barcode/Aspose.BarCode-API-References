---
title: "HIBCLICCombinedCodetext"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于对嵌入 HIBC LIC 代码中、存储主数据和次要数据的文本进行编码和解码的类。"
type: docs
weight: 440
url: /zh/nodejs/aspose.barcode/hibcliccombinedcodetext/
---

## HIBCLICCombinedCodetext class

用于对嵌入 HIBC LIC 代码中、存储主数据和次要数据的文本进行编码和解码的类。此示例展示了如何使用 HIBCLICCombinedCodetext 对 HIBC LIC 进行编码和解码。

```js
new HIBCLICCombinedCodetext()
```

**Example:**

```js
let combinedCodetext = new HIBCLICCombinedCodetext();
combinedCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
combinedCodetext.setPrimaryData(new PrimaryData());
combinedCodetext.getPrimaryData().setProductOrCatalogNumber("12345");
combinedCodetext.getPrimaryData().setLabelerIdentificationCode("A999");
combinedCodetext.getPrimaryData().setUnitOfMeasureID(1);
combinedCodetext.setSecondaryAndAdditionalData(new SecondaryAndAdditionalData());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDate(new Date());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDateFormat(HIBCLICDateFormat.MMDDYY);
combinedCodetext.getSecondaryAndAdditionalData().setQuantity(30);
combinedCodetext.getSecondaryAndAdditionalData().setLotNumber("LOT123");
combinedCodetext.getSecondaryAndAdditionalData().setSerialNumber("SERIAL123");
combinedCodetext.getSecondaryAndAdditionalData().setDateOfManufacture(new Date());
ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getPrimaryData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getPrimaryData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getPrimaryData().getUnitOfMeasureID());
print("Expiry date: " + result.getSecondaryAndAdditionalData().getExpiryDate());
print("Quantity: " + result.getSecondaryAndAdditionalData().getQuantity());
print("Lot number: " + result.getSecondaryAndAdditionalData().getLotNumber());
print("Serial number: " + result.getSecondaryAndAdditionalData().getSerialNumber());
print("Date of manufacture: " + result.getSecondaryAndAdditionalData().getDateOfManufacture());
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals(obj)](#equals) | 返回一个值，指示此实例是否等于指定的 `HIBCLICCombinedCodetext` 值。 |
| [getConstructedCodetext()](#getconstructedcodetext) | 构造 codetext |
| [getPrimaryData()](#getprimarydata) | 标识主数据。 |
| [getSecondaryAndAdditionalData()](#getsecondaryandadditionaldata) | 标识次要数据和其他补充数据。 |
| [hashCode()](#hashcode) | 返回此实例的哈希码。 |
| [initFromString(constructedCodetext)](#initfromstring) | 从构造的 codetext 初始化实例。 |
| [setPrimaryData()](#setprimarydata) | 标识主数据。 |
| [setSecondaryAndAdditionalData()](#setsecondaryandadditionaldata) | 标识次要数据和其他补充数据。 |

### equals(obj) {#equals}

返回一个值，指示此实例是否等于指定的 `HIBCLICCombinedCodetext` 值。

| 参数 | 描述 |
| --- | --- |
| obj | 用于与此实例比较的 `HIBCLICCombinedCodetext` 值。 |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

构造 codetext

**Returns:** Constructed codetext

### getPrimaryData() {#getprimarydata}

标识主数据。

### getSecondaryAndAdditionalData() {#getsecondaryandadditionaldata}

标识次要数据和其他补充数据。

### hashCode() {#hashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

从构造的 codetext 初始化实例。

| 参数 | 描述 |
| --- | --- |
| constructedCodetext | 已构造的 codetext。 |

### setPrimaryData() {#setprimarydata}

标识主数据。

### setSecondaryAndAdditionalData() {#setsecondaryandadditionaldata}

标识次要数据和其他补充数据。
