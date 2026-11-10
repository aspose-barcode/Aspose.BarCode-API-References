---
title: "类 QrParametersUI"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Windows.Forms.QrParametersUI 类。QrParameters 类的 UI 包装器"
type: docs
weight: 1870
url: /zh/net/aspose.barcode.windows.forms/qrparametersui/
---
## QrParametersUI class

UI 包装器用于 [`QrParameters`](../../aspose.barcode.generation/qrparameters/) 类。

```csharp
public class QrParametersUI
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AspectRatio](../../aspose.barcode.windows.forms/qrparametersui/aspectratio/) { get; set; } | 2D 条码模块的高/宽比。 |
| [ECIEncoding](../../aspose.barcode.windows.forms/qrparametersui/eciencoding/) { get; set; } | 扩展信道解释标识符。它用于向条码阅读器提供有关在符号中对数据进行编码所使用的参考的详细信息。当前实现包含所有已知的字符集编码。MicroQR 不支持。 |
| [EncodeGS1SeparatorInByteMode](../../aspose.barcode.windows.forms/qrparametersui/encodegs1separatorinbytemode/) { get; set; } | 获取或设置一个值，指示是否应在 QR 和 RectMicroQR 条码的字节模式下对 GS1 特殊字符进行编码。 |
| [EncodeMode](../../aspose.barcode.windows.forms/qrparametersui/encodemode/) { get; set; } | 条码的编码模式的 QR 符号类型。默认值：QREncodeMode.Auto。 |
| [ErrorLevel](../../aspose.barcode.windows.forms/qrparametersui/errorlevel/) { get; set; } | QR、MicroQR 和 RectMicroQR 条码的 Reed-Solomon 错误更正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。参见 QRErrorLevel。 |
| [MicroQrVersion](../../aspose.barcode.windows.forms/qrparametersui/microqrversion/) { get; set; } | MicroQR 码的版本。从 M1 版到 M4 版。默认值为 MicroQRVersion.Auto。 |
| [RectMicroQrVersion](../../aspose.barcode.windows.forms/qrparametersui/rectmicroqrversion/) { get; set; } | RectMicroQR 码的版本。从 R7x59 版到 R17x139 版。默认值为 RectMicroQRVersion.Auto。 |
| [Version](../../aspose.barcode.windows.forms/qrparametersui/version/) { get; set; } | QR 码的版本。QR 码从 Version1 到 Version40，MicroQr 从 M1 到 M4。默认值为 QRVersion.Auto。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/qrparametersui/tostring/)() | 返回此 [`QrParameters`](../../aspose.barcode.generation/qrparameters/) 的人类可读字符串表示。 |

### 另见

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


