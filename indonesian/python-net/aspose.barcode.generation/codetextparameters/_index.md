---
title: "CodetextParameters"
second_title: "Aspose.BarCode for Python via .NET Referensi API"
description: 
type: docs
url: /id/python-net/aspose.barcode.generation/codetextparameters/
---

## CodetextParameters class

Parameter codetext.

Tipe CodetextParameters menyajikan anggota berikut:
## Properti
| Nama | Deskripsi |
| :- | :- |
| two_d_display_text | Teks yang akan ditampilkan alih-alih codetext pada barcode 2D.<br/>            Digunakan untuk: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| font_mode | Tentukan FontMode. Jika FontMode diatur ke Auto, ukuran font akan dihitung secara otomatis berdasarkan nilai xDimension.<br/>            Disarankan menggunakan FontMode.Auto terutama pada AutoSizeMode.Nearest atau AutoSizeMode.Interpolation.<br/>            Nilai default: FontMode.Auto. |
| font | Tentukan font yang menampilkan CodeText.<br/>            Nilai default: Arial 5pt regular.<br/>            Diabaikan jika FontMode diatur ke FontMode.Auto. |
| space | Spasi antara CodeText dan BarCode dalam nilai [Unit](/barcode/python-net/aspose.barcode.generation/unit/).<br/>            Nilai default: 2pt.<br/>            Diabaikan untuk EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| perataan | Mendapatkan atau mengatur perataan teks kode.<br/>            Nilai default: StringAlignment.Center. |
| warna | Tentukan Warna CodeText yang ditampilkan.<br/>            Nilai default: Color.Black. |
| lokasi | Tentukan Lokasi CodeText yang ditampilkan, setel ke CodeLocation.None untuk menyembunyikan CodeText.<br/>            Nilai default: CodeLocation.Below untuk barcode 1D dan CodeLocation.None untuk barcode 2D. |
| tanpa_lipat | Tentukan pembungkusan kata (pemutusan baris) dalam teks.<br/>            Nilai default: false. |

### Lihat Juga

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

