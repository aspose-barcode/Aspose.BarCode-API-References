---
title: "类 GS1Codetext"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.ComplexBarcode.GS1Codetext 类。表示用于编码和解码的 GS1 codetext，作为 Application Identifier 元素的有序序列。保留源顺序和重复的 Application Identifier。括号表示形式为 AIvalueAIvalue。值内部的字面左括号 必须写成 \\(，这是唯一支持的转义序列。值内部的右括号 ) 不需要转义。"
type: docs
weight: 530
url: /zh/net/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class

表示用于编码和解码的 GS1 代码文本，作为 Application Identifier 元素的有序序列。保留源顺序和重复的 Application Identifier。括号表示形式为 (AI)value(AI)value。值内部的字面左括号 '(' 必须写成 \(；这是唯一支持的转义序列。值内部的右括号 ')' 无需转义。

```csharp
public sealed class GS1Codetext : IComplexCodetext
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GS1Codetext](gs1codetext/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/barcodetype/) { get; set; } | 获取或设置用于编码此 GS1 codetext 的条形码类型。支持的类型有 GS1Aztec、GS1CodablockF、GS1Code128、GS1DataMatrix、GS1DotCode、GS1HanXin、GS1MicroPdf417、GS1QR 和 GS1 DataBar 类型。默认值为 GS1Code128。 |
| [Count](../../aspose.barcode.complexbarcode/gs1codetext/count/) { get; } | 获取 Application Identifier 元素的数量。 |
| [Elements](../../aspose.barcode.complexbarcode/gs1codetext/elements/) { get; } | 获取所有元素的副本，按源顺序排列。 |
| [Item](../../aspose.barcode.complexbarcode/gs1codetext/item/) { get; } | 按有序序列中的位置获取元素。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Parse](../../aspose.barcode.complexbarcode/gs1codetext/parse/)(string) | 解析形式为 (AI)value(AI)value 的括号 GS1 元素字符串。值内部的字面 '(' 必须写成 \(；不支持其他转义序列，')' 不需要转义。 |
| [Add](../../aspose.barcode.complexbarcode/gs1codetext/add/)(string, string) | 追加已验证的 Application Identifier 元素。 |
| [GetAll](../../aspose.barcode.complexbarcode/gs1codetext/getall/)(string) | 按源顺序获取 Application Identifier 的所有值。 |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/getbarcodetype/)() | 获取用于编码此 GS1 codetext 的条形码类型。 |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1codetext/getconstructedcodetext/)() | 构造括号形式的 GS1 代码文本，格式为 (AI)value(AI)value。值中的字面左括号需转义为 \\(.。 |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1codetext/getfirst/)(string) | 获取 Application Identifier 的第一个值。 |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1codetext/initfromstring/)(string) | 根据括号形式的 GS1 代码文本（格式为 (AI)value(AI)value）初始化此实例。仅在成功解析提供的代码文本后才会替换现有元素。 |
| override [ToString](../../aspose.barcode.complexbarcode/gs1codetext/tostring/)() | 返回括号形式的 GS1 表示，格式为 (AI)value(AI)value。 |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1codetext/tryparse/)(string, out GS1Codetext, out GS1ValidationResult) | 尝试解析括号形式的 GS1 元素字符串（格式为 (AI)value(AI)value），并返回结构化的验证错误。值中的字面 '(' 必须写成 \\(; 不支持其他转义序列，')' 不需要转义。 |
| static [Validate](../../aspose.barcode.complexbarcode/gs1codetext/validate/)(string) | 在不构建对象的情况下验证括号形式的 GS1 元素字符串（格式为 (AI)value(AI)value）。值中的字面 '(' 必须写成 \\(; 不支持其他转义序列，')' 不需要转义。 |

### 另见

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


