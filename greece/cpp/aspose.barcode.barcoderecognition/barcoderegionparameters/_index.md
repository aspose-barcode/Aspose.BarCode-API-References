---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class. Αντιπροσωπεύει την περιοχή του αναγνωρισμένου barcode'' και τη γωνία του barcode σε C++."
type: docs
weight: 600
url: /el/cpp/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class


Αντιπροσωπεύει την περιοχή του αναγνωρισμένου barcode και τη γωνία του barcode

```cpp
class BarCodeRegionParameters : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_Angle](./get_angle/)() const | Λαμβάνει τη γωνία του barcode (0-360). |
| [get_Points](./get_points/)() const | Λαμβάνει τον πίνακα [Point](../)s που οριοθετεί την περιοχή του barcode |
| [get_Quadrangle](./get_quadrangle/)() const | Λαμβάνει το [Aspose::BarCode::BarCodeRecognition::Quadrangle](../quadrangle/) που οριοθετεί την περιοχή του barcode |
| [get_Rectangle](./get_rectangle/)() const | Λαμβάνει το **System::Drawing::Rectangle** που οριοθετεί την περιοχή του barcode |
| [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [ToString](./tostring/)() const override | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [BarCodeRegionParameters](./). |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να λάβετε τη γωνία του barcode και τις τιμές του οριοθετημένου τετραγώνου.
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

## Δείτε επίσης

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
