---
title: Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters class
linktitle: DataBarExtendedParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters class. Stores a DataBar additional information of recognized barcode in C++.'
type: docs
weight: 1400
url: /cpp/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class


Stores a DataBar additional information of recognized barcode

```cpp
class DataBarExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Description |
| --- | --- |
| [get_Is2DCompositeComponent](./get_is2dcompositecomponent/)() | Gets the DataBar 2D composite component flag. Default value is false. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() | **Tests** whether all parameters has only default values |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [DataBarExtendedParameters](./). |
## Remarks


This sample shows how to get DataBar additional information 
```cpp
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

## See Also

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
