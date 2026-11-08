---
title: "Aspose::BarCode::Generation::EncodeTypes sınıfı"
linktitle: "EncodeTypes"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Generation::EncodeTypes sınıfı. C++'da kodlanacak barkod tipini belirtir."
type: docs
weight: 2300
url: /tr/cpp/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class


Kodlanacak barkod tipini belirtir.

```cpp
class EncodeTypes
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [EncodeTypes](./encodetypes/)() |  |
| static [get_AllEncodeTypes](./get_allencodetypes/)() | Verilerin tüm mevcut sembolojilerle kontrol edileceğini belirtir. |
| static [GetNames](./getnames/)() | Kodlama tiplerinin adlarını içeren bir dizi getirir. |
| static [Parse](./parse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | [BaseEncodeType](../baseencodetype/) dize temsilini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | [BaseEncodeType](../baseencodetype/) dize temsilini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [AustralianPosteParcel](./australianposteparcel/) | Verilerin **Australian Post Domestic eParcel Barcode** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [AustraliaPost](./australiapost/) | Australia Post Müşteri [BarCode](../../aspose.barcode/) temsil eder |
| static [Aztec](./aztec/) | Verilerin **Aztec** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [Codabar](./codabar/) | Verinin **CODABAR** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [CodablockF](./codablockf/) | Verinin **Codablock-F** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [Code11](./code11/) | Verinin **CODE 11** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [Code128](./code128/) | Verinin **CODE 128** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [Code16K](./code16k/) | Code 16K barkodu temsil eder. |
| static [Code32](./code32/) | Verinin **Code32** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [Code39](./code39/) | Verinin **Code 39** temel karakter seti barkod spesifikasyonu ile kodlanması gerektiğini belirtir: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Verinin **Code 39** tam ASCII karakter seti barkod spesifikasyonu ile kodlanması gerektiğini belirtir: ISO/IEC 16388 |
| static [Code93](./code93/) | Verinin **CODE 93** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [DatabarExpanded](./databarexpanded/) | GS1 Databar genişletilmiş barkodu temsil eder. |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | GS1 Databar genişletilmiş yığılmış barkodu temsil eder. |
| static [DatabarLimited](./databarlimited/) | GS1 Databar sınırlı barkodu temsil eder. |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Verinin **GS1 Databar omni-directional** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [DatabarStacked](./databarstacked/) | GS1 Databar yığılmış barkodu temsil eder. |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | GS1 Databar yığılmış omni-directional barkodu temsil eder. |
| static [DatabarTruncated](./databartruncated/) | Verinin **GS1 Databar truncated** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [DataLogic2of5](./datalogic2of5/) | Verinin **DataLogic 2 of 5** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [DataMatrix](./datamatrix/) | 2D barkod sembolojisi DataMatrix |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Deutsch Post barkodunu temsil eder, bu semboloji ayrıca Identcode, CodeIdentcode, German Postal 2 of 5 Identcode, Deutsch Post AG Identcode, Deutsch Frachtpost Identcode, Deutsch Post AG (DHL) olarak da bilinir |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Deutsch Post Leitcode barkodunu temsil eder, ayrıca German Postal 2 of 5 Leitcode, CodeLeitcode, Leitcode, Deutsch Post AG (DHL) olarak da bilinir. |
| static [DotCode](./dotcode/) | Verinin **DotCode** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [DutchKIX](./dutchkix/) | Verinin **Dutch KIX** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [EAN13](./ean13/) | Verinin **EAN-13** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [EAN14](./ean14/) | Verinin **EAN14** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [EAN8](./ean8/) | Verinin **EAN-8** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [GS1Aztec](./gs1aztec/) | Verinin **GS1 Aztec** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. Kod metni AI için parantez içermelidir. |
| static [GS1CodablockF](./gs1codablockf/) | Verinin **GS1 Codablock-F** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. Kod metni AI için parantez içermelidir. |
| static [GS1Code128](./gs1code128/) | Verinin **GS1 Code 128** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. Kod metni AI için parantez içermelidir. |
| static [GS1CompositeBar](./gs1compositebar/) | Verinin **GS1 Composite Bar** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. Kod metni AI için parantez içermelidir. 1D kod metni ve 2D kod metni '/' sembolü ile ayrılmalıdır. |
| static [GS1DataMatrix](./gs1datamatrix/) | GS1 dize formatı ile 2D barkod sembolojisi DataMatrix. |
| static [GS1DotCode](./gs1dotcode/) | Verinin **GS1 DotCode** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. Kod metni AI için parantez içermelidir. |
| static [GS1HanXin](./gs1hanxin/) | GS1 dize formatı ile 2D barkod sembolojisi HanXin. |
| static [GS1MicroPdf417](./gs1micropdf417/) | Verinin **GS1MicroPdf417** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [GS1QR](./gs1qr/) | GS1 dize formatı ile 2D barkod sembolojisi QR. |
| static [HanXin](./hanxin/) | Verinin **Han Xin** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [HIBCAztecLIC](./hibcazteclic/) | Verinin **HIBC LIC Aztec** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [HIBCAztecPAS](./hibcaztecpas/) | Verinin **HIBC PAS Aztec** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [HIBCCode128LIC](./hibccode128lic/) | Verinin **HIBC LIC Code128** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [HIBCCode128PAS](./hibccode128pas/) | Verinin **HIBC PAS Code128** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [HIBCCode39LIC](./hibccode39lic/) | Verinin **HIBC LIC Code39** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [HIBCCode39PAS](./hibccode39pas/) | Verinin **HIBC PAS Code39** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Verinin **HIBC LIC DataMatrix** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Verinin **HIBC PAS DataMatrix** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [HIBCQRLIC](./hibcqrlic/) | Verinin **HIBC LIC QR** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [HIBCQRPAS](./hibcqrpas/) | Verinin **HIBC PAS QR** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [IATA2of5](./iata2of5/) | IATA 2 of 5 barkodunu temsil eder. IATA (Uluslararası Hava Taşımacılığı Birliği), bu barkodu hava kargo yönetimi için kullanır. |
| static [Interleaved2of5](./interleaved2of5/) | Verinin **INTERLEAVED 2 of 5** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [ISBN](./isbn/) | Verinin **ISBN** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [ISMN](./ismn/) | Verinin **ISMN** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [ISSN](./issn/) | Verinin **ISSN** barkod spesifikasyonu ile kodlanması gerektiğini belirtir. |
| static [ItalianPost25](./italianpost25/) | İtalyan Posta 25 barkodunu temsil eder. |
| static [ITF14](./itf14/) | Verinin **ITF14** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [ITF6](./itf6/) | ITF-6 barkodunu temsil eder. |
| static [JapanPost](./japanpost/) | Japon Posta [BarCode](../../aspose.barcode/) temsil eder |
| static [MacroPdf417](./macropdf417/) | Verinin **MacroPdf417** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [Mailmark](./mailmark/) | Royal Mail Mailmark barkodunu temsil eder. |
| static [Matrix2of5](./matrix2of5/) | Matrix 2 of 5 [BarCode](../../aspose.barcode/) temsil eder |
| static [MaxiCode](./maxicode/) | Verinin **MaxiCode** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [MicroPdf417](./micropdf417/) | Verinin **MicroPdf417** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [MicroQR](./microqr/) | Verinin **MicroQR Code** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [MSI](./msi/) | Verinin **MSI Plessey** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [None](./none/) | Belirtilmemiş kodlama türü. |
| static [OneCode](./onecode/) | Verinin USPS **OneCode** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [OPC](./opc/) | OPC (Optical Product Code) Barkodunu temsil eder, aynı zamanda VCA Barcode VCA OPC, Vision Council of America OPC Barcode olarak da bilinir. |
| static [PatchCode](./patchcode/) | Patch kod barkodunu temsil eder |
| static [Pdf417](./pdf417/) | Verinin **Pdf417** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [Pharmacode](./pharmacode/) | Pharmacode barkodunu temsil eder. |
| static [Planet](./planet/) | Verinin **Planet** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [Postnet](./postnet/) | Verinin **Postnet** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [PZN](./pzn/) | PZN barkodunu temsil eder. Bu semboloji aynı zamanda Pharmacy central number, Pharmazentralnummer olarak da bilinir. PZN7 ve PZN8 desteklenir. PZN7, 6 veya daha az rakamdan, örneğin "123456" gibi üretilir. PZN8, 7 veya daha fazla rakamdan, örneğin "1234567" gibi üretilir. Sağlanan son kontrol basamağı göz ardı edilir ve barkod motoru tarafından üretilir. |
| static [QR](./qr/) | Verinin **QR Code** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [RectMicroQR](./rectmicroqr/) | Verinin **RectMicroQR (rMQR) Code** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [RM4SCC](./rm4scc/) | RM4SCC barkodunu temsil eder. RM4SCC (Royal Mail 4-state Customer Code), Birleşik Krallık'ta otomatik posta sınıflandırma sürecinde kullanılır. |
| static [SCC14](./scc14/) | Verinin **SCC14** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [SingaporePost](./singaporepost/) | Verinin **Singapore Post Barcode** barkod spesifikasyonu ile kodlanması gerektiğini belirtir |
| static [SSCC18](./sscc18/) | Verinin **SSCC18** barkod spesifikasyonuna göre kodlanması gerektiğini belirtir |
| static [Standard2of5](./standard2of5/) | Verinin **Standard 2 of 5** barkod spesifikasyonuna göre kodlanması gerektiğini belirtir |
| static [SwissPostParcel](./swisspostparcel/) | Verinin **Swiss Post Parcel Barcode** barkod spesifikasyonuna göre kodlanması gerektiğini belirtir. Desteklenen tipler: Yerel Posta, Uluslararası Posta, Ek Hizmetler (yeni) |
| static [UPCA](./upca/) | Verinin **UPC-A** barkod spesifikasyonuna göre kodlanması gerektiğini belirtir |
| static [UpcaGs1Code128Coupon](./upcags1code128coupon/) | Verinin **UPC coupon with GS1-128 Extended Code** barkod spesifikasyonuna göre kodlanması gerektiğini belirtir. Giriş dizesine bir örnek: BarcodeGenerator.Codetext = "514141100906(8102)03", burada UPCA kısmı "514141100906", GS1Code128 kısmı (8102)03. |
| static [UpcaGs1DatabarCoupon](./upcags1databarcoupon/) | Verinin **UPC coupon with GS1 DataBar addition** barkod spesifikasyonuna göre kodlanması gerektiğini belirtir. Giriş dizesine bir örnek: BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000", burada UPCA kısmı "514141100906", Databar kısmı "(8110)106141416543213500110000310123196000". Başlığı değiştirmek için Parameters.CaptionAbove.Text = "company prefix + offer code"; |
| static [UPCE](./upce/) | Verinin **UPC-E** barkod spesifikasyonuna göre kodlanması gerektiğini belirtir |
| static [VIN](./vin/) | VIN (Vehicle Identification Number) barkodunu temsil eder. |
## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
