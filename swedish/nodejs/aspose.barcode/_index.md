---
title: "aspose.barcode"
linktitle: "aspose.barcode"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Namnutrymmet aspose.barcode erbjuder klasser och uppräkningar för att skapa, anpassa och avkoda ett brett utbud av streckkodstyper i Node.js via Java."
type: docs
weight: 10
url: /sv/nodejs/aspose.barcode/
---
Använd dessa typer för att konfigurera inställningar för streckkodsgenerering såsom adressformat, regionala specifikationer och avancerade parametrar för Aztec och andra symboler. Namnutrymmet innehåller hjälpfunktioner för att bygga utökade kodtexter och hantera specialiserade poststandarder.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Address](./address/) | Adress för borgenär eller gäldenär. Du kan antingen ange gata, husnummer, postnummer och ort (typ strukturerad adress) o |
| [AlternativeScheme](./alternativescheme/) | Instruktioner för alternativ betalningsplan |
| [AustraliaPostSettings](./australiapostsettings/) | Avkodningsparametrar för AustraliaPost. Innehåller parametrar som påverkar den igenkända datan för AustraliaPost‑symbolen |
| [AustralianPostParameters](./australianpostparameters/) | AustralianPost streckkodparametrar. |
| [AztecExtCodetextBuilder](./aztecextcodetextbuilder/) | Utökad kodtextgenerator för Aztec‑streckkoder för ExtendedCodetext‑läget i AztecEncodeMode. Använd egenskapen TwoDDisplayText. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Lagrar specialdata för Aztec‑igenkänd streckkod. Detta exempel visar hur man får Aztec‑råvärden låt generator = new Barcod |
| [AztecParameters](./aztecparameters/) | Aztec‑parametrar. |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Lagrar utökade parametrar för igenkänd streckkod |
| [BarCodeReader](./barcodereader/) | BarCodeReader kapslar in en bild som kan innehålla en eller flera streckkoder, och kan sedan utföra ReadBarCodes‑operationen |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Representerar den igenkända streckkodens region och streckkodsvinkel |
| [BarCodeResult](./barcoderesult/) | Lagrar igenkända streckkoddata såsom SingleDecodeType‑typ, `string` kodtext, BarCodeRegionParameters‑region och andra p |
| [BarcodeException](./barcodeexception/) |  |
| [BarcodeGenerator](./barcodegenerator/) | BarcodeGenerator för generering av streckkodsbilder i backend. stödda symboler: 1D: Codabar, Code11, Code128, Code39Stand |
| [BarcodeParameters](./barcodeparameters/) | Parametrar för streckkodsgenerering. |
| [BarcodeSettings](./barcodesettings/) | De viktigaste avkodningsparametrarna för streckkod. Innehåller parametrar som påverkar den igenkända datan. |
| [BaseGenerationParameters](./basegenerationparameters/) | Parametrar för generering av streckkodsbilder. |
| [BorderParameters](./borderparameters/) | Parametrar för streckkodsbildens kant |
| [CMYKColor](./cmykcolor/) | Klass för CMYK-färg. En null-instans betyder att CMYK inte används och standard‑RGB‑färg är i bruk. |
| [CaptionParameters](./captionparameters/) | Parametrar för rubrik. |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Lagrar extra information för Codabar för den igenkända streckkoden |
| [CodabarParameters](./codabarparameters/) | Codabar-parametrar. |
| [CodablockParameters](./codablockparameters/) | Codablock-parametrar. |
| [Code128DataPortion](./code128dataportion/) | Innehåller data för undertypen av Code128‑streckkod |
| [Code128ExtendedParameters](./code128extendedparameters/) | Lagrar specialdata för igenkänd Code128‑streckkod. Representerar den igenkända streckkodens region och vinkel. |
| [Code128Parameters](./code128parameters/) | Code128-parametrar. |
| [Code16KParameters](./code16kparameters/) | Code16K-parametrar. |
| [CodetextParameters](./codetextparameters/) | Kodtext‑parametrar. |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | ComplexBarcodeGenerator för generering av backend‑komplexa streckkodsbilder (t.ex. SwissQR). |
| [ComplexCodetextReader](./complexcodetextreader/) | ComplexCodetextReader avkodar kodtext till angiven komplex streckkodstyp. |
| [CouponParameters](./couponparameters/) | Kupongparametrar. Används för UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarExtendedParameters](./databarextendedparameters/) | Lagrar extra information för DataBar för den igenkända streckkoden |
| [DataBarParameters](./databarparameters/) | Databar-parametrar. |
| [DataElement](./dataelement/) | Representerar ett jurisdiktionsspecifikt datafält som används i dokument, till exempel ElementID = \"ZVA\" med Value = \"01\". |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/) | Utökad kodtextgenerator för 2D DataMatrix‑streckkoder för ExtendedCodetext‑läge i DataMatrixEncodeMode //Extended code |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Lagrar specialdata för igenkänd DataMatrix‑streckkod. Detta exempel visar hur man får DataMatrix‑råvärden, låt generator = |
| [DataMatrixParameters](./datamatrixparameters/) | DataMatrix-parametrar. |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | Utökad kodtextgenerator för 2D DotCode‑streckkoder för ExtendedCodetext‑läge i DotCodeEncodeMode |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Lagrar specialdata för igenkänd DotCode‑streckkod. Detta exempel visar hur man får DotCode‑råvärden |
| [DotCodeParameters](./dotcodeparameters/) | DotCode-parametrar. |
| [ExtCodetextBuilder](./extcodetextbuilder/) | Hjälparklass för automatisk generering av kodtext för det utökade kodtextläget |
| [FontUnit](./fontunit/) | Definierar ett specifikt format för text, inklusive teckensnitt, storlek och stilattribut där storleken är i enhetsvärdesegenskapen. |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Lagrar speciella data för den igenkända streckkoden `GS1 Composite Bar ` |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | GS1 Composite bar-parametrar. |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | Klass för kodning och avkodning av text som är inbäddad i HIBC LIC-koden som lagrar primära och sekundära data. Detta samp |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | Basisklass för kodning och avkodning av text som är inbäddad i HIBC LIC-koden. Detta exempel visar hur man avkodar rå HIBC LI |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | Klass för kodning och avkodning av text som är inbäddad i HIBC LIC-koden som lagrar primära data. Detta exempel visar hur |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | Klass för kodning och avkodning av text som är inbäddad i HIBC LIC-koden som lagrar sekundära data. |
| [HIBCPASCodetext](./hibcpascodetext/) | Klass för kodning och avkodning av text som är inbäddad i HIBC PAS-koden. |
| [HIBCPASRecord](./hibcpasrecord/) | Klass för lagring av HIBC PAS-post. |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/) | Utökad kodtextgenerator för Han Xin-kod för utökat läge i HanXinEncodeMode //Extended codetext mode //create cod |
| [HanXinParameters](./hanxinparameters/) | Han Xin-parametrar. |
| [HslaColor](./hslacolor/) | Klass för att representera HSLA-färg (Hue, Saturation, Lightness, Alpha) |
| [IComplexCodetext](./icomplexcodetext/) | Gränssnitt för komplex kodtext som används med ComplexBarcodeGenerator. |
| [ITFParameters](./itfparameters/) | ITF-parametrar. |
| [ImageParameters](./imageparameters/) | Bildparametrar. |
| [License](./license/) | Tillhandahåller metoder för att licensiera komponenten. |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | Klass för kodning och avkodning av text som är inbäddad i Royal Mail 2D Mailmark-koden. |
| [MailmarkCodetext](./mailmarkcodetext/) | Klass för kodning och avkodning av text som är inbäddad i den 4‑stegs Royal Mailmark-koden. |
| [MandatoryFields](./mandatoryfields/) | Obligatoriska element (fält) på kortet |
| [MaxiCodeCodetext](./maxicodecodetext/) | Basisklass för kodning och avkodning av text som är inbäddad i MaxiCode-koden. Detta exempel visar hur man avkodar rå MaxiCod |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | Klass för kodning och avkodning av text som är inbäddad i MaxiCode-koden för läge 2. |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | Klass för kodning och avkodning av text som är inbäddad i MaxiCode-koden för läge 3. Detta exempel visar hur man kodar och |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | Utökad kodtextgenerator för MaxiCode-streckkoder för ExtendedCodetext-läge i MaxiCodeEncodeMode Använd TwoDDisplayText pr |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Lagrar ytterligare information om MaxiCode för igenkänd streckkod |
| [MaxiCodeParameters](./maxicodeparameters/) | MaxiCode-parametrar. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | Klass för kodning och avkodning av MaxiCode‑kodtext för lägena 4, 5 och 6. |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | Klass för kodning och avkodning av MaxiCode‑kodtext för lägena 4, 5 och 6. |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | Klass för kodning och avkodning av standard andra meddelandet för MaxiCode‑streckkod. |
| [MaxiCodeStandartSecondMessage](./maxicodestandartsecondmessage/) | Klass för kodning och avkodning av standard andra meddelandet för MaxiCode‑streckkod. |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | Bas‑klass för kodning och avkodning av texten som är inbäddad i MaxiCode‑koden för lägena 2 och 3. |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | Klass för kodning och avkodning av strukturerat andra meddelande för MaxiCode‑streckkod. |
| [OneDExtendedParameters](./onedextendedparameters/) | Lagrar speciella data för 1D‑igenkänd streckkod, såsom separat kodtext och kontrollsumma |
| [OptionalFields](./optionalfields/) | Valfria element (fält) i kortet |
| [Padding](./padding/) | Utfyllnadsparametrar. |
| [PatchCodeParameters](./patchcodeparameters/) | PatchCode-parametrar. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Lagrar metadata‑information för MacroPdf417 för igenkänd streckkod |
| [Pdf417Parameters](./pdf417parameters/) | PDF417-parametrar. Innehåller PDF417, MacroPDF417, MicroPDF417 och GS1MicroPdf417‑parametrar. MacroPDF417 kräver två fält |
| [PdfParameters](./pdfparameters/) | PDF‑parameteromslag. Förväntar sig en underliggande `mwObject`‑instans som tillhandahåller motsvarande hämta‑/sätt‑metoder |
| [PostalParameters](./postalparameters/) | Postparametrar. Används för Postnet, Planet. |
| [PrimaryData](./primarydata/) | Klass för lagring av primära HIBC LIC‑data. |
| [QRExtendedParameters](./qrextendedparameters/) | Lagrar QR Structured Append‑information för igenkänd streckkod |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/) | Utökad kodtextgenerator för 2D‑QR‑streckkoder för ExtendedCodetext‑läge i QREncodeMode. Använd Display2DText‑egenskapen i B |
| [QrParameters](./qrparameters/) | QR-parametrar. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters/) | QR Structured Append‑parametrar. |
| [Quadrangle](./quadrangle/) | Lagrar en uppsättning av fyra punkter som representerar ett fyrhörningsområde. |
| [QualitySettings](./qualitysettings/) | QualitySettings möjliggör att manuellt konfigurera igenkänningskvalitet och hastighet. Du kan snabbt ställa in QualitySettings genom att ... |
| [RecognitionAbortedException](./recognitionabortedexception/) | Representerar ett avbrottsundantag för igenkänning som kastas när tidsgränsen överskrids under igenkänning med BarCodeReader. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | Klass för lagring av sekundära och ytterligare HIBC LIC‑data. |
| [SubfileProperties](./subfileproperties/) | USA DL‑underfilsegenskaper, offset och längd sätts automatiskt. |
| [SupplementParameters](./supplementparameters/) | Kompletterande parametrar. Används för Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SvgParameters](./svgparameters/) | SVG-parametrar. |
| [SwissQRBill](./swissqrbill/) | SwissQR-fakturadata |
| [SwissQRCodetext](./swissqrcodetext/) | Klass för kodning och avkodning av text som är inbäddad i SwissQR-koden. |
| [USADriveIdCodetext](./usadriveidcodetext/) | Klass för kodning och avkodning av text som är inbäddad i USA:s körkort PDF417-kod. |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | Klass för jurisdiktionsspecifika fält för USA:s körkort |
| [Unit](./unit/) | Anger storleksvärdet i olika enheter (pixel, tum osv.). |
