---
title: "Enum BarcodeQualityMode"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Enum Aspose.BarCode.BarCodeRecognition.BarcodeQualityMode. Mode yang memungkinkan metode untuk mengenali elemen barcode dengan kualitas yang dipilih. Elemen barcode dengan kualitas lebih rendah memerlukan metode yang lebih berat yang memperlambat proses pengenalan."
type: docs
weight: 110
url: /id/net/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enumeration

Mode yang memungkinkan metode untuk mengenali elemen barcode dengan kualitas yang dipilih. Elemen barcode dengan kualitas lebih rendah memerlukan metode yang lebih berat yang memperlambat proses pengenalan.

```csharp
public enum BarcodeQualityMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| High | `0` | Mengaktifkan metode pengenalan untuk barcode berkualitas Tinggi. |
| Normal | `1` | Mengaktifkan metode pengenalan untuk barcode berkualitas Umum (Normal). |
| Low | `2` | Mengaktifkan metode pengenalan untuk barcode berkualitas Rendah. |

## Contoh

Contoh ini menunjukkan cara menggunakan mode BarcodeQuality

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Lihat Juga

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


