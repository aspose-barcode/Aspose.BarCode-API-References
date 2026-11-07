---
title: "enum"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Cara menggunakan enum di C++."
type: docs
weight: 3800
url: /id/cpp/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enum




```cpp
enum class DeconvolutionMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Cepat | 0 | Mengaktifkan metode dekonvolusi cepat untuk gambar berkualitas tinggi. |
| Normal | 1 | Mengaktifkan metode dekonvolusi normal untuk gambar umum. |
| Lambat | 2 | Mengaktifkan metode dekonvolusi lambat untuk gambar berkualitas rendah. |

## Catatan


Mode dekonvolusi (pemulihan gambar) yang menentukan tingkat degradasi gambar. Pada awalnya dekonvolusi adalah fungsi yang dapat memulihkan gambar yang terdegradasi (konvolusi) oleh fungsi alami apa pun seperti blur, selama pengambilan gambar dengan kamera. Karena kami tidak dapat mendeteksi fungsi gambar yang merusak gambar, kami harus memeriksa fungsi yang paling dikenal seperti sharp atau morfologi matematika.

Contoh ini menunjukkan cara menggunakan mode Deconvolution
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Lihat Juga

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
