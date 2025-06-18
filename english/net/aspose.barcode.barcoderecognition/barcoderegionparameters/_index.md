---
title: Class BarCodeRegionParameters
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.BarCodeRegionParameters class. Represents the recognized barcodes region and barcode angle
type: docs
weight: 90
url: /net/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class

Represents the recognized barcode's region and barcode angle

```csharp
public sealed class BarCodeRegionParameters
```

## Properties

| Name | Description |
| --- | --- |
| [Angle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/angle/) { get; } | Gets the angle of the barcode (0-360). |
| [Points](../../aspose.barcode.barcoderecognition/barcoderegionparameters/points/) { get; } | Gets Points array bounding barcode region |
| [Quadrangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/quadrangle/) { get; } | Gets [`Quadrangle`](../quadrangle/) bounding barcode region |
| [Rectangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/rectangle/) { get; } | Gets Rectangle bounding barcode region |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderegionparameters/equals/)(object) | Returns a value indicating whether this instance is equal to a specified `BarCodeRegionParameters` value. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderegionparameters/gethashcode/)() | Returns the hash code for this instance. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderegionparameters/tostring/)() | Returns a human-readable string representation of this `BarCodeRegionParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_equality/) | Returns a value indicating whether the first `BarCodeRegionParameters` value is equal to the second. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_inequality/) | Returns a value indicating if the first `BarCodeRegionParameters` value is different from the second. |

## Examples

This sample shows how to get barcode Angle and bounding quadrangle values

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

### See Also

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


