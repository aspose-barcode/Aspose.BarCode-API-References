---
title: "DataMatrixParameters"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "DataMatrix 参数。"
type: docs
weight: 360
url: /zh/nodejs/aspose.barcode/datamatrixparameters/
---

## DataMatrixParameters class

DataMatrix 参数。

```js
new DataMatrixParameters()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | 2D 条形码模块的高宽比。 |
| [getColumns()](#getcolumns) | 列数。 |
| [getDataMatrixEcc()](#getdatamatrixecc) ~~(deprecated)~~ | 获取 Datamatrix ECC 类型。默认值：DataMatrixEccType.ECC_200。 |
| [getDataMatrixEncodeMode()](#getdatamatrixencodemode) ~~(deprecated)~~ | Datamatrix 条形码的编码模式。默认值：DataMatrixEncodeMode.AUTO。 |
| [getDataMatrixVersion()](#getdatamatrixversion) ~~(deprecated)~~ | 获取 Datamatrix 符号大小。默认值：DataMatrixVersion.Auto。 |
| [getEccType()](#getecctype) | 获取 Datamatrix ECC 类型。默认值：DataMatrixEccType.Ecc200。 |
| [getECIEncoding()](#geteciencoding) | 获取 ECI 编码。当 DataMatrixEncodeMode 为 Auto 时使用。默认值：ISO-8859-1。 |
| [getEncodeMode()](#getencodemode) | Datamatrix 条形码的编码模式。默认值：EncodeMode.Auto。 |
| [getMacroCharacters()](#getmacrocharacters) | ISO/IEC 16022 5.2.4.7 宏字符 11.3 首位宏字符协议（仅 ECC 200）Macro Cha |
| [getRows()](#getrows) | 行数。 |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Datamatrix 条形码结构化追加模式的条形码 ID。默认值：0。 |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Datamatrix 条形码结构化追加模式的条形码数量。默认值：0。 |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Datamatrix 条形码结构化追加模式的文件 ID。默认值：0。 |
| [getVersion()](#getversion) | 获取 Datamatrix 符号大小。默认值：Version.Auto。 |
| [isReaderProgramming()](#isreaderprogramming) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [setAspectRatio()](#setaspectratio) | 2D 条形码模块的高宽比。 |
| [setColumns()](#setcolumns) | 列数。 |
| [setDataMatrixEcc()](#setdatamatrixecc) ~~(deprecated)~~ | 设置 Datamatrix ECC 类型。默认值：DataMatrixEccType.ECC_200。 |
| [setDataMatrixEncodeMode()](#setdatamatrixencodemode) ~~(deprecated)~~ | Datamatrix 条形码的编码模式。默认值：DataMatrixEncodeMode.AUTO。 |
| [setDataMatrixVersion()](#setdatamatrixversion) ~~(deprecated)~~ | 设置 Datamatrix 符号大小。默认值：DataMatrixVersion.Auto。 |
| [setEccType(value)](#setecctype) | 设置 Datamatrix ECC 类型。默认值：DataMatrixEccType.Ecc200。 |
| [setECIEncoding()](#seteciencoding) | 设置 ECI 编码。当 DataMatrixEncodeMode 为 Auto 时使用。默认值：ISO-8859-1。 |
| [setEncodeMode()](#setencodemode) | Datamatrix 条形码的编码模式。默认值：EncodeMode.Auto。 |
| [setMacroCharacters()](#setmacrocharacters) | ISO/IEC 16022 5.2.4.7 宏字符 11.3 首位宏字符协议（仅 ECC 200）Macro Cha |
| [setReaderProgramming()](#setreaderprogramming) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [setRows()](#setrows) | 行数。 |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | Datamatrix 条形码结构化追加模式的条形码 ID。默认值：0。 |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | Datamatrix 条形码结构化追加模式的条形码数量。默认值：0。 |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | Datamatrix 条形码结构化追加模式的文件 ID。默认值：0。 |
| [setVersion(value)](#setversion) | 设置 Datamatrix 符号大小。默认值：Version.Auto。 |
| [toString()](#tostring) | 返回此 DataMatrixParameters 的人类可读字符串表示。 |

### getAspectRatio() {#getaspectratio}

2D 条形码模块的高宽比。

### getColumns() {#getcolumns}

列数。

### getDataMatrixEcc() {#getdatamatrixecc}

> **Deprecated.** See method description for replacement.

获取 Datamatrix ECC 类型。默认值：DataMatrixEccType.ECC_200。

### getDataMatrixEncodeMode() {#getdatamatrixencodemode}

> **Deprecated.** See method description for replacement.

Datamatrix 条形码的编码模式。默认值：DataMatrixEncodeMode.AUTO。

### getDataMatrixVersion() {#getdatamatrixversion}

> **Deprecated.** See method description for replacement.

获取 Datamatrix 符号大小。默认值：DataMatrixVersion.Auto。

### getEccType() {#getecctype}

获取 Datamatrix ECC 类型。默认值：DataMatrixEccType.Ecc200。

**Returns:** a Datamatrix ECC type.

### getECIEncoding() {#geteciencoding}

获取 ECI 编码。当 DataMatrixEncodeMode 为 Auto 时使用。默认值：ISO-8859-1。

### getEncodeMode() {#getencodemode}

Datamatrix 条形码的编码模式。默认值：EncodeMode.Auto。

### getMacroCharacters() {#getmacrocharacters}

ISO/IEC 16022 5.2.4.7 宏字符 11.3 首位宏字符协议（仅 ECC 200）宏字符 05 和 06 值用于在特殊模式下获得更紧凑的编码。只能与 DataMatrixEccType.ECC_200 或 DataMatrixEccType.ECC_AUTO 一起使用。不能与 EncodeTypes.GS_1_DATA_MATRIX 一起使用。默认值：MacroCharacter.NONE。

### getRows() {#getrows}

行数。

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Datamatrix 条形码结构化追加模式的条形码 ID。默认值：0。

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Datamatrix 条形码结构化追加模式的条形码数量。默认值：0。

### getStructuredAppendFileId() {#getstructuredappendfileid}

Datamatrix 条形码结构化追加模式的文件 ID。默认值：0。

### getVersion() {#getversion}

获取 Datamatrix 符号大小。默认值：Version.Auto。

**Returns:** a Datamatrix symbol size.

### isReaderProgramming() {#isreaderprogramming}

用于指示读取器将符号中包含的数据解释为读取器初始化的编程。默认值：false。

### setAspectRatio() {#setaspectratio}

2D 条形码模块的高宽比。

### setColumns() {#setcolumns}

列数。

### setDataMatrixEcc() {#setdatamatrixecc}

> **Deprecated.** See method description for replacement.

设置 Datamatrix ECC 类型。默认值：DataMatrixEccType.ECC_200。

### setDataMatrixEncodeMode() {#setdatamatrixencodemode}

> **Deprecated.** See method description for replacement.

Datamatrix 条形码的编码模式。默认值：DataMatrixEncodeMode.AUTO。

### setDataMatrixVersion() {#setdatamatrixversion}

> **Deprecated.** See method description for replacement.

设置 Datamatrix 符号大小。默认值：DataMatrixVersion.Auto。

### setEccType(value) {#setecctype}

设置 Datamatrix ECC 类型。默认值：DataMatrixEccType.Ecc200。

| 参数 | 描述 |
| --- | --- |
| 值 | 一种 Datamatrix ECC 类型。 |

### setECIEncoding() {#seteciencoding}

设置 ECI 编码。当 DataMatrixEncodeMode 为 Auto 时使用。默认值：ISO-8859-1。

### setEncodeMode() {#setencodemode}

Datamatrix 条形码的编码模式。默认值：EncodeMode.Auto。

### setMacroCharacters() {#setmacrocharacters}

ISO/IEC 16022 5.2.4.7 宏字符 11.3 首位宏字符协议（仅 ECC 200）宏字符 05 和 06 值用于在特殊模式下获得更紧凑的编码。只能与 DataMatrixEccType.ECC_200 或 DataMatrixEccType.ECC_AUTO 一起使用。不能与 EncodeTypes.GS_1_DATA_MATRIX 一起使用。默认值：MacroCharacter.NONE。

### setReaderProgramming() {#setreaderprogramming}

用于指示读取器将符号中包含的数据解释为读取器初始化的编程。默认值：false。

### setRows() {#setrows}

行数。

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

Datamatrix 条形码结构化追加模式的条形码 ID。默认值：0。

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

Datamatrix 条形码结构化追加模式的条形码数量。默认值：0。

### setStructuredAppendFileId() {#setstructuredappendfileid}

Datamatrix 条形码结构化追加模式的文件 ID。默认值：0。

### setVersion(value) {#setversion}

设置 Datamatrix 符号大小。默认值：Version.Auto。

| 参数 | 描述 |
| --- | --- |
| 值 | 一种 Datamatrix 符号尺寸。 |

### toString() {#tostring}

返回此 DataMatrixParameters 的人类可读字符串表示。

**Returns:** presentation of this DataMatrixParameters.
