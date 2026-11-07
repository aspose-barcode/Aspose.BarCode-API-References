---
title: "Methode"
linktitle: "get_IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. Das Flag, das den AustraliaPost-Decodierer zwingt, die letzten Füllmuster im Customer Information-Feld beim Decodieren mit der CTable-Methode zu ignorieren. Die CTable-Codierungsmethode hat keine Lücken in der Codierungstabelle und die Sequenz \"333\" von Füllmustern wird in C++ als Buchstabe \"z\" decodiert."
type: docs
weight: 300
url: /de/cpp/aspose.barcode.barcoderecognition/australiapostsettings/get_ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings::get_IgnoreEndingFillingPatternsForCTable method


Das Flag, das den AustraliaPost‑Decoder zwingt, die letzten Füllmuster im Customer Information Field während der Dekodierung nach der CTable‑Methode zu ignorieren. Die CTable‑Kodierungsmethode hat keine Lücken in der Kodierungstabelle und die Sequenz \"333\" der Füllmuster wird als Buchstabe \"z\" dekodiert.

```cpp
bool Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings::get_IgnoreEndingFillingPatternsForCTable() const
```

## Hinweise


Das Flag, das den AustraliaPost-Decodierer zwingt, die letzten Füllmuster beim Decodieren mit der CTable-Methode zu ignorieren

Dieses Beispiel zeigt, wie man einen Australia Post-Barcode mit CTable-Interpretationstyp erzeugt und erkennt, wobei Füllmuster ignoriert werden.
```cpp
    [C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable;
        reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable
            reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = True
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
```

## Siehe auch

* Class [AustraliaPostSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
