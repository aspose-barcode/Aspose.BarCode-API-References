---
title: "metode"
linktitle: "get_IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " method. Bendera yang memaksa decoder AustraliaPost mengabaikan pola pengisian terakhir dalam Field Informasi Pelanggan selama decoding dengan metode CTable. Metode encoding CTable tidak memiliki celah dalam tabel encoding dan urutan \"333\" dari pola pengisian didekode menjadi huruf \"z\" dalam C++."
type: docs
weight: 300
url: /id/cpp/aspose.barcode.barcoderecognition/australiapostsettings/get_ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings::get_IgnoreEndingFillingPatternsForCTable method


Bendera yang memaksa decoder AustraliaPost mengabaikan pola pengisian terakhir dalam Customer Information Field selama decoding dengan metode CTable. Metode pengkodean CTable tidak memiliki celah dalam tabel pengkodean dan urutan "333" dari pola pengisian didekode sebagai huruf "z".

```cpp
bool Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings::get_IgnoreEndingFillingPatternsForCTable() const
```

## Catatan


Bendera yang memaksa decoder AustraliaPost mengabaikan pola pengisian terakhir selama decoding dengan metode CTable

Contoh ini menunjukkan cara menghasilkan dan mengenali kode batang Australia Post dengan Tipe Interpretasi CTable serta mengabaikan pola pengisian.
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

## Lihat Juga

* Class [AustraliaPostSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
