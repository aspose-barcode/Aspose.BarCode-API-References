---
title: "MaxiCodeCodetext"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于对嵌入 MaxiCode 代码中的文本进行编码和解码的基类。"
type: docs
weight: 600
url: /zh/nodejs/aspose.barcode/maxicodecodetext/
---

## MaxiCodeCodetext class

用于对嵌入 MaxiCode 代码中的文本进行编码和解码的基类。此示例展示了如何将原始 MaxiCode 文本解码为 MaxiCodeCodetext 实例。

```js
new MaxiCodeCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     console.log("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
     console.log("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
     console.log("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | 获取条形码类型。 |
| [getECIEncoding()](#geteciencoding) | 获取 ECI 编码。当 MaxiCodeEncodeMode 为 AUTO 时使用。 |
| [getEncodeMode()](#getencodemode) | 获取 MaxiCode 编码模式。默认值：Auto。 |
| [getMaxiCodeEncodeMode()](#getmaxicodeencodemode) ~~(deprecated)~~ | 获取 MaxiCode 编码模式。 |
| [getMode()](#getmode) | 获取 MaxiCode 模式。 |
| [setECIEncoding()](#seteciencoding) | 设置 ECI 编码。当 MaxiCodeEncodeMode 为 AUTO 时使用。 |
| [setEncodeMode(value)](#setencodemode) | 设置 MaxiCode 编码模式。默认值：Auto。 |
| [setMaxiCodeEncodeMode()](#setmaxicodeencodemode) ~~(deprecated)~~ | 设置 MaxiCode 编码模式。 |

### getBarcodeType() {#getbarcodetype}

获取条形码类型。

**Returns:** Barcode type

### getECIEncoding() {#geteciencoding}

获取 ECI 编码。当 MaxiCodeEncodeMode 为 AUTO 时使用。

### getEncodeMode() {#getencodemode}

获取 MaxiCode 编码模式。默认值：Auto。

**Returns:** a MaxiCode encode mode.

### getMaxiCodeEncodeMode() {#getmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

获取 MaxiCode 编码模式。

### getMode() {#getmode}

获取 MaxiCode 模式。

**Returns:** MaxiCode mode

### setECIEncoding() {#seteciencoding}

设置 ECI 编码。当 MaxiCodeEncodeMode 为 AUTO 时使用。

### setEncodeMode(value) {#setencodemode}

设置 MaxiCode 编码模式。默认值：Auto。

| 参数 | 描述 |
| --- | --- |
| 值 | 一个 MaxiCode 编码模式。 |

### setMaxiCodeEncodeMode() {#setmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

设置 MaxiCode 编码模式。
