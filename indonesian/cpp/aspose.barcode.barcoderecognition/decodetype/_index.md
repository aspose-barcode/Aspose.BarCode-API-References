---
title: "Aspose::BarCode::BarCodeRecognition::DecodeType kelas"
linktitle: "DecodeType"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::BarCodeRecognition::DecodeType kelas. Menentukan tipe barcode yang akan dibaca dalam C++."
type: docs
weight: 1600
url: /id/cpp/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class


Tentukan tipe kode batang yang akan dibaca.

```cpp
class DecodeType
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [DecodeType](./decodetype/)() |  |
| static [get_AllSupportedTypesArray](./get_allsupportedtypesarray/)() | Mendapatkan array yang mewakili AllSupportedTypes |
| static [GetNames](./getnames/)() | Mengambil array nama-nama tipe decode. |
| static [Is1D](./is1d/)(System::SharedPtr\<BaseDecodeType\>) | Menentukan apakah [BaseDecodeType](../basedecodetype/) yang ditentukan berisi simbol barcode 1D apa pun |
| static [Is2D](./is2d/)(System::SharedPtr\<BaseDecodeType\>) | Menentukan apakah [BaseDecodeType](../basedecodetype/) yang ditentukan berisi simbol barcode 2D apa pun |
| static [IsPostal](./ispostal/)(System::SharedPtr\<BaseDecodeType\>) | Menentukan apakah [BaseDecodeType](../basedecodetype/) yang ditentukan berisi simbol barcode Pos apa pun |
| static [Parse](./parse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Mengonversi representasi string dari [SingleDecodeType](../singledecodetype/) menjadi instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |
| static [ScanSets](./scansets/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Tentukan set pemindaian berdasarkan barcodeTypes |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Mengonversi representasi string dari [SingleDecodeType](../singledecodetype/) menjadi instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Mengonversi representasi string dari [MultiDecodeType](../multidecodetype/) ke instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [AllSupportedTypes](./allsupportedtypes/) | Menentukan bahwa data akan diperiksa dengan semua simbol yang tersedia |
| static [AustralianPosteParcel](./australianposteparcel/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Australian Post Domestic eParcel Barcode** |
| static [AustraliaPost](./australiapost/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Australia Post** |
| static [Aztec](./aztec/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Aztec** |
| static [Codabar](./codabar/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **CODABAR** |
| static [CodablockF](./codablockf/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **CodablockF** |
| static [Code11](./code11/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **CODE 11** |
| static [Code128](./code128/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **CODE 128** |
| static [Code16K](./code16k/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **SCode16K** |
| static [Code32](./code32/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Code32** |
| static [Code39](./code39/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Code 39** set karakter dasar: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Code 39** set karakter ASCII penuh: ISO/IEC 16388 |
| static [Code93](./code93/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **CODE 93** |
| static [CompactPdf417](./compactpdf417/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **CompactPdf417** (Pdf417Truncated) |
| static [DatabarExpanded](./databarexpanded/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **GS1 Databar expanded** |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **GS1 Databar expanded stacked** |
| static [DatabarLimited](./databarlimited/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **GS1 Databar limited** |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **GS1 Databar omni-directional** |
| static [DatabarStacked](./databarstacked/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **GS1 Databar stacked** |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **GS1 Databar stacked omni-directional** |
| static [DatabarTruncated](./databartruncated/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **GS1 Databar truncated** |
| static [DataLogic2of5](./datalogic2of5/) | Menentukan bahwa data harus didekode dengan **DataLogic 2 of 5** spesifikasi barcode |
| static [DataMatrix](./datamatrix/) | Menentukan bahwa data harus didekode dengan **[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** simbol barcode |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Menentukan bahwa data harus didekode dengan **DeutschePost Ident code** spesifikasi barcode |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Menentukan bahwa data harus didekode dengan **DeutschePost Leit code** spesifikasi barcode |
| static [DotCode](./dotcode/) | Menentukan bahwa data harus didekode dengan **DotCode** spesifikasi barcode |
| static [DutchKIX](./dutchkix/) | Menentukan bahwa data harus didekode dengan **DotCode** spesifikasi barcode |
| static [EAN13](./ean13/) | Menentukan bahwa data harus didekode dengan **EAN-13** spesifikasi barcode |
| static [EAN14](./ean14/) | Menentukan bahwa data harus didekode dengan **EAN14** spesifikasi barcode |
| static [EAN8](./ean8/) | Menentukan bahwa data harus didekode dengan **EAN-8** spesifikasi barcode |
| static [GS1Aztec](./gs1aztec/) | Menentukan bahwa data harus didekode dengan **GS1 Aztec** spesifikasi barcode |
| static [GS1Code128](./gs1code128/) | Menentukan bahwa data harus didekode dengan **GS1 CODE 128** spesifikasi barcode |
| static [GS1CompositeBar](./gs1compositebar/) | Menentukan bahwa data harus didekode dengan **GS1 Composite Bar** spesifikasi barcode |
| static [GS1DataMatrix](./gs1datamatrix/) | Menentukan bahwa data harus didekode dengan **GS1DataMatrix** simbol barcode |
| static [GS1DotCode](./gs1dotcode/) | Menentukan bahwa data harus didekode dengan **GS1 DotCode** spesifikasi barcode |
| static [GS1HanXin](./gs1hanxin/) | Menentukan bahwa data harus didekode dengan **GS1 Han Xin Code** spesifikasi barcode |
| static [GS1MicroPdf417](./gs1micropdf417/) | Menentukan bahwa data harus didekode dengan **MicroPdf417** spesifikasi barcode |
| static [GS1QR](./gs1qr/) | Menentukan bahwa data harus didekode dengan **GS1 [QR](../../aspose.barcode.barcoderecognition.qr/)** spesifikasi barcode |
| static [HanXin](./hanxin/) | Menentukan bahwa data harus didekode dengan **Han Xin Code** spesifikasi barcode |
| static [HIBCAztecLIC](./hibcazteclic/) | Menentukan bahwa data harus didekode dengan **HIBC LIC Aztec** spesifikasi barcode |
| static [HIBCAztecPAS](./hibcaztecpas/) | Menentukan bahwa data harus didekode dengan **HIBC PAS Aztec** spesifikasi barcode |
| static [HIBCCode128LIC](./hibccode128lic/) | Menentukan bahwa data harus didekode dengan **HIBC LIC Code128** spesifikasi barcode |
| static [HIBCCode128PAS](./hibccode128pas/) | Menentukan bahwa data harus didekode dengan **HIBC PAS Code128** spesifikasi barcode |
| static [HIBCCode39LIC](./hibccode39lic/) | Menentukan bahwa data harus didekode dengan **HIBC LIC Code39** spesifikasi barcode |
| static [HIBCCode39PAS](./hibccode39pas/) | Menentukan bahwa data harus didekode dengan **HIBC PAS Code39** spesifikasi barcode |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Menentukan bahwa data harus didekode dengan **HIBC LIC [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** spesifikasi barcode |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Menentukan bahwa data harus didekode dengan **HIBC PAS [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** spesifikasi barcode |
| static [HIBCQRLIC](./hibcqrlic/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **HIBC LIC [QR](../../aspose.barcode.barcoderecognition.qr/)** |
| static [HIBCQRPAS](./hibcqrpas/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **HIBC PAS [QR](../../aspose.barcode.barcoderecognition.qr/)** |
| static [IATA2of5](./iata2of5/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **IATA 2 of 5**. IATA (International Air Transport Association) menggunakan barcode ini untuk pengelolaan kargo udara. |
| static [Interleaved2of5](./interleaved2of5/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **INTERLEAVED 2 of 5** |
| static [ISBN](./isbn/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **ISBN** |
| static [ISMN](./ismn/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **ISMN** |
| static [ISSN](./issn/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **ISSN** |
| static [ItalianPost25](./italianpost25/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Italian Post 25** |
| static [ITF14](./itf14/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **ITF14** |
| static [ITF6](./itf6/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **ITF6** |
| static [JapanPost](./japanpost/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Japan Post** |
| static [MacroPdf417](./macropdf417/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **MacroPdf417** |
| static [Mailmark](./mailmark/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Royal Mail Mailmark**. |
| static [Matrix2of5](./matrix2of5/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Matrix 2 of 5** |
| static [MaxiCode](./maxicode/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **MaxiCode** |
| static [MicrE13B](./micre13b/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **MICR E-13B** |
| static [MicroPdf417](./micropdf417/) | Menentukan bahwa data harus didekode dengan **MicroPdf417** spesifikasi barcode |
| static [MicroQR](./microqr/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **MicroQR Code** |
| static [MostCommonTypes](./mostcommontypes/) | Menentukan bahwa data akan diperiksa dengan simbol yang paling umum digunakan |
| static [MSI](./msi/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **MSI Plessey** |
| static [None](./none/) | Tipe decode tidak ditentukan. |
| static [OneCode](./onecode/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode USPS **OneCode** |
| static [OPC](./opc/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **OPC** |
| static [PatchCode](./patchcode/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Patch code**. Simbol barcode ini digunakan untuk pemindaian otomatis |
| static [Pdf417](./pdf417/) | Menentukan bahwa data harus didekode dengan simbol barcode **Pdf417** |
| static [Pharmacode](./pharmacode/) | Menentukan bahwa data harus didekode dengan barcode **Pharmacode**. Simbol ini juga dikenal sebagai Pharmaceutical Binary Code |
| static [Planet](./planet/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Planet** |
| static [PostalTypes](./postaltypes/) | Menentukan bahwa data akan diperiksa dengan semua simbol barcode **1.5D Postal**, seperti **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** |
| static [Postnet](./postnet/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Postnet** |
| static [PZN](./pzn/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **PZN**. Simbol ini juga dikenal sebagai Pharma Zentral Nummer. PZN7 dan PZN8 didukung. |
| static [QR](./qr/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **[QR](../../aspose.barcode.barcoderecognition.qr/) Code** |
| static [RectMicroQR](./rectmicroqr/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **RectMicroQR (rMQR) Code** |
| static [RM4SCC](./rm4scc/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **RM4SCC**. RM4SCC (Royal Mail 4-state Customer Code) digunakan untuk proses penyortiran surat otomatis di Inggris. |
| static [SCC14](./scc14/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **SCC14** |
| static [SSCC18](./sscc18/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **SSCC18** |
| static [Standard2of5](./standard2of5/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Standard 2 of 5** |
| static [Supplement](./supplement/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Supplement(EAN2, EAN5)** |
| static [SwissPostParcel](./swisspostparcel/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Swiss Post Parcel Barcode** |
| static [Types1D](./types1d/) | Menentukan bahwa data akan diperiksa dengan semua simbol barcode **1D** |
| static [Types2D](./types2d/) | Menentukan bahwa data akan diperiksa dengan semua simbol barcode **2D** |
| static [UPCA](./upca/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **UPC-A** |
| static [UPCE](./upce/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **UPC-E** |
| static [VIN](./vin/) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **VIN** (Vehicle Identification Number) |
## Catatan


Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## Lihat Juga

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
