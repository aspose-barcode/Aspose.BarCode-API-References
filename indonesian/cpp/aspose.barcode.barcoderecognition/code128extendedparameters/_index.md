---
title: "kelas Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "kelas Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters. Menyimpan data khusus barcode Code128 yang dikenali dalam C++."
type: docs
weight: 1300
url: /id/cpp/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class


Menyimpan data khusus dari kode batang Code128 yang dikenali

```cpp
class Code128ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Code128DataPortions](./get_code128dataportions/)() const | Mendapatkan array [Code128DataPortion](../code128dataportion/) dari barcode Code128 yang dikenali |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** apakah semua parameter hanya memiliki nilai default |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [Code128ExtendedParameters](./) ini. |
## Catatan


Mewakili wilayah kode batang yang dikenali dan sudut kode batang

Contoh ini menunjukkan cara mendapatkan nilai mentah code128
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

## Lihat Juga

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
