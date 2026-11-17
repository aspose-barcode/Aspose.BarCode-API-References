---
title: "Aspose::BarCode::Generation::QrParameters 类"
linktitle: "QrParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::QrParameters 类。C++ 中的 QR 参数。"
type: docs
weight: 4400
url: /zh/cpp/aspose.barcode.generation/qrparameters/
---
## QrParameters class


QR 参数。

```cpp
class QrParameters : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) 模块的高/宽比。 |
| [get_ECIEncoding](./get_eciencoding/)() const | 扩展信道解释标识符。它用于向条码阅读器提供有关在符号中对数据进行编码所使用的参考的详细信息。当前实现包含所有已知的字符集编码。不受 MicroQR 支持。 |
| [get_EncodeGS1SeparatorInByteMode](./get_encodegs1separatorinbytemode/)() const |  |
| [get_EncodeMode](./get_encodemode/)() const | QR 符号类型为 [BarCode](../../aspose.barcode/) 的编码模式。默认值: [QREncodeMode.Auto](../aztecencodemode/)。 |
| [get_ErrorLevel](./get_errorlevel/)() const | QR、MicroQR 和 RectMicroQR 条码的 Reed-Solomon 错误纠正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。参见 QRErrorLevel。 |
| [get_MicroQRVersion](./get_microqrversion/)() const | MicroQR 码的版本。从 M1 版到 M4 版。默认值为 [MicroQRVersion.Auto](../aztecencodemode/)。 |
| [get_RectMicroQrVersion](./get_rectmicroqrversion/)() const | RectMicroQR 码的版本。从 R7x59 版到 R17x139 版。默认值为 [RectMicroQRVersion.Auto](../aztecencodemode/)。 |
| [get_StructuredAppend](./get_structuredappend/)() const | QR 结构化追加参数。MicroQR 和 RectMicroQR 条码不支持结构化追加模式。 |
| [get_Version](./get_version/)() const | QR 码的版本。从 Version1 到 Version40。默认值为 [QRVersion.Auto](../aztecencodemode/)。 |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) 模块的高/宽比。 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | 扩展信道解释标识符。它用于向条码阅读器提供有关在符号中对数据进行编码所使用的参考的详细信息。当前实现包含所有已知的字符集编码。不受 MicroQR 支持。 |
| [set_EncodeGS1SeparatorInByteMode](./set_encodegs1separatorinbytemode/)(bool) |  |
| [set_EncodeMode](./set_encodemode/)(QREncodeMode) | QR 符号类型为 [BarCode](../../aspose.barcode/) 的编码模式。默认值: [QREncodeMode.Auto](../aztecencodemode/)。 |
| [set_ErrorLevel](./set_errorlevel/)(QRErrorLevel) | QR、MicroQR 和 RectMicroQR 条码的 Reed-Solomon 错误纠正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。参见 QRErrorLevel。 |
| [set_MicroQRVersion](./set_microqrversion/)(Aspose::BarCode::Generation::MicroQRVersion) | MicroQR 码的版本。从 M1 版到 M4 版。默认值为 [MicroQRVersion.Auto](../aztecencodemode/)。 |
| [set_RectMicroQrVersion](./set_rectmicroqrversion/)(RectMicroQRVersion) | RectMicroQR 码的版本。从 R7x59 版到 R17x139 版。默认值为 [RectMicroQRVersion.Auto](../aztecencodemode/)。 |
| [set_StructuredAppend](./set_structuredappend/)(System::SharedPtr\<QrStructuredAppendParameters\>) | QR 结构化追加参数。MicroQR 和 RectMicroQR 条码不支持结构化追加模式。 |
| [set_Version](./set_version/)(QRVersion) | QR 码的版本。从 Version1 到 Version40。默认值为 [QRVersion.Auto](../aztecencodemode/)。 |
| [ToString](./tostring/)() const override | 返回此 [QrParameters](./) 的可读字符串表示。 |
## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
