---
title: "Aspose::BarCode::Generation::BaseGenerationParameters class"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::Generation::BaseGenerationParameters class. Parameter untuk menghasilkan gambar barcode dalam C++."
type: docs
weight: 700
url: /id/cpp/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class


Parameter pembuatan gambar kode batang.

```cpp
class BaseGenerationParameters : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_AutoSizeMode](./get_autosizemode/)() const | Menentukan berbagai jenis mode penyesuaian ukuran otomatis. Nilai default: [AutoSizeMode.None](../autosizemode/). |
| [get_BackColor](./get_backcolor/)() const | Warna latar belakang gambar barcode. Nilai default: Color.White. Lihat [Color](../). |
| [get_Barcode](./get_barcode/)() const | Mendapatkan [BarcodeParameters](../barcodeparameters/) yang berisi semua properti barcode. |
| [get_Border](./get_border/)() const | Mendapatkan [BorderParameters](../borderparameters/) yang berisi semua properti konfigurasi untuk border barcode. |
| [get_CaptionAbove](./get_captionabove/)() const | Keterangan di atas gambar [BarCode](../../aspose.barcode/). Lihat [CaptionParameters](../captionparameters/). |
| [get_CaptionBelow](./get_captionbelow/)() const | Keterangan di bawah gambar [BarCode](../../aspose.barcode/). Lihat [CaptionParameters](../captionparameters/). |
| [get_Image](./get_image/)() const | Parameter gambar. Lihat [ImageParameters](../imageparameters/). |
| [get_ImageHeight](./get_imageheight/)() const | Tinggi gambar [BarCode](../../aspose.barcode/) ketika properti [AutoSizeMode](../autosizemode/) diatur ke [AutoSizeMode.Nearest](../autosizemode/) atau [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_ImageWidth](./get_imagewidth/)() const | Lebar gambar [BarCode](../../aspose.barcode/) ketika properti [AutoSizeMode](../autosizemode/) diatur ke [AutoSizeMode.Nearest](../autosizemode/) atau [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_Resolution](./get_resolution/)() const | Mendapatkan resolusi gambar [BarCode](../../aspose.barcode/). Satu nilai untuk kedua dimensi. Nilai default: 96 dpi. |
| [get_RotationAngle](./get_rotationangle/)() const | Sudut rotasi gambar [BarCode](../../aspose.barcode/), diukur dalam derajat, misalnya RotationAngle = 0 atau RotationAngle = 360 berarti tidak ada rotasi. Jika RotationAngle TIDAK sama dengan 90, 180, 270 atau 0, hal ini dapat meningkatkan kesulitan pemindai untuk membaca gambar. Nilai default: 0. |
| [get_UseAntiAlias](./get_useantialias/)() const | Mendapatkan nilai yang menunjukkan apakah mode anti-aliasing digunakan untuk merender gambar |
| [set_AutoSizeMode](./set_autosizemode/)(Aspose::BarCode::Generation::AutoSizeMode) | Menentukan berbagai jenis mode penyesuaian ukuran otomatis. Nilai default: [AutoSizeMode.None](../autosizemode/). |
| [set_BackColor](./set_backcolor/)(System::Drawing::Color) | Warna latar belakang gambar barcode. Nilai default: Color.White. Lihat [Color](../). |
| [set_ImageHeight](./set_imageheight/)(System::SharedPtr\<Unit\>) | Tinggi gambar [BarCode](../../aspose.barcode/) ketika properti [AutoSizeMode](../autosizemode/) diatur ke [AutoSizeMode.Nearest](../autosizemode/) atau [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_ImageWidth](./set_imagewidth/)(System::SharedPtr\<Unit\>) | Lebar gambar [BarCode](../../aspose.barcode/) ketika properti [AutoSizeMode](../autosizemode/) diatur ke [AutoSizeMode.Nearest](../autosizemode/) atau [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_Resolution](./set_resolution/)(float) | Mengatur resolusi gambar [BarCode](../../aspose.barcode/). Satu nilai untuk kedua dimensi. Nilai default: 96 dpi. |
| [set_RotationAngle](./set_rotationangle/)(float) | Sudut rotasi gambar [BarCode](../../aspose.barcode/), diukur dalam derajat, misalnya RotationAngle = 0 atau RotationAngle = 360 berarti tidak ada rotasi. Jika RotationAngle TIDAK sama dengan 90, 180, 270 atau 0, hal ini dapat meningkatkan kesulitan pemindai untuk membaca gambar. Nilai default: 0. |
| [set_UseAntiAlias](./set_useantialias/)(bool) | Mengatur nilai yang menunjukkan apakah mode anti-aliasing digunakan untuk merender gambar |
## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
