---
title: "类 GS1DigitalLink"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.ComplexBarcode.GS1DigitalLink 类。表示用于编码和解码的 GS1 Digital Link 代码文本，作为有序的应用标识符元素序列。保留源顺序和重复的应用标识符。构建的代码文本是未压缩的 GS1 Digital Link URI。解析时会忽略非 GS1 查询参数和 URI 片段。"
type: docs
weight: 540
url: /zh/net/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class

表示用于编码和解码的 GS1 Digital Link 代码文本，作为 Application Identifier 元素的有序序列。保留源顺序和重复的 Application Identifier。构建的代码文本是未压缩的 GS1 Digital Link URI。解析时会忽略非 GS1 的查询参数和 URI 片段。

```csharp
public sealed class GS1DigitalLink : IComplexCodetext
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GS1DigitalLink](gs1digitallink/#constructor)(string) | 使用指定的 URI 主干初始化一个空的 GS1 Digital Link。当恰好存在一个主键候选时，主键会自动选择。 |
| [GS1DigitalLink](gs1digitallink/#constructor_1)(string, string) | 使用指定的 URI 主干和主键初始化一个空的 GS1 Digital Link。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/barcodetype/) { get; set; } | 获取或设置用于编码此 GS1 Digital Link 的条形码类型。支持的类型有 QR、DataMatrix、Aztec、Pdf417、MicroPdf417、DotCode、HanXin、CodablockF 和 Code128。默认值为 QR。 |
| [Count](../../aspose.barcode.complexbarcode/gs1digitallink/count/) { get; } | 获取 Application Identifier 元素的数量。 |
| [Elements](../../aspose.barcode.complexbarcode/gs1digitallink/elements/) { get; } | 获取所有元素的副本，按源顺序排列。 |
| [Item](../../aspose.barcode.complexbarcode/gs1digitallink/item/) { get; } | 按有序序列中的位置获取元素。 |
| [PrimaryApplicationIdentifier](../../aspose.barcode.complexbarcode/gs1digitallink/primaryapplicationidentifier/) { get; } | 获取用作 Digital Link 主键的 Application Identifier。Null 表示在构建 URI 时自动选择主键。 |
| [UriStem](../../aspose.barcode.complexbarcode/gs1digitallink/uristem/) { get; } | 获取在 GS1 主键路径段之前的绝对 URI 前缀。该前缀不包含查询字符串或片段。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create)(string, GS1Codetext) | 通过从 GS1 codetext 复制所有元素并选择唯一可用的主键来创建 GS1 Digital Link。 |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create_1)(string, GS1Codetext, string) | 通过从 GS1 codetext 复制所有元素并使用指定的主键来创建 GS1 Digital Link。 |
| static [Parse](../../aspose.barcode.complexbarcode/gs1digitallink/parse/)(string) | 解析未压缩的 GS1 Digital Link URI。 |
| [Add](../../aspose.barcode.complexbarcode/gs1digitallink/add/)(string, string) | 追加已验证的 Application Identifier 元素。 |
| [GetAll](../../aspose.barcode.complexbarcode/gs1digitallink/getall/)(string) | 按源顺序获取 Application Identifier 的所有值。 |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/getbarcodetype/)() | 获取用于编码此 GS1 Digital Link 的条形码类型。 |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1digitallink/getconstructedcodetext/)() | 构建未压缩的 GS1 Digital Link URI。 |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1digitallink/getfirst/)(string) | 获取 Application Identifier 的第一个值。 |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1digitallink/initfromstring/)(string) | 从未压缩的 GS1 Digital Link URI 初始化此实例。仅在成功解析提供的 URI 后才会替换现有状态。所选的条形码类型将被保留。 |
| [ToGS1Codetext](../../aspose.barcode.complexbarcode/gs1digitallink/togs1codetext/)() | 创建一个独立的 GS1 codetext，包含当前的 GS1 元素。不包括仅限 URI 的信息。 |
| override [ToString](../../aspose.barcode.complexbarcode/gs1digitallink/tostring/)() | 返回未压缩的 GS1 Digital Link URI。 |
| [ToUriString](../../aspose.barcode.complexbarcode/gs1digitallink/touristring/)() | 将当前对象状态格式化为未压缩的 GS1 Digital Link URI。 |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1digitallink/tryparse/)(string, out GS1DigitalLink, out GS1ValidationResult) | 尝试解析未压缩的 GS1 Digital Link URI 并返回结构化的验证错误。 |
| static [Validate](../../aspose.barcode.complexbarcode/gs1digitallink/validate/)(string) | 在不构建对象的情况下验证未压缩的 GS1 Digital Link URI。 |

### 另见

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


