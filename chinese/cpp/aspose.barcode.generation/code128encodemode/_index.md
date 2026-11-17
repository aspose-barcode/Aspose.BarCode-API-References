---
title: "枚举"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode for C++ API 参考"
description: "枚举。用于 Code128 条形码的编码模式。C++ 中的 Code 128 规范。"
type: docs
weight: 5900
url: /zh/cpp/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enum


Code128 条码的编码模式。Code 128

规范。

```cpp
enum class Code128EncodeMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| 自动 | 0 | 在经典的 ISO 15417 模式下编码代码文本。该模式应在所有常规情况下使用。 |
| CodeA | 1 | 仅在 128A 代码集编码代码文本。 |
| CodeB | 2 | 仅在 128B 代码集编码代码文本。 |
| CodeC | 4 | 仅在 128C 代码集编码代码文本。 |
| CodeAB | 3 | 仅在 128A 和 128B 代码集编码代码文本。 |
| CodeAC | 5 | 仅在 128A 和 128C 代码集编码代码文本。 |
| CodeBC | 6 | 仅在 128B 和 128C 代码集编码代码文本。 |

## 备注


此代码演示了如何使用不同的编码生成 Code 128。
```cpp
[C#]
//使用 ISO 15417 编码生成 Code 128。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//仅使用代码集 A 编码生成 Code 128。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
