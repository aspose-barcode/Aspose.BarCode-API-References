---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class. Vertegenwoordigt de regio van de herkende barcode en de barcodehoek in C++."
type: docs
weight: 600
url: /nl/cpp/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class


Stelt de regio en hoek van de herkende barcode voor

```cpp
class BarCodeRegionParameters : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Angle](./get_angle/)() const | Haalt de hoek van de barcode op (0-360). |
| [get_Points](./get_points/)() const | Haalt de array van [Point](../)s op die de barcode-regio begrenzen. |
| [get_Quadrangle](./get_quadrangle/)() const | Haalt de [Aspose::BarCode::BarCodeRecognition::Quadrangle](../quadrangle/) op die de barcode-regio begrenst. |
| [get_Rectangle](./get_rectangle/)() const | Haalt **System::Drawing::Rectangle** op die de barcode-regio begrenst. |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [ToString](./tostring/)() const override | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [BarCodeRegionParameters](./). |
## Opmerkingen


Dit voorbeeld toont hoe de barcodehoek en de begrenzende vierhoekwaarden op te halen.
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

## Zie ook

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
