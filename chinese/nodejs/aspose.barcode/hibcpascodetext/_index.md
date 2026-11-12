---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于对嵌入 HIBC PAS 代码中的文本进行编码和解码的类。"
type: docs
weight: 480
url: /zh/nodejs/aspose.barcode/hibcpascodetext/
---

## HIBCPASCodetext class

用于对嵌入 HIBC PAS 代码中的文本进行编码和解码的类。

```js
new HIBCPASCodetext()
```

**Example:**

```js
This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.

 let complexCodetext = new HIBCPASComplexCodetext();
 complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
 complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
 complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
 complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
 let generator = new ComplexBarcodeGenerator(complexCodetext);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(BarCodeImageFormat.PNG), null, DecodeType.HIBC_DATA_MATRIX_PAS);
 reader.readBarCodes();
 let codetext = reader.getFoundBarCodes()[0].getCodeText();
	let readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
 print("Data location: " + readCodetext.getDataLocation());
 print("Data type: " + readCodetext.getRecords()[0].getDataType());
 print("Data: " + readCodetext.getRecords()[0].getData());
 print("Data type: " + readCodetext.getRecords()[1].getDataType());
 print("Data: " + readCodetext.getRecords()[1].getData());
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [_fromMwObject()](#-frommwobject) *(static)* | HIBCPASRecord 构造函数 |
| [addHIBCPASRecord(record)](#addhibcpasrecord) | 添加新记录 |
| [addRecord(dataType, data)](#addrecord) | 添加新记录 |
| [clear()](#clear) | 清除记录列表 |
| [equals(obj)](#equals) | 返回一个值，指示此实例是否等于指定的 `HIBCPASCodetext` 值。 |
| [getBarcodeType()](#getbarcodetype) | 获取条形码类型。 |
| [getConstructedCodetext()](#getconstructedcodetext) | 构造 codetext |
| [getDataLocation()](#getdatalocation) | 标识数据位置。 |
| [getRecords()](#getrecords) | 获取记录列表 |
| [hashCode()](#hashcode) | 返回此实例的哈希码。 |
| [initFromString(constructedCodetext)](#initfromstring) | 从构造的 codetext 初始化实例。 |
| [setBarcodeType()](#setbarcodetype) | 获取或设置条码类型。HIBC PAS 编码文本可以使用 HIBCCode39PAS、HIBCCode128PAS、HIBCAztec:PAS、HIBCData 进行编码。 |
| [setDataLocation()](#setdatalocation) | 标识数据位置。 |

### _fromMwObject() (static) {#-frommwobject}

HIBCPASRecord 构造函数

### addHIBCPASRecord(record) {#addhibcpasrecord}

添加新记录

| 参数 | 描述 |
| --- | --- |
| 记录 | 要添加的记录 |

### addRecord(dataType, data) {#addrecord}

添加新记录

| 参数 | 描述 |
| --- | --- |
| 数据类型 | 数据类型 |
| 数据 | 数据字符串 |

### clear() {#clear}

清除记录列表

### equals(obj) {#equals}

返回一个值，指示此实例是否等于指定的 `HIBCPASCodetext` 值。

| 参数 | 描述 |
| --- | --- |
| obj | 用于与此实例比较的 `HIBCPASCodetext` 值。 |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getBarcodeType() {#getbarcodetype}

获取条形码类型。

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

构造 codetext

**Returns:** Constructed codetext

### getDataLocation() {#getdatalocation}

标识数据位置。

### getRecords() {#getrecords}

获取记录列表

**Returns:** List of records

### hashCode() {#hashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

从构造的 codetext 初始化实例。

| 参数 | 描述 |
| --- | --- |
| constructedCodetext | 已构造的 codetext。 |

### setBarcodeType() {#setbarcodetype}

获取或设置条码类型。HIBC PAS 编码文本可以使用 HIBCCode39PAS、HIBCCode128PAS、HIBCAztec:PAS、HIBCDataMatrixPAS 和 HIBCQRPAS 编码类型进行编码。默认值：HIBCCode39PAS。

**Returns:** Barcode type.

### setDataLocation() {#setdatalocation}

标识数据位置。
