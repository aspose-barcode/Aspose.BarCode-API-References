---
title: "DotCodeExtendedParameters"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "存储已识别 DotCode 条形码的特殊数据。此示例展示如何获取 DotCode 原始值"
type: docs
weight: 380
url: /zh/nodejs/aspose.barcode/dotcodeextendedparameters/
---

## DotCodeExtendedParameters class

存储已识别 DotCode 条形码的特殊数据。此示例展示如何获取 DotCode 原始值

```js
new DotCodeExtendedParameters()
```

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
generator.save("test.png", BarCodeImageFormat.PNG);

let reader = new BarCodeReader("test.png", null, DecodeType.DOT_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    print("BarCode type: " + result.getCodeTypeName());
    print("BarCode codetext: " + result.getCodeText());
    print("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
    print("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
}
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals(obj)](#equals) | 返回一个值，指示此实例是否等于指定的 `DotCodeExtendedParameters` 值。 |
| [getDotCodeIsReaderInitialization()](#getdotcodeisreaderinitialization) ~~(deprecated)~~ | 指示代码是否用于指示读取器将以下数据解释为初始化指令或 |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | 获取 DotCode 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。 |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | 获取 DotCode 结构化追加模式条码的数量。默认值为 -1。计数必须是 1 到 35 之间的值。值： |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | 获取 DotCode 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。 |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | 获取 DotCode 结构化追加模式条码的数量。默认值为 -1。计数必须是 1 到 35 之间的值。值： |
| [hashCode()](#hashcode) | 返回此实例的哈希码。 |
| [isReaderInitialization()](#isreaderinitialization) | 指示代码是否用于指示读取器将以下数据解释为初始化指令或 |
| [toString()](#tostring) | 返回此 `DotCodeExtendedParameters` 的人类可读字符串表示。 |

### equals(obj) {#equals}

返回一个值，指示此实例是否等于指定的 `DotCodeExtendedParameters` 值。

| 参数 | 描述 |
| --- | --- |
| obj | 用于与此实例比较的 System.Object 值。 |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDotCodeIsReaderInitialization() {#getdotcodeisreaderinitialization}

> **Deprecated.** See method description for replacement.

指示代码是否用于指示条码读取器将以下数据解释为初始化或重新编程指令。默认值为 false。

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

获取 DotCode 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。默认值为 -1。值：DotCode 结构化追加模式条码的 ID。

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

获取 DotCode 结构化追加模式条码的数量。默认值为 -1。计数必须是 1 到 35 之间的值。值：DotCode 结构化追加模式条码的数量。

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

获取 DotCode 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。默认值为 -1。值：DotCode 结构化追加模式条码的 ID。

**Returns:** the ID of the DotCode structured append mode barcode.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

获取 DotCode 结构化追加模式条码的数量。默认值为 -1。计数必须是 1 到 35 之间的值。值：DotCode 结构化追加模式条码的数量。

**Returns:** the DotCode structured append mode barcodes count.

### hashCode() {#hashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

指示代码是否用于指示条码读取器将以下数据解释为初始化或重新编程指令。默认值为 false。

### toString() {#tostring}

返回此 `DotCodeExtendedParameters` 的人类可读字符串表示。

**Returns:** A string that represents this `DotCodeExtendedParameters`.
