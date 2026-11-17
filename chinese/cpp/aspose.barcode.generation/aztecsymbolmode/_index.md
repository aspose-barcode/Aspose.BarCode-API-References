---
title: "枚举"
linktitle: "AztecSymbolMode"
second_title: "Aspose.BarCode for C++ API 参考"
description: "枚举。指定 C++ 中的 Aztec 符号模式。"
type: docs
weight: 5400
url: /zh/cpp/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enum


指定 Aztec 符号模式。

```cpp
enum class AztecSymbolMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| 自动 | 0 | 指定自动为 Aztec 选择最佳符号（Compact 或 Full-range）。这是默认值。 |
| Compact | 1 | 指定 Aztec 的 Compact 符号。Aztec Compact 符号仅允许 1、2、3 或 4 层。 |
| FullRange | 2 | 指定 Aztec 的 Full-range 符号。Aztec Full-range 符号允许 1 到 32 层。 |
| Rune | 3 | 指定 Aztec 的 Rune 符号。Aztec Runes 是一系列小而独特的机器可读标记。它仅允许 0 到 255 的数值。 |

## 备注


此示例展示了如何更改 Aztec Symbol 模式并保存 [BarCode](../../aspose.barcode/) 图像。
```cpp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.CodeText = "125";
    generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune;
    generator.Save("test.png");
}
    [VB.NET]
    Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec)
        generator.CodeText = "125"
        generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune
        generator.Save("test.png")
    End Using
```

## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
