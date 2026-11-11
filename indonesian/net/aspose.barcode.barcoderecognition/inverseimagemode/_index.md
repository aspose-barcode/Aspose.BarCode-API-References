---
title: "Enum InverseImageMode"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Aspose.BarCode.BarCodeRecognition.InverseImageMode enum. Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode pada gambar dengan luminansi warna terbalik"
type: docs
weight: 270
url: /id/net/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enumeration

Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode pada gambar dengan warna terbalik (luminansi).

```csharp
public enum InverseImageMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Auto | `0` | Menonaktifkan pengenalan tambahan barcode pada gambar terbalik untuk semua jenis barcode kecuali QR Code. |
| Disabled | `1` | Menonaktifkan pengenalan tambahan barcode pada gambar terbalik. |
| Enabled | `2` | Mengaktifkan pengenalan tambahan barcode pada gambar terbalik |

## Contoh

Contoh ini menunjukkan cara menggunakan mode InverseImage

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Lihat Juga

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


