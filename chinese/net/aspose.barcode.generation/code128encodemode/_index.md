---
title: "Code128EncodeMode 枚举"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.Code128EncodeMode 枚举。Code128 条形码的编码模式。Code 128 规范"
type: docs
weight: 1120
url: /zh/net/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enumeration

Code128 条形码的编码模式。[Code 128](https://en.wikipedia.org/wiki/Code_128) 规范。

```csharp
public enum Code128EncodeMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | `0` | 在经典 ISO 15417 模式下编码代码文本。该模式应在所有普通情况下使用。 |
| CodeA | `1` | 仅在 128A 代码集下编码代码文本。 |
| CodeB | `2` | 仅在 128B 代码集下编码代码文本。 |
| CodeC | `4` | 仅在 128C 代码集下编码代码文本。 |
| CodeAB | `3` | 仅在 128A 和 128B 代码集下编码代码文本。 |
| CodeAC | `5` | 仅在 128A 和 128C 代码集下编码代码文本。 |
| CodeBC | `6` | 仅在 128B 和 128C 代码集下编码代码文本。 |

## 示例

此代码演示如何使用不同的编码生成 Code 128

```csharp
[C#]
//使用 ISO 15417 编码生成 Code 128
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//仅使用 A 代码集编码生成 Code 128
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


