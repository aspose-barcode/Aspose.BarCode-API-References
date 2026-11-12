---
title: "AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "存储 Aztec 识别的条码的特殊数据。本示例展示如何获取 Aztec 原始值 let generator = new BarcodeGenerator(EncodeTypes.AZTEC, \"12345\"); "
type: docs
weight: 60
url: /zh/nodejs/aspose.barcode/aztecextendedparameters/
---

## AztecExtendedParameters class

存储 Aztec 识别的条码的特殊数据。本示例展示如何获取 Aztec 原始值 let generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345"); generator.save("test.png", BarcodeImageFormat.PNG);

```js
new AztecExtendedParameters()
```

**Example:**

```js
BarCodeReader reader = new BarCodeReader("test.png", null, DecodeType.AZTEC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode type: " + result.getCodeTypeName());
    console.log("BarCode codetext: " + result.getCodeText());
    console.log("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
    console.log("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
    console.log("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
    console.log("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
}
</pre>
</pre></blockquote></hr></p>
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals(obj)](#equals) | 返回一个值，指示此实例是否等于指定的 `AztecExtendedParameters` 值。 |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | 获取 Aztec 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。D |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | 获取 Aztec 结构化追加模式的条码数量。默认值为 0。计数必须在 1 到 26 之间。值：The |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | 获取 Aztec 结构化追加模式的文件 ID。默认值为空字符串。值：The File ID of the Aztec stru |
| [hashCode()](#hashcode) | 返回此实例的哈希码。 |
| [isReaderInitialization()](#isreaderinitialization) | 指示代码是否用于指示读取器将以下数据解释为初始化指令或 |
| [toString()](#tostring) | 返回此 `AztecExtendedParameters` 的人类可读字符串表示。 |

### equals(obj) {#equals}

返回一个值，指示此实例是否等于指定的 `AztecExtendedParameters` 值。

| 参数 | 描述 |
| --- | --- |
| obj | 用于与此实例比较的 System.Object 值。 |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

获取 Aztec 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。默认值为 0。值：Aztec 结构化追加模式的条码 ID。

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

获取 Aztec 结构化追加模式的条码数量。默认值为 0。计数必须在 1 到 26 之间。值：Aztec 结构化追加模式的条码数量。

### getStructuredAppendFileId() {#getstructuredappendfileid}

获取 Aztec 结构化追加模式的文件 ID。默认值为空字符串。值：Aztec 结构化追加模式的文件 ID。

### hashCode() {#hashcode}

返回此实例的哈希码。

**Returns:** 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

指示代码是否用于指示条码读取器将以下数据解释为初始化或重新编程指令。默认值为 false。

### toString() {#tostring}

返回此 `AztecExtendedParameters` 的人类可读字符串表示。

**Returns:** A string that represents this `AztecExtendedParameters`.
