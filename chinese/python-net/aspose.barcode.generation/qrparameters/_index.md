---
title: "QrParameters"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.generation/qrparameters/
---

## QrParameters class

QR 参数。

QrParameters 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| eci_encoding | 扩展通道解释标识符。它用于向条码阅读器提供有关在符号中对数据进行编码所使用的引用的详细信息。<br/>            当前实现包含所有已知的字符集编码。<br/>            MicroQR 不支持。 |
| encode_mode | QR 符号类型，表示 BarCode 的编码模式。<br/>            默认值：QREncodeMode.Auto. |
| error_level | QR、MicroQR 和 RectMicroQR 条码的 Reed-Solomon 错误更正级别。<br/>             从低到高：LevelL、LevelM、LevelQ、LevelH。参见 QRErrorLevel。 |
| version | QR 码的版本。从 Version1 到 Version40。<br/>            默认值为 QRVersion.Auto。 |
| micro_qr_version | MicroQR 码的版本。从 M1 版到 M4 版。<br/>            默认值为 MicroQRVersion.Auto。 |
| rect_micro_qr_version | RectMicroQR 码的版本。从 R7x59 版到 R17x139 版。<br/>            默认值为 RectMicroQRVersion.Auto。 |
| aspect_ratio | 2D 条码模块的高/宽比例。 |
| structured_append | QR 结构化追加参数。<br/>            MicroQR 和 RectMicroQR 条码不支持结构化追加模式。 |
| encode_gs1_separator_in_byte_mode |  |

### 另见

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

