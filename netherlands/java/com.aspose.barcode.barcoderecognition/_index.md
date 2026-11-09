---
title: "com.aspose.barcode.barcoderecognition"
second_title: "Aspose.BarCode for Java API-referentie"
description: "Dit pakket bevat tools voor 1D/2D barcodeherkenning."
type: docs
weight: 12
url: /nl/java/com.aspose.barcode.barcoderecognition/
---

Dit pakket bevat tools voor 1D/2D barcodeherkenning.


## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | AustraliaPost decodeerparameters. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Slaat speciale gegevens op van een herkende Aztec-barcode. |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Slaat uitgebreide parameters op van een herkende barcode. |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader omsluit een afbeelding die één of meerdere barcodes kan bevatten; deze kan vervolgens de ReadBarCodes‑bewerking uitvoeren om barcodes te detecteren. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Algemene uitzondering gegooid door BarCodeReader, geërfd van BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Stelt de regio en hoek van de herkende barcode voor. |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Slaat herkende barcodegegevens op, zoals type SingleDecodeType, string codetext, BarCodeRegionParameters regio en andere parameters. |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | De belangrijkste BarCode-decodeerparameters. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Instellingen voor barcode‑detector. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Basisklasse voor MultiDecodeType en SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Basis‑klasse voor het opslaan van uitgebreide parameters van herkende barcodes. |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Slaat extra informatie van een herkende Codabar-barcode op |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Bevat de gegevens van de subtype voor Code128-type barcode |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Slaat speciale gegevens van een herkende Code128-barcode op |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Slaat extra informatie van een herkende DataBar-barcode op BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Slaat speciale gegevens van een herkende DataMatrix-barcode op |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Geef het type barcode op dat gelezen moet worden. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Slaat speciale gegevens van een herkende DotCode-barcode op |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Slaat speciale gegevens van een herkende **GS1 Composite Bar**-barcode op |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Slaat extra informatie van een herkende MaxiCode-barcode op |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Samengestelde decodeertype. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Slaat speciale gegevens van een herkende 1D-barcode op, zoals afzonderlijke codetekst en controlesom |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Slaat metadata-informatie van een herkende MacroPdf417-barcode op |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings maakt het mogelijk barcodes te herkennen met multi-threaded prestatieverbetering |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Slaat QR Structured Append-informatie van een herkende barcode op |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Slaat een set van vier Point s op die een Quadrangle-regio vertegenwoordigen. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings maakt het mogelijk de herkenningskwaliteit en -snelheid handmatig te configureren. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Stelt een herkenningsafbreek-exceptie voor die wordt gegooid bij het overschrijden van de time-out tijdens herkenning met BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Enkel decodeertype. |

## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Publieke interface voor het decoderen van Customer Information Field die wordt gebruikt in de AustraliaPost-symbologie. |

## Enumeraties

| Enum | Beschrijving |
| --- | --- |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Bevat het herkenningsvertrouwensniveau |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Bevat types van Code128-subset. |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Definieert het interpretatietype (C\_TABLE of N\_TABLE) van klantinformatie voor AustralianPost BarCode. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
