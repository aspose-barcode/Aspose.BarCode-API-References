---
title: "BaseGenerationParameters"
second_title: "Aspose.BarCode for Python via .NET Referensi API"
description: 
type: docs
url: /id/python-net/aspose.barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

Parameter pembuatan gambar barcode.

Tipe BaseGenerationParameters menampilkan anggota-anggota berikut:
## Properti
| Nama | Deskripsi |
| :- | :- |
| use_anti_alias | Mendapatkan atau mengatur nilai yang menunjukkan apakah mode anti-aliasing digunakan untuk merender gambar |
| back_color | Warna latar belakang gambar barcode.<br/>            Nilai default: Color.White.<br/>            Lihat [Color](/barcode/python-net/aspose.drawing/color/). |
| resolusi | Mendapatkan atau mengatur resolusi gambar BarCode.<br/>            Satu nilai untuk kedua dimensi.<br/>            Nilai default: 96 dpi. |
| rotation_angle | Sudut rotasi gambar BarCode, diukur dalam derajat, misalnya RotationAngle = 0 atau RotationAngle = 360 berarti tidak ada rotasi.<br/>            Jika RotationAngle TIDAK sama dengan 90, 180, 270, atau 0, hal ini dapat meningkatkan kesulitan pemindai untuk membaca gambar.<br/>            Nilai default: 0. |
| caption_above | Keterangan di atas gambar BarCode. Lihat [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| caption_below | Keterangan di bawah gambar BarCode. Lihat [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| image | Parameter gambar. Lihat [ImageParameters](/barcode/python-net/aspose.barcode.generation/imageparameters/). |
| auto_size_mode | Menentukan berbagai jenis mode penyesuaian ukuran otomatis.<br/>            Nilai default: AutoSizeMode.None. |
| image_height | Tinggi gambar BarCode ketika properti [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) diatur ke AutoSizeMode.Nearest atau AutoSizeMode.Interpolation. |
| image_width | Lebar gambar BarCode ketika properti [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) diatur ke AutoSizeMode.Nearest atau AutoSizeMode.Interpolation. |
| barcode | Mendapatkan [BarcodeParameters](/barcode/python-net/aspose.barcode.generation/barcodeparameters/) yang berisi semua properti barcode. |
| border | Mendapatkan [BorderParameters](/barcode/python-net/aspose.barcode.generation/borderparameters/) yang berisi semua properti konfigurasi untuk border barcode. |

### Lihat Juga

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

