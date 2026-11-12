---
title: "QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "存储已识别条形码的 QR 结构化追加信息"
type: docs
weight: 810
url: /zh/nodejs/aspose.barcode/qrextendedparameters/
---

## QRExtendedParameters class

存储已识别条形码的 QR 结构化追加信息

```js
new QRExtendedParameters()
```

**Example:**

```js
//This sample shows how to get QR Structured Append data

let reader = new BarCodeReader("test.png", null,  DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
   console.log("QR Structured Append Index: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodeIndex());
   console.log("QR Structured Append ParityData: " + result.getExtended().getQR().getQRStructuredAppendModeParityData());
}
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals(obj)](#equals) | 返回一个值，指示此实例是否等于指定的 QRExtendedParameters 值。 |
| [getErrorLevel()](#geterrorlevel) | 已识别条码的 Reed-Solomon 错误纠正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。 |
| [getMicroQRVersion()](#getmicroqrversion) | 已识别 MicroQR 码的版本。从 M1 到 M4。 |
| [getQRErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | 已识别条码的 Reed-Solomon 错误纠正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。 |
| [getQRStructuredAppendModeBarCodeIndex()](#getqrstructuredappendmodebarcodeindex) ~~(deprecated)~~ | 获取 QR 结构追加模式条码的索引。索引从 0 开始。默认值为 -1。值：数量 |
| [getQRStructuredAppendModeBarCodesQuantity()](#getqrstructuredappendmodebarcodesquantity) ~~(deprecated)~~ | 获取 QR 结构追加模式条码的数量。默认值为 -1。值：QR 结构追加模式的数量 |
| [getQRStructuredAppendModeParityData()](#getqrstructuredappendmodeparitydata) ~~(deprecated)~~ | 获取 QR 结构追加模式的奇偶校验数据。默认值为 -1。值：QR 结构追加模式的索引 |
| [getQRVersion()](#getqrversion) ~~(deprecated)~~ | 已识别 QR 码的版本。从 Version1 到 Version40。 |
| [getRectMicroQRVersion()](#getrectmicroqrversion) | 已识别 RectMicroQR 码的版本。从 R7x43 到 R17x139。 |
| [getStructuredAppendModeBarCodeIndex()](#getstructuredappendmodebarcodeindex) | 获取 QR 结构追加模式条码的索引。索引从 0 开始。默认值为 -1。值：数量 |
| [getStructuredAppendModeBarCodesQuantity()](#getstructuredappendmodebarcodesquantity) | 获取 QR 结构追加模式条码的数量。默认值为 -1。值：QR 结构追加模式的数量 |
| [getStructuredAppendModeParityData()](#getstructuredappendmodeparitydata) | 获取 QR 结构追加模式的奇偶校验数据。默认值为 -1。值：QR 结构追加模式的索引 |
| [getVersion()](#getversion) | 已识别 QR 码的版本。从 Version1 到 Version40。 |
| [hashCode()](#hashcode) | 返回此实例的哈希码。 |
| [isEmpty()](#isempty) | 测试所有参数是否仅具有默认值。值 |
| [toString()](#tostring) | 返回此 QRExtendedParameters 的人类可读字符串表示。 |

### equals(obj) {#equals}

返回一个值，指示此实例是否等于指定的 QRExtendedParameters 值。

| 参数 | 描述 |
| --- | --- |
| obj | 用于与此实例比较的对象值。 |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getErrorLevel() {#geterrorlevel}

已识别条码的 Reed-Solomon 错误纠正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。

### getMicroQRVersion() {#getmicroqrversion}

已识别 MicroQR 码的版本。从 M1 到 M4。

**Returns:** Version of recognized MicroQR Code. From M1 to M4.

### getQRErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

已识别条码的 Reed-Solomon 错误纠正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。

**Returns:** Reed-Solomon error correction level of recognized barcode.

### getQRStructuredAppendModeBarCodeIndex() {#getqrstructuredappendmodebarcodeindex}

> **Deprecated.** See method description for replacement.

获取 QR 结构追加模式条码的索引。索引从 0 开始。默认值为 -1。值：QR 结构追加模式条码的数量。

### getQRStructuredAppendModeBarCodesQuantity() {#getqrstructuredappendmodebarcodesquantity}

> **Deprecated.** See method description for replacement.

获取 QR 结构追加模式条码的数量。默认值为 -1。值：QR 结构追加模式条码的数量。

### getQRStructuredAppendModeParityData() {#getqrstructuredappendmodeparitydata}

> **Deprecated.** See method description for replacement.

获取 QR 结构追加模式的奇偶校验数据。默认值为 -1。值：QR 结构追加模式条码的索引。

### getQRVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

已识别 QR 码的版本。从 Version1 到 Version40。

**Returns:** Version of recognized QR Code

### getRectMicroQRVersion() {#getrectmicroqrversion}

已识别 RectMicroQR 码的版本。从 R7x43 到 R17x139。

**Returns:** Version of recognized RectMicroQR Code

### getStructuredAppendModeBarCodeIndex() {#getstructuredappendmodebarcodeindex}

获取 QR 结构化追加模式条形码的索引。索引从 0 开始。默认值为 -1。值：QR 结构化追加模式条形码的数量。

**Returns:** the index of the QR structured append mode barcode.

### getStructuredAppendModeBarCodesQuantity() {#getstructuredappendmodebarcodesquantity}

获取 QR 结构化追加模式条形码的数量。默认值为 -1。值：QR 结构化追加模式条形码的数量。

**Returns:** the QR structured append mode barcodes quantity.

### getStructuredAppendModeParityData() {#getstructuredappendmodeparitydata}

获取 QR 结构化追加模式奇偶校验数据。默认值为 -1。值：QR 结构化追加模式条形码的索引。

**Returns:** the QR structured append mode parity data.

### getVersion() {#getversion}

已识别 QR 码的版本。从 Version1 到 Version40。

### hashCode() {#hashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

测试所有参数是否仅具有默认值。值

**Returns:** true if all parameters has only default values; otherwise, `false `.

### toString() {#tostring}

返回此 QRExtendedParameters 的人类可读字符串表示。

**Returns:** A string that represents this QRExtendedParameters.
