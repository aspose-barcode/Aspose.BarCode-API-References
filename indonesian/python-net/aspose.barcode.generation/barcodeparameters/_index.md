---
title: "BarcodeParameters"
second_title: "Aspose.BarCode for Python via .NET Referensi API"
description: 
type: docs
url: /id/python-net/aspose.barcode.generation/barcodeparameters/
---

## BarcodeParameters class

Parameter pembuatan barcode.

Tipe BarcodeParameters menampilkan anggota-anggota berikut:
## Properti
| Nama | Deskripsi |
| :- | :- |
| x_dimension | x-dimension adalah lebar terkecil dari unit bar atau spasi BarCode.<br/>            Meningkatkan nilai ini akan meningkatkan lebar keseluruhan gambar barcode.<br/>            Diabaikan jika properti [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) disetel ke AutoSizeMode.Nearest atau AutoSizeMode.Interpolation. |
| bar_height | Tinggi bar barcode 1D dalam nilai [Unit](/barcode/python-net/aspose.barcode.generation/unit/).<br/>            Diabaikan jika properti [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) disetel ke AutoSizeMode.Nearest atau AutoSizeMode.Interpolation. |
| bar_color | Warna bar.<br/>            Nilai default: Color.Black. |
| padding | Padding barcode.<br/>            Nilai default: 5pt 5pt 5pt 5pt. |
| checksum_always_show | Selalu tampilkan digit checksum dalam teks yang dapat dibaca manusia untuk barcode Code128 dan GS1Code128. |
| is_checksum_enabled |  |
| throw_exception_when_code_text_incorrect | Hanya untuk barcode 1D.<br/>            Jika codetext tidak benar dan nilai disetel ke true - pengecualian akan dilempar. Jika tidak, codetext akan diperbaiki agar sesuai dengan spesifikasi barcode.<br/>            Pengecualian selalu akan dilempar untuk: simbol Databar jika codetext tidak benar.<br/>            Pengecualian tidak akan pernah dilempar untuk: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, simbol Code128 jika codetext tidak benar. |
| wide_narrow_ratio | Rasio bar Lebar terhadap bar Sempit.<br/>            Nilai default: 3, yaitu bar lebar 3 kali lebih lebar daripada bar sempit.<br/>            Digunakan untuk ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| code_text_parameters | Parameter codetext. |
| filled_bars | Mendapatkan atau mengatur nilai yang menunjukkan apakah bar terisi.<br/>            Hanya untuk barcode 1D.<br/>            Nilai default: true. |
| bar_width_reduction | Mendapatkan atau mengatur nilai pengurangan bar yang digunakan untuk mengkompensasi penyebaran tinta saat mencetak.<br/>            Nilai default: 0 |
| postal | Parameter pos. Digunakan untuk Postnet, Planet. |
| patch_code | Parameter PatchCode. |
| australian_post | Parameter kode batang AustralianPost. |
| data_bar | Parameter Databar. |
| gs1_composite_bar | GS1 Composite Bar parameter. |
| codablock | Parameter Codablock. |
| data_matrix | Parameter DataMatrix. |
| code_16k | Parameter Code16K. |
| dot_code | Parameter DotCode. |
| itf | Parameter ITF. |
| pdf417 | PDF417 parameter. |
| qr | QR, MicroQR and RectMicroQR parameter. |
| supplement | Parameter tambahan. Digunakan untuk Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| maxi_code | Parameter MaxiCode. |
| aztec | Parameter Aztec. |
| code128 | Parameter Code128. |
| codabar | Parameter Codabar. |
| coupon | Parameter kupon. Digunakan untuk UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| han_xin | HanXin parameter. |
| gs1 | Parameter GS1. |

### Lihat Juga

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

