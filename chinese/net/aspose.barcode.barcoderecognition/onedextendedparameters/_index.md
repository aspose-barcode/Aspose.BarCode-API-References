---
title: "类 OneDExtendedParameters"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.OneDExtendedParameters 类。存储 1D 识别条码的特殊数据，如单独的代码文本和校验和。"
type: docs
weight: 330
url: /zh/net/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class

存储已识别的 1D 条形码的特殊数据，例如独立的代码文本和校验和

```csharp
public sealed class OneDExtendedParameters : BaseExtendedParameters
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CheckSum](../../aspose.barcode.barcoderecognition/onedextendedparameters/checksum/) { get; } | 获取 1D 条码的校验和。 |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | 测试所有参数是否仅具有默认值 |
| [Value](../../aspose.barcode.barcoderecognition/onedextendedparameters/value/) { get; } | 获取 1D 条码的代码文本（不含校验和）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/onedextendedparameters/equals/)(object) | 返回一个值，指示此实例是否等于指定的 `OneDExtendedParameters` 值。 |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/onedextendedparameters/gethashcode/)() | 返回此实例的哈希码。 |
| override [ToString](../../aspose.barcode.barcoderecognition/onedextendedparameters/tostring/)() | 返回此 `OneDExtendedParameters` 的可读字符串表示。 |
| [operator ==](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_equality/) | 返回一个值，指示第一个 `OneDExtendedParameters` 值是否等于第二个。 |
| [operator !=](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_inequality/) | 返回一个值，指示第一个 `OneDExtendedParameters` 值是否不同于第二个。 |

## 示例

此示例展示了如何获取 1D 条码的值和校验和

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

### 另见

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


