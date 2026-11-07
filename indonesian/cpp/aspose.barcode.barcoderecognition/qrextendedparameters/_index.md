---
title: "Kelas Aspose::BarCode::BarCodeRecognition::QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Kelas Aspose::BarCode::BarCodeRecognition::QRExtendedParameters. Menyimpan informasi QR Structured Append dari barcode yang dikenali dalam C++."
type: docs
weight: 2900
url: /id/cpp/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class


Menyimpan informasi Structured Append [QR](../../aspose.barcode.barcoderecognition.qr/) dari barcode yang dikenali

```cpp
class QRExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_ErrorLevel](./get_errorlevel/)() const | Level koreksi kesalahan Reed-Solomon dari barcode yang dikenali. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** apakah semua parameter hanya memiliki nilai default |
| [get_MicroQRVersion](./get_microqrversion/)() const | Versi MicroQR Code yang dikenali. Dari M1 hingga M4. |
| [get_RectMicroQRVersion](./get_rectmicroqrversion/)() const | Versi RectMicroQR Code yang dikenali. Dari R7x43 hingga R17x139. |
| [get_StructuredAppendModeBarCodeIndex](./get_structuredappendmodebarcodeindex/)() const | Mendapatkan indeks barcode mode structured append [QR](../../aspose.barcode.barcoderecognition.qr/). Indeks dimulai dari 0. Nilai default adalah -1. |
| [get_StructuredAppendModeBarCodesQuantity](./get_structuredappendmodebarcodesquantity/)() const | Mendapatkan jumlah barcode mode structured append [QR](../../aspose.barcode.barcoderecognition.qr/). Nilai default adalah -1. |
| [get_StructuredAppendModeParityData](./get_structuredappendmodeparitydata/)() const | Mendapatkan data parity mode structured append [QR](../../aspose.barcode.barcoderecognition.qr/). Nilai default adalah -1. |
| [get_Version](./get_version/)() const | Versi [QR](../../aspose.barcode.barcoderecognition.qr/) Code yang dikenali. Dari Version1 hingga Version40. |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [QRExtendedParameters](./). |
## Catatan


Contoh ini menunjukkan cara mendapatkan data Structured Append [QR](../../aspose.barcode.barcoderecognition.qr/)
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex);
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex)
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData)
    Next
End Using
```

## Lihat Juga

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
