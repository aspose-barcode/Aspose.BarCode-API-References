---
title: "Aspose::BarCode::Generation::EncodeTypes klasse"
linktitle: "EncodeTypes"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::Generation::EncodeTypes klasse. Specificeert het type barcode dat moet worden gecodeerd in C++."
type: docs
weight: 2300
url: /nl/cpp/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class


Specificeert het type barcode om te coderen.

```cpp
class EncodeTypes
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [EncodeTypes](./encodetypes/)() |  |
| static [get_AllEncodeTypes](./get_allencodetypes/)() | Specificeert dat gegevens worden gecontroleerd met alle beschikbare symbolen. |
| static [GetNames](./getnames/)() | Haalt een array op van de namen van de codeertypen. |
| static [Parse](./parse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Converteert de tekenreeksrepresentatie van een [BaseEncodeType](../baseencodetype/) naar de instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Converteert de tekenreeksrepresentatie van een [BaseEncodeType](../baseencodetype/) naar de instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| static [AustralianPosteParcel](./australianposteparcel/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **Australian Post Domestic eParcel Barcode** barcode‑specificatie |
| static [AustraliaPost](./australiapost/) | Stelt Australia Post Customer [BarCode](../../aspose.barcode/) voor |
| static [Aztec](./aztec/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **Aztec** barcode‑specificatie |
| static [Codabar](./codabar/) | Specificeert dat de gegevens moeten worden gecodeerd met **CODABAR** barcode-specificatie |
| static [CodablockF](./codablockf/) | Specificeert dat de gegevens moeten worden gecodeerd met **Codablock-F** barcode-specificatie. |
| static [Code11](./code11/) | Specificeert dat de gegevens moeten worden gecodeerd met **CODE 11** barcode-specificatie |
| static [Code128](./code128/) | Specificeert dat de gegevens moeten worden gecodeerd met **CODE 128** barcode-specificatie |
| static [Code16K](./code16k/) | Stelt Code 16K barcode voor. |
| static [Code32](./code32/) | Specificeert dat de gegevens moeten worden gecodeerd met **Code32** barcode-specificatie |
| static [Code39](./code39/) | Specificeert dat de gegevens moeten worden gecodeerd met **Code 39** basis-tekenset barcode-specificatie: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Specificeert dat de gegevens moeten worden gecodeerd met **Code 39** volledige ASCII-tekenset barcode-specificatie: ISO/IEC 16388 |
| static [Code93](./code93/) | Specificeert dat de gegevens moeten worden gecodeerd met **CODE 93** barcode-specificatie |
| static [DatabarExpanded](./databarexpanded/) | Stelt een uitgebreide GS1 Databar barcode voor. |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Stelt een uitgebreide gestapelde GS1 Databar barcode voor. |
| static [DatabarLimited](./databarlimited/) | Stelt een beperkte GS1 Databar barcode voor. |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Specificeert dat de gegevens moeten worden gecodeerd met **GS1 Databar omni-directional** barcode-specificatie. |
| static [DatabarStacked](./databarstacked/) | Stelt een gestapelde GS1 Databar barcode voor. |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Stelt een gestapelde omni-directionele GS1 Databar barcode voor. |
| static [DatabarTruncated](./databartruncated/) | Specificeert dat de gegevens moeten worden gecodeerd met **GS1 Databar truncated** barcode-specificatie. |
| static [DataLogic2of5](./datalogic2of5/) | Specificeert dat de gegevens moeten worden gecodeerd met **DataLogic 2 of 5** barcode-specificatie |
| static [DataMatrix](./datamatrix/) | 2D barcode-symbool DataMatrix |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Stelt Deutsch Post barcode voor, dit symbool is ook bekend als Identcode,CodeIdentcode,German Postal 2 of 5 Identcode, Deutsch Post AG Identcode, Deutsch Frachtpost Identcode, Deutsch Post AG (DHL) |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Stelt Deutsch Post Leitcode Barcode voor, ook bekend als German Postal 2 of 5 Leitcode, CodeLeitcode, Leitcode, Deutsch Post AG (DHL). |
| static [DotCode](./dotcode/) | Specificeert dat de gegevens moeten worden gecodeerd met **DotCode** barcode-specificatie |
| static [DutchKIX](./dutchkix/) | Specificeert dat de gegevens moeten worden gecodeerd met **Dutch KIX** barcode-specificatie |
| static [EAN13](./ean13/) | Specificeert dat de gegevens moeten worden gecodeerd met **EAN-13** barcode-specificatie |
| static [EAN14](./ean14/) | Specificeert dat de gegevens moeten worden gecodeerd met **EAN14** barcode-specificatie |
| static [EAN8](./ean8/) | Specificeert dat de gegevens moeten worden gecodeerd met **EAN-8** barcode-specificatie |
| static [GS1Aztec](./gs1aztec/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **GS1 Aztec** barcode-specificatie. De codetekst moet haakjes bevatten voor AI. |
| static [GS1CodablockF](./gs1codablockf/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **GS1 Codablock-F** barcode-specificatie. De codetekst moet haakjes bevatten voor AI. |
| static [GS1Code128](./gs1code128/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **GS1 Code 128** barcode-specificatie. De codetekst moet haakjes bevatten voor AI. |
| static [GS1CompositeBar](./gs1compositebar/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **GS1 Composite Bar** barcode-specificatie. De codetekst moet haakjes bevatten voor AI. 1D-codetekst en 2D-codetekst moeten worden gescheiden door het symbool '/' |
| static [GS1DataMatrix](./gs1datamatrix/) | 2D-barcode‑symbool DataMatrix met GS1-tekenreeksindeling |
| static [GS1DotCode](./gs1dotcode/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **GS1 DotCode** barcode-specificatie. De codetekst moet haakjes bevatten voor AI. |
| static [GS1HanXin](./gs1hanxin/) | 2D-barcode‑symbool HanXin met GS1-tekenreeksindeling |
| static [GS1MicroPdf417](./gs1micropdf417/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **GS1MicroPdf417** barcode-specificatie |
| static [GS1QR](./gs1qr/) | 2D-barcode‑symbool QR met GS1-tekenreeksindeling |
| static [HanXin](./hanxin/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **Han Xin** barcode-specificatie |
| static [HIBCAztecLIC](./hibcazteclic/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **HIBC LIC Aztec** barcode-specificatie. |
| static [HIBCAztecPAS](./hibcaztecpas/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **HIBC PAS Aztec** barcode-specificatie. |
| static [HIBCCode128LIC](./hibccode128lic/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **HIBC LIC Code128** barcode-specificatie. |
| static [HIBCCode128PAS](./hibccode128pas/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **HIBC PAS Code128** barcode-specificatie. |
| static [HIBCCode39LIC](./hibccode39lic/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **HIBC LIC Code39** barcode-specificatie. |
| static [HIBCCode39PAS](./hibccode39pas/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **HIBC PAS Code39** barcode-specificatie. |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **HIBC LIC DataMatrix** barcode-specificatie. |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **HIBC PAS DataMatrix** barcode-specificatie. |
| static [HIBCQRLIC](./hibcqrlic/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **HIBC LIC QR** barcode-specificatie. |
| static [HIBCQRPAS](./hibcqrpas/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **HIBC PAS QR** barcode-specificatie. |
| static [IATA2of5](./iata2of5/) | Stelt de IATA 2 of 5 barcode voor. IATA (International Air Transport Association) gebruikt deze barcode voor het beheer van luchtvracht. |
| static [Interleaved2of5](./interleaved2of5/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **INTERLEAVED 2 of 5** barcode-specificatie |
| static [ISBN](./isbn/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **ISBN** barcode-specificatie |
| static [ISMN](./ismn/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **ISMN** barcode-specificatie |
| static [ISSN](./issn/) | Specificeert dat de gegevens moeten worden gecodeerd volgens de **ISSN** barcode-specificatie |
| static [ItalianPost25](./italianpost25/) | Vertegenwoordigt de Italian Post 25 barcode. |
| static [ITF14](./itf14/) | Specificeert dat de gegevens moeten worden gecodeerd met de **ITF14** barcode-specificatie |
| static [ITF6](./itf6/) | Vertegenwoordigt de ITF-6 barcode. |
| static [JapanPost](./japanpost/) | Vertegenwoordigt Japan Post [BarCode](../../aspose.barcode/) |
| static [MacroPdf417](./macropdf417/) | Specificeert dat de gegevens moeten worden gecodeerd met de **MacroPdf417** barcode-specificatie |
| static [Mailmark](./mailmark/) | Vertegenwoordigt de Royal Mail Mailmark barcode. |
| static [Matrix2of5](./matrix2of5/) | Vertegenwoordigt Matrix 2 of 5 [BarCode](../../aspose.barcode/) |
| static [MaxiCode](./maxicode/) | Specificeert dat de gegevens moeten worden gecodeerd met de **MaxiCode** barcode-specificatie |
| static [MicroPdf417](./micropdf417/) | Specificeert dat de gegevens moeten worden gecodeerd met de **MicroPdf417** barcode-specificatie |
| static [MicroQR](./microqr/) | Specificeert dat de gegevens moeten worden gecodeerd met de **MicroQR Code** barcode-specificatie |
| static [MSI](./msi/) | Specificeert dat de gegevens moeten worden gecodeerd met de **MSI Plessey** barcode-specificatie |
| static [None](./none/) | Niet-gespecificeerd coderings type. |
| static [OneCode](./onecode/) | Specificeert dat de gegevens moeten worden gecodeerd met de USPS **OneCode** barcode-specificatie |
| static [OPC](./opc/) | Vertegenwoordigt OPC (Optical Product Code) barcode, ook bekend als VCA Barcode VCA OPC, Vision Council of America OPC Barcode. |
| static [PatchCode](./patchcode/) | Vertegenwoordigt Patch code barcode |
| static [Pdf417](./pdf417/) | Specificeert dat de gegevens moeten worden gecodeerd met de **Pdf417** barcode-specificatie |
| static [Pharmacode](./pharmacode/) | Vertegenwoordigt de Pharmacode barcode. |
| static [Planet](./planet/) | Specificeert dat de gegevens moeten worden gecodeerd met de **Planet** barcode-specificatie |
| static [Postnet](./postnet/) | Specificeert dat de gegevens moeten worden gecodeerd met de **Postnet** barcode-specificatie |
| static [PZN](./pzn/) | Vertegenwoordigt de PZN barcode. Deze symbologie staat ook bekend als Pharmacy central number, Pharmazentralnummer. PZN7 en PZN8 worden ondersteund. PZN7 wordt gegenereerd uit 6 of minder cijfers, zoals "123456". PZN8 wordt gegenereerd uit 7 of meer cijfers, zoals "1234567". Het opgegeven laatste controlecijfer wordt genegeerd en gegenereerd door de barcode-engine. |
| static [QR](./qr/) | Specificeert dat de gegevens moeten worden gecodeerd met de **QR Code** barcode-specificatie |
| static [RectMicroQR](./rectmicroqr/) | Specificeert dat de gegevens moeten worden gecodeerd met de **RectMicroQR (rMQR) Code** barcode-specificatie |
| static [RM4SCC](./rm4scc/) | Vertegenwoordigt de RM4SCC barcode. RM4SCC (Royal Mail 4-state Customer Code) wordt gebruikt voor geautomatiseerde postsortering in het VK. |
| static [SCC14](./scc14/) | Specificeert dat de gegevens moeten worden gecodeerd met de **SCC14** barcode-specificatie |
| static [SingaporePost](./singaporepost/) | Specificeert dat de gegevens moeten worden gecodeerd met de **Singapore Post Barcode** barcode-specificatie |
| static [SSCC18](./sscc18/) | Specificeert dat de gegevens moeten worden gecodeerd met de **SSCC18** barcode-specificatie |
| static [Standard2of5](./standard2of5/) | Specificeert dat de gegevens moeten worden gecodeerd met de **Standard 2 of 5** barcode-specificatie |
| static [SwissPostParcel](./swisspostparcel/) | Specificeert dat de gegevens moeten worden gecodeerd met de **Swiss Post Parcel Barcode** barcode-specificatie. Ondersteunde types: Binnenlandse post, Internationale post, Aanvullende diensten (nieuw) |
| static [UPCA](./upca/) | Specificeert dat de gegevens moeten worden gecodeerd met de **UPC-A** barcode-specificatie |
| static [UpcaGs1Code128Coupon](./upcags1code128coupon/) | Specificeert dat de gegevens moeten worden gecodeerd met de **UPC coupon with GS1-128 Extended Code** barcode-specificatie. Een voorbeeld van de invoerreeks: BarcodeGenerator.Codetext = "514141100906(8102)03", waarbij het UPCA-gedeelte "514141100906" is, het GS1Code128-gedeelte (8102)03 is. |
| static [UpcaGs1DatabarCoupon](./upcags1databarcoupon/) | Specificeert dat de gegevens moeten worden gecodeerd met de **UPC coupon with GS1 DataBar addition** barcode-specificatie. Een voorbeeld van de invoerreeks: BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000", waarbij het UPCA-gedeelte "514141100906" is, het Databar-gedeelte "(8110)106141416543213500110000310123196000" is. Om de bijschrift te wijzigen, gebruik Parameters.CaptionAbove.Text = "company prefix + offer code"; |
| static [UPCE](./upce/) | Specificeert dat de gegevens moeten worden gecodeerd met de **UPC-E** barcode-specificatie |
| static [VIN](./vin/) | Stelt een VIN (Vehicle Identification Number) barcode voor. |
## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
