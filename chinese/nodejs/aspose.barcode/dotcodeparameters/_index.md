---
title: "DotCodeParameters"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "DotCode 参数。"
type: docs
weight: 390
url: /zh/nodejs/aspose.barcode/dotcodeparameters/
---

## DotCodeParameters class

DotCode 参数。

```js
new DotCodeParameters()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | 2D 条形码模块的高宽比。 |
| [getColumns()](#getcolumns) | 标识列计数。DotCode 符号的行数加列数之和必须为奇数。Number o |
| [getDotCodeEncodeMode()](#getdotcodeencodemode) ~~(deprecated)~~ | 标识 DotCode 编码模式。默认值：Auto。 |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | 标识 DotCode 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。 |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | 标识 DotCode 结构化追加模式条码计数。默认值为 -1。计数必须在 1 到 35 之间。 |
| [getECIEncoding()](#geteciencoding) | 标识 ECI 编码。当 DotCodeEncodeMode 为 AUTO 时使用。默认值：ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | 标识 DotCode 编码模式。默认值：Auto。 |
| [getRows()](#getrows) | 标识行计数。DotCode 符号的行数加列数之和必须为奇数。Number of r |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | 标识 DotCode 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。 |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | 标识 DotCode 结构化追加模式条码计数。默认值为 -1。计数必须在 1 到 35 之间。 |
| [isReaderInitialization()](#isreaderinitialization) | 指示代码是否用于指示读取器将以下数据解释为初始化指令或 |
| [setAspectRatio()](#setaspectratio) | 2D 条形码模块的高宽比。 |
| [setColumns()](#setcolumns) | 标识列计数。DotCode 符号的行数加列数之和必须为奇数。Number o |
| [setDotCodeEncodeMode()](#setdotcodeencodemode) ~~(deprecated)~~ | 标识 DotCode 编码模式。默认值：Auto。 |
| [setDotCodeStructuredAppendModeBarcodeId()](#setdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | 标识 DotCode 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。 |
| [setDotCodeStructuredAppendModeBarcodesCount()](#setdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | 标识 DotCode 结构化追加模式条码计数。默认值为 -1。计数必须在 1 到 35 之间。 |
| [setECIEncoding()](#seteciencoding) | 标识 ECI 编码。当 DotCodeEncodeMode 为 AUTO 时使用。默认值：ISO-8859-1 |
| [setEncodeMode()](#setencodemode) | 标识 DotCode 编码模式。默认值：Auto。 |
| [setReaderInitialization()](#setreaderinitialization) | 指示代码是否用于指示读取器将以下数据解释为初始化指令或 |
| [setRows()](#setrows) | 标识行计数。DotCode 符号的行数加列数之和必须为奇数。Number of r |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | 标识 DotCode 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。 |
| [setStructuredAppendModeBarcodesCount()](#setstructuredappendmodebarcodescount) | 标识 DotCode 结构化追加模式条码计数。默认值为 -1。计数必须在 1 到 35 之间。 |
| [toString()](#tostring) | 返回此 DotCodeParameters 的可读字符串表示。 |

### getAspectRatio() {#getaspectratio}

2D 条形码模块的高宽比。

### getColumns() {#getcolumns}

标识列数。DotCode 符号的行数与列数之和必须为奇数。列数必须至少为 5。默认值：-1

### getDotCodeEncodeMode() {#getdotcodeencodemode}

> **Deprecated.** See method description for replacement.

标识 DotCode 编码模式。默认值：Auto。

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

标识 DotCode 结构追加模式条形码的 ID。ID 从 1 开始，且必须小于或等于条形码数量。默认值为 -1。

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

标识 DotCode 结构化追加模式条码计数。默认值为 -1。计数必须在 1 到 35 之间。

### getECIEncoding() {#geteciencoding}

标识 ECI 编码。当 DotCodeEncodeMode 为 AUTO 时使用。默认值：ISO-8859-1

### getEncodeMode() {#getencodemode}

标识 DotCode 编码模式。默认值：Auto。

### getRows() {#getrows}

标识行数。DotCode 符号的行数与列数之和必须为奇数。行数必须至少为 5。默认值：-1

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

标识 DotCode 结构追加模式条形码的 ID。ID 从 1 开始，且必须小于或等于条形码数量。默认值为 -1。

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

标识 DotCode 结构化追加模式条码计数。默认值为 -1。计数必须在 1 到 35 之间。

### isReaderInitialization() {#isreaderinitialization}

指示代码是否用于指示条码读取器将以下数据解释为初始化或重新编程指令。默认值为 false。

### setAspectRatio() {#setaspectratio}

2D 条形码模块的高宽比。

### setColumns() {#setcolumns}

标识列数。DotCode 符号的行数与列数之和必须为奇数。列数必须至少为 5。默认值：-1

### setDotCodeEncodeMode() {#setdotcodeencodemode}

> **Deprecated.** See method description for replacement.

标识 DotCode 编码模式。默认值：Auto。

### setDotCodeStructuredAppendModeBarcodeId() {#setdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

标识 DotCode 结构追加模式条形码的 ID。ID 从 1 开始，且必须小于或等于条形码数量。默认值为 -1。

### setDotCodeStructuredAppendModeBarcodesCount() {#setdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

标识 DotCode 结构化追加模式条码计数。默认值为 -1。计数必须在 1 到 35 之间。

### setECIEncoding() {#seteciencoding}

标识 ECI 编码。当 DotCodeEncodeMode 为 AUTO 时使用。默认值：ISO-8859-1

### setEncodeMode() {#setencodemode}

标识 DotCode 编码模式。默认值：Auto。

### setReaderInitialization() {#setreaderinitialization}

指示代码是否用于指示条码读取器将以下数据解释为初始化或重新编程指令。默认值为 false。

### setRows() {#setrows}

标识行数。DotCode 符号的行数与列数之和必须为奇数。行数必须至少为 5。默认值：-1

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

标识 DotCode 结构追加模式条形码的 ID。ID 从 1 开始，且必须小于或等于条形码数量。默认值为 -1。

### setStructuredAppendModeBarcodesCount() {#setstructuredappendmodebarcodescount}

标识 DotCode 结构化追加模式条码计数。默认值为 -1。计数必须在 1 到 35 之间。

### toString() {#tostring}

返回此 DotCodeParameters 的可读字符串表示。

**Returns:** A string that represents this DotCodeParameters.
