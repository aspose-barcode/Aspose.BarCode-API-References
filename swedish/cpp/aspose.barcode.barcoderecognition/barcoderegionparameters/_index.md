---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters-klass"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters-klass. Representerar den igenkända streckkodens region och streckkodsvinkeln i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class


Representerar den avlästa streckkodens region och streckkodsvinkel

```cpp
class BarCodeRegionParameters : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Angle](./get_angle/)() const | Hämtar vinkeln på streckkoden (0-360). |
| [get_Points](./get_points/)() const | Hämtar [Point](../)s-array som avgränsar streckkodens region |
| [get_Quadrangle](./get_quadrangle/)() const | Hämtar [Aspose::BarCode::BarCodeRecognition::Quadrangle](../quadrangle/) som avgränsar streckkodens region |
| [get_Rectangle](./get_rectangle/)() const | Hämtar **System::Drawing::Rectangle** som avgränsar streckkodens region |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [BarCodeRegionParameters](./). |
## Anmärkningar


Detta exempel visar hur man får streckkodsvinkeln och avgränsande kvadrangelvärden
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

## Se även

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
