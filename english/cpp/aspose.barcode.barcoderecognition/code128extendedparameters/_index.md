---
title: Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters class
linktitle: Code128ExtendedParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters class. Stores special data of Code128 recognized barcode in C++.'
type: docs
weight: 1300
url: /cpp/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class


Stores special data of Code128 recognized barcode

```cpp
class Code128ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Description |
| --- | --- |
| [get_Code128DataPortions](./get_code128dataportions/)() | Gets [Code128DataPortion](../code128dataportion/) array of recognized Code128 barcode |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() | **Tests** whether all parameters has only default values |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [Code128ExtendedParameters](./). |
## Remarks


Represents the recognized barcode's region and barcode angle 

This sample shows how to get code128 raw values 
```cpp
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

## See Also

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
