---
title: "Enum DeconvolutionMode"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Aspose.BarCode.BarCodeRecognition.DeconvolutionMode enum. Mode restorasi gambar dekonvolusi yang menentukan tingkat degradasi gambar. Pada awalnya dekonvolusi adalah fungsi yang dapat memulihkan gambar yang terdegradasi karena konvolusi oleh fungsi alami apa pun seperti blur saat memperoleh gambar dengan kamera. Karena kami tidak dapat mendeteksi fungsi gambar yang merusak gambar, kami harus memeriksa fungsi-fungsi yang paling dikenal seperti sharp atau morfologi matematis"
type: docs
weight: 240
url: /id/net/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enumeration

Mode dekonvolusi (restorasi gambar) yang menentukan tingkat degradasi gambar. Pada awalnya dekonvolusi adalah fungsi yang dapat memulihkan gambar yang terdegradasi (terkonvolusi) oleh fungsi alami apa pun seperti blur, saat memperoleh gambar dengan kamera. Karena kami tidak dapat mendeteksi fungsi gambar yang merusak gambar, kami harus memeriksa fungsi-fungsi yang paling dikenal seperti sharp atau morfologi matematis.

```csharp
public enum DeconvolutionMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Fast | `0` | Mengaktifkan metode dekonvolusi cepat untuk gambar berkualitas tinggi. |
| Normal | `1` | Mengaktifkan metode dekonvolusi normal untuk gambar umum. |
| Slow | `2` | Mengaktifkan metode dekonvolusi lambat untuk gambar berkualitas rendah. |

## Contoh

Contoh ini menunjukkan cara menggunakan mode Deconvolution

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Lihat Juga

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


