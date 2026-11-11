---
title: "Enum ComplexBackgroundMode"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Aspose.BarCode.BarCodeRecognition.ComplexBackgroundMode enum. Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan kode batang berwarna pada gambar berwarna"
type: docs
weight: 200
url: /id/net/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enumeration

Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan kode batang berwarna pada gambar berwarna.

```csharp
public enum ComplexBackgroundMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Auto | `0` | Saat ini sama dengan Disabled. Menonaktifkan pengenalan tambahan kode batang berwarna pada gambar berwarna. |
| Disabled | `1` | Menonaktifkan pengenalan tambahan kode batang berwarna pada gambar berwarna. |
| Enabled | `2` | Mengaktifkan pengenalan tambahan kode batang berwarna pada gambar berwarna. |

## Contoh

Contoh ini menunjukkan cara menggunakan mode ComplexBackground

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Lihat Juga

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


