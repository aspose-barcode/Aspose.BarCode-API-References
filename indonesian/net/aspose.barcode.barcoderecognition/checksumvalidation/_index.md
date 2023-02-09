---
title: ChecksumValidation
second_title: Aspose.BarCode untuk .NET API Referensi
description: Aktifkan validasi checksum selama pengenalan untuk kode batang 1D dan Pos.
type: docs
weight: 140
url: /id/net/aspose.barcode.barcoderecognition/checksumvalidation/
---
## ChecksumValidation enumeration

Aktifkan validasi checksum selama pengenalan untuk kode batang 1D dan Pos.

Default diperlakukan sebagai Ya untuk simbol yang harus mengandung checksum, sebagai Tidak di mana checksum hanya memungkinkan.

Checksum tidak pernah digunakan: Codabar, PatchCode, Pharmacode, DataLogic2of5

Checksum dimungkinkan: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Checksum selalu digunakan: Simbol istirahat

```csharp
public enum ChecksumValidation
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| Default | `0` | Jika checksum diperlukan oleh spesifikasi - ini akan divalidasi. |
| On | `1` | Selalu validasi checksum jika memungkinkan. |
| Off | `2` | Jangan validasi checksum. |

### Contoh

Contoh ini menunjukkan pengaruh ChecksumValidation pada kualitas dan hasil pengenalan

```csharp
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
    'checksum dinonaktifkan
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum diaktifkan
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

### Lihat juga

* ruang nama [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->