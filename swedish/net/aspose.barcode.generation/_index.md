---
title: Aspose.BarCode.Generation
second_title: Aspose.BarCode för .NET API-referens
description: Den Aspose.BarCode.Generation som innehåller allmänna klasser för implementering av streckkodsgenereringsfunktioner.
type: docs
weight: 50
url: /sv/net/aspose.barcode.generation/
---
Den **Aspose.BarCode.Generation** som innehåller allmänna klasser för implementering av streckkodsgenereringsfunktioner.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AustralianPostParameters](./australianpostparameters) | AustralianPost streckkodsparametrar. |
| [AztecParameters](./aztecparameters) | Aztec parametrar. |
| [BarcodeGenerator](./barcodegenerator) | BarcodeGenerator för generering av backend-streckkodsbilder. |
| [BarcodeParameters](./barcodeparameters) | Parametrar för generering av streckkoder. |
| [BaseEncodeType](./baseencodetype) | Basklass för SymbologyEncodeType. |
| [BaseGenerationParameters](./basegenerationparameters) | Parametrar för generering av streckkodsbilder. |
| [BorderParameters](./borderparameters) | Streckkodsbild kantparametrar |
| [CaptionParameters](./captionparameters) | Bildtextparametrar. |
| [CodabarParameters](./codabarparameters) | Codabar-parametrar. |
| [CodablockParameters](./codablockparameters) | Codablock parametrar. |
| [Code16KParameters](./code16kparameters) | Code16K parametrar. |
| [CodetextParameters](./codetextparameters) | Kodtextparametrar. |
| [CouponParameters](./couponparameters) | Kupongparametrar. Används för UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarParameters](./databarparameters) | Datafältsparametrar. |
| [DataMatrixParameters](./datamatrixparameters) | DataMatrix parametrar. |
| [DotCodeParameters](./dotcodeparameters) | DotCode parametrar. |
| [EncodeTypes](./encodetypes) | Anger vilken typ av streckkod som ska kodas. |
| [ExtCodetextBuilder](./extcodetextbuilder) | Hjälparklass för automatisk kodtextgenerering av det utökade kodtextläget |
| [FontUnit](./fontunit) | Definierar ett visst format för text, inklusive teckensnitt, storlek och stilattribut där storlek i egenskapen Unit value. |
| [GS1CompositeBarParameters](./gs1compositebarparameters) | GS1 Sammansatta stapelparametrar. |
| [ITFParameters](./itfparameters) | ITF-parametrar. |
| [MaxiCodeParameters](./maxicodeparameters) | MaxiCode parametrar. |
| [Padding](./padding) | Paddings parametrar. |
| [PatchCodeParameters](./patchcodeparameters) | PatchCode parametrar. |
| [Pdf417Parameters](./pdf417parameters) | PDF417 parametrar. Innehåller parametrarna PDF417, MacroPDF417 och MicroPDF417. MacroPDF417 kräver två fält: Pdf417MacroFileID och Pdf417MacroSegmentID. Alla andra fält är valfria. MicroPDF417 i Structured Append-läge (samma som MacroPDF417-läge) kräver två fält: Pdf417MacroFileID och Pdf417MacroSegmentID. Alla andra fält är valfria. |
| [PostalParameters](./postalparameters) | Postparametrar. Används för Postnet, Planet. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder) | Utökad kodtextgenerator för 2D QR-streckkoder för ExtendedCodetext Mode för QrEncodeMode |
| [QrParameters](./qrparameters) | QR-parametrar. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters) | QR-strukturerade tilläggsparametrar. |
| [SupplementParameters](./supplementparameters) | Tilläggsparametrar. Används för Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SymbologyEncodeType](./symbologyencodetype) | Symbolkodningstyp. Se EncodeTypes för att hämta instans. |
| [Unit](./unit) | Anger storleksvärdet i olika enheter (pixel, tum, etc.). |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [AutoSizeMode](./autosizemode) | Anger olika typer av automatiska storlekslägen. |
| [AztecSymbolMode](./aztecsymbolmode) | Anger det aztekiska symbolläget. |
| [BarcodeClassifications](./barcodeclassifications) | Symbologisk klassificering |
| [BarCodeImageFormat](./barcodeimageformat) | Anger filformatet för bilden. |
| [BorderDashStyle](./borderdashstyle) | Anger stilen för streckade kantlinjer. |
| [CodabarChecksumMode](./codabarchecksummode) | Anger kontrollsummaalgoritmen för Codabar |
| [CodabarSymbol](./codabarsymbol) | Anger start- eller stoppsymbolen för Codabars streckkodsspecifikation. |
| [Code128Emulation](./code128emulation) | Funktionskodord för kod 128-emulering. Gällde endast för MicroPDF417. Ignoreras för streckkoderna PDF417 och MacroPDF417. |
| [CodeLocation](./codelocation) | Kodtext plats |
| [DataMatrixEccType](./datamatrixecctype) | Ange vilken typ av ECC som ska kodas. |
| [DataMatrixEncodeMode](./datamatrixencodemode) | DataMatrix-kodarens kodningsläge, standard till Auto |
| [ECIEncodings](./eciencodings) | Identifierare för utökad kanaltolkning. Den används för att berätta streckkodsläsarens detaljer om de referenser som används för att koda data i symbolen. Den nuvarande implementeringen består av alla välkända teckenuppsättningskoder. För närvarande används den endast för QR 2D-streckkoder. |
| [EnableChecksum](./enablechecksum) | Aktivera kontrollsumma under generering för 1D-streckkoder. |
| [FontMode](./fontmode) | Läge för teckenstorlek. |
| [ITF14BorderType](./itf14bordertype) | ITF14 kanttyp av streckkod |
| [MacroCharacter](./macrocharacter) | Makrotecken 05 och 06 värden används för att erhålla mer kompakt kodning i speciallägen. 05 Makro craracter översätts till "[)&gt;\u001E05\u001D" som avkodad datahuvud och "\u001E" som avkodad data. 06 Makro craracter är översatt till "[)&gt;\u001E06\u001D" som avkodad datahuvud och "\u001E\u0004" som avkodad datatrailer. |
| [PatchFormat](./patchformat) | PatchCode-format. Välj PatchOnly för att generera en enda PatchCode. Använd sidformat för att generera patchsida med patchkoder som borders |
| [Pdf417CompactionMode](./pdf417compactionmode) | Pdf417 streckkodskomprimeringsläge |
| [Pdf417ErrorLevel](./pdf417errorlevel) | pdf417 streckkodens felkorrigeringsnivå, från nivå 0 till nivå 9, nivå 0 betyder ingen felkorrigering, nivå 9 betyder bästa felkorrigering |
| [QREncodeMode](./qrencodemode) | Kodningsläge för QR-streckkoder. Det rekommenderas att använda Auto med CodeTextEncoding = Encoding.UTF8 för latinska symboler eller siffror och Utf8BOM för Unicode-symboler. |
| [QREncodeType](./qrencodetype) | QR / MicroQR-väljarläge. Välj ForceQR för standard QR-symboler, Auto för MicroQR. ForceMicroQR används för starkt generering av MicroQR-symboler om det är möjligt. |
| [QRErrorLevel](./qrerrorlevel) | Nivå av Reed-Solomon felkorrigering. Från låg till hög: LevelL, LevelM, LevelQ, LevelH. |
| [QRVersion](./qrversion) | Version av QR Code. Från Version1 till Version40 för QR-kod och från M1 till M4 för MicroQr. |
| [TextAlignment](./textalignment) | Textjustering. |
| [TwoDComponentType](./twodcomponenttype) | Typ av 2D-komponent |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
