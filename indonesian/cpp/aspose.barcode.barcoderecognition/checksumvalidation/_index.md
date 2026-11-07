---
title: "enum"
linktitle: "ChecksumValidation"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Cara menggunakan enum di C++."
type: docs
weight: 3300
url: /id/cpp/aspose.barcode.barcoderecognition/checksumvalidation/
---
## ChecksumValidation enum




```cpp
enum class ChecksumValidation
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Bawaan | 0 | Jika checksum diperlukan oleh spesifikasi - itu akan divalidasi. |
| Aktif | 1 | Selalu validasi checksum jika memungkinkan. |
| Nonaktif | 2 | Jangan validasi checksum. |

## Catatan


Aktifkan validasi checksum selama pengenalan untuk barcode 1D dan Pos.

Bawaan diperlakukan sebagai Ya untuk simbol yang harus mengandung checksum, sebagai Tidak dimana checksum hanya mungkin.

Checksum tidak pernah digunakan: Codabar, PatchCode, Pharmacode, DataLogic2of5

Checksum memungkinkan: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Checksum selalu digunakan: Simbol lainnya

Contoh ini menunjukkan pengaruh ChecksumValidation pada kualitas dan hasil pengenalan
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //checksum dinonaktifkan
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //checksum diaktifkan
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum disabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum enabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

## Lihat Juga

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
