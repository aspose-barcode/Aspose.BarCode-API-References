---
title: "Aspose::BarCode::BarCodeRecognition::DecodeType class"
linktitle: "DecodeType"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::BarCodeRecognition::DecodeType class. C++'ta okunacak barkod tipini belirtir."
type: docs
weight: 1600
url: /tr/cpp/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class


Okunacak barkod tipini belirtin.

```cpp
class DecodeType
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [DecodeType](./decodetype/)() |  |
| static [get_AllSupportedTypesArray](./get_allsupportedtypesarray/)() | AllSupportedTypes'ı temsil eden bir dizi alır |
| static [GetNames](./getnames/)() | Kod çözme türlerinin adlarını içeren bir dizi alır. |
| static [Is1D](./is1d/)(System::SharedPtr\<BaseDecodeType\>) | Belirtilen [BaseDecodeType](../basedecodetype/) içinde herhangi bir 1D barkod sembolojisi olup olmadığını belirler |
| static [Is2D](./is2d/)(System::SharedPtr\<BaseDecodeType\>) | Belirtilen [BaseDecodeType](../basedecodetype/) içinde herhangi bir 2D barkod sembolojisi olup olmadığını belirler |
| static [IsPostal](./ispostal/)(System::SharedPtr\<BaseDecodeType\>) | Belirtilen [BaseDecodeType](../basedecodetype/) içinde herhangi bir Posta barkod sembolojisi olup olmadığını belirler |
| static [Parse](./parse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | [SingleDecodeType](../singledecodetype/) öğesinin dize temsilini örneğine dönüştürür. Döndürülen değer, dönüşümün başarılı olup olmadığını gösterir. |
| static [ScanSets](./scansets/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Tarama setlerini barkodTürlerine göre belirtin |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | [SingleDecodeType](../singledecodetype/) öğesinin dize temsilini örneğine dönüştürür. Döndürülen değer, dönüşümün başarılı olup olmadığını gösterir. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | [MultiDecodeType](../multidecodetype/) dize temsiliğini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [AllSupportedTypes](./allsupportedtypes/) | Verilerin tüm mevcut sembolojilerle kontrol edileceğini belirtir |
| static [AustralianPosteParcel](./australianposteparcel/) | Verilerin **Australian Post Domestic eParcel Barcode** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [AustraliaPost](./australiapost/) | Verilerin **Australia Post** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [Aztec](./aztec/) | Verilerin **Aztec** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [Codabar](./codabar/) | Verilerin **CODABAR** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [CodablockF](./codablockf/) | Verilerin **CodablockF** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [Code11](./code11/) | Verilerin **CODE 11** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [Code128](./code128/) | Verilerin **CODE 128** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [Code16K](./code16k/) | Verilerin **SCode16K** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [Code32](./code32/) | Verilerin **Code32** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [Code39](./code39/) | Verilerin **Code 39** temel karakter seti barkod spesifikasyonu ile çözüleceğini belirtir: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Verilerin **Code 39** tam ASCII karakter seti barkod spesifikasyonu ile çözüleceğini belirtir: ISO/IEC 16388 |
| static [Code93](./code93/) | Verilerin **CODE 93** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [CompactPdf417](./compactpdf417/) | Verilerin **CompactPdf417** (Pdf417Truncated) barkod spesifikasyonu ile çözüleceğini belirtir |
| static [DatabarExpanded](./databarexpanded/) | Verilerin **GS1 Databar expanded** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Verilerin **GS1 Databar expanded stacked** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [DatabarLimited](./databarlimited/) | Verilerin **GS1 Databar limited** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Verilerin **GS1 Databar omni-directional** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [DatabarStacked](./databarstacked/) | Verilerin **GS1 Databar stacked** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Verilerin **GS1 Databar stacked omni-directional** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [DatabarTruncated](./databartruncated/) | Verilerin **GS1 Databar truncated** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [DataLogic2of5](./datalogic2of5/) | Verinin **DataLogic 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [DataMatrix](./datamatrix/) | Verinin **[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** barkod sembolojisi ile çözüleceğini belirtir |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Verinin **DeutschePost Ident code** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Verinin **DeutschePost Leit code** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [DotCode](./dotcode/) | Verinin **DotCode** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [DutchKIX](./dutchkix/) | Verinin **DotCode** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [EAN13](./ean13/) | Verinin **EAN-13** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [EAN14](./ean14/) | Verinin **EAN14** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [EAN8](./ean8/) | Verinin **EAN-8** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [GS1Aztec](./gs1aztec/) | Verinin **GS1 Aztec** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [GS1Code128](./gs1code128/) | Verinin **GS1 CODE 128** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [GS1CompositeBar](./gs1compositebar/) | Verinin **GS1 Composite Bar** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [GS1DataMatrix](./gs1datamatrix/) | Verinin **GS1DataMatrix** barkod sembolojisi ile çözüleceğini belirtir |
| static [GS1DotCode](./gs1dotcode/) | Verinin **GS1 DotCode** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [GS1HanXin](./gs1hanxin/) | Verinin **GS1 Han Xin Code** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [GS1MicroPdf417](./gs1micropdf417/) | Verinin **MicroPdf417** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [GS1QR](./gs1qr/) | Verinin **GS1 [QR](../../aspose.barcode.barcoderecognition.qr/)** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [HanXin](./hanxin/) | Verinin **Han Xin Code** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [HIBCAztecLIC](./hibcazteclic/) | Verinin **HIBC LIC Aztec** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [HIBCAztecPAS](./hibcaztecpas/) | Verinin **HIBC PAS Aztec** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [HIBCCode128LIC](./hibccode128lic/) | Verinin **HIBC LIC Code128** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [HIBCCode128PAS](./hibccode128pas/) | Verinin **HIBC PAS Code128** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [HIBCCode39LIC](./hibccode39lic/) | Verinin **HIBC LIC Code39** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [HIBCCode39PAS](./hibccode39pas/) | Verinin **HIBC PAS Code39** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Verinin **HIBC LIC [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Verinin **HIBC PAS [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [HIBCQRLIC](./hibcqrlic/) | Verinin **HIBC LIC [QR](../../aspose.barcode.barcoderecognition.qr/)** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [HIBCQRPAS](./hibcqrpas/) | Verinin **HIBC PAS [QR](../../aspose.barcode.barcoderecognition.qr/)** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [IATA2of5](./iata2of5/) | Verinin **IATA 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir. IATA (International Air Transport Association) bu barkodu hava kargo yönetimi için kullanır. |
| static [Interleaved2of5](./interleaved2of5/) | Verinin **INTERLEAVED 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [ISBN](./isbn/) | Verinin **ISBN** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [ISMN](./ismn/) | Verinin **ISMN** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [ISSN](./issn/) | Verinin **ISSN** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [ItalianPost25](./italianpost25/) | Verinin **Italian Post 25** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [ITF14](./itf14/) | Verinin **ITF14** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [ITF6](./itf6/) | Verinin **ITF6** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [JapanPost](./japanpost/) | Verinin **Japan Post** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [MacroPdf417](./macropdf417/) | Verinin **MacroPdf417** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [Mailmark](./mailmark/) | Verinin **Royal Mail Mailmark** barkod spesifikasyonu ile çözüleceğini belirtir. |
| static [Matrix2of5](./matrix2of5/) | Verinin **Matrix 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [MaxiCode](./maxicode/) | Verinin **MaxiCode** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [MicrE13B](./micre13b/) | Verinin **MICR E-13B** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [MicroPdf417](./micropdf417/) | Verinin **MicroPdf417** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [MicroQR](./microqr/) | Verinin **MicroQR Code** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [MostCommonTypes](./mostcommontypes/) | Verinin en yaygın kullanılan sembolojilerle kontrol edileceğini belirtir |
| static [MSI](./msi/) | Verinin **MSI Plessey** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [None](./none/) | Belirtilmemiş çözümleme türü. |
| static [OneCode](./onecode/) | Verinin USPS **OneCode** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [OPC](./opc/) | Verinin **OPC** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [PatchCode](./patchcode/) | Verinin **Patch code** barkod spesifikasyonu ile çözüleceğini belirtir. Barkod sembolojisi otomatik tarama için kullanılır |
| static [Pdf417](./pdf417/) | Verinin **Pdf417** barkod sembolojisi ile çözüleceğini belirtir |
| static [Pharmacode](./pharmacode/) | Verinin **Pharmacode** barkodu ile çözüleceğini belirtir. Bu semboloji ayrıca Pharmaceutical Binary Code olarak da bilinir |
| static [Planet](./planet/) | Verinin **Planet** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [PostalTypes](./postaltypes/) | Verinin **1.5D Postal** barkod sembolojilerinin tümüyle, örneğin **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** kontrol edileceğini belirtir |
| static [Postnet](./postnet/) | Verinin **Postnet** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [PZN](./pzn/) | Verinin **PZN** barkod spesifikasyonu ile çözüleceğini belirtir. Bu semboloji aynı zamanda Pharma Zentral Nummer olarak bilinir. PZN7 ve PZN8 desteklenir. |
| static [QR](./qr/) | Verinin **[QR](../../aspose.barcode.barcoderecognition.qr/) Code** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [RectMicroQR](./rectmicroqr/) | Verinin **RectMicroQR (rMQR) Code** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [RM4SCC](./rm4scc/) | Verinin **RM4SCC** barkod spesifikasyonu ile çözüleceğini belirtir. RM4SCC (Royal Mail 4-state Customer Code), Birleşik Krallık'ta otomatik posta sınıflandırma sürecinde kullanılır. |
| static [SCC14](./scc14/) | Verinin **SCC14** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [SSCC18](./sscc18/) | Verinin **SSCC18** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [Standard2of5](./standard2of5/) | Verinin **Standard 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [Supplement](./supplement/) | Verinin **Supplement(EAN2, EAN5)** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [SwissPostParcel](./swisspostparcel/) | Verinin **Swiss Post Parcel Barcode** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [Types1D](./types1d/) | Verinin **1D** barkod sembolojilerinin tümüyle kontrol edileceğini belirtir |
| static [Types2D](./types2d/) | Verinin **2D** barkod sembolojilerinin tümüyle kontrol edileceğini belirtir |
| static [UPCA](./upca/) | Verinin **UPC-A** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [UPCE](./upce/) | Verinin **UPC-E** barkod spesifikasyonu ile çözüleceğini belirtir |
| static [VIN](./vin/) | Verinin **VIN** (Vehicle Identification Number) barkod spesifikasyonu ile çözüleceğini belirtir |
## Açıklamalar


Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
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

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
