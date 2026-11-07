---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters Klasse. Stellt die Region des erkannten Barcodes und den Barcode‑Winkel in C++ dar."
type: docs
weight: 600
url: /de/cpp/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class


Stellt die Region des erkannten Barcodes und den Barcode-Winkel dar

```cpp
class BarCodeRegionParameters : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_Angle](./get_angle/)() const | Ermittelt den Winkel des Barcodes (0‑360). |
| [get_Points](./get_points/)() const | Ermittelt das [Point](../)-Array, das die Barcode‑Region begrenzt |
| [get_Quadrangle](./get_quadrangle/)() const | Ermittelt das [Aspose::BarCode::BarCodeRecognition::Quadrangle](../quadrangle/), das die Barcode‑Region begrenzt |
| [get_Rectangle](./get_rectangle/)() const | Ermittelt **System::Drawing::Rectangle**, das die Barcode‑Region begrenzt |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [BarCodeRegionParameters](./) zurück. |
## Hinweise


Dieses Beispiel zeigt, wie man den Barcode-Winkel und die Begrenzungs-Quadrangle-Werte erhält.
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

## Siehe auch

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
