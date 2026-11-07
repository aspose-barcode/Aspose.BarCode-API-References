---
title: "Aspose::BarCode::Generation::CodetextParameters class"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::Generation::CodetextParameters class. Parameter codetext dalam C++."
type: docs
weight: 1500
url: /id/cpp/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class


Parameter teks kode.

```cpp
class CodetextParameters : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Alignment](./get_alignment/)() const | Mendapatkan perataan teks kode. Nilai default: [StringAlignment.Center](../textalignment/). |
| [get_Color](./get_color/)() const | Tentukan Warna CodeText yang ditampilkan. Nilai default: Color.Black. |
| [get_Font](./get_font/)() const | Tentukan font CodeText yang ditampilkan. Nilai default: Arial 5pt regular. Diabaikan jika FontMode diatur ke [FontMode.Auto](../aztecencodemode/). |
| [get_FontMode](./get_fontmode/)() const | Tentukan FontMode. Jika FontMode diatur ke Auto, ukuran font akan dihitung secara otomatis berdasarkan nilai xDimension. Disarankan untuk menggunakan [FontMode.Auto](../aztecencodemode/) terutama dalam [AutoSizeMode.Nearest](../autosizemode/) atau [AutoSizeMode.Interpolation](../autosizemode/). Nilai default: [FontMode.Auto](../aztecencodemode/). |
| [get_Location](./get_location/)() const | Tentukan Lokasi CodeText yang ditampilkan, atur ke [CodeLocation.None](../codelocation/) untuk menyembunyikan CodeText. Nilai default: [CodeLocation.Below](../codelocation/) untuk barcode 1D dan [CodeLocation.None](../codelocation/) untuk barcode 2D. |
| [get_NoWrap](./get_nowrap/)() const | Tentukan pembungkusan kata (pemotongan baris) dalam teks. Nilai default: false. |
| [get_Space](./get_space/)() const | Jarak antara CodeText dan [BarCode](../../aspose.barcode/) dalam nilai [Unit ](../unit/). Nilai default: 2pt. Diabaikan untuk EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [get_TwoDDisplayText](./get_twoddisplaytext/)() const | Teks yang akan ditampilkan sebagai pengganti codetext pada barcode 2D. Digunakan untuk: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [set_Alignment](./set_alignment/)(TextAlignment) | Mengatur perataan teks kode. Nilai default: [StringAlignment.Center](../textalignment/). |
| [set_Color](./set_color/)(System::Drawing::Color) | Tentukan Warna CodeText yang ditampilkan. Nilai default: Color.Black. |
| [set_FontMode](./set_fontmode/)(Aspose::BarCode::Generation::FontMode) | Tentukan FontMode. Jika FontMode diatur ke Auto, ukuran font akan dihitung secara otomatis berdasarkan nilai xDimension. Disarankan untuk menggunakan [FontMode.Auto](../aztecencodemode/) terutama dalam [AutoSizeMode.Nearest](../autosizemode/) atau [AutoSizeMode.Interpolation](../autosizemode/). Nilai default: [FontMode.Auto](../aztecencodemode/). |
| [set_Location](./set_location/)(CodeLocation) | Tentukan Lokasi CodeText yang ditampilkan, atur ke [CodeLocation.None](../codelocation/) untuk menyembunyikan CodeText. Nilai default: [CodeLocation.Below](../codelocation/) untuk barcode 1D dan [CodeLocation.None](../codelocation/) untuk barcode 2D. |
| [set_NoWrap](./set_nowrap/)(bool) | Tentukan pembungkusan kata (pemotongan baris) dalam teks. Nilai default: false. |
| [set_Space](./set_space/)(System::SharedPtr\<Unit\>) | Jarak antara CodeText dan [BarCode](../../aspose.barcode/) dalam nilai [Unit ](../unit/). Nilai default: 2pt. Diabaikan untuk EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [set_TwoDDisplayText](./set_twoddisplaytext/)(System::String) | Teks yang akan ditampilkan sebagai pengganti codetext pada barcode 2D. Digunakan untuk: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [CodetextParameters](./). |
## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
