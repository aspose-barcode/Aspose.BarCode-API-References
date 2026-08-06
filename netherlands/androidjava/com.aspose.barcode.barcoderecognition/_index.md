---
title: com.aspose.barcode.barcoderecognition
second_title: Aspose.BarCode for Android via Java API-referentie
description: Dit pakket bevat tools voor 1D/2D barcodeherkenning.
type: docs
weight: 11
url: /nl/androidjava/com.aspose.barcode.barcoderecognition/
---

Dit pakket bevat tools voor 1D/2D barcodeherkenning.


## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | AustraliaPost-decoderingparameters. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Slaat speciale gegevens op van de herkende Aztec-barcode |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Bevat het herkenningsvertrouwensniveau |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Slaat uitgebreide parameters op van de herkende barcode |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader omvat een afbeelding die één of meerdere barcodes kan bevatten; deze kan vervolgens de ReadBarCodes-bewerking uitvoeren om barcodes te detecteren. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Algemene uitzondering gegooid door BarCodeReader, geërfd van BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Stelt de regio en hoek van de herkende barcode voor |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Slaat herkende barcode-gegevens op zoals type SingleDecodeType, string codetext, BarCodeRegionParameters regio en andere parameters |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | De belangrijkste BarCode-decoderingparameters. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Barcode-detectorinstellingen. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Basisklasse voor MultiDecodeType en SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Basis-klasse voor het opslaan van uitgebreide parameters van de herkende barcode |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Slaat aanvullende informatie van Codabar op voor de herkende barcode |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Bevat de gegevens van de subtype voor Code128-type barcode |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Slaat speciale gegevens op van de herkende Code128 barcode |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Bevat typen van de Code128‑subset |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Slaat extra DataBar-informatie op van de herkende barcode BarCodeReader reader = new BarCodeReader("test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Slaat speciale gegevens op van de herkende DataMatrix barcode |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Specificeer het type barcode om te lezen. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Slaat speciale gegevens op van de herkende DotCode barcode |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Slaat speciale gegevens op van de herkende **GS1 Composite Bar** barcode |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Slaat extra MaxiCode‑informatie op van de herkende barcode |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Samengestelde decodeertype. |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) | Samengestelde decodeertype. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Slaat speciale gegevens op van de herkende 1D barcode, zoals afzonderlijke codetekst en controlesom |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Slaat macro‑Pdf417‑metadata‑informatie op van de herkende barcode |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings maakt het mogelijk om barcodes te herkennen met multi‑threaded prestatieverbetering |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Slaat QR Structured Append‑informatie op van de herkende barcode |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Slaat een set van vier punten op die een vierhoekig gebied vertegenwoordigen. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings maakt het mogelijk om de herkenningskwaliteit en -snelheid handmatig te configureren. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Stelt een herkennings‑abort‑exception voor die wordt gegooid bij het overschrijden van de time‑out tijdens herkenning met BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Enkel decodeertype. |
| [TextEncodingDetection](../com.aspose.barcode.barcoderecognition/textencodingdetection) |  |

## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Publieke interface voor het decoderen van Customer Information Field die wordt gebruikt in AustraliaPost‑symbologie. |

## Enumeraties

| Enum | Beschrijving |
| --- | --- |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Definieert het interpretatietype (C\_TABLE of N\_TABLE) van klantinformatie voor AustralianPost‑barcode. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | Specificeer de grootte van de geschaalde afbeelding |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
