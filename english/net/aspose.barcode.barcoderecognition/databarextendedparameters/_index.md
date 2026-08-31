---
title: Class DataBarExtendedParameters
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.DataBarExtendedParameters class. Stores a DataBar additional information of recognized barcode
type: docs
weight: 210
url: /net/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class

Stores a DataBar additional information of recognized barcode

```csharp
public sealed class DataBarExtendedParameters : BaseExtendedParameters
```

## Properties

| Name | Description |
| --- | --- |
| [Is2DCompositeComponent](../../aspose.barcode.barcoderecognition/databarextendedparameters/is2dcompositecomponent/) { get; } | Gets the DataBar 2D composite component flag. Default value is false. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Tests whether all parameters has only default values |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/databarextendedparameters/equals/)(object) | Returns a value indicating whether this instance is equal to a specified `DataBarExtendedParameters` value. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/databarextendedparameters/gethashcode/)() | Returns the hash code for this instance. |
| override [ToString](../../aspose.barcode.barcoderecognition/databarextendedparameters/tostring/)() | Returns a human-readable string representation of this `DataBarExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_equality/) | Returns a value indicating whether the first `DataBarExtendedParameters` value is equal to the second. |
| [operator !=](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_inequality/) | Returns a value indicating if the first `DataBarExtendedParameters` value is different from the second. |

## Examples

This sample shows how to get DataBar additional information

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

### See Also

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


