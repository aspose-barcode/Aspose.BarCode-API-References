---
title: "枚举 AztecSymbolMode"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.AztecSymbolMode 枚举。指定 Aztec 符号模式"
type: docs
weight: 970
url: /zh/net/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enumeration

指定 Aztec 符号模式。

```csharp
public enum AztecSymbolMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | `0` | 指定自动为 Aztec 选择最佳符号（紧凑或全范围）。这是默认值。 |
| Compact | `1` | 指定 Aztec 的紧凑符号。Aztec 紧凑符号仅允许 1、2、3 或 4 层。 |
| FullRange | `2` | 指定 Aztec 的全范围符号。Aztec 全范围符号允许 1 到 32 层。 |
| Rune | `3` | 指定 Aztec 的符文符号。Aztec 符文是一系列小但独特的机器可读标记。它仅允许 0 到 255 的数值。 |

## 示例

此示例展示如何更改 Aztec 符号模式并保存条形码图像。

```csharp
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

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


