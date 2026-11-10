---
title: "类 QRExtendedParameters"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.QRExtendedParameters 类。存储已识别条码的 QR 结构化追加信息"
type: docs
weight: 350
url: /zh/net/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class

存储已识别的条形码的 QR 结构化追加信息

```csharp
public sealed class QRExtendedParameters : BaseExtendedParameters
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ErrorLevel](../../aspose.barcode.barcoderecognition/qrextendedparameters/errorlevel/) { get; } | 已识别条码的 Reed-Solomon 错误纠正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。 |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | 测试所有参数是否仅具有默认值 |
| [MicroQRVersion](../../aspose.barcode.barcoderecognition/qrextendedparameters/microqrversion/) { get; } | 已识别 MicroQR 码的版本。从 M1 到 M4。 |
| [RectMicroQRVersion](../../aspose.barcode.barcoderecognition/qrextendedparameters/rectmicroqrversion/) { get; } | 已识别 RectMicroQR 码的版本。从 R7x43 到 R17x139。 |
| [StructuredAppendModeBarCodeIndex](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodebarcodeindex/) { get; } | 获取 QR 结构化追加模式条码的索引。索引从 0 开始。默认值为 -1。 |
| [StructuredAppendModeBarCodesQuantity](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodebarcodesquantity/) { get; } | 获取 QR 结构化追加模式条码的数量。默认值为 -1。 |
| [StructuredAppendModeParityData](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodeparitydata/) { get; } | 获取 QR 结构化追加模式的奇偶校验数据。默认值为 -1。 |
| [Version](../../aspose.barcode.barcoderecognition/qrextendedparameters/version/) { get; } | 已识别 QR 码的版本。从 Version1 到 Version40。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/qrextendedparameters/equals/)(object) | 返回一个值，指示此实例是否等于指定的 `QRExtendedParameters` 值。 |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/qrextendedparameters/gethashcode/)() | 返回此实例的哈希码。 |
| override [ToString](../../aspose.barcode.barcoderecognition/qrextendedparameters/tostring/)() | 返回此 `QRExtendedParameters` 的人类可读字符串表示。 |
| [operator ==](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_equality/) | 返回一个值，指示第一个 `QRExtendedParameters` 值是否等于第二个。 |
| [operator !=](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_inequality/) | 返回一个值，指示第一个 `QRExtendedParameters` 值是否不同于第二个。 |

## 示例

此示例展示如何获取 QR Structured Append 数据

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex);
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex)
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData)
    Next
End Using
```

### 另见

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


