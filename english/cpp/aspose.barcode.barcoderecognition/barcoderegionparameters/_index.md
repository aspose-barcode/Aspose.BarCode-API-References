---
title: Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class
linktitle: BarCodeRegionParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class. Represents the recognized barcode''s region and barcode angle in C++.'
type: docs
weight: 600
url: /cpp/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class


Represents the recognized barcode's region and barcode angle

```cpp
class BarCodeRegionParameters : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Angle](./get_angle/)() | Gets the angle of the barcode (0-360). |
| [get_Points](./get_points/)() | Gets [Point](../)s array bounding barcode region |
| [get_Quadrangle](./get_quadrangle/)() | Gets [Aspose::BarCode::BarCodeRecognition::Quadrangle](../quadrangle/) bounding barcode region |
| [get_Rectangle](./get_rectangle/)() | Gets **System::Drawing::Rectangle** bounding barcode region |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [BarCodeRegionParameters](./). |
## Remarks


This sample shows how to get barcode Angle and bounding quadrangle values 
```cpp
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

## See Also

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
