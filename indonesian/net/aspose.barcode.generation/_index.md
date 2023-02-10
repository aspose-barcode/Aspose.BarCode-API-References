---
title: Aspose.BarCode.Generation
second_title: Aspose.BarCode untuk .NET API Referensi
description: Itu Aspose.BarCode.Generation berisi kelaskelas umum untuk implementasi fungsi pembuatan BarCode.
type: docs
weight: 50
url: /id/net/aspose.barcode.generation/
---
Itu **Aspose.BarCode.Generation** berisi kelas-kelas umum untuk implementasi fungsi pembuatan BarCode.

## Kelas

| Kelas | Keterangan |
| --- | --- |
| [AustralianPostParameters](./australianpostparameters/) | parameter kode batang AustralianPost. |
| [AztecParameters](./aztecparameters/) | parameter Aztec. |
| [BarcodeGenerator](./barcodegenerator/) | BarcodeGenerator untuk pembuatan gambar barcode backend. |
| [BarcodeParameters](./barcodeparameters/) | Parameter pembuatan barcode. |
| [BaseEncodeType](./baseencodetype/) | Kelas dasar untuk SymbologyEncodeType. |
| [BaseGenerationParameters](./basegenerationparameters/) | Parameter pembuatan gambar barcode. |
| [BorderParameters](./borderparameters/) | Parameter perbatasan gambar barcode |
| [CaptionParameters](./captionparameters/) | Parameter keterangan. |
| [CodabarParameters](./codabarparameters/) | Parameter Codabar. |
| [CodablockParameters](./codablockparameters/) | Parameter Codablock. |
| [Code16KParameters](./code16kparameters/) | parameter Code16K. |
| [CodetextParameters](./codetextparameters/) | parameter Codetext. |
| [CouponParameters](./couponparameters/) | Parameter kupon. Digunakan untuk UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarParameters](./databarparameters/) | Parameter bilah data. |
| [DataMatrixParameters](./datamatrixparameters/) | parameter DataMatrix. |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | Generator codetext yang diperluas untuk barcode DotCode 2D untuk Mode ExtendedCodetext dari DotCodeEncodeMode |
| [DotCodeParameters](./dotcodeparameters/) | parameter DotCode. |
| [EncodeTypes](./encodetypes/) | Menentukan jenis barcode yang akan dikodekan. |
| [ExtCodetextBuilder](./extcodetextbuilder/) | Kelas pembantu untuk pembuatan teks kode otomatis dari Extended Codetext Mode |
| [FontUnit](./fontunit/) | Menentukan format tertentu untuk teks, termasuk tampilan font, ukuran, dan atribut gaya dengan ukuran dalam properti nilai Unit. |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | Parameter batang komposit GS1. |
| [ITFParameters](./itfparameters/) | parameter ITF. |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | Generator codetext yang diperluas untuk kode batang MaxiCode untuk Mode ExtendedCodetext dari MaxiCodeEncodeMode |
| [MaxiCodeParameters](./maxicodeparameters/) | parameter MaxiCode. |
| [Padding](./padding/) | Parameter pengisi. |
| [PatchCodeParameters](./patchcodeparameters/) | parameter PatchCode. |
| [Pdf417Parameters](./pdf417parameters/) | parameter PDF417. Berisi parameter PDF417, MacroPDF417 dan MicroPDF417. MacroPDF417 membutuhkan dua bidang: Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua kolom lainnya bersifat opsional. MicroPDF417 dalam mode Structured Append (sama seperti mode MacroPDF417) membutuhkan dua kolom: Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua kolom lainnya bersifat opsional. |
| [PostalParameters](./postalparameters/) | Parameter pos. Digunakan untuk Postnet, Planet. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/) | Generator codetext yang diperluas untuk barcode QR 2D untuk Mode ExtendedCodetext dari QrEncodeMode |
| [QrParameters](./qrparameters/) | parameter QR. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters/) | parameter penambahan terstruktur QR. |
| [SupplementParameters](./supplementparameters/) | Parameter pelengkap. Digunakan untuk Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SymbologyEncodeType](./symbologyencodetype/) | Jenis penyandian simbologi. Lihat EncodeTypes untuk mendapatkan instance. |
| [Unit](./unit/) | Menentukan nilai ukuran dalam satuan yang berbeda (Piksel, Inci, dll.). |
## Pencacahan

| Pencacahan | Keterangan |
| --- | --- |
| [AutoSizeMode](./autosizemode/) | Menentukan berbagai jenis mode ukuran otomatis. |
| [AztecSymbolMode](./aztecsymbolmode/) | Menentukan mode simbol Aztec. |
| [BarcodeClassifications](./barcodeclassifications/) | Klasifikasi Simbologi |
| [BarCodeImageFormat](./barcodeimageformat/) | Menentukan format file gambar. |
| [BorderDashStyle](./borderdashstyle/) | Menentukan gaya garis batas putus-putus. |
| [CodabarChecksumMode](./codabarchecksummode/) | Menentukan algoritme checksum untuk Codabar |
| [CodabarSymbol](./codabarsymbol/) | Menentukan simbol mulai atau berhenti dari spesifikasi kode batang Codabar. |
| [Code128Emulation](./code128emulation/) | Kata kode fungsi untuk emulasi Kode 128. Diterapkan hanya untuk MicroPDF417. Diabaikan untuk barcode PDF417 dan MacroPDF417. |
| [CodeLocation](./codelocation/) | lokasi teks kode |
| [DataMatrixEccType](./datamatrixecctype/) | Tentukan jenis ECC yang akan dikodekan. |
| [DataMatrixEncodeMode](./datamatrixencodemode/) | mode penyandian encoder DataMatrix, default ke Auto |
| [DotCodeEncodeMode](./dotcodeencodemode/) | Mode pengkodean untuk barcode DotCode. |
| [ECIEncodings](./eciencodings/) | Pengidentifikasi Interpretasi Saluran yang Diperluas. Ini digunakan untuk memberi tahu detail pembaca barcode tentang referensi yang digunakan untuk mengkodekan data dalam simbol. Implementasi saat ini terdiri dari semua pengkodean charset terkenal. Saat ini, ini hanya digunakan untuk barcode QR 2D. |
| [EnableChecksum](./enablechecksum/) | Aktifkan checksum selama pembuatan untuk kode batang 1D. |
| [FontMode](./fontmode/) | Mode ukuran font. |
| [ITF14BorderType](./itf14bordertype/) | Barcode tipe batas ITF14 |
| [MacroCharacter](./macrocharacter/) | Nilai Karakter Makro 05 dan 06 digunakan untuk mendapatkan penyandian yang lebih ringkas dalam mode khusus. 05 Craracter makro diterjemahkan menjadi "[)&gt;\u001E05\u001D" sebagai header data yang didekodekan dan "\u001E\u0004" sebagai cuplikan data yang didekodekan. 06 Craracter makro diterjemahkan ke "[)&gt;\u001E06\u001D" sebagai header data yang didekode dan "\u001E\u0004" sebagai trailer data yang didekode. |
| [MaxiCodeEncodeMode](./maxicodeencodemode/) | Mode penyandian untuk kode batang MaxiCode. |
| [MaxiCodeMode](./maxicodemode/) | Mode penyandian untuk kode batang MaxiCode. |
| [PatchFormat](./patchformat/) | Format Kode Patch. Pilih PatchOnly untuk menghasilkan satu PatchCode. Gunakan format halaman untuk menghasilkan halaman Patch dengan PatchCodes sebagai border |
| [Pdf417CompactionMode](./pdf417compactionmode/) | Mode pemadatan kode batang pdf417 |
| [Pdf417ErrorLevel](./pdf417errorlevel/) | level koreksi error barcode pdf417, dari level 0 ke level 9, level 0 artinya tidak ada koreksi error, level 9 artinya koreksi error terbaik |
| [Pdf417MacroTerminator](./pdf417macroterminator/) | Digunakan untuk memberi tahu encoder apakah akan menambahkan Macro PDF417 Terminator (codeword 922) ke segmen. Hanya berlaku untuk Makro PDF417. |
| [QREncodeMode](./qrencodemode/) | Mode penyandian untuk kode batang QR. Disarankan untuk Menggunakan Otomatis dengan CodeTextEncoding = Encoding.UTF8 untuk simbol atau angka Latin dan Utf8BOM untuk simbol Unicode. |
| [QREncodeType](./qrencodetype/) | Mode pemilih QR / MikroQR. Pilih ForceQR untuk simbol QR standar, Otomatis untuk MicroQR. ForceMicroQR digunakan untuk pembuatan simbol MicroQR yang kuat jika memungkinkan. |
| [QRErrorLevel](./qrerrorlevel/) | Tingkat koreksi kesalahan Reed-Solomon. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH. |
| [QRVersion](./qrversion/) | Versi Kode QR. Dari Versi 1 hingga Versi 40 untuk kode QR dan dari M1 hingga M4 untuk MicroQr. |
| [TextAlignment](./textalignment/) | Perataan teks. |
| [TwoDComponentType](./twodcomponenttype/) | Jenis komponen 2D |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
