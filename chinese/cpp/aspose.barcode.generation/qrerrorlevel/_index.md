---
title: "枚举"
linktitle: "QRErrorLevel"
second_title: "Aspose.BarCode for C++ API 参考"
description: "枚举。Reed-Solomon 错误校正的级别。从低到高：LevelL、LevelM、LevelQ、LevelH（C++ 中）。"
type: docs
weight: 8200
url: /zh/cpp/aspose.barcode.generation/qrerrorlevel/
---
## QRErrorLevel enum


Reed-Solomon 错误纠正的级别。从低到高：LevelL、LevelM、LevelQ、LevelH。

```cpp
enum class QRErrorLevel
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| LevelL | 0 | 错误校正 Level L 可应用于 QR 和 MicroQR 条码。允许恢复 7% 的代码文本。 |
| LevelM | 1 | 错误校正 Level M 可应用于 QR 条码、RectMicroQR 条码以及版本为 M2 到 M4 的 MicroQR 条码。允许恢复 15% 的代码文本。 |
| LevelQ | 2 | 错误校正 Level Q 可应用于 QR 条码和版本为 M4 的 MicroQR 条码。允许恢复 25% 的代码文本。 |
| LevelH | 3 | 错误校正 Level H 可应用于 QR 和 RectMicroQR 条码。允许恢复 30% 的代码文本。 |

## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
