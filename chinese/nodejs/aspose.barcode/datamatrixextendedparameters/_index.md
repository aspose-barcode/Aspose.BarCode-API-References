---
title: "DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "存储已识别 DataMatrix 条码的特殊数据 此示例展示如何获取 DataMatrix 原始值 let generator = new BarcodeGenerator(EncodeTypes.DATA_MA"
type: docs
weight: 350
url: /zh/nodejs/aspose.barcode/datamatrixextendedparameters/
---

## DataMatrixExtendedParameters class

存储已识别 DataMatrix 条码的特殊数据 此示例展示如何获取 DataMatrix 原始值 let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345")) generator.save("test.png", BarcodeImageFormat.PNG); let reader = new BarCodeReader("test.png", null, DecodeType.DATA_MATRIX)) let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode type: " + result.getCodeTypeName()); console.log("BarCode codetext: " + result.getCodeText()); console.log("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId()); console.log("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount()); console.log("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId()); console.log("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming()); }

```js
new DataMatrixExtendedParameters()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals(obj)](#equals) | 返回一个值，指示此实例是否等于指定的 `DataMatrixExtendedParameters` 值。 |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | 获取 DataMatrix 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量 cou |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | 获取 DataMatrix 结构化追加模式条码的计数。默认值为 -1。计数必须在 1 到 35 之间。Valu |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | 获取 DataMatrix 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量 cou |
| [hashCode()](#hashcode) | 返回此实例的哈希码。 |
| [isReaderProgramming()](#isreaderprogramming) | 指示代码是否用于指示读取器将以下数据解释为初始化指令或 |
| [toString()](#tostring) | 返回此 `DataMatrixExtendedParameters` 的人类可读字符串表示。 |

### equals(obj) {#equals}

返回一个值，指示此实例是否等于指定的 `DataMatrixExtendedParameters` 值。

| 参数 | 描述 |
| --- | --- |
| obj | 用于与此实例比较的 System.Object 值。 |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

获取 DataMatrix 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码计数。默认值为 -1。值：DataMatrix 结构化追加模式条码的 ID。

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

获取 DataMatrix 结构化追加模式条码的计数。默认值为 -1。计数必须在 1 到 35 之间。值：DataMatrix 结构化追加模式条码的计数。

### getStructuredAppendFileId() {#getstructuredappendfileid}

获取 DataMatrix 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码计数。默认值为 -1。值：DataMatrix 结构化追加模式条码的 ID。

### hashCode() {#hashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code.

### isReaderProgramming() {#isreaderprogramming}

指示代码是否用于指示条码读取器将以下数据解释为初始化或重新编程指令。默认值为 false。

### toString() {#tostring}

返回此 `DataMatrixExtendedParameters` 的人类可读字符串表示。

**Returns:** A string that represents this `DataMatrixExtendedParameters`.
