---
title: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters kelas"
linktitle: "DataBarExtendedParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters class. Menyimpan informasi tambahan DataBar dari barcode yang dikenali dalam C++."
type: docs
weight: 1400
url: /id/cpp/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class


Menyimpan informasi tambahan DataBar dari kode batang yang dikenali

```cpp
class DataBarExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Is2DCompositeComponent](./get_is2dcompositecomponent/)() const | Mendapatkan flag komponen komposit DataBar 2D. Nilai bawaan adalah false. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** apakah semua parameter hanya memiliki nilai default |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [DataBarExtendedParameters](./). |
## Catatan


Contoh ini menunjukkan cara mendapatkan informasi tambahan DataBar
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DatabarOmniDirectional))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.DatabarOmniDirectional)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
    Next
End Using
```

## Lihat Juga

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
