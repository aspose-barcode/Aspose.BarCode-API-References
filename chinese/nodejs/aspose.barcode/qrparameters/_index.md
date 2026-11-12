---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "QR 参数。"
type: docs
weight: 830
url: /zh/nodejs/aspose.barcode/qrparameters/
---

## QrParameters class

QR 参数。

```js
new QrParameters()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | 2D 条形码模块的高宽比。 |
| [getECIEncoding()](#geteciencoding) | 扩展通道解释标识符。用于向条码读取器提供有关所使用参考的详细信息。 |
| [getEncodeGS1SeparatorInByteMode()](#getencodegs1separatorinbytemode) | 获取或设置一个值，指示是否应在 QR 和 RectMicroQR 条码中以字节模式编码 GS1 特殊字符 |
| [getEncodeMode()](#getencodemode) | QR 符号类型的 BarCode 编码模式。默认值：QREncodeMode.Auto。 |
| [getErrorLevel()](#geterrorlevel) | QR、MicroQR 和 RectMicroQR 条码的 Reed-Solomon 错误更正级别。从低到高：LevelL、LevelM、LevelQ |
| [getMicroQRVersion()](#getmicroqrversion) | MicroQR 码的版本。从 M1 版到 M4 版。默认值为 MicroQRVersion.Auto。 |
| [getQrECIEncoding()](#getqreciencoding) ~~(deprecated)~~ | 扩展通道解释标识符。用于向条码读取器提供有关所使用参考的详细信息。 |
| [getQrEncodeMode()](#getqrencodemode) | QR 符号类型的 BarCode 编码模式。默认值：QREncodeMode.AUTO。 |
| [getQrEncodeType()](#getqrencodetype) ~~(deprecated)~~ | QR / MicroQR 选择模式。对标准 QR 符号选择 ForceQR，对 MicroQR 选择 Auto。 |
| [getQrErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | QR 条码的 Reed-Solomon 错误更正级别。从低到高：LEVEL_L、LEVEL_M、LEVEL_Q、LEVEL_H。参见 QRError |
| [getQrVersion()](#getqrversion) ~~(deprecated)~~ | QR 码的版本。从 Version1 到 Version40（适用于 QR 码），以及从 M1 到 M4（适用于 MicroQr）。默认值为 QRVersion.AUT。 |
| [getRectMicroQrVersion()](#getrectmicroqrversion) | RectMicroQR 码的版本。从 R7x59 版到 R17x139 版。默认值为 RectMicroQRVersion.Auto。 |
| [getStructuredAppend()](#getstructuredappend) | QR 结构化追加参数。 |
| [getVersion()](#getversion) | QR 码的版本。从 Version1 到 Version40。默认值为 QRVersion.Auto。 |
| [setAspectRatio()](#setaspectratio) | 2D 条形码模块的高宽比。 |
| [setECIEncoding()](#seteciencoding) | 扩展通道解释标识符。用于向条码读取器提供有关所使用参考的详细信息。 |
| [setEncodeGS1SeparatorInByteMode(value)](#setencodegs1separatorinbytemode) | 获取或设置一个值，指示是否应在 QR 和 RectMicroQR 条码中以字节模式编码 GS1 特殊字符 |
| [setEncodeMode()](#setencodemode) | QR 符号类型的 BarCode 编码模式。默认值：QREncodeMode.Auto。 |
| [setErrorLevel()](#seterrorlevel) | QR、MicroQR 和 RectMicroQR 条码的 Reed-Solomon 错误更正级别。从低到高：LevelL、LevelM、LevelQ |
| [setMicroQRVersion()](#setmicroqrversion) | MicroQR 码的版本。从 M1 版到 M4 版。默认值为 MicroQRVersion.Auto。 |
| [setQrECIEncoding()](#setqreciencoding) ~~(deprecated)~~ | 扩展通道解释标识符。用于向条码读取器提供有关所使用参考的详细信息。 |
| [setQrEncodeMode()](#setqrencodemode) ~~(deprecated)~~ | QR 符号类型的 BarCode 编码模式。默认值：QREncodeMode.AUTO。 |
| [setQrEncodeType()](#setqrencodetype) ~~(deprecated)~~ | QR / MicroQR 选择模式。对标准 QR 符号选择 ForceQR，对 MicroQR 选择 Auto。 |
| [setQrErrorLevel()](#setqrerrorlevel) ~~(deprecated)~~ | QR 条码的 Reed-Solomon 错误更正级别。从低到高：LEVEL_L、LEVEL_M、LEVEL_Q、LEVEL_H。参见 QRError |
| [setQrVersion()](#setqrversion) ~~(deprecated)~~ | QR 码的版本。从 Version1 到 Version40（适用于 QR 码），以及从 M1 到 M4（适用于 MicroQr）。默认值为 QRVersion.AUT。 |
| [setRectMicroQrVersion()](#setrectmicroqrversion) | RectMicroQR 码的版本。从 R7x59 版到 R17x139 版。默认值为 RectMicroQRVersion.Auto。 |
| [setStructuredAppend()](#setstructuredappend) | QR 结构化追加参数。 |
| [setVersion()](#setversion) | QR 码的版本。从 Version1 到 Version40。默认值为 QRVersion.Auto。 |
| [toString()](#tostring) | 返回此 QrParameters 的可读字符串表示。 |

### getAspectRatio() {#getaspectratio}

2D 条形码模块的高宽比。

### getECIEncoding() {#geteciencoding}

扩展通道解释标识符。用于向条码阅读器提供有关在符号中编码数据所使用的参考信息的详细信息。当前实现包含所有已知的字符集编码。MicroQR 不支持此功能。

### getEncodeGS1SeparatorInByteMode() {#getencodegs1separatorinbytemode}

获取或设置一个值，指示是否应在 QR 和 RectMicroQR 条码中以字节模式编码 GS1 特殊字符。如果为 false，则根据 QR 规范，GS1 分隔符可能在字母数字模式下编码为 '%'。如果为 true，则 GS1 组分隔符以字节模式编码为 0x1D 字符，且 '%' 字符也以字节模式编码以保留为数据。此选项可能提升对期望字节级 GS1 组分隔符的解码器的兼容性，并防止将 '%' 数据字符解释为 GS1 分隔符。

**Returns:** a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

### getEncodeMode() {#getencodemode}

QR 符号类型的 BarCode 编码模式。默认值：QREncodeMode.Auto。

### getErrorLevel() {#geterrorlevel}

QR、MicroQR 和 RectMicroQR 条码的 Reed-Solomon 错误更正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。参见 QRErrorLevel。

### getMicroQRVersion() {#getmicroqrversion}

MicroQR 码的版本。从 M1 版到 M4 版。默认值为 MicroQRVersion.Auto。

### getQrECIEncoding() {#getqreciencoding}

> **Deprecated.** See method description for replacement.

扩展通道解释标识符。它用于向条码阅读器提供有关在符号中对数据进行编码所使用的参考的详细信息。当前实现包括所有已知的字符集编码。

### getQrEncodeMode() {#getqrencodemode}

QR 符号类型的 BarCode 编码模式。默认值：QREncodeMode.AUTO。

### getQrEncodeType() {#getqrencodetype}

> **Deprecated.** See method description for replacement.

QR / MicroQR 选择模式。对标准 QR 符号选择 ForceQR，对 MicroQR 选择 Auto。

### getQrErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

QR 条码的 Reed-Solomon 错误更正级别。从低到高：LEVEL_L、LEVEL_M、LEVEL_Q、LEVEL_H。参见 QRErrorLevel。

### getQrVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

QR 码的版本。从 Version1 到 Version40（适用于 QR 码），以及从 M1 到 M4（适用于 MicroQr）。默认值为 QRVersion.AUTO。

### getRectMicroQrVersion() {#getrectmicroqrversion}

RectMicroQR 码的版本。从 R7x59 版到 R17x139 版。默认值为 RectMicroQRVersion.Auto。

### getStructuredAppend() {#getstructuredappend}

QR 结构化追加参数。

### getVersion() {#getversion}

QR 码的版本。从 Version1 到 Version40。默认值为 QRVersion.Auto。

### setAspectRatio() {#setaspectratio}

2D 条形码模块的高宽比。

### setECIEncoding() {#seteciencoding}

扩展通道解释标识符。用于向条码阅读器提供有关在符号中编码数据所使用的参考信息的详细信息。当前实现包含所有已知的字符集编码。MicroQR 不支持此功能。

### setEncodeGS1SeparatorInByteMode(value) {#setencodegs1separatorinbytemode}

获取或设置一个值，指示是否应在 QR 和 RectMicroQR 条码中以字节模式编码 GS1 特殊字符。如果为 false，则根据 QR 规范，GS1 分隔符可能在字母数字模式下编码为 '%'。如果为 true，则 GS1 组分隔符以字节模式编码为 0x1D 字符，且 '%' 字符也以字节模式编码以保留为数据。此选项可能提升对期望字节级 GS1 组分隔符的解码器的兼容性，并防止将 '%' 数据字符解释为 GS1 分隔符。

| 参数 | 描述 |
| --- | --- |
| 值 | 指示是否应在 QR 和 RectMicroQR 条码中以字节模式编码 GS1 特殊字符的值。 |

### setEncodeMode() {#setencodemode}

QR 符号类型的 BarCode 编码模式。默认值：QREncodeMode.Auto。

### setErrorLevel() {#seterrorlevel}

QR、MicroQR 和 RectMicroQR 条码的 Reed-Solomon 错误更正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。参见 QRErrorLevel。

### setMicroQRVersion() {#setmicroqrversion}

MicroQR 码的版本。从 M1 版到 M4 版。默认值为 MicroQRVersion.Auto。

### setQrECIEncoding() {#setqreciencoding}

> **Deprecated.** See method description for replacement.

扩展通道解释标识符。它用于向条码阅读器提供有关在符号中对数据进行编码所使用的参考的详细信息。当前实现包括所有已知的字符集编码。

### setQrEncodeMode() {#setqrencodemode}

> **Deprecated.** See method description for replacement.

QR 符号类型的 BarCode 编码模式。默认值：QREncodeMode.AUTO。

### setQrEncodeType() {#setqrencodetype}

> **Deprecated.** See method description for replacement.

QR / MicroQR 选择模式。对标准 QR 符号选择 ForceQR，对 MicroQR 选择 Auto。

### setQrErrorLevel() {#setqrerrorlevel}

> **Deprecated.** See method description for replacement.

QR 条码的 Reed-Solomon 错误更正级别。从低到高：LEVEL_L、LEVEL_M、LEVEL_Q、LEVEL_H。参见 QRErrorLevel。

### setQrVersion() {#setqrversion}

> **Deprecated.** See method description for replacement.

QR 码的版本。从 Version1 到 Version40（适用于 QR 码），以及从 M1 到 M4（适用于 MicroQr）。默认值为 QRVersion.AUTO。

### setRectMicroQrVersion() {#setrectmicroqrversion}

RectMicroQR 码的版本。从 R7x59 版到 R17x139 版。默认值为 RectMicroQRVersion.Auto。

### setStructuredAppend() {#setstructuredappend}

QR 结构化追加参数。

### setVersion() {#setversion}

QR 码的版本。从 Version1 到 Version40。默认值为 QRVersion.Auto。

### toString() {#tostring}

返回此 QrParameters 的可读字符串表示。

**Returns:** A string that represents this QrParameters.
