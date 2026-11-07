---
title: "Aspose::BarCode::BarCodeRecognition::QualitySettings kelas"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::BarCodeRecognition::QualitySettings kelas. QualitySettings memungkinkan mengkonfigurasi kualitas dan kecepatan pengenalan secara manual. Anda dapat dengan cepat mengatur QualitySettings dengan preset tersemat: HighPerformance, NormalQuality, HighQuality, MaxQuality atau Anda dapat mengkonfigurasi opsi terpisah secara manual. Nilai default QualitySettings adalah NormalQuality dalam C++."
type: docs
weight: 3100
url: /id/cpp/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class


[QualitySettings](./) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](./) with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of [QualitySettings](./) is NormalQuality.

```cpp
class QualitySettings : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_AllowIncorrectBarcodes](./get_allowincorrectbarcodes/)() const | Mengizinkan mesin mengenali kode batang yang memiliki checksum atau nilai yang tidak benar. Mode ini dapat digunakan untuk mengenali kode batang yang rusak dengan teks yang tidak benar. |
| [get_BarcodeQuality](./get_barcodequality/)() const | Mode yang memungkinkan metode mengenali elemen kode batang dengan kualitas yang dipilih. Elemen kode batang dengan kualitas lebih rendah memerlukan metode yang lebih berat yang memperlambat pengenalan. |
| [get_ComplexBackground](./get_complexbackground/)() const | Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan kode batang berwarna pada gambar berwarna. |
| [get_Deconvolution](./get_deconvolution/)() const | Mode dekonvolusi (pemulihan gambar) yang menentukan tingkat degradasi gambar. Pada awalnya dekonvolusi adalah fungsi yang dapat memulihkan gambar yang terdegradasi (konvolusi) oleh fungsi alami apa pun seperti blur, selama pengambilan gambar dengan kamera. Karena kami tidak dapat mendeteksi fungsi gambar yang merusak gambar, kami harus memeriksa fungsi yang paling dikenal seperti sharp atau morfologi matematika. |
| static [get_HighPerformance](./get_highperformance/)() | Preset kualitas pengenalan HighPerformance. Kode batang berkualitas tinggi dikenali dengan baik dalam mode ini. |
| static [get_HighQuality](./get_highquality/)() | Preset kualitas pengenalan HighQuality. Preset ini dikembangkan untuk kode batang berkualitas rendah. Mengizinkan deteksi kode batang yang sangat rusak. |
| [get_InverseImage](./get_inverseimage/)() const | Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan kode batang pada gambar dengan warna terbalik (luminansi). |
| static [get_MaxQuality](./get_maxquality/)() | Preset kualitas pengenalan MaxQuality. Preset ini dikembangkan untuk mengenali semua barcode yang mungkin, bahkan barcode yang tidak benar. |
| [get_MinimalXDimension](./get_minimalxdimension/)() const | Ukuran minimal XDimension dalam piksel yang digunakan dengan UseMinimalXDimension. |
| static [get_NormalQuality](./get_normalquality/)() | Preset kualitas pengenalan NormalQuality. Cocok untuk sebagian besar barcode. |
| [get_XDimension](./get_xdimension/)() const | Mode [Recognition](../../aspose.barcode.barcoderecognition.recognition/) yang mengatur ukuran (dari 1 hingga tak terhingga) elemen minimal barcode: sel matriks atau bar. |
| [set_AllowIncorrectBarcodes](./set_allowincorrectbarcodes/)(bool) | Mengizinkan mesin mengenali kode batang yang memiliki checksum atau nilai yang tidak benar. Mode ini dapat digunakan untuk mengenali kode batang yang rusak dengan teks yang tidak benar. |
| [set_BarcodeQuality](./set_barcodequality/)(BarcodeQualityMode) | Mode yang memungkinkan metode mengenali elemen kode batang dengan kualitas yang dipilih. Elemen kode batang dengan kualitas lebih rendah memerlukan metode yang lebih berat yang memperlambat pengenalan. |
| [set_ComplexBackground](./set_complexbackground/)(ComplexBackgroundMode) | Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan kode batang berwarna pada gambar berwarna. |
| [set_Deconvolution](./set_deconvolution/)(DeconvolutionMode) | Mode dekonvolusi (pemulihan gambar) yang menentukan tingkat degradasi gambar. Pada awalnya dekonvolusi adalah fungsi yang dapat memulihkan gambar yang terdegradasi (konvolusi) oleh fungsi alami apa pun seperti blur, selama pengambilan gambar dengan kamera. Karena kami tidak dapat mendeteksi fungsi gambar yang merusak gambar, kami harus memeriksa fungsi yang paling dikenal seperti sharp atau morfologi matematika. |
| [set_InverseImage](./set_inverseimage/)(InverseImageMode) | Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan kode batang pada gambar dengan warna terbalik (luminansi). |
| [set_MinimalXDimension](./set_minimalxdimension/)(float) | Ukuran minimal XDimension dalam piksel yang digunakan dengan UseMinimalXDimension. |
| [set_XDimension](./set_xdimension/)(XDimensionMode) | Mode [Recognition](../../aspose.barcode.barcoderecognition.recognition/) yang mengatur ukuran (dari 1 hingga tak terhingga) elemen minimal barcode: sel matriks atau bar. |
## Catatan


Contoh ini menunjukkan cara menggunakan [QualitySettings](./) dengan [BarCodeReader](../barcodereader/)
```cpp
[C#]
//atur mode pengenalan HighPerformance
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//atur mode pengenalan HighQuality
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//atur mode pengenalan HighPerformance untuk barcode berukuran kecil
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//atur mode pengenalan HighPerformance untuk barcode berkualitas rendah
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Lihat Juga

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
