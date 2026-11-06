---
title: "com.aspose.barcode.barcoderecognition"
second_title: "Aspose.BarCode voor Android via Java API-referentie"
description: "Dit pakket bevat tools voor 1D/2D barcodeherkenning."
type: docs
weight: 11
url: /nl/androidjava/com.aspose.barcode.barcoderecognition/
---

Dit pakket bevat tools voor 1D/2D barcodeherkenning.


## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | AustraliaPost decodeerparameters. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Slaat speciale gegevens op van de herkende Aztec-barcode |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Slaat uitgebreide parameters op van de herkende barcode |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader omvat een afbeelding die één of meerdere barcodes kan bevatten, waarna het de ReadBarCodes‑operatie kan uitvoeren om barcodes te detecteren. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Algemene uitzondering gegooid door BarCodeReader, geërfd van BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Stelt de regio en hoek van de herkende barcode voor |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Slaat herkende barcodegegevens op zoals type SingleDecodeType, string codetext, BarCodeRegionParameters regio en andere parameters |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | De belangrijkste BarCode-decodeerparameters. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Barcode-detectorinstellingen. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Basisklasse voor MultiDecodeType en SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Basis‑klasse voor het opslaan van uitgebreide parameters van herkende barcodes |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Slaat aanvullende informatie van Codabar op van de herkende barcode |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Bevat de gegevens van de subtype voor Code128-type barcode |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Slaat speciale gegevens op van de herkende Code128-barcode |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Slaat extra DataBar-informatie van herkende barcode op BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Slaat speciale gegevens van herkende DataMatrix-barcode op |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Specificeer het type barcode om te lezen. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Slaat speciale gegevens van herkende DotCode-barcode op |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Slaat speciale gegevens van herkende **GS1 Composite Bar** barcode op |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Slaat extra MaxiCode-informatie van herkende barcode op |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Samengestelde decodeertype. |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) |  |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Slaat speciale gegevens van herkende 1D-barcode op, zoals afzonderlijke codetekst en controlesom |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Slaat macro‑Pdf417-metadata‑informatie van herkende barcode op |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings maakt het mogelijk barcodes te herkennen met multi‑threading voor betere prestaties |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Slaat QR Structured Append‑informatie van herkende barcode op |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Slaat een set van vier punten op die een vierhoekig gebied vertegenwoordigen. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings maakt handmatige configuratie van herkenningskwaliteit en -snelheid mogelijk. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Stelt een herkennings‑abort‑exception voor die wordt gegooid bij het overschrijden van de time‑out tijdens herkenning met BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Enkel decodeertype. |

## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Openbare interface voor het decoderen van Customer Information Field die wordt gebruikt in AustraliaPost-symbologie. |

## Enumeraties

| Enum | Beschrijving |
| --- | --- |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Bevat herkennings‑vertrouwensniveau |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Bevat types van Code128‑subsets. |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Definieert het interpretatietype (C\_TABLE of N\_TABLE) van klantinformatie voor AustralianPost‑barcode. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | Specificeer de grootte van de geschaalde afbeelding |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
