---
title: "类 QrParameters"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.QrParameters 类。QR 参数"
type: docs
weight: 1650
url: /zh/net/aspose.barcode.generation/qrparameters/
---
## QrParameters class

QR 参数。

```csharp
public class QrParameters
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/qrparameters/aspectratio/) { get; set; } | 2D 条码模块的高/宽比。 |
| [ECIEncoding](../../aspose.barcode.generation/qrparameters/eciencoding/) { get; set; } | 扩展信道解释标识符。它用于向条码阅读器提供有关在符号中对数据进行编码所使用的参考的详细信息。当前实现包含所有已知的字符集编码。MicroQR 不支持。 |
| [EncodeGS1SeparatorInByteMode](../../aspose.barcode.generation/qrparameters/encodegs1separatorinbytemode/) { get; set; } | 获取或设置一个值，指示是否应在 QR 和 RectMicroQR 条码的字节模式下对 GS1 特殊字符进行编码。 |
| [EncodeMode](../../aspose.barcode.generation/qrparameters/encodemode/) { get; set; } | 条码的编码模式的 QR 符号类型。默认值：QREncodeMode.Auto。 |
| [ErrorLevel](../../aspose.barcode.generation/qrparameters/errorlevel/) { get; set; } | QR、MicroQR 和 RectMicroQR 条形码的 Reed-Solomon 错误更正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。参见 QRErrorLevel。 |
| [MicroQRVersion](../../aspose.barcode.generation/qrparameters/microqrversion/) { get; set; } | MicroQR 码的版本。从 M1 版到 M4 版。默认值为 MicroQRVersion.Auto。 |
| [RectMicroQrVersion](../../aspose.barcode.generation/qrparameters/rectmicroqrversion/) { get; set; } | RectMicroQR 码的版本。从 R7x59 版到 R17x139 版。默认值为 RectMicroQRVersion.Auto。 |
| [StructuredAppend](../../aspose.barcode.generation/qrparameters/structuredappend/) { get; set; } | QR 结构化追加参数。MicroQR 和 RectMicroQR 条形码不支持结构化追加模式。 |
| [Version](../../aspose.barcode.generation/qrparameters/version/) { get; set; } | QR 码的版本。从 Version1 到 Version40。默认值为 QRVersion.Auto。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/qrparameters/tostring/)() | 返回此 `QrParameters` 的人类可读字符串表示。 |

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


