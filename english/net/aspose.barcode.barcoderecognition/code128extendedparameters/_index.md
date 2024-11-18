---
title: Class Code128ExtendedParameters
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.Code128ExtendedParameters class. Stores special data of Code128 recognized barcode
type: docs
weight: 180
url: /net/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class

Stores special data of Code128 recognized barcode

Represents the recognized barcode's region and barcode angle

```csharp
public sealed class Code128ExtendedParameters : BaseExtendedParameters
```

## Properties

| Name | Description |
| --- | --- |
| [Code128DataPortions](../../aspose.barcode.barcoderecognition/code128extendedparameters/code128dataportions/) { get; } | Gets [`Code128DataPortion`](../code128dataportion/) array of recognized Code128 barcode |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Tests whether all parameters has only default values |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/code128extendedparameters/equals/)(object) | Returns a value indicating whether this instance is equal to a specified `Code128ExtendedParameters` value. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/code128extendedparameters/gethashcode/)() | Returns the hash code for this instance. |
| override [ToString](../../aspose.barcode.barcoderecognition/code128extendedparameters/tostring/)() | Returns a human-readable string representation of this `Code128ExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/code128extendedparameters/op_equality/) | Returns a value indicating whether the first `Code128ExtendedParameters` value is equal to the second. |
| [operator !=](../../aspose.barcode.barcoderecognition/code128extendedparameters/op_inequality/) | Returns a value indicating if the first `Code128ExtendedParameters` value is different from the second. |

## Examples

This sample shows how to get code128 raw values

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

### See Also

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


