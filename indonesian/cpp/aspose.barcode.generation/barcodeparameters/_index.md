---
title: "kelas Aspose::BarCode::Generation::BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "kelas Aspose::BarCode::Generation::BarcodeParameters. Parameter generasi barcode dalam C++."
type: docs
weight: 500
url: /id/cpp/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class


Parameter pembuatan kode batang.

```cpp
class BarcodeParameters : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_AustralianPost](./get_australianpost/)() const | Parameter kode batang AustralianPost. |
| [get_Aztec](./get_aztec/)() const | Parameter Aztec. |
| [get_BarColor](./get_barcolor/)() const | Warna bar. Nilai default: Color.Black. |
| [get_BarHeight](./get_barheight/)() const | Tinggi bar pada barcode 1D dalam nilai [Unit](../unit/). Diabaikan jika properti [BaseGenerationParameters::AutoSizeMode](../) disetel ke [AutoSizeMode.Nearest](../autosizemode/) atau [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_BarWidthReduction](./get_barwidthreduction/)() const | Mendapatkan atau mengatur nilai pengurangan bar yang digunakan untuk mengkompensasi penyebaran tinta saat mencetak. Nilai default: 0 |
| [get_ChecksumAlwaysShow](./get_checksumalwaysshow/)() const | Selalu tampilkan digit checksum dalam teks yang dapat dibaca manusia untuk barcode Code128 dan GS1Code128. |
| [get_Codabar](./get_codabar/)() const | Parameter Codabar. |
| [get_Codablock](./get_codablock/)() const | Parameter Codablock. |
| [get_Code128](./get_code128/)() const | Parameter Code128. |
| [get_Code16K](./get_code16k/)() const | Parameter Code16K. |
| [get_CodeTextParameters](./get_codetextparameters/)() const | Parameter teks kode. |
| [get_Coupon](./get_coupon/)() const | Parameter kupon. Digunakan untuk UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [get_DataBar](./get_databar/)() const | Parameter Databar. |
| [get_DataMatrix](./get_datamatrix/)() const | Parameter DataMatrix. |
| [get_DotCode](./get_dotcode/)() const | Parameter DotCode. |
| [get_FilledBars](./get_filledbars/)() const | Mendapatkan nilai yang menunjukkan apakah bar terisi. Hanya untuk barcode 1D. Nilai default: true. |
| [get_GS1](./get_gs1/)() const | Parameter GS1. |
| [get_GS1CompositeBar](./get_gs1compositebar/)() const | Parameter GS1 Composite Bar. |
| [get_HanXin](./get_hanxin/)() const | Parameter HanXin. |
| [get_IsChecksumEnabled](./get_ischecksumenabled/)() const |  |
| [get_ITF](./get_itf/)() const | Parameter ITF. |
| [get_MaxiCode](./get_maxicode/)() const | Parameter MaxiCode. |
| [get_Padding](./get_padding/)() const | Padding barcode. Nilai default: 5pt 5pt 5pt 5pt. |
| [get_PatchCode](./get_patchcode/)() const | Parameter PatchCode. |
| [get_Pdf417](./get_pdf417/)() const | Parameter PDF417. |
| [get_Postal](./get_postal/)() const | Parameter pos. Digunakan untuk Postnet, Planet. |
| [get_QR](./get_qr/)() const | Parameter QR, MicroQR, dan RectMicroQR. |
| [get_Supplement](./get_supplement/)() const | Parameter suplemen. Digunakan untuk Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [get_ThrowExceptionWhenCodeTextIncorrect](./get_throwexceptionwhencodetextincorrect/)() const | Hanya untuk barcode 1D. Jika codetext tidak benar dan nilai diatur ke true - pengecualian akan dilempar. Jika tidak, codetext akan diperbaiki agar sesuai dengan spesifikasi barcode. Pengecualian selalu akan dilempar untuk: Databar symbology jika codetext tidak benar. Pengecualian tidak akan pernah dilempar untuk: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 symbology jika codetext tidak benar. |
| [get_WideNarrowRatio](./get_widenarrowratio/)() const | Rasio bar lebar terhadap bar sempit. Nilai default: 3, yaitu bar lebar 3 kali lebih lebar daripada bar sempit. Digunakan untuk ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [get_XDimension](./get_xdimension/)() const | x-dimension adalah lebar terkecil dari unit bar atau spasi [BarCode](../../aspose.barcode/). Meningkatkan nilai ini akan meningkatkan lebar seluruh gambar barcode. Diabaikan jika properti [BaseGenerationParameters::AutoSizeMode](../) diatur ke [AutoSizeMode.Nearest](../autosizemode/) atau [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarColor](./set_barcolor/)(System::Drawing::Color) | Warna bar. Nilai default: Color.Black. |
| [set_BarHeight](./set_barheight/)(System::SharedPtr\<Unit\>) | Tinggi bar pada barcode 1D dalam nilai [Unit](../unit/). Diabaikan jika properti [BaseGenerationParameters::AutoSizeMode](../) disetel ke [AutoSizeMode.Nearest](../autosizemode/) atau [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarWidthReduction](./set_barwidthreduction/)(System::SharedPtr\<Unit\>) | Mendapatkan atau mengatur nilai pengurangan bar yang digunakan untuk mengkompensasi penyebaran tinta saat mencetak. Nilai default: 0 |
| [set_ChecksumAlwaysShow](./set_checksumalwaysshow/)(bool) | Selalu tampilkan digit checksum dalam teks yang dapat dibaca manusia untuk barcode Code128 dan GS1Code128. |
| [set_FilledBars](./set_filledbars/)(bool) | Mengatur nilai yang menunjukkan apakah bar terisi. Hanya untuk barcode 1D. Nilai default: true. |
| [set_GS1CompositeBar](./set_gs1compositebar/)(System::SharedPtr\<GS1CompositeBarParameters\>) | Parameter GS1 Composite Bar. |
| [set_IsChecksumEnabled](./set_ischecksumenabled/)(EnableChecksum) |  |
| [set_ThrowExceptionWhenCodeTextIncorrect](./set_throwexceptionwhencodetextincorrect/)(bool) | Hanya untuk barcode 1D. Jika codetext tidak benar dan nilai diatur ke true - pengecualian akan dilempar. Jika tidak, codetext akan diperbaiki agar sesuai dengan spesifikasi barcode. Pengecualian selalu akan dilempar untuk: Databar symbology jika codetext tidak benar. Pengecualian tidak akan pernah dilempar untuk: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 symbology jika codetext tidak benar. |
| [set_WideNarrowRatio](./set_widenarrowratio/)(float) | Rasio bar lebar terhadap bar sempit. Nilai default: 3, yaitu bar lebar 3 kali lebih lebar daripada bar sempit. Digunakan untuk ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [set_XDimension](./set_xdimension/)(System::SharedPtr\<Unit\>) | x-dimension adalah lebar terkecil dari unit bar atau spasi [BarCode](../../aspose.barcode/). Meningkatkan nilai ini akan meningkatkan lebar seluruh gambar barcode. Diabaikan jika properti [BaseGenerationParameters::AutoSizeMode](../) diatur ke [AutoSizeMode.Nearest](../autosizemode/) atau [AutoSizeMode.Interpolation](../autosizemode/). |
## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
