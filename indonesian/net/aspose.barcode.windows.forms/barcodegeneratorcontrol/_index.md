---
title: BarCodeGeneratorControl
second_title: Aspose.BarCode untuk .NET API Referensi
description: BarCode Windows Control buka panel toolbox Anda dan tambahkan Aspose.BarCode.dll dan Anda akan melihat BarcodeGeneratorControl muncul. Cukup seret dan lepas ke formulir Windows Anda. lihat lihat
type: docs
weight: 1320
url: /id/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control, buka panel toolbox Anda dan tambahkan Aspose.BarCode.dll, dan Anda akan melihat BarcodeGeneratorControl muncul. Cukup seret dan lepas ke formulir Windows Anda. lihat lihat

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol/)() | Konstruktor default. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode/) { get; set; } | Mendapatkan atau menyetel mode di mana kode batang diubah ukurannya secara otomatis. Nilai default adalah AutoSizeMode.None. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor/) { get; set; } | Warna latar belakang gambar barcode. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight/) { get; } | tinggi gambar BarCode saat[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) properti diatur ke AutoSizeMode.Nearest atau AutoSizeMode.Interpolation. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings/) { get; } | Mendapat atau menyetel parameter bantalan Barcode[`Padding`](../../aspose.barcode.generation/padding/) . |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype/) { get; set; } | Jenis enkode BarCode (simbolologi). Penggunaan[`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) untuk mendapatkan simbologi saat ini. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth/) { get; } | Lebar gambar BarCode saat[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) properti diatur ke AutoSizeMode.Nearest atau AutoSizeMode.Interpolation. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor/) { get; set; } | Warna batang. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight/) { get; } | Tinggi batang barcode 1D. Diabaikan jika[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) properti diatur ke AutoSizeMode.Nearest atau AutoSizeMode.Interpolation. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border/) { get; } | Mendapat atau menyetel parameter Perbatasan[`BorderParameters`](../../aspose.barcode.generation/borderparameters/) . |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove/) { get; } | Caption Di Atas Gambar BarCode. Melihat[`CaptionParameters`](../../aspose.barcode.generation/captionparameters/) . |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow/) { get; } | Keterangan Di bawah gambar BarCode. Melihat[`CaptionParameters`](../../aspose.barcode.generation/captionparameters/) . |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow/) { get; set; } | Selalu tampilkan digit checksum dalam teks yang dapat dibaca manusia untuk kode batang Code128 dan GS1Code128. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext/) { get; set; } | Data yang akan dikodekan, jenis BarCode yang berbeda mungkin memiliki batasan panjang CodeText yang berbeda. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters/) { get; } | Mendapat atau mengatur parameter CodeText[`CodetextParameters`](../../aspose.barcode.generation/codetextparameters/) . |
| [EnableEscape](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/enableescape/) { get; set; } | Menunjukkan apakah menjelaskan karakter "\" sebagai karakter pelarian di properti CodeText. Digunakan untuk Pdf417, DataMatrix, Code128 only Jika EnableEscape benar, "\" akan dijelaskan sebagai karakter escape khusus. Jika tidak, "\" berfungsi sebagai karakter normal. Aspose.BarCode mendukung penginputan kode ascii desimal dan mnemonik untuk karakter kode kontrol ASCII. Misalnya, \013 dan \\CR singkatan dari CR. |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype/) { get; set; } | Jenis enkode BarCode (simbolologi). Penggunaan[`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) untuk mendapatkan simbologi saat ini. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah bar terisi. Hanya untuk barcode 1D. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled/) { get; set; } | Aktifkan checksum selama pembuatan barcode 1D. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution/) { get; set; } | Mendapat atau mengatur resolusi gambar BarCode. Satu nilai untuk kedua dimensi. Nilai default: 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle/) { get; set; } | Sudut rotasi gambar BarCode, diukur dalam derajat, misalnya RotationAngle = 0 atau RotationAngle = 360 berarti tidak ada rotasi. Jika RotationAngle TIDAK sama dengan 90, 180, 270 atau 0, ini dapat menambah kesulitan pemindai untuk membaca gambar. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific/) { get; } | Parameter spesifik |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect/) { get; set; } | Hanya untuk kode batang 1D. Jika teks kode salah dan nilainya disetel ke benar - pengecualian akan dibuang. Jika tidak, teks kode akan diperbaiki agar sesuai dengan spesifikasi kode batang. Pengecualian selalu akan ditampilkan untuk: Simbologi bilah data jika teks kode salah. Pengecualian selalu tidak akan ditampilkan untuk: Simbologi AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128 jika teks kode salah . |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio/) { get; set; } | Rasio batang lebar ke batang sempit. Nilai default: 3, yaitu, batang lebar 3 kali lebar batang sempit. Digunakan untuk ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension/) { get; } | X-dimension adalah lebar terkecil dari unit bar atau spasi BarCode. Peningkatan ini akan menambah lebar seluruh gambar barcode. Diabaikan jika[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) properti diatur ke AutoSizeMode.Nearest atau AutoSizeMode.Interpolation. |

### Lihat juga

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol/)
* ruang nama [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
