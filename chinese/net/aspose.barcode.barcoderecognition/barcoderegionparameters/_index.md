---
title: "类 BarCodeRegionParameters"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeRegionParameters 类。表示已识别条形码的区域和条形码角度"
type: docs
weight: 90
url: /zh/net/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class

表示已识别条码的区域和条码角度。

```csharp
public sealed class BarCodeRegionParameters
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Angle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/angle/) { get; } | 获取条形码的角度（0-360）。 |
| [Points](../../aspose.barcode.barcoderecognition/barcoderegionparameters/points/) { get; } | 获取界定条形码区域的 Points 数组 |
| [Quadrangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/quadrangle/) { get; } | 获取界定条形码区域的 [`Quadrangle`](../quadrangle/) |
| [Rectangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/rectangle/) { get; } | 获取界定条形码区域的 Rectangle |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderegionparameters/equals/)(object) | 返回一个值，指示此实例是否等于指定的 `BarCodeRegionParameters` 值。 |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderegionparameters/gethashcode/)() | 返回此实例的哈希码。 |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderegionparameters/tostring/)() | 返回此 `BarCodeRegionParameters` 的人类可读字符串表示。 |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_equality/) | 返回一个值，指示第一个 `BarCodeRegionParameters` 值是否等于第二个。 |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_inequality/) | 返回一个值，指示第一个 `BarCodeRegionParameters` 值是否不同于第二个。 |

## 示例

此示例展示如何获取条形码角度和界定四边形的值

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
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle)
    Next
End Using
```

### 另见

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


