---
title: "HIBCLICPrimaryDataCodetext"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于对嵌入 HIBC LIC 代码中、存储主数据的文本进行编码和解码的类。"
type: docs
weight: 460
url: /zh/nodejs/aspose.barcode/hibclicprimarydatacodetext/
---

## HIBCLICPrimaryDataCodetext class

用于对嵌入 HIBC LIC 代码中、存储主数据的文本进行编码和解码的类。此示例展示了如何使用 HIBCLICPrimaryCodetext 对 HIBC LIC 进行编码和解码。

```js
new HIBCLICPrimaryDataCodetext()
```

**Example:**

```js
let complexCodetext  = new HIBCLICPrimaryCodetext();
complexCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
complexCodetext.setData(new PrimaryData());
complexCodetext.getData().setProductOrCatalogNumber("12345");
complexCodetext.getData().setLabelerIdentificationCode("A999");
complexCodetext.getData().setUnitOfMeasureID(1);
let generator = new ComplexBarcodeGenerator(complexCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getData().getUnitOfMeasureID());
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals(obj)](#equals) | 返回一个值，指示此实例是否等于指定的 `HIBCLICPrimaryDataCodetext` 值。 |
| [getConstructedCodetext()](#getconstructedcodetext) | 构造 codetext |
| [getData()](#getdata) | 标识主数据。 |
| [hashCode()](#hashcode) | 返回此实例的哈希码。 |
| [initFromString(constructedCodetext)](#initfromstring) | 从构造的 codetext 初始化实例。 |
| [setData()](#setdata) | 标识主数据。 |

### equals(obj) {#equals}

返回一个值，指示此实例是否等于指定的 `HIBCLICPrimaryDataCodetext` 值。

| 参数 | 描述 |
| --- | --- |
| obj | 用于与此实例比较的 `HIBCLICPrimaryDataCodetext` 值。 |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

构造 codetext

**Returns:** Constructed codetext

### getData() {#getdata}

标识主数据。

### hashCode() {#hashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

从构造的 codetext 初始化实例。

| 参数 | 描述 |
| --- | --- |
| constructedCodetext | 已构造的 codetext。 |

### setData() {#setdata}

标识主数据。
