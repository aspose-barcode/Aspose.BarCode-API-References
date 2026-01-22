---
title: Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters class
linktitle: OneDExtendedParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters class. Stores special data of 1D recognized barcode like separate codetext and checksum in C++.'
type: docs
weight: 2400
url: /cpp/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class


Stores special data of 1D recognized barcode like separate codetext and checksum

```cpp
class OneDExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Description |
| --- | --- |
| [get_CheckSum](./get_checksum/)() | Gets the checksum for 1D barcodes. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() | **Tests** whether all parameters has only default values |
| [get_Value](./get_value/)() | Gets the codetext of 1D barcodes without checksum. |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [OneDExtendedParameters](./). |
## Remarks


This sample shows how to get 1D barcode value and checksum 
```cpp
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

## See Also

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
