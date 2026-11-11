---
title: "Sınıf DecodeType"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.DecodeType sınıfı. Okunacak barkod tipini belirtin"
type: docs
weight: 230
url: /tr/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

Okunacak barkod tipini belirtin.

```csharp
public static class DecodeType
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray/) { get; } | AllSupportedTypes'ı temsil eden bir dizi alır |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames/)() | Kod çözme türlerinin adlarını içeren bir dizi alır. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d/)(BaseDecodeType) | Belirtilen [`BaseDecodeType`](../basedecodetype/) öğesinin herhangi bir 1D barkod sembolojisi içerip içermediğini belirler |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d/)(BaseDecodeType) | Belirtilen [`BaseDecodeType`](../basedecodetype/) öğesinin herhangi bir 2D barkod sembolojisi içerip içermediğini belirler |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal/)(BaseDecodeType) | Belirtilen [`BaseDecodeType`](../basedecodetype/) öğesinin herhangi bir Posta barkod sembolojisi içerip içermediğini belirler |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse/)(string, out SingleDecodeType) | SingleDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer dönüşümün başarılı olup olmadığını gösterir. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets/)(params BaseDecodeType[]) | barcodeTypes ile tarama setlerini belirtin |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse)(string, out MultiDecodeType) | MultiDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer dönüşümün başarılı olup olmadığını gösterir. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse_1)(string, out SingleDecodeType) | SingleDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer dönüşümün başarılı olup olmadığını gösterir. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes/) | Verilerin tüm mevcut sembolojilerle kontrol edileceğini belirtir |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel/) | Verilerin **Australian Post Domestic eParcel Barcode** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost/) | Verilerin **Australia Post** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec/) | Verilerin **Aztec** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar/) | Verilerin **CODABAR** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf/) | Verilerin **CodablockF** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11/) | Verilerin **CODE 11** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128/) | Verilerin **CODE 128** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k/) | Verilerin **SCode16K** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32/) | Verilerin **Code32** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [Code39](../../aspose.barcode.barcoderecognition/decodetype/code39/) | Verilerin **Code 39** temel karakter kümesi barkod spesifikasyonu ile çözüleceğini belirtir: ISO/IEC 16388 |
| static readonly [Code39FullASCII](../../aspose.barcode.barcoderecognition/decodetype/code39fullascii/) | Verilerin **Code 39** tam ASCII karakter kümesi barkod spesifikasyonu ile çözüleceğini belirtir: ISO/IEC 16388 |
| static readonly [Code93](../../aspose.barcode.barcoderecognition/decodetype/code93/) | Verinin **CODE 93** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417/) | Verinin **CompactPdf417** (Pdf417Truncated) barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded/) | Verinin **GS1 Databar expanded** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked/) | Verinin **GS1 Databar expanded stacked** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited/) | Verinin **GS1 Databar limited** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional/) | Verinin **GS1 Databar omni-directional** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked/) | Verinin **GS1 Databar stacked** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional/) | Verinin **GS1 Databar stacked omni-directional** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated/) | Verinin **GS1 Databar truncated** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5/) | Verinin **DataLogic 2 of 5** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix/) | Verinin **DataMatrix** barkod sembolojisiyle çözüleceğini belirtir |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode/) | Verinin **DeutschePost Ident code** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode/) | Verinin **DeutschePost Leit code** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode/) | Verinin **DotCode** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix/) | Verinin **DotCode** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13/) | Verinin **EAN-13** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14/) | Verinin **EAN14** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8/) | Verinin **EAN-8** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [GS1Aztec](../../aspose.barcode.barcoderecognition/decodetype/gs1aztec/) | Verinin **GS1 Aztec** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128/) | Verinin **GS1 CODE 128** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [GS1CompositeBar](../../aspose.barcode.barcoderecognition/decodetype/gs1compositebar/) | Verinin **GS1 Composite Bar** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix/) | Verinin **GS1DataMatrix** barkod sembolojisiyle çözüleceğini belirtir |
| static readonly [GS1DotCode](../../aspose.barcode.barcoderecognition/decodetype/gs1dotcode/) | Verinin **GS1 DotCode** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [GS1HanXin](../../aspose.barcode.barcoderecognition/decodetype/gs1hanxin/) | Verinin **GS1 Han Xin Code** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [GS1MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/gs1micropdf417/) | Verinin **MicroPdf417** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr/) | Verinin **GS1 QR** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [HanXin](../../aspose.barcode.barcoderecognition/decodetype/hanxin/) | Verinin **Han Xin Code** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [HIBCAztecLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcazteclic/) | Verinin **HIBC LIC Aztec** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [HIBCAztecPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcaztecpas/) | Verinin **HIBC PAS Aztec** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [HIBCCode128LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode128lic/) | Verinin **HIBC LIC Code128** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [HIBCCode128PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode128pas/) | Verinin **HIBC PAS Code128** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [HIBCCode39LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode39lic/) | Verinin **HIBC LIC Code39** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [HIBCCode39PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode39pas/) | Verinin **HIBC PAS Code39** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixlic/) | Verinin **HIBC LIC DataMatrix** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixpas/) | Verinin **HIBC PAS DataMatrix** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [HIBCQRLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcqrlic/) | Verinin **HIBC LIC QR** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [HIBCQRPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcqrpas/) | Verinin **HIBC PAS QR** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5/) | Verinin **IATA 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir. IATA (Uluslararası Hava Taşımacılığı Birliği), bu barkodu hava kargo yönetimi için kullanır. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5/) | Verinin **INTERLEAVED 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn/) | Verinin **ISBN** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn/) | Verinin **ISMN** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn/) | Verinin **ISSN** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25/) | Verinin **Italian Post 25** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14/) | Verinin **ITF14** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6/) | Verinin **ITF6** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [JapanPost](../../aspose.barcode.barcoderecognition/decodetype/japanpost/) | Verinin **Japan Post** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417/) | Verinin **MacroPdf417** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark/) | Verinin **Royal Mail Mailmark** barkod spesifikasyonu ile çözüleceğini belirtir. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5/) | Verinin **Matrix 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode/) | Verinin **MaxiCode** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b/) | Verinin **MICR E-13B** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417/) | Verinin **MicroPdf417** barkod spesifikasyonuyle çözüleceğini belirtir |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr/) | Verilerin **MicroQR Code** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes/) | Verilerin en yaygın kullanılan sembolojilerle kontrol edileceğini belirtir |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi/) | Verilerin **MSI Plessey** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none/) | Belirtilmemiş çözümleme türü. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode/) | Verilerin USPS **OneCode** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc/) | Verilerin **OPC** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode/) | Verilerin **Patch code** barkod spesifikasyonu ile çözüleceğini belirtir. Barkod sembolojisi otomatik tarama için kullanılır |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417/) | Verilerin **Pdf417** barkod sembolojisi ile çözüleceğini belirtir |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode/) | Verilerin **Pharmacode** barkodu ile çözüleceğini belirtir. Bu semboloji ayrıca Pharmaceutical Binary Code olarak da bilinir |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet/) | Verilerin **Planet** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes/) | Verilerin **1.5D Postal** barkod sembollerinin tümüyle, örneğin **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** gibi, kontrol edileceğini belirtir |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet/) | Verilerin **Postnet** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn/) | Verilerin **PZN** barkod spesifikasyonu ile çözüleceğini belirtir. Bu semboloji ayrıca Pharma Zentral Nummer olarak da bilinir. PZN7 ve PZN8 desteklenir. |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr/) | Verilerin **QR Code** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [RectMicroQR](../../aspose.barcode.barcoderecognition/decodetype/rectmicroqr/) | Verilerin **RectMicroQR (rMQR) Code** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc/) | Verilerin **RM4SCC** barkod spesifikasyonu ile çözüleceğini belirtir. RM4SCC (Royal Mail 4-state Customer Code), Birleşik Krallık'ta otomatik posta sınıflandırma sürecinde kullanılır. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14/) | Verilerin **SCC14** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18/) | Verilerin **SSCC18** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5/) | Verilerin **Standard 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement/) | Verilerin **Supplement(EAN2, EAN5)** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel/) | Verilerin **Swiss Post Parcel Barcode** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d/) | Verilerin **1D** barkod sembollerinin tümüyle kontrol edileceğini belirtir |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d/) | Verilerin **2D** barkod sembollerinin tümüyle kontrol edileceğini belirtir |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca/) | Verilerin **UPC-A** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce/) | Verilerin **UPC-E** barkod spesifikasyonu ile çözüleceğini belirtir |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin/) | Verilerin **VIN** (Vehicle Identification Number) barkod spesifikasyonu ile çözüleceğini belirtir |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
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

### Ayrıca Bakınız

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


