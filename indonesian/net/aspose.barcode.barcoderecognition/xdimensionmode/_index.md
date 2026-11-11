---
title: "Enum XDimensionMode"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Enum Aspose.BarCode.BarCodeRecognition.XDimensionMode. Mode pengenalan yang menetapkan ukuran dari 1 hingga tak terhingga dari sel matriks elemen minimal barcode atau bar."
type: docs
weight: 400
url: /id/net/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enumeration

Mode pengenalan yang menetapkan ukuran (dari 1 hingga tak terhingga) dari elemen minimal barcode: sel matriks atau bar.

```csharp
public enum XDimensionMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Auto | `0` | Nilai XDimension terdeteksi oleh AI (SVM). Saat ini sama dengan Normal. |
| Small | `1` | Mendeteksi barcode dengan XDimension kecil dalam 1 piksel atau lebih dengan kualitas dari BarcodeQuality. |
| Normal | `2` | Mendeteksi barcode dengan XDimension klasik dalam 2 piksel atau lebih dengan kualitas dari BarcodeQuality atau barcode berkualitas tinggi. |
| Large | `3` | Mendeteksi barcode dengan XDimension besar dengan kualitas dari BarcodeQuality yang diambil dengan kamera resolusi tinggi. |
| UseMinimalXDimension | `4` | Mendeteksi barcode dari ukuran yang ditetapkan dalam MinimalXDimension dengan kualitas dari BarcodeQuality. |

## Contoh

Contoh ini menunjukkan cara menggunakan mode XDimension.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Lihat Juga

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


