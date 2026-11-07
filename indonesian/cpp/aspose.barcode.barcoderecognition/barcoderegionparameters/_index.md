---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class. Mewakili wilayah barcode yang dikenali dan sudut barcode dalam C++."
type: docs
weight: 600
url: /id/cpp/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class


Mewakili wilayah kode batang yang dikenali dan sudut kode batang

```cpp
class BarCodeRegionParameters : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Angle](./get_angle/)() const | Mendapatkan sudut barcode (0-360). |
| [get_Points](./get_points/)() const | Mendapatkan array [Point](../) yang membatasi wilayah barcode |
| [get_Quadrangle](./get_quadrangle/)() const | Mendapatkan [Aspose::BarCode::BarCodeRecognition::Quadrangle](../quadrangle/) yang membatasi wilayah barcode |
| [get_Rectangle](./get_rectangle/)() const | Mendapatkan **System::Drawing::Rectangle** yang membatasi wilayah barcode |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [BarCodeRegionParameters](./). |
## Catatan


Contoh ini menunjukkan cara mendapatkan nilai Sudut barcode dan kuadrangle pembatas
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

## Lihat Juga

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
