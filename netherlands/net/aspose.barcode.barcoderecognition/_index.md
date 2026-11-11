---
title: "Aspose.BarCode.BarCodeRecognition"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "De Aspose.BarCode.BarCodeRecognition bevat tools voor de herkenning van 1D/2D barcodes"
type: docs
weight: 20
url: /nl/net/aspose.barcode.barcoderecognition/
---
De **Aspose.BarCode.BarCodeRecognition** bevat hulpmiddelen voor de herkenning van 1D/2D‑barcodes.

## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost-decoderingparameters. Bevat parameters die invloed hebben op de herkende gegevens van de AustraliaPost-symbologie. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Slaat speciale gegevens op van de herkende Aztec barcode |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Slaat uitgebreide parameters op van de herkende barcode |
| [BarCodeReader](./barcodereader/) | BarCodeReader omvat een afbeelding die één of meerdere barcodes kan bevatten; deze kan vervolgens de ReadBarCodes‑operatie uitvoeren om barcodes te detecteren. |
| [BarCodeRecognitionException](./barcoderecognitionexception/) | Algemene uitzondering gegooid door BarCodeReader, geërfd van BarCodeException |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Stelt de regio en hoek van de herkende barcode voor |
| [BarCodeResult](./barcoderesult/) | Slaat herkende barcodegegevens op zoals type [`SingleDecodeType`](../aspose.barcode.barcoderecognition/singledecodetype/), String codetext, regio [`BarCodeRegionParameters`](../aspose.barcode.barcoderecognition/barcoderegionparameters/) en andere parameters |
| [BarcodeSettings](./barcodesettings/) | De belangrijkste BarCode-decoderingparameters. Bevat parameters die invloed hebben op de herkende gegevens. |
| [BaseDecodeType](./basedecodetype/) | Basisklasse voor MultiDecodeType en SingleDecodeType. |
| [BaseExtendedParameters](./baseextendedparameters/) | Basis klasse voor uitgebreide parameters van het opslaan van herkende barcodes |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Slaat extra informatie van een Codabar van de herkende barcode op |
| [Code128DataPortion](./code128dataportion/) | Bevat de gegevens van de subtype voor Code128-type barcode |
| [Code128ExtendedParameters](./code128extendedparameters/) | Slaat speciale gegevens op van de herkende Code128 barcode |
| [DataBarExtendedParameters](./databarextendedparameters/) | Slaat aanvullende informatie van een DataBar van de herkende barcode op |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Slaat speciale gegevens op van de herkende DataMatrix barcode |
| [DecodeType](./decodetype/) | Specificeer het type barcode om te lezen. |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Slaat speciale gegevens op van de herkende DotCode barcode |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Slaat speciale gegevens op van de herkende barcode **GS1 Composite Bar** |
| [Iso15416Quality](./iso15416quality/) | Slaat barcode-kwaliteitsklassen op die zijn berekend volgens de ISO/IEC 15416-standaard voor 1D-barcodes. |
| [IsoSymbolQuality](./isosymbolquality/) | Slaat resultaten van de kwaliteitsbeoordeling van barcode-symbolen op volgens ISO/IEC-standaarden. |
| [LuminanceFrame](./luminanceframe/) | Stelt een 8-bit grijswaardenbeeldframe voor. Elke pixel wordt weergegeven door één byte die de luminantiewaarde bevat. |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Slaat extra informatie van MaxiCode op van de herkende barcode |
| [MultiDecodeType](./multidecodetype/) | Composite decodeertype. |
| [OneDExtendedParameters](./onedextendedparameters/) | Slaat speciale gegevens op van de herkende 1D-barcode, zoals afzonderlijke codetekst en controlesom |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Slaat metadata-informatie van MacroPdf417 op van de herkende barcode |
| [QRExtendedParameters](./qrextendedparameters/) | Slaat QR Structured Append-informatie op van de herkende barcode |
| [Quadrangle](./quadrangle/) | Slaat een set van vier punten op die een [`Quadrangle`](../aspose.barcode.barcoderecognition/quadrangle/) regio vertegenwoordigen. |
| [QualitySettings](./qualitysettings/) | QualitySettings maakt het mogelijk om de herkenningskwaliteit en -snelheid handmatig te configureren. Je kunt QualitySettings snel instellen met ingebouwde presets: HighPerformance, NormalQuality, HighQuality, MaxQuality, of je kunt handmatig afzonderlijke opties configureren. De standaardwaarde van QualitySettings is NormalQuality. |
| [RecognitionAbortedException](./recognitionabortedexception/) | Stelt een herkenningsafbreek-exceptie voor die wordt gegooid bij het overschrijden van de time-out tijdens herkenning met BarCodeReader. |
| [SingleDecodeType](./singledecodetype/) | Enkel decodeertype. Zie decodeertype om een instantie te krijgen. |
## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | Publieke interface voor het decoderen van Customer Information Field die wordt gebruikt in de AustraliaPost-symbologie. Implementatie moet door de gebruiker worden geleverd. |
## Enumeratie

| Enumeratie | Beschrijving |
| --- | --- |
| [BarCodeConfidence](./barcodeconfidence/) | Bevat het herkenningsvertrouwensniveau |
| [BarcodeQualityMode](./barcodequalitymode/) | Modus die methoden inschakelt om barcode‑elementen te herkennen met de geselecteerde kwaliteit. Een barcode‑element met lagere kwaliteit vereist meer intensieve methoden, wat de herkenning vertraagt. |
| [ChecksumValidation](./checksumvalidation/) | Schakel controle‑somvalidatie in tijdens herkenning voor 1D- en post‑barcodes. |
| [Code128SubType](./code128subtype/) | Bevat typen van de Code128‑subset |
| [ComplexBackgroundMode](./complexbackgroundmode/) | Modus die extra herkenning van gekleurde barcodes op kleurafbeeldingen in- of uitschakelt. |
| [DeconvolutionMode](./deconvolutionmode/) | Deconvolutie‑modus (beeldherstel) die het niveau van beelddegradatie definieert. Oorspronkelijk is deconvolutie een functie die een door een natuurlijke functie, zoals vervaging, gedegradeerd (geconvolueerd) beeld kan herstellen bij het verkrijgen van een afbeelding met een camera. Omdat we de beeldfunctie die het beeld corrumpeert niet kunnen detecteren, moeten we de meest bekende functies zoals scherpte of wiskundige morfologie controleren. |
| [InverseImageMode](./inverseimagemode/) | Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt. |
| [XDimensionMode](./xdimensionmode/) | Herkenningsmodus die de grootte (van 1 tot oneindig) van het minimale barcode‑element instelt: matrixcel of balk. |


