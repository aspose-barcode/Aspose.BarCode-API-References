---
title: "Aspose::BarCode::Generation::EncodeTypes class"
linktitle: "EncodeTypes"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::Generation::EncodeTypes class. Menentukan jenis barcode yang akan di-encode dalam C++."
type: docs
weight: 2300
url: /id/cpp/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class


Menentukan jenis barcode yang akan dienkode.

```cpp
class EncodeTypes
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [EncodeTypes](./encodetypes/)() |  |
| static [get_AllEncodeTypes](./get_allencodetypes/)() | Menentukan bahwa data akan diperiksa dengan semua simbol yang tersedia. |
| static [GetNames](./getnames/)() | Mengambil array nama-nama tipe encode. |
| static [Parse](./parse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Mengonversi representasi string dari [BaseEncodeType](../baseencodetype/) menjadi instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Mengonversi representasi string dari [BaseEncodeType](../baseencodetype/) menjadi instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [AustralianPosteParcel](./australianposteparcel/) | Menentukan bahwa data harus di-encode dengan **Australian Post Domestic eParcel Barcode** spesifikasi barcode |
| static [AustraliaPost](./australiapost/) | Mewakili Australia Post Customer [BarCode](../../aspose.barcode/) |
| static [Aztec](./aztec/) | Menentukan bahwa data harus di-encode dengan **Aztec** spesifikasi barcode |
| static [Codabar](./codabar/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **CODABAR** |
| static [CodablockF](./codablockf/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **Codablock-F**. |
| static [Code11](./code11/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **CODE 11** |
| static [Code128](./code128/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **CODE 128** |
| static [Code16K](./code16k/) | Mewakili barcode Code 16K. |
| static [Code32](./code32/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **Code32** |
| static [Code39](./code39/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **Code 39** charset dasar: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **Code 39** charset ASCII penuh: ISO/IEC 16388 |
| static [Code93](./code93/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **CODE 93** |
| static [DatabarExpanded](./databarexpanded/) | Mewakili barcode GS1 Databar yang diperluas. |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Mewakili barcode GS1 Databar yang diperluas dan ditumpuk. |
| static [DatabarLimited](./databarlimited/) | Mewakili barcode GS1 Databar terbatas. |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **GS1 Databar omni-directional**. |
| static [DatabarStacked](./databarstacked/) | Mewakili barcode GS1 Databar yang ditumpuk. |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Mewakili barcode GS1 Databar yang ditumpuk omni-directional. |
| static [DatabarTruncated](./databartruncated/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **GS1 Databar truncated**. |
| static [DataLogic2of5](./datalogic2of5/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **DataLogic 2 of 5** |
| static [DataMatrix](./datamatrix/) | Simbol barcode 2D DataMatrix |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Mewakili barcode Deutsch Post, Simbol ini juga dikenal sebagai Identcode,CodeIdentcode,German Postal 2 of 5 Identcode, Deutsch Post AG Identcode, Deutsch Frachtpost Identcode, Deutsch Post AG (DHL) |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Mewakili barcode Deutsch Post Leitcode, juga dikenal sebagai German Postal 2 of 5 Leitcode, CodeLeitcode, Leitcode, Deutsch Post AG (DHL). |
| static [DotCode](./dotcode/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **DotCode** |
| static [DutchKIX](./dutchkix/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **Dutch KIX** |
| static [EAN13](./ean13/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **EAN-13** |
| static [EAN14](./ean14/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **EAN14** |
| static [EAN8](./ean8/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **EAN-8** |
| static [GS1Aztec](./gs1aztec/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **GS1 Aztec**. Codetext harus berisi tanda kurung untuk AI. |
| static [GS1CodablockF](./gs1codablockf/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **GS1 Codablock-F**. Codetext harus berisi tanda kurung untuk AI. |
| static [GS1Code128](./gs1code128/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **GS1 Code 128**. Codetext harus berisi tanda kurung untuk AI. |
| static [GS1CompositeBar](./gs1compositebar/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **GS1 Composite Bar**. Codetext harus berisi tanda kurung untuk AI. Codetext 1D dan 2D harus dipisahkan dengan simbol '/' |
| static [GS1DataMatrix](./gs1datamatrix/) | Simbol barcode 2D DataMatrix dengan format string GS1 |
| static [GS1DotCode](./gs1dotcode/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **GS1 DotCode**. Codetext harus berisi tanda kurung untuk AI. |
| static [GS1HanXin](./gs1hanxin/) | Simbol barcode 2D HanXin dengan format string GS1 |
| static [GS1MicroPdf417](./gs1micropdf417/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **GS1MicroPdf417**. |
| static [GS1QR](./gs1qr/) | Simbol barcode 2D QR dengan format string GS1 |
| static [HanXin](./hanxin/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **Han Xin**. |
| static [HIBCAztecLIC](./hibcazteclic/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **HIBC LIC Aztec**. |
| static [HIBCAztecPAS](./hibcaztecpas/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **HIBC PAS Aztec**. |
| static [HIBCCode128LIC](./hibccode128lic/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **HIBC LIC Code128**. |
| static [HIBCCode128PAS](./hibccode128pas/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **HIBC PAS Code128**. |
| static [HIBCCode39LIC](./hibccode39lic/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **HIBC LIC Code39**. |
| static [HIBCCode39PAS](./hibccode39pas/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **HIBC PAS Code39**. |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **HIBC LIC DataMatrix**. |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **HIBC PAS DataMatrix**. |
| static [HIBCQRLIC](./hibcqrlic/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **HIBC LIC QR**. |
| static [HIBCQRPAS](./hibcqrpas/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **HIBC PAS QR**. |
| static [IATA2of5](./iata2of5/) | Mewakili barcode IATA 2 of 5. IATA (International Air Transport Association) menggunakan barcode ini untuk manajemen kargo udara. |
| static [Interleaved2of5](./interleaved2of5/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **INTERLEAVED 2 of 5** |
| static [ISBN](./isbn/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **ISBN** |
| static [ISMN](./ismn/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **ISMN** |
| static [ISSN](./issn/) | Menentukan bahwa data harus dikodekan dengan spesifikasi barcode **ISSN** |
| static [ItalianPost25](./italianpost25/) | Mewakili kode batang Italian Post 25. |
| static [ITF14](./itf14/) | Menentukan bahwa data harus dienkode dengan spesifikasi kode batang **ITF14** |
| static [ITF6](./itf6/) | Mewakili Kode Batang ITF-6. |
| static [JapanPost](./japanpost/) | Mewakili Japan Post [BarCode](../../aspose.barcode/) |
| static [MacroPdf417](./macropdf417/) | Menentukan bahwa data harus dienkode dengan spesifikasi kode batang **MacroPdf417** |
| static [Mailmark](./mailmark/) | Mewakili kode batang Royal Mail Mailmark. |
| static [Matrix2of5](./matrix2of5/) | Mewakili Matrix 2 of 5 [BarCode](../../aspose.barcode/) |
| static [MaxiCode](./maxicode/) | Menentukan bahwa data harus dienkode dengan spesifikasi kode batang **MaxiCode** |
| static [MicroPdf417](./micropdf417/) | Menentukan bahwa data harus dienkode dengan spesifikasi kode batang **MicroPdf417** |
| static [MicroQR](./microqr/) | Menentukan bahwa data harus dienkode dengan spesifikasi kode batang **MicroQR Code** |
| static [MSI](./msi/) | Menentukan bahwa data harus dienkode dengan spesifikasi kode batang **MSI Plessey** |
| static [None](./none/) | Tipe enkode tidak ditentukan. |
| static [OneCode](./onecode/) | Menentukan bahwa data harus dienkode dengan spesifikasi kode batang USPS **OneCode** |
| static [OPC](./opc/) | Mewakili Kode Batang OPC (Optical Product Code), juga dikenal sebagai VCA Barcode VCA OPC, Vision Council of America OPC Barcode. |
| static [PatchCode](./patchcode/) | Mewakili kode batang Patch code |
| static [Pdf417](./pdf417/) | Menentukan bahwa data harus dienkode dengan spesifikasi kode batang **Pdf417** |
| static [Pharmacode](./pharmacode/) | Mewakili kode batang Pharmacode. |
| static [Planet](./planet/) | Menentukan bahwa data harus dienkode dengan spesifikasi kode batang **Planet** |
| static [Postnet](./postnet/) | Menentukan bahwa data harus dienkode dengan spesifikasi kode batang **Postnet** |
| static [PZN](./pzn/) | Mewakili kode batang PZN. Simbologi ini juga dikenal sebagai Pharmacy central number, Pharmazentralnummer. PZN7 dan PZN8 didukung. PZN7 dihasilkan dari 6 digit atau kurang, seperti \"123456\". PZN8 dihasilkan dari 7 digit atau lebih, seperti \"1234567\". Digit checksum terakhir yang diberikan diabaikan dan dihasilkan oleh mesin kode batang. |
| static [QR](./qr/) | Menentukan bahwa data harus dienkode dengan spesifikasi kode batang **QR Code** |
| static [RectMicroQR](./rectmicroqr/) | Menentukan bahwa data harus dienkode dengan spesifikasi kode batang **RectMicroQR (rMQR) Code** |
| static [RM4SCC](./rm4scc/) | Mewakili kode batang RM4SCC. RM4SCC (Royal Mail 4-state Customer Code) digunakan untuk proses penyortiran surat otomatis di UK. |
| static [SCC14](./scc14/) | Menentukan bahwa data harus dienkode dengan spesifikasi kode batang **SCC14** |
| static [SingaporePost](./singaporepost/) | Menentukan bahwa data harus dienkode dengan spesifikasi kode batang **Singapore Post Barcode** |
| static [SSCC18](./sscc18/) | Menentukan bahwa data harus dienkode dengan spesifikasi barcode **SSCC18** |
| static [Standard2of5](./standard2of5/) | Menentukan bahwa data harus dienkode dengan spesifikasi barcode **Standard 2 of 5** |
| static [SwissPostParcel](./swisspostparcel/) | Menentukan bahwa data harus dienkode dengan spesifikasi barcode **Swiss Post Parcel Barcode**. Tipe yang didukung: Domestic Mail, International Mail, Additional Services (new) |
| static [UPCA](./upca/) | Menentukan bahwa data harus dienkode dengan spesifikasi barcode **UPC-A** |
| static [UpcaGs1Code128Coupon](./upcags1code128coupon/) | Menentukan bahwa data harus dienkode dengan spesifikasi barcode **UPC coupon with GS1-128 Extended Code**. Contoh string input: BarcodeGenerator.Codetext = "514141100906(8102)03", di mana bagian UPCA adalah "514141100906", bagian GS1Code128 adalah (8102)03. |
| static [UpcaGs1DatabarCoupon](./upcags1databarcoupon/) | Menentukan bahwa data harus dienkode dengan spesifikasi barcode **UPC coupon with GS1 DataBar addition**. Contoh string input: BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000", di mana bagian UPCA adalah "514141100906", bagian Databar adalah "(8110)106141416543213500110000310123196000". Untuk mengubah caption, gunakan Parameters.CaptionAbove.Text = "company prefix + offer code"; |
| static [UPCE](./upce/) | Menentukan bahwa data harus dienkode dengan spesifikasi barcode **UPC-E** |
| static [VIN](./vin/) | Mewakili barcode VIN (Vehicle Identification Number). |
## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
