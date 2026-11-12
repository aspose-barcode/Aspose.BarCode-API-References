---
title: "AztecParameters"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "Aztec 参数。"
type: docs
weight: 70
url: /zh/nodejs/aspose.barcode/aztecparameters/
---

## AztecParameters class

Aztec 参数。

```js
new AztecParameters()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | 2D 条形码模块的高宽比。 |
| [getAztecEncodeMode()](#getaztecencodemode) ~~(deprecated)~~ | 获取 Aztec 编码模式。默认值：Auto。 |
| [getAztecErrorLevel()](#getaztecerrorlevel) ~~(deprecated)~~ | Aztec 条形码的错误纠正级别。取值应在 5 到 95 之间。 |
| [getAztecSymbolMode()](#getaztecsymbolmode) ~~(deprecated)~~ | 获取 Aztec 符号模式。默认值：AztecSymbolMode.Auto。 |
| [getECIEncoding()](#geteciencoding) | 获取 ECI 编码。当 AztecEncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | 获取 Aztec 编码模式。默认值：Auto。 |
| [getErrorLevel()](#geterrorlevel) | Aztec 条形码的错误纠正级别。取值应在 5 到 95 之间。 |
| [getLayersCount()](#getlayerscount) | 获取 Aztec 符号的层数。紧凑模式下层数应在 1 到 3 范围内，其他模式也应在 1 到 3 范围内 |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Aztec 条形码结构化追加模式的条形码 ID。条形码 ID 应在 1 到条形码总数的范围内。默认值 |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Aztec 条形码的结构追加模式的条形码计数。条形码计数应在 1 到 26 的范围内。默认值 |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Aztec 条形码的结构追加模式的文件 ID（可选字段）。文件 ID 不应包含空格。默认值： |
| [getSymbolMode()](#getsymbolmode) | 获取 Aztec 符号模式。默认值：AztecSymbolMode.Auto。 |
| [isReaderInitialization()](#isreaderinitialization) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [setAspectRatio()](#setaspectratio) | 2D 条形码模块的高宽比。 |
| [setAztecEncodeMode()](#setaztecencodemode) ~~(deprecated)~~ | 设置 Aztec 编码模式。默认值：Auto。 |
| [setAztecErrorLevel()](#setaztecerrorlevel) ~~(deprecated)~~ | Aztec 条形码的错误纠正级别。取值应在 5 到 95 之间。 |
| [setAztecSymbolMode()](#setaztecsymbolmode) ~~(deprecated)~~ | 设置 Aztec 符号模式。默认值：AztecSymbolMode.Auto。 |
| [setECIEncoding()](#seteciencoding) | 设置 ECI 编码。当 AztecEncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| [setEncodeMode(value)](#setencodemode) | 设置 Aztec 编码模式。默认值：Auto。 |
| [setErrorLevel()](#seterrorlevel) | Aztec 条形码的错误纠正级别。取值应在 5 到 95 之间。 |
| [setLayersCount()](#setlayerscount) | 设置 Aztec 符号的层数。层数在紧凑模式下应在 1 到 3 的范围内，并在 1 到 3 |
| [setReaderInitialization()](#setreaderinitialization) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | Aztec 条形码结构化追加模式的条形码 ID。条形码 ID 应在 1 到条形码总数的范围内。默认值 |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | Aztec 条形码的结构追加模式的条形码计数。条形码计数应在 1 到 26 的范围内。默认值 |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | Aztec 条形码的结构追加模式的文件 ID（可选字段）。文件 ID 不应包含空格。默认值： |
| [setSymbolMode(value)](#setsymbolmode) | 设置 Aztec 符号模式。默认值：AztecSymbolMode.Auto。 |
| [toString()](#tostring) | 返回此 `AztecParameters` 的人类可读字符串表示。 |

### getAspectRatio() {#getaspectratio}

2D 条形码模块的高宽比。

### getAztecEncodeMode() {#getaztecencodemode}

> **Deprecated.** See method description for replacement.

获取 Aztec 编码模式。默认值：Auto。

### getAztecErrorLevel() {#getaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Aztec 条形码的错误纠正级别。取值应在 5 到 95 之间。

### getAztecSymbolMode() {#getaztecsymbolmode}

> **Deprecated.** See method description for replacement.

获取 Aztec 符号模式。默认值：AztecSymbolMode.Auto。

### getECIEncoding() {#geteciencoding}

获取 ECI 编码。当 AztecEncodeMode 为 Auto 时使用。默认值：ISO-8859-1

### getEncodeMode() {#getencodemode}

获取 Aztec 编码模式。默认值：Auto。

**Returns:** a Aztec encode mode.

### getErrorLevel() {#geterrorlevel}

Aztec 条形码的错误纠正级别。取值应在 5 到 95 之间。

### getLayersCount() {#getlayerscount}

获取 Aztec 符号的层数。层数在紧凑模式下应在 1 到 3 的范围内，在全范围模式下应在 1 到 32 的范围内。默认值：0（自动）。

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Aztec 条形码的结构追加模式的条形码 ID。条形码 ID 应在 1 到条形码计数的范围内。默认值：0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Aztec 条形码的结构追加模式的条形码计数。条形码计数应在 1 到 26 的范围内。默认值：0

### getStructuredAppendFileId() {#getstructuredappendfileid}

Aztec 条形码的结构追加模式的文件 ID（可选字段）。文件 ID 不应包含空格。默认值：空字符串

### getSymbolMode() {#getsymbolmode}

获取 Aztec 符号模式。默认值：AztecSymbolMode.Auto。

**Returns:** a Aztec Symbol mode.

### isReaderInitialization() {#isreaderinitialization}

用于指示读取器将符号中包含的数据解释为读取器初始化的编程。

### setAspectRatio() {#setaspectratio}

2D 条形码模块的高宽比。

### setAztecEncodeMode() {#setaztecencodemode}

> **Deprecated.** See method description for replacement.

设置 Aztec 编码模式。默认值：Auto。

### setAztecErrorLevel() {#setaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Aztec 条形码的错误纠正级别。取值应在 5 到 95 之间。

### setAztecSymbolMode() {#setaztecsymbolmode}

> **Deprecated.** See method description for replacement.

设置 Aztec 符号模式。默认值：AztecSymbolMode.Auto。

### setECIEncoding() {#seteciencoding}

设置 ECI 编码。当 AztecEncodeMode 为 Auto 时使用。默认值：ISO-8859-1

### setEncodeMode(value) {#setencodemode}

设置 Aztec 编码模式。默认值：Auto。

| 参数 | 描述 |
| --- | --- |
| 值 | 一个 Aztec 编码模式。 |

### setErrorLevel() {#seterrorlevel}

Aztec 条形码的错误纠正级别。取值应在 5 到 95 之间。

### setLayersCount() {#setlayerscount}

设置 Aztec 符号的层数。层数在紧凑模式下应在 1 到 3 的范围内，在全范围模式下应在 1 到 32 的范围内。默认值：0（自动）。

### setReaderInitialization() {#setreaderinitialization}

用于指示读取器将符号中包含的数据解释为读取器初始化的编程。

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

Aztec 条形码的结构追加模式的条形码 ID。条形码 ID 应在 1 到条形码计数的范围内。默认值：0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

Aztec 条形码的结构追加模式的条形码计数。条形码计数应在 1 到 26 的范围内。默认值：0

### setStructuredAppendFileId() {#setstructuredappendfileid}

Aztec 条形码的结构追加模式的文件 ID（可选字段）。文件 ID 不应包含空格。默认值：空字符串

### setSymbolMode(value) {#setsymbolmode}

设置 Aztec 符号模式。默认值：AztecSymbolMode.Auto。

| 参数 | 描述 |
| --- | --- |
| 值 | 一个 Aztec 符号模式。 |

### toString() {#tostring}

返回此 `AztecParameters` 的人类可读字符串表示。

**Returns:** A string that represents this `AztecParameters`.
