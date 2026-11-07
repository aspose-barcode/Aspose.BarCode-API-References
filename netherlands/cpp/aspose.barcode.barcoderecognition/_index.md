---
title: "Aspose::BarCode::BarCodeRecognition namespace"
linktitle: "Aspose::BarCode::BarCodeRecognition"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Hoe de Aspose::BarCode::BarCodeRecognition namespace te gebruiken in C++."
type: docs
weight: 200
url: /nl/cpp/aspose.barcode.barcoderecognition/
---



## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | Openbare interface voor het decoderen van Customer Information Field die wordt gebruikt in AustraliaPost-symbologie. Implementatie moet door de gebruiker worden geleverd. |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost-decodering parameters. Bevat parameters die invloed hebben op de herkende gegevens van AustraliaPost-symbologie. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Slaat speciale gegevens op van de herkende Aztec-barcode |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Slaat uitgebreide parameters op van de herkende barcode |
| [BarCodeReader](./barcodereader/) | [BarCodeReader](./barcodereader/) omvat een afbeelding die één of meerdere barcodes kan bevatten, waarna het de ReadBarCodes‑bewerking kan uitvoeren om barcodes te detecteren. |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Stelt de regio en hoek van de herkende barcode voor |
| [BarCodeResult](./barcoderesult/) | Slaat herkende barcode‑gegevens op zoals het type [SingleDecodeType](./singledecodetype/), **System::String** codetext, de regio [BarCodeRegionParameters](./barcoderegionparameters/) en andere parameters |
| [BarcodeSettings](./barcodesettings/) | De belangrijkste [BarCode](../aspose.barcode/) decoderingparameters. Bevat parameters die invloed hebben op de herkende gegevens. |
| [BaseDecodeType](./basedecodetype/) | Basisklasse voor [MultiDecodeType](./multidecodetype/) en [SingleDecodeType](./singledecodetype/). |
| [BaseExtendedParameters](./baseextendedparameters/) | Basis­klasse voor het opslaan van uitgebreide parameters van herkende barcodes |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Slaat aanvullende informatie van Codabar op voor de herkende barcode |
| [Code128DataPortion](./code128dataportion/) | Bevat de gegevens van de subtype voor Code128‑type barcode |
| [Code128ExtendedParameters](./code128extendedparameters/) | Slaat speciale gegevens op van de herkende Code128‑barcode |
| [DataBarExtendedParameters](./databarextendedparameters/) | Slaat aanvullende informatie van DataBar op voor de herkende barcode |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Slaat speciale gegevens op van de herkende [DataMatrix](../aspose.barcode.barcoderecognition.datamatrix/)-barcode |
| [DecodeType](./decodetype/) | Specificeer het type barcode om te lezen. |
| [Details_BarCodeRecognitionException](./details_barcoderecognitionexception/) | Algemene uitzondering die wordt gegooid door [BarCodeReader](./barcodereader/), geërfd van BarCodeException |
| [Details_RecognitionAbortedException](./details_recognitionabortedexception/) | Stelt de herkennings‑afbreekuitzondering voor die wordt gegooid bij het overschrijden van de time‑out tijdens herkenning met [BarCodeReader](./barcodereader/). |
| [Details_RecognitionEngineException](./details_recognitionengineexception/) |  |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Slaat speciale gegevens op van de herkende DotCode‑barcode |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Slaat speciale gegevens op van de herkende **GS1 Composite Bar**‑barcode |
| [Iso15416Quality](./iso15416quality/) | Slaat barcode-kwaliteitsklassen op die zijn berekend volgens de ISO/IEC 15416-standaard voor 1D-barcodes. |
| [IsoSymbolQuality](./isosymbolquality/) | Slaat resultaten van barcode-symboolkwaliteitsbeoordeling op volgens ISO/IEC-standaarden. |
| [LuminanceFrame](./luminanceframe/) | Stelt een 8-bit grijswaardenbeeldframe voor. Elke pixel wordt weergegeven door één byte die de luminantiewaarde bevat. |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Slaat extra MaxiCode-informatie van herkende barcode op |
| [MultiDecodeType](./multidecodetype/) | Samengestelde decodeertype. |
| [OneDExtendedParameters](./onedextendedparameters/) | Slaat speciale gegevens van 1D-herkende barcode op, zoals aparte codetekst en controlesom |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Slaat macroPdf417-metadata-informatie van herkende barcode op |
| [QRExtendedParameters](./qrextendedparameters/) | Slaat een [QR](../aspose.barcode.barcoderecognition.qr/) Structured Append-informatie van herkende barcode op |
| [Quadrangle](./quadrangle/) | Slaat een set van vier [Point](../)s op die een [Quadrangle](./quadrangle/) regio vertegenwoordigen. |
| [QualitySettings](./qualitysettings/) | [QualitySettings](./qualitysettings/) maakt handmatige configuratie van herkenningskwaliteit en -snelheid mogelijk. Je kunt snel [QualitySettings](./qualitysettings/) instellen met ingebouwde presets: HighPerformance, NormalQuality, HighQuality, MaxQuality of je kunt handmatig afzonderlijke opties configureren. De standaardwaarde van [QualitySettings](./qualitysettings/) is NormalQuality. |
| [SingleDecodeType](./singledecodetype/) | Enkel decodeertype. Zie decodeertype om een instantie te verkrijgen. |
## Enums

| Enum | Beschrijving |
| --- | --- |
| [ChecksumValidation](./checksumvalidation/) |  |
| [Code128SubType](./code128subtype/) | Bevat typen van Code128-subset |
| [BarCodeConfidence](./barcodeconfidence/) | Bevat herkenningsvertrouwensniveau |
| [BarcodeQualityMode](./barcodequalitymode/) |  |
| [ComplexBackgroundMode](./complexbackgroundmode/) |  |
| [DeconvolutionMode](./deconvolutionmode/) |  |
| [InverseImageMode](./inverseimagemode/) |  |
| [XDimensionMode](./xdimensionmode/) |  |
## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [BarCodeRecognitionException](./barcoderecognitionexception/) |  |
| [RecognitionEngineException](./recognitionengineexception/) |  |
| [RecognitionAbortedException](./recognitionabortedexception/) |  |
