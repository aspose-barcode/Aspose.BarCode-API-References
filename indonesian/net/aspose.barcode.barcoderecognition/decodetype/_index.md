---
title: DecodeType
second_title: Aspose.BarCode untuk .NET API Referensi
description: Tentukan jenis barcode yang akan dibaca.
type: docs
weight: 190
url: /id/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

Tentukan jenis barcode yang akan dibaca.

```csharp
public static class DecodeType
```

## Properti

| Nama | Keterangan |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray/) { get; } | Mendapat array yang mewakili AllSupportedTypes |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames/)() | Mengambil larik nama jenis dekode. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d/)(BaseDecodeType) | Menentukan apakah yang ditentukan[`BaseDecodeType`](../basedecodetype/) berisi simbologi barcode 1D |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d/)(BaseDecodeType) | Menentukan apakah yang ditentukan[`BaseDecodeType`](../basedecodetype/) berisi simbologi barcode 2D |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal/)(BaseDecodeType) | Menentukan apakah yang ditentukan[`BaseDecodeType`](../basedecodetype/) berisi simbologi barcode pos apa saja |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse/)(string, out SingleDecodeType) | Mengonversi representasi string dari SingleDecodeType ke instance-nya. Nilai yang dikembalikan menunjukkan apakah konversi berhasil atau gagal. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets/)(params BaseDecodeType[]) | Tentukan kumpulan pemindaian berdasarkan barcodeTypes |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse)(string, out MultyDecodeType) | Mengonversi representasi string dari MultyDecodeType ke instance-nya. Nilai yang dikembalikan menunjukkan apakah konversi berhasil atau gagal. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse_1)(string, out SingleDecodeType) | Mengonversi representasi string dari SingleDecodeType ke instance-nya. Nilai yang dikembalikan menunjukkan apakah konversi berhasil atau gagal. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes/) | Menentukan bahwa data akan diperiksa dengan semua simbol yang tersedia |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel/) | Menentukan bahwa data harus didekodekan **Barcode eParcel Domestik Pos Australia** spesifikasi kode batang |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost/) | Menentukan bahwa data harus didekodekan **Pos Australia** spesifikasi kode batang |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec/) | Menentukan bahwa data harus didekodekan **Aztek** spesifikasi kode batang |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar/) | Menentukan bahwa data harus didekodekan **CODABAR** spesifikasi kode batang |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf/) | Menentukan bahwa data harus didekodekan **CodablockF** spesifikasi kode batang |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11/) | Menentukan bahwa data harus didekodekan **KODE 11** spesifikasi kode batang |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128/) | Menentukan bahwa data harus didekodekan **KODE 128** spesifikasi kode batang |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k/) | Menentukan bahwa data harus didekodekan **SCode16K** spesifikasi kode batang |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32/) | Menentukan bahwa data harus didekodekan **Kode32** spesifikasi kosong |
| static readonly [Code39Extended](../../aspose.barcode.barcoderecognition/decodetype/code39extended/) | Menentukan bahwa data harus didekodekan **KODE yang Diperpanjang 39** spesifikasi kode batang |
| static readonly [Code39Standard](../../aspose.barcode.barcoderecognition/decodetype/code39standard/) | Menentukan bahwa data harus didekodekan **KODE Standar 39** spesifikasi kode batang |
| static readonly [Code93Extended](../../aspose.barcode.barcoderecognition/decodetype/code93extended/) | Menentukan bahwa data harus didekodekan **KODE yang Diperpanjang 93** spesifikasi kode batang |
| static readonly [Code93Standard](../../aspose.barcode.barcoderecognition/decodetype/code93standard/) | Menentukan bahwa data harus didekodekan **KODE Standar 93** spesifikasi kode batang |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417/) | Menentukan bahwa data harus didekodekan **CompactPdf417** (Pdf417Terpotong) spesifikasi kode batang |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded/) | Menentukan bahwa data harus didekodekan **GS1 Databar diperluas** spesifikasi kode batang |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked/) | Menentukan bahwa data harus didekodekan **GS1 Databar diperluas bertumpuk** spesifikasi kode batang |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited/) | Menentukan bahwa data harus didekodekan **GS1 Databar terbatas** spesifikasi kode batang |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional/) | Menentukan bahwa data harus didekodekan **GS1 Databar omni-directional** spesifikasi kode batang |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked/) | Menentukan bahwa data harus didekodekan **GS1 Databar ditumpuk** spesifikasi kode batang |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional/) | Menentukan bahwa data harus didekodekan **GS1 Databar ditumpuk segala arah** spesifikasi kode batang |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated/) | Menentukan bahwa data harus didekodekan **GS1 Databar terpotong** spesifikasi kode batang |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5/) | Menentukan bahwa data harus didekodekan **DataLogic 2 dari 5** spesifikasi kosong |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix/) | Menentukan bahwa data harus didekodekan **DataMatrix** simbologi barcode |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode/) | Menentukan bahwa data harus didekodekan **Kode Identitas DeutschePost** spesifikasi kode batang |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode/) | Menentukan bahwa data harus didekodekan **Kode DeutschePost Leit** spesifikasi kode batang |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode/) | Menentukan bahwa data harus didekodekan **Kode Titik** spesifikasi kosong |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix/) | Menentukan bahwa data harus didekodekan **Kode Titik** spesifikasi kosong |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13/) | Menentukan bahwa data harus didekodekan **EAN-13** spesifikasi kode batang |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14/) | Menentukan bahwa data harus didekodekan **EAN14** spesifikasi kode batang |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8/) | Menentukan bahwa data harus didekodekan **EAN-8** spesifikasi kode batang |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128/) | Menentukan bahwa data harus didekodekan **KODE GS1 128** spesifikasi kode batang |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix/) | Menentukan bahwa data harus didekodekan **GS1DataMatrix** simbologi barcode |
| static readonly [GS1DotCode](../../aspose.barcode.barcoderecognition/decodetype/gs1dotcode/) | Menentukan bahwa data harus didekodekan **GS1 DotCode** spesifikasi kosong |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr/) | Menentukan bahwa data harus didekodekan **GS1 QR** spesifikasi kode batang |
| static readonly [HIBCAztecLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcazteclic/) | Menentukan bahwa data harus didekodekan **HIBC LIC Aztek** spesifikasi kosong |
| static readonly [HIBCAztecPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcaztecpas/) | Menentukan bahwa data harus didekodekan **HIBC PAS Aztek** spesifikasi kosong |
| static readonly [HIBCCode128LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode128lic/) | Menentukan bahwa data harus didekodekan **Kode HIBC LIC128** spesifikasi kosong |
| static readonly [HIBCCode128PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode128pas/) | Menentukan bahwa data harus didekodekan **Kode HIBC PAS128** spesifikasi kosong |
| static readonly [HIBCCode39LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode39lic/) | Menentukan bahwa data harus didekodekan **Kode HIBC LIC39** spesifikasi kosong |
| static readonly [HIBCCode39PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode39pas/) | Menentukan bahwa data harus didekodekan **Kode HIBC PAS39** spesifikasi kosong |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixlic/) | Menentukan bahwa data harus didekodekan **HIBC LIC DataMatrix** spesifikasi kosong |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixpas/) | Menentukan bahwa data harus didekodekan **HIBC PAS DataMatrix** spesifikasi kosong |
| static readonly [HIBCQRLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcqrlic/) | Menentukan bahwa data harus didekodekan **HIBC LIC QR** spesifikasi kosong |
| static readonly [HIBCQRPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcqrpas/) | Menentukan bahwa data harus didekodekan **HIBC PAS QR** spesifikasi kosong |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5/) | Menentukan bahwa data harus didekodekan **IATA 2 dari 5**spesifikasi kode batang. IATA (International Air Transport Association) menggunakan barcode ini untuk pengelolaan kargo udara. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5/) | Menentukan bahwa data harus didekodekan **INTERLEAVED 2 dari 5** spesifikasi kode batang |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn/) | Menentukan bahwa data harus didekodekan **ISBN** spesifikasi kode batang |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn/) | Menentukan bahwa data harus didekodekan **ISMN** spesifikasi kode batang |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn/) | Menentukan bahwa data harus didekodekan **ISSN** spesifikasi kode batang |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25/) | Menentukan bahwa data harus didekodekan **Pos Italia 25** spesifikasi kode batang |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14/) | Menentukan bahwa data harus didekodekan **ITF14** spesifikasi kode batang |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6/) | Menentukan bahwa data harus didekodekan **ITF6** spesifikasi kode batang |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417/) | Menentukan bahwa data harus didekodekan **MacroPdf417** spesifikasi kode batang |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark/) | Menentukan bahwa data harus didekodekan **Tanda Surat Royal Mail** spesifikasi barcode. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5/) | Menentukan bahwa data harus didekodekan **Matriks 2 dari 5** spesifikasi kode batang |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode/) | Menentukan bahwa data harus didekodekan **MaxiCode** spesifikasi kode batang |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b/) | Menentukan bahwa data harus didekodekan **MICR E-13B** spesifikasi kosong |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417/) | Menentukan bahwa data harus didekodekan **MicroPdf417** spesifikasi kode batang |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr/) | Menentukan bahwa data harus didekodekan **Kode MikroQR** spesifikasi kode batang |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes/) | Menentukan bahwa data akan diperiksa dengan simbol yang paling umum digunakan |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi/) | Menentukan bahwa data harus didekodekan **MSI Plessey** spesifikasi kode batang |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none/) | Jenis dekode tidak ditentukan. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode/) | Menentukan bahwa data harus didekodekan dengan USPS **OneCode** spesifikasi kode batang |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc/) | Menentukan bahwa data harus didekodekan **OPC** spesifikasi kode batang |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode/) | Menentukan bahwa data harus didekodekan **Kode tambalan** spesifikasi kode batang. Simbologi kode batang digunakan untuk pemindaian otomatis |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417/) | Menentukan bahwa data harus didekodekan **Pdf417** simbologi barcode |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode/) | Menentukan bahwa data harus didekodekan **Farmasi** kode batang. Simbologi ini juga dikenal sebagai Pharmaceutical Binary Code |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet/) | Menentukan bahwa data harus didekodekan **Planet** spesifikasi kode batang |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes/) | Menentukan bahwa data akan diperiksa dengan semua **Pos 1.5D** simbologi barcode, seperti **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet/) | Menentukan bahwa data harus didekodekan **Postnet** spesifikasi kode batang |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn/) | Menentukan bahwa data harus didekodekan **PZN** spesifikasi kode batang. Simbologi ini juga dikenal sebagai Pharma Zentral Number |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr/) | Menentukan bahwa data harus didekodekan **Kode QR** spesifikasi kode batang |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc/) | Menentukan bahwa data harus didekodekan **RM4SCC** spesifikasi kode batang. RM4SCC (Royal Mail 4-state Customer Code) digunakan untuk proses pengurutan surat otomatis di Inggris. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14/) | Menentukan bahwa data harus didekodekan **SCC14** spesifikasi kode batang |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18/) | Menentukan bahwa data harus didekodekan **SSCC18** spesifikasi kode batang |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5/) | Menentukan bahwa data harus didekodekan **Standar 2 dari 5** spesifikasi kode batang |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement/) | Menentukan bahwa data harus didekodekan **Tambahan (EAN2, EAN5)** spesifikasi kode batang |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel/) | Menentukan bahwa data harus didekodekan **Barcode Paket Pos Swiss** spesifikasi kode batang |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d/) | Menentukan bahwa data akan diperiksa dengan semua **1D** simbologi barcode |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d/) | Menentukan bahwa data akan diperiksa dengan semua **2D** simbologi barcode |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca/) | Menentukan bahwa data harus didekodekan **UPC-A** spesifikasi kode batang |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce/) | Menentukan bahwa data harus didekodekan **UPC-E** spesifikasi kode batang |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin/) | Menentukan bahwa data harus didekodekan **VIN** (Nomor Identifikasi Kendaraan) spesifikasi barcode |

### Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Lihat juga

* ruang nama [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
