---
title: "Aspose::BarCode::Generation::EncodeTypes class"
linktitle: "EncodeTypes"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::EncodeTypes class. Anger vilken typ av streckkod som ska kodas i C++."
type: docs
weight: 2300
url: /sv/cpp/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class


Anger vilken typ av streckkod som ska kodas.

```cpp
class EncodeTypes
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [EncodeTypes](./encodetypes/)() |  |
| static [get_AllEncodeTypes](./get_allencodetypes/)() | Anger att data kommer att kontrolleras med alla tillgängliga symboler. |
| static [GetNames](./getnames/)() | Hämtar en array med namnen på kodningstyperna. |
| static [Parse](./parse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Konverterar strängrepresentationen av en [BaseEncodeType](../baseencodetype/) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Konverterar strängrepresentationen av en [BaseEncodeType](../baseencodetype/) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [AustralianPosteParcel](./australianposteparcel/) | Anger att data ska kodas med **Australian Post Domestic eParcel Barcode** streckkodsspecifikation |
| static [AustraliaPost](./australiapost/) | Representerar Australia Post Customer [BarCode](../../aspose.barcode/) |
| static [Aztec](./aztec/) | Anger att data ska kodas med **Aztec** streckkodsspecifikation |
| static [Codabar](./codabar/) | Anger att data ska kodas med **CODABAR** streckkodsspecifikation |
| static [CodablockF](./codablockf/) | Anger att data ska kodas med **Codablock-F** streckkodsspecifikation. |
| static [Code11](./code11/) | Anger att data ska kodas med **CODE 11** streckkodsspecifikation |
| static [Code128](./code128/) | Anger att data ska kodas med **CODE 128** streckkodsspecifikation |
| static [Code16K](./code16k/) | Representerar Code 16K streckkod. |
| static [Code32](./code32/) | Anger att data ska kodas med **Code32** streckkodsspecifikation |
| static [Code39](./code39/) | Anger att data ska kodas med **Code 39** grundläggande teckenuppsättning streckkodsspecifikation: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Anger att data ska kodas med **Code 39** fullständig ASCII-teckenuppsättning streckkodsspecifikation: ISO/IEC 16388 |
| static [Code93](./code93/) | Anger att data ska kodas med **CODE 93** streckkodsspecifikation |
| static [DatabarExpanded](./databarexpanded/) | Representerar GS1 Databar utökad streckkod. |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Representerar GS1 Databar utökad staplad streckkod. |
| static [DatabarLimited](./databarlimited/) | Representerar GS1 Databar begränsad streckkod. |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Anger att data ska kodas med **GS1 Databar omni-directional** streckkodsspecifikation. |
| static [DatabarStacked](./databarstacked/) | Representerar GS1 Databar staplad streckkod. |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Representerar GS1 Databar staplad omni-directional streckkod. |
| static [DatabarTruncated](./databartruncated/) | Anger att data ska kodas med **GS1 Databar truncated** streckkodsspecifikation. |
| static [DataLogic2of5](./datalogic2of5/) | Anger att data ska kodas med **DataLogic 2 of 5** streckkodsspecifikation |
| static [DataMatrix](./datamatrix/) | 2D streckkodssymbolik DataMatrix |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Representerar Deutsch Post streckkod, denna symbolik är även känd som Identcode,CodeIdentcode,German Postal 2 of 5 Identcode, Deutsch Post AG Identcode, Deutsch Frachtpost Identcode, Deutsch Post AG (DHL) |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Representerar Deutsch Post Leitcode streckkod, även känd som German Postal 2 of 5 Leitcode, CodeLeitcode, Leitcode, Deutsch Post AG (DHL). |
| static [DotCode](./dotcode/) | Anger att data ska kodas med **DotCode** streckkodsspecifikation |
| static [DutchKIX](./dutchkix/) | Anger att data ska kodas med **Dutch KIX** streckkodsspecifikation |
| static [EAN13](./ean13/) | Anger att data ska kodas med **EAN-13** streckkodsspecifikation |
| static [EAN14](./ean14/) | Anger att data ska kodas med **EAN14** streckkodsspecifikation |
| static [EAN8](./ean8/) | Anger att data ska kodas med **EAN-8** streckkodsspecifikation |
| static [GS1Aztec](./gs1aztec/) | Anger att data ska kodas med **GS1 Aztec** streckkodsspecifikation. Kodtexten måste innehålla parenteser för AI. |
| static [GS1CodablockF](./gs1codablockf/) | Anger att data ska kodas med **GS1 Codablock-F** streckkodsspecifikation. Kodtexten måste innehålla parenteser för AI. |
| static [GS1Code128](./gs1code128/) | Anger att data ska kodas med **GS1 Code 128** streckkodsspecifikation. Kodtexten måste innehålla parenteser för AI. |
| static [GS1CompositeBar](./gs1compositebar/) | Anger att data ska kodas med **GS1 Composite Bar** streckkodsspecifikation. Kodtexten måste innehålla parenteser för AI. 1D‑kodtext och 2D‑kodtext måste separeras med symbolen '/' |
| static [GS1DataMatrix](./gs1datamatrix/) | 2D‑streckkodssymbolen DataMatrix med GS1‑strängformat |
| static [GS1DotCode](./gs1dotcode/) | Anger att data ska kodas med **GS1 DotCode** streckkodsspecifikation. Kodtexten måste innehålla parenteser för AI. |
| static [GS1HanXin](./gs1hanxin/) | 2D‑streckkodssymbolen HanXin med GS1‑strängformat |
| static [GS1MicroPdf417](./gs1micropdf417/) | Anger att data ska kodas med **GS1MicroPdf417** streckkodsspecifikation |
| static [GS1QR](./gs1qr/) | 2D‑streckkodssymbolen QR med GS1‑strängformat |
| static [HanXin](./hanxin/) | Anger att data ska kodas med **Han Xin** streckkodsspecifikation |
| static [HIBCAztecLIC](./hibcazteclic/) | Anger att data ska kodas med **HIBC LIC Aztec** streckkodsspecifikation. |
| static [HIBCAztecPAS](./hibcaztecpas/) | Anger att data ska kodas med **HIBC PAS Aztec** streckkodsspecifikation. |
| static [HIBCCode128LIC](./hibccode128lic/) | Anger att data ska kodas med **HIBC LIC Code128** streckkodsspecifikation. |
| static [HIBCCode128PAS](./hibccode128pas/) | Anger att data ska kodas med **HIBC PAS Code128** streckkodsspecifikation. |
| static [HIBCCode39LIC](./hibccode39lic/) | Anger att data ska kodas med **HIBC LIC Code39** streckkodsspecifikation. |
| static [HIBCCode39PAS](./hibccode39pas/) | Anger att data ska kodas med **HIBC PAS Code39** streckkodsspecifikation. |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Anger att data ska kodas med **HIBC LIC DataMatrix** streckkodsspecifikation. |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Anger att data ska kodas med **HIBC PAS DataMatrix** streckkodsspecifikation. |
| static [HIBCQRLIC](./hibcqrlic/) | Anger att data ska kodas med **HIBC LIC QR** streckkodsspecifikation. |
| static [HIBCQRPAS](./hibcqrpas/) | Anger att data ska kodas med **HIBC PAS QR** streckkodsspecifikation. |
| static [IATA2of5](./iata2of5/) | Representerar IATA 2 av 5‑streckkod. IATA (International Air Transport Association) använder denna streckkod för hantering av luftfrakt. |
| static [Interleaved2of5](./interleaved2of5/) | Anger att data ska kodas med **INTERLEAVED 2 of 5** streckkodsspecifikation |
| static [ISBN](./isbn/) | Anger att data ska kodas med **ISBN** streckkodsspecifikation |
| static [ISMN](./ismn/) | Anger att data ska kodas med **ISMN** streckkodsspecifikation |
| static [ISSN](./issn/) | Anger att data ska kodas med **ISSN** streckkodsspecifikation |
| static [ItalianPost25](./italianpost25/) | Representerar Italian Post 25 streckkod. |
| static [ITF14](./itf14/) | Anger att data ska kodas med **ITF14** streckkodsspecifikation |
| static [ITF6](./itf6/) | Representerar ITF-6 streckkod. |
| static [JapanPost](./japanpost/) | Representerar Japan Post [BarCode](../../aspose.barcode/) |
| static [MacroPdf417](./macropdf417/) | Anger att data ska kodas med **MacroPdf417** streckkodsspecifikation |
| static [Mailmark](./mailmark/) | Representerar Royal Mail Mailmark streckkod. |
| static [Matrix2of5](./matrix2of5/) | Representerar Matrix 2 of 5 [BarCode](../../aspose.barcode/) |
| static [MaxiCode](./maxicode/) | Anger att data ska kodas med **MaxiCode** streckkodsspecifikation |
| static [MicroPdf417](./micropdf417/) | Anger att data ska kodas med **MicroPdf417** streckkodsspecifikation |
| static [MicroQR](./microqr/) | Anger att data ska kodas med **MicroQR Code** streckkodsspecifikation |
| static [MSI](./msi/) | Anger att data ska kodas med **MSI Plessey** streckkodsspecifikation |
| static [None](./none/) | Ospecificerad kodningstyp. |
| static [OneCode](./onecode/) | Anger att data ska kodas med USPS **OneCode** streckkodsspecifikation |
| static [OPC](./opc/) | Representerar OPC (Optical Product Code) streckkod, även känd som VCA Barcode VCA OPC, Vision Council of America OPC Barcode. |
| static [PatchCode](./patchcode/) | Representerar Patch code streckkod |
| static [Pdf417](./pdf417/) | Anger att data ska kodas med **Pdf417** streckkodsspecifikation |
| static [Pharmacode](./pharmacode/) | Representerar Pharmacode streckkod. |
| static [Planet](./planet/) | Anger att data ska kodas med **Planet** streckkodsspecifikation |
| static [Postnet](./postnet/) | Anger att data ska kodas med **Postnet** streckkodsspecifikation |
| static [PZN](./pzn/) | Representerar PZN streckkod. Denna symbolik är också känd som Pharmacy central number, Pharmazentralnummer. PZN7 och PZN8 stöds. PZN7 genereras från 6 eller färre siffror, som "123456". PZN8 genereras från 7 eller fler siffror, som "1234567". Angivet sista kontrollsiffra ignoreras och genereras av streckkodsmotorn. |
| static [QR](./qr/) | Anger att data ska kodas med **QR Code** streckkodsspecifikation |
| static [RectMicroQR](./rectmicroqr/) | Anger att data ska kodas med **RectMicroQR (rMQR) Code** streckkodsspecifikation |
| static [RM4SCC](./rm4scc/) | Representerar RM4SCC-streckkod. RM4SCC (Royal Mail 4-state Customer Code) används för automatiserad postsortering i Storbritannien. |
| static [SCC14](./scc14/) | Anger att data ska kodas med **SCC14** streckkodsspecifikation |
| static [SingaporePost](./singaporepost/) | Anger att data ska kodas med **Singapore Post Barcode** streckkodsspecifikation |
| static [SSCC18](./sscc18/) | Anger att data ska kodas med **SSCC18** streckkodsspecifikation |
| static [Standard2of5](./standard2of5/) | Anger att data ska kodas med **Standard 2 of 5** streckkodsspecifikation |
| static [SwissPostParcel](./swisspostparcel/) | Anger att data ska kodas med **Swiss Post Parcel Barcode** streckkodsspecifikation. Stödda typer: Inrikes post, Internationell post, Ytterligare tjänster (nytt) |
| static [UPCA](./upca/) | Anger att data ska kodas med **UPC-A** streckkodsspecifikation |
| static [UpcaGs1Code128Coupon](./upcags1code128coupon/) | Anger att data ska kodas med **UPC coupon with GS1-128 Extended Code** streckkodsspecifikation. Ett exempel på inmatningssträngen: BarcodeGenerator.Codetext = "514141100906(8102)03", där UPCA-delen är "514141100906", GS1Code128-delen är (8102)03. |
| static [UpcaGs1DatabarCoupon](./upcags1databarcoupon/) | Anger att data ska kodas med **UPC coupon with GS1 DataBar addition** streckkodsspecifikation. Ett exempel på inmatningssträngen: BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000", där UPCA-delen är "514141100906", Databar-delen är "(8110)106141416543213500110000310123196000". För att ändra rubriken, använd Parameters.CaptionAbove.Text = "company prefix + offer code"; |
| static [UPCE](./upce/) | Anger att data ska kodas med **UPC-E** streckkodsspecifikation |
| static [VIN](./vin/) | Representerar VIN (Vehicle Identification Number) streckkod. |
## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
