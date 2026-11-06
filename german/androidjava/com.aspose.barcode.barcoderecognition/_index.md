---
title: "com.aspose.barcode.barcoderecognition"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Dieses Paket enthält Werkzeuge für die 1D/2D-Barcode-Erkennung."
type: docs
weight: 11
url: /de/androidjava/com.aspose.barcode.barcoderecognition/
---

Dieses Paket enthält Werkzeuge für die 1D/2D-Barcode-Erkennung.


## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | Dekodierungsparameter für AustraliaPost. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Speichert spezielle Daten des erkannten Aztec-Barcodes |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Speichert erweiterte Parameter des erkannten Barcodes |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader kapselt ein Bild, das einen oder mehrere Barcodes enthalten kann, und kann anschließend die ReadBarCodes-Operation ausführen, um Barcodes zu erkennen. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Allgemeine Ausnahme, die von BarCodeReader ausgelöst wird und von BarCodeException erbt |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Stellt die Region des erkannten Barcodes und den Barcode-Winkel dar |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Speichert erkannte Barcode-Daten wie den Typ SingleDecodeType, den String codetext, die BarCodeRegionParameters-Region und weitere Parameter |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | Die wichtigsten BarCode-Dekodierungsparameter. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Einstellungen des Barcode-Detektors. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Basisklasse für MultiDecodeType und SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Grundklasse für die Speicherung erweiterter Parameter des erkannten Barcodes |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Speichert zusätzliche Informationen des erkannten Codabar-Barcodes |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Enthält die Daten des Subtyps für den Code128-Barcode |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Speichert spezielle Daten des erkannten Code128-Barcodes |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Speichert zusätzliche DataBar-Informationen des erkannten Barcodes BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Speichert spezielle Daten des erkannten DataMatrix-Barcodes |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Geben Sie den zu lesenden Barcodetyp an. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Speichert spezielle Daten des erkannten DotCode-Barcodes |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Speichert spezielle Daten des erkannten **GS1 Composite Bar** Barcodes |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Speichert zusätzliche MaxiCode-Informationen des erkannten Barcodes |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Composite-Dekodierungstyp. |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) |  |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Speichert spezielle Daten des erkannten 1D-Barcodes, wie separaten Codetext und Prüfsumme |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Speichert Metadateninformationen von MacroPdf417 des erkannten Barcodes |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings ermöglichen das Erkennen von Barcodes mit multithreaded Leistungssteigerung |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Speichert QR Structured Append-Informationen des erkannten Barcodes |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Speichert ein Set von vier Punkten, die eine Viereck-Region darstellen. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings ermöglicht die manuelle Konfiguration von Erkennungsqualität und -geschwindigkeit. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Stellt eine Erkennungsabbruch-Ausnahme dar, die bei Überschreitung des Zeitlimits während der Erkennung mit BarCodeReader ausgelöst wird. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Einzelner Dekodierungstyp. |

## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Öffentliche Schnittstelle für die Dekodierung des Customer Information Field, die in der AustraliaPost-Symbologie verwendet wird. |

## Aufzählungen

| Aufzählung | Beschreibung |
| --- | --- |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Enthält das Erkennungsvertrauensniveau |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Enthält Typen des Code128-Subset. |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Definiert den Interpretationstyp (C\\_TABLE oder N\\_TABLE) der Kundeninformation für AustralianPost BarCode. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | Geben Sie die Größe des skalierten Bildes an |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
