---
title: com.aspose.barcode.barcoderecognition
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Dieses Paket enthält Werkzeuge zur 1D/2D‑Barcode‑Erkennung.
type: docs
weight: 11
url: /de/androidjava/com.aspose.barcode.barcoderecognition/
---

Dieses Paket enthält Werkzeuge zur 1D/2D‑Barcode‑Erkennung.


## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | Dekodierungsparameter für AustraliaPost. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Speichert spezielle Daten des erkannten Aztec-Barcodes |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Enthält das Erkennungsvertrauensniveau |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Speichert erweiterte Parameter des erkannten Barcodes |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader kapselt ein Bild, das einen oder mehrere Barcodes enthalten kann, und kann anschließend die ReadBarCodes-Operation ausführen, um Barcodes zu erkennen. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Allgemeine Ausnahme, die von BarCodeReader ausgelöst wird und von BarCodeException erbt |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Stellt den Bereich des erkannten Barcodes und den Barcode-Winkel dar |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Speichert erkannte Barcode-Daten wie den Typ SingleDecodeType, den String codetext, die BarCodeRegionParameters-Region und weitere Parameter |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | Die wichtigsten BarCode-Dekodierungsparameter. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Barcode-Detektoreinstellungen. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Basisklasse für MultiDecodeType und SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Grundklasse für das Speichern erweiterter Parameter erkannter Barcodes |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Speichert zusätzliche Informationen des erkannten Codabar-Barcodes |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Enthält die Daten des Subtyps für den Code128-Barcode |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Speichert spezielle Daten des erkannten Code128‑Strichcodes |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Enthält Typen des Code128‑Teilsets |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Speichert zusätzliche DataBar‑Informationen des erkannten Strichcodes BarCodeReader reader = new BarCodeReader("test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Speichert spezielle Daten des erkannten DataMatrix‑Strichcodes |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Geben Sie den zu lesenden Strichcodetyp an. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Speichert spezielle Daten des erkannten DotCode‑Strichcodes |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Speichert spezielle Daten des erkannten **GS1 Composite Bar** Strichcodes |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Speichert zusätzliche MaxiCode‑Informationen des erkannten Strichcodes |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Composite‑Dekodierungstyp. |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) | Composite‑Dekodierungstyp. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Speichert spezielle Daten des erkannten 1D‑Strichcodes, wie separaten Codetext und Prüfsumme |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Speichert Metadateninformationen von MacroPdf417 des erkannten Strichcodes |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings ermöglichen das Erkennen von Strichcodes mit mehrthreadiger Leistungssteigerung |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Speichert QR‑Structured‑Append‑Informationen des erkannten Strichcodes |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Speichert ein Set von vier  Point s, die eine  Quadrangle  Region darstellen. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings ermöglicht die manuelle Konfiguration von Erkennungsqualität und -geschwindigkeit. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Stellt eine Erkennungsabbruch‑Ausnahme dar, die bei Überschreitung des Zeitlimits während der Erkennung mit BarCodeReader ausgelöst wird. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Einzelner Dekodierungstyp. |
| [TextEncodingDetection](../com.aspose.barcode.barcoderecognition/textencodingdetection) |  |

## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Öffentliche Schnittstelle für die Decodierung des Customer Information Field, die in der AustraliaPost‑Symbolik verwendet wird. |

## Aufzählungen

| Aufzählung | Beschreibung |
| --- | --- |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Definiert den Interpretations­typ (C\_TABLE oder N\_TABLE) der Kundeninformation für AustralianPost‑BarCode. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | Geben Sie die Größe des skalierten Bildes an. |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
