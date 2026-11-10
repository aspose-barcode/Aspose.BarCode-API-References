---
title: "类 BarcodeGenerator"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.BarcodeGenerator 类。BarcodeGenerator 用于后端条形码图像生成"
type: docs
weight: 1000
url: /zh/net/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class

用于后端条形码图像生成的 BarcodeGenerator。

支持的符号集：1D：Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D：Aztec, DataMatrix, PDf417, QR code ...

```csharp
public sealed class BarcodeGenerator : Component
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BarcodeGenerator](barcodegenerator/#constructor)(BaseEncodeType) | 创建 BarcodeGenerator 的实例。 |
| [BarcodeGenerator](barcodegenerator/#constructor_1)(BaseEncodeType, string) | 创建 BarcodeGenerator 的实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BarcodeType](../../aspose.barcode.generation/barcodegenerator/barcodetype/) { get; set; } | 条形码符号类型。 |
| [CodeText](../../aspose.barcode.generation/barcodegenerator/codetext/) { get; set; } | 要编码的文本。 |
| [Parameters](../../aspose.barcode.generation/barcodegenerator/parameters/) { get; } | 生成参数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml)(Stream) | 从指定的 xml-stream 导入 BarCode 属性并创建 BarcodeGenerator 实例。 |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml_1)(string) | 从指定的 xml-file 导入 BarCode 属性并创建 BarcodeGenerator 实例。 |
| [DrawWpf](../../aspose.barcode.generation/barcodegenerator/drawwpf/)(DrawingContext) | 在 WPF 画布上绘制条形码图像。 |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml)(Stream) | 将 BarCode 属性导出到指定的 xml 流 |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml_1)(string) | 将 BarCode 属性导出到指定的 xml 文件 |
| [GenerateBarCodeImage](../../aspose.barcode.generation/barcodegenerator/generatebarcodeimage/)() | 根据当前设置生成条形码图像。 |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_1)(string) | 将条形码图像保存到指定文件。 |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save)(Stream, BarCodeImageFormat) | 以特定格式将条形码图像保存到流中。 |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_2)(string, BarCodeImageFormat) | 以特定格式将条形码图像保存到指定文件。 |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext)(byte[]) | 将 codetext 设置为字节序列。 |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_1)(string, Encoding) | 使用指定的 **encoding** 将 Unicode **codeText** 编码为字节序列。UTF-8 是最常用的编码。如果该编码支持，函数会自动插入 [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding)。 |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_2)(string, Encoding, bool) | 使用指定的 **encoding** 将 Unicode **codeText** 编码为字节序列。UTF-8 是最常用的编码。如果该编码支持且 **insertBOM** 被设置为 `true`，函数会包含一个 [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding)。 |

## 示例

此示例展示了如何创建并保存条形码图像。

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


