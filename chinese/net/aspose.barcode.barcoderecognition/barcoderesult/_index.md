---
title: "类 BarCodeResult"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeResult 类。存储已识别的条形码数据，如 SingleDecodeType 类型、字符串 codetext、BarCodeRegionParameters 区域以及其他参数。"
type: docs
weight: 100
url: /zh/net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

存储已识别的条形码数据，如 [`SingleDecodeType`](../singledecodetype/) 类型、String codetext、[`BarCodeRegionParameters`](../barcoderegionparameters/) 区域以及其他参数。

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BarCodeResult](barcoderesult/)(BarCodeResult) | 创建 `BarCodeResult` 类的副本。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes/) { get; } | 获取已编码的代码字节 |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext/) { get; } | 获取代码文本 |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype/) { get; } | 获取条形码类型 |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename/) { get; } | 获取条形码类型的名称 |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence/) { get; } | 获取已识别条形码的识别置信度水平 |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended/) { get; } | 获取已识别条形码的扩展参数 |
| [IsoSymbolQuality](../../aspose.barcode.barcoderecognition/barcoderesult/isosymbolquality/) { get; } | 获取已识别条形码的 ISO/IEC 符号质量评估结果。 |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality/) { get; } | 获取读取质量。适用于 1D 和邮政条形码。 |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region/) { get; } | 获取条形码区域 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone/)() | 创建 `BarCodeResult` 类的副本。 |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals)(BarCodeResult) | 返回一个值，指示此实例是否等于指定的 `BarCodeResult` 值。 |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals_1)(object) | 返回一个值，指示此实例是否等于指定的 `BarCodeResult` 值。 |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext/)(Encoding) | 获取带编码的代码文本。 |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode/)() | 返回此实例的哈希码。 |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring/)() | 返回此 `BarCodeResult` 的可读字符串表示形式。 |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality/) | 返回一个值，指示第一个 `BarCodeResult` 值是否等于第二个。 |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality/) | 返回一个值，指示第一个 `BarCodeResult` 值是否不同于第二个。 |

## 示例

此示例展示如何获取 BarCodeResult。

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

### 另见

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


