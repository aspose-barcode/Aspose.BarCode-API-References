---
title: Class QRExtendedParameters
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.QRExtendedParameters class. Stores a QR Structured Append information of recognized barcode
type: docs
weight: 280
url: /net/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class

Stores a QR Structured Append information of recognized barcode

```csharp
public sealed class QRExtendedParameters : BaseExtendedParameters
```

## Properties

| Name | Description |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Tests whether all parameters has only default values |
| [QRStructuredAppendModeBarCodeIndex](../../aspose.barcode.barcoderecognition/qrextendedparameters/qrstructuredappendmodebarcodeindex/) { get; } | Gets the index of the QR structured append mode barcode. Index starts from 0. Default value is -1. |
| [QRStructuredAppendModeBarCodesQuantity](../../aspose.barcode.barcoderecognition/qrextendedparameters/qrstructuredappendmodebarcodesquantity/) { get; } | Gets the QR structured append mode barcodes quantity. Default value is -1. |
| [QRStructuredAppendModeParityData](../../aspose.barcode.barcoderecognition/qrextendedparameters/qrstructuredappendmodeparitydata/) { get; } | Gets the QR structured append mode parity data. Default value is -1. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/qrextendedparameters/equals/)(object) | Returns a value indicating whether this instance is equal to a specified `QRExtendedParameters` value. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/qrextendedparameters/gethashcode/)() | Returns the hash code for this instance. |
| override [ToString](../../aspose.barcode.barcoderecognition/qrextendedparameters/tostring/)() | Returns a human-readable string representation of this `QRExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_equality/) | Returns a value indicating whether the first `QRExtendedParameters` value is equal to the second. |
| [operator !=](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_inequality/) | Returns a value indicating if the first `QRExtendedParameters` value is different from the second. |

## Examples

This sample shows how to get QR Structured Append data

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

### See Also

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


