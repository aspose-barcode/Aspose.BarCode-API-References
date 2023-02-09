---
title: BarcodeParameters
second_title: Aspose.BarCode untuk .NET API Referensi
description: Parameter pembuatan barcode.
type: docs
weight: 710
url: /id/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

Parameter pembuatan barcode.

```csharp
public class BarcodeParameters
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost/) { get; } | parameter kode batang AustralianPost. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec/) { get; } | parameter Aztec. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor/) { get; set; } | Warna batang. Nilai default: Warna.Hitam. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight/) { get; set; } | Tinggi bar barcode 1D di[`Unit`](../unit/) value. Jika diabaikanAutoSizeMode properti diatur ke AutoSizeMode.Nearest atau AutoSizeMode.Interpolation. |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction/) { get; set; } | Mendapatkan atau menetapkan nilai pengurangan batang yang digunakan untuk mengkompensasi penyebaran tinta saat mencetak. Nilai default: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow/) { get; set; } | Selalu tampilkan digit checksum dalam teks yang dapat dibaca manusia untuk kode batang Code128 dan GS1Code128. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar/) { get; } | Parameter Codabar. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock/) { get; } | Parameter Codablock. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k/) { get; } | parameter Code16K. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters/) { get; } | parameter Codetext. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon/) { get; } | Parameter kupon. Digunakan untuk UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar/) { get; } | Parameter bilah data. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix/) { get; } | parameter DataMatrix. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode/) { get; } | parameter DotCode. |
| [EnableEscape](../../aspose.barcode.generation/barcodeparameters/enableescape/) { get; set; } | Menunjukkan apakah menjelaskan karakter "\" sebagai karakter pelarian di properti CodeText. Digunakan untuk Pdf417, DataMatrix, Code128 only Jika EnableEscape benar, "\" akan dijelaskan sebagai karakter escape khusus. Jika tidak, "\" berfungsi sebagai karakter normal. Aspose.BarCode mendukung penginputan kode ascii desimal dan mnemonik untuk karakter kode kontrol ASCII. Misalnya, \013 dan \\CR singkatan dari CR. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah bar terisi. Hanya untuk barcode 1D. Nilai default: true. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar/) { get; set; } | Parameter Batang Komposit GS1. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled/) { get; set; } | Aktifkan checksum selama pembuatan barcode 1D. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf/) { get; } | parameter ITF. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode/) { get; } | parameter MaxiCode. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding/) { get; } | Barcode paddings. Nilai default: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode/) { get; } | parameter PatchCode. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417/) { get; } | parameter PDF417. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal/) { get; } | Parameter pos. Digunakan untuk Postnet, Planet. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr/) { get; } | parameter QR. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement/) { get; } | Parameter pelengkap. Digunakan untuk Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect/) { get; set; } | Hanya untuk kode batang 1D. Jika teks kode salah dan nilainya disetel ke benar - pengecualian akan dibuang. Jika tidak, teks kode akan diperbaiki agar sesuai dengan spesifikasi kode batang. Pengecualian selalu akan ditampilkan untuk: Simbologi bilah data jika teks kode salah. Pengecualian selalu tidak akan ditampilkan untuk: Simbologi AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128 jika teks kode salah . |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio/) { get; set; } | Rasio batang lebar ke batang sempit. Nilai default: 3, yaitu, batang lebar 3 kali lebar batang sempit. Digunakan untuk ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension/) { get; set; } | x-dimension adalah lebar terkecil dari satuan bar atau spasi BarCode. Peningkatan ini akan menambah lebar seluruh gambar barcode. Diabaikan jikaAutoSizeMode properti diatur ke AutoSizeMode.Nearest atau AutoSizeMode.Interpolation. |

### Lihat juga

* ruang nama [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
