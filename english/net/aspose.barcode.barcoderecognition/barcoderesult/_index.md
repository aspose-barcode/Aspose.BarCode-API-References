---
title: Class BarCodeResult
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.BarCodeResult class. Stores recognized barcode data like SingleDecodeType type String codetext BarCodeRegionParameters region and other parameters
type: docs
weight: 100
url: /net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

Stores recognized barcode data like [`SingleDecodeType`](../singledecodetype/) type, String codetext, [`BarCodeRegionParameters`](../barcoderegionparameters/) region and other parameters

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## Constructors

| Name | Description |
| --- | --- |
| [BarCodeResult](barcoderesult/)(BarCodeResult) | Creates a a copy of the `BarCodeResult` class. |

## Properties

| Name | Description |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes/) { get; } | Gets the encoded code bytes |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext/) { get; } | Gets the code text |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype/) { get; } | Gets the barcode type |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename/) { get; } | Gets the name of the barcode type |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence/) { get; } | Gets recognition confidence level of the recognized barcode |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended/) { get; } | Gets extended parameters of recognized barcode |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality/) { get; } | Gets the reading quality. Works for 1D and postal barcodes. |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region/) { get; } | Gets the barcode region |

## Methods

| Name | Description |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone/)() | Creates a copy of `BarCodeResult` class. |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals)(BarCodeResult) | Returns a value indicating whether this instance is equal to a specified `BarCodeResult` value. |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals_1)(object) | Returns a value indicating whether this instance is equal to a specified `BarCodeResult` value. |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext/)(Encoding) | Gets the code text with encoding. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode/)() | Returns the hash code for this instance. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring/)() | Returns a human-readable string representation of this `BarCodeResult`. |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality/) | Returns a value indicating whether the first `BarCodeResult` value is equal to the second. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality/) | Returns a value indicating if the first `BarCodeResult` value is different from the second. |

## Examples

This sample shows how to obtain BarCodeResult.

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

### See Also

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


