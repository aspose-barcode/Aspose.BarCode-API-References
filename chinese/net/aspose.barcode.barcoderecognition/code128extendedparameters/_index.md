---
title: "类 Code128ExtendedParameters"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.Code128ExtendedParameters 类。存储 Code128 识别条码的特殊数据。"
type: docs
weight: 180
url: /zh/net/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class

存储已识别 Code128 条码的特殊数据。

表示已识别条码的区域和条码角度。

```csharp
public sealed class Code128ExtendedParameters : BaseExtendedParameters
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Code128DataPortions](../../aspose.barcode.barcoderecognition/code128extendedparameters/code128dataportions/) { get; } | 获取已识别 Code128 条码的 [`Code128DataPortion`](../code128dataportion/) 数组 |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | 测试所有参数是否仅具有默认值 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/code128extendedparameters/equals/)(object) | 返回一个值，指示此实例是否等于指定的 `Code128ExtendedParameters` 值。 |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/code128extendedparameters/gethashcode/)() | 返回此实例的哈希码。 |
| override [ToString](../../aspose.barcode.barcoderecognition/code128extendedparameters/tostring/)() | 返回此 `Code128ExtendedParameters` 的可读字符串表示。 |
| [operator ==](../../aspose.barcode.barcoderecognition/code128extendedparameters/op_equality/) | 返回一个值，指示第一个 `Code128ExtendedParameters` 值是否等于第二个。 |
| [operator !=](../../aspose.barcode.barcoderecognition/code128extendedparameters/op_inequality/) | 返回一个值，指示第一个 `Code128ExtendedParameters` 值是否不同于第二个。 |

## 示例

此示例展示了如何获取 code128 原始值

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128)
    Next
End Using
```

### 另见

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


