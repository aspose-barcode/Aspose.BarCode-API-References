---
title: "类 DataBarExtendedParameters"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.DataBarExtendedParameters 类。存储已识别条形码的 DataBar 附加信息"
type: docs
weight: 210
url: /zh/net/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class

存储已识别条码的 DataBar 附加信息。

```csharp
public sealed class DataBarExtendedParameters : BaseExtendedParameters
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Is2DCompositeComponent](../../aspose.barcode.barcoderecognition/databarextendedparameters/is2dcompositecomponent/) { get; } | 获取 DataBar 2D 复合组件标志。默认值为 false。 |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | 测试所有参数是否仅具有默认值 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/databarextendedparameters/equals/)(object) | 返回一个值，指示此实例是否等于指定的 `DataBarExtendedParameters` 值。 |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/databarextendedparameters/gethashcode/)() | 返回此实例的哈希码。 |
| override [ToString](../../aspose.barcode.barcoderecognition/databarextendedparameters/tostring/)() | 返回此 `DataBarExtendedParameters` 的可读字符串表示。 |
| [operator ==](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_equality/) | 返回一个值，指示第一个 `DataBarExtendedParameters` 值是否等于第二个。 |
| [operator !=](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_inequality/) | 返回一个值，指示第一个 `DataBarExtendedParameters` 值是否不同于第二个。 |

## 示例

此示例展示如何获取 DataBar 附加信息

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DatabarOmniDirectional))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.DatabarOmniDirectional)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
    Next
End Using
```

### 另见

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


