---
title: "com.aspose.barcode.barcoderecognition"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "Dieses Paket enthält Werkzeuge zur 1D/2D‑Barcode-Erkennung."
type: docs
weight: 12
url: /de/java/com.aspose.barcode.barcoderecognition/
---

Dieses Paket enthält Werkzeuge zur 1D/2D‑Barcode-Erkennung.


## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | AustraliaPost-Dekodierungsparameter. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Speichert spezielle Daten des erkannten Aztec‑Barcodes. |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Speichert erweiterte Parameter des erkannten Barcodes. |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader kapselt ein Bild, das einen oder mehrere Barcodes enthalten kann, und kann anschließend die ReadBarCodes‑Operation ausführen, um Barcodes zu erkennen. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Allgemeine Ausnahme, die von BarCodeReader ausgelöst wird und von BarCodeException erbt. |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Stellt die Region des erkannten Barcodes und den Barcode‑Winkel dar. |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Speichert erkannte Barcode‑Daten wie den Typ SingleDecodeType, den String codetext, die BarCodeRegionParameters‑Region und weitere Parameter. |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | Die wichtigsten Barcode‑Dekodierungsparameter. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Barcode‑Detektoreinstellungen. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Basisklasse für MultiDecodeType und SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Grundklasse für das Speichern erweiterter Parameter erkannter Barcodes. |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Speichert zusätzliche Informationen eines erkannten Codabar-Strichcodes |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Enthält die Daten des Subtyps für den Code128-Typ-Strichcode |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Speichert spezielle Daten des erkannten Code128-Strichcodes |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Speichert zusätzliche DataBar-Informationen eines erkannten Strichcodes BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Speichert spezielle Daten des erkannten DataMatrix-Strichcodes |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Geben Sie den zu lesenden Strichcode-Typ an. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Speichert spezielle Daten des erkannten DotCode-Strichcodes |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Speichert spezielle Daten des erkannten **GS1 Composite Bar** Strichcodes |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Speichert zusätzliche MaxiCode-Informationen eines erkannten Strichcodes |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Zusammengesetzter Decodierungstyp. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Speichert spezielle Daten eines erkannten 1D-Strichcodes, wie separaten Code-Text und Prüfsumme |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Speichert Metadateninformationen des erkannten MacroPdf417-Strichcodes |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings ermöglichen das Erkennen von Strichcodes mit mehrthreadiger Leistungssteigerung |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Speichert QR Structured Append-Informationen eines erkannten Strichcodes |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Speichert ein Set von vier Point s, die eine Quadrangle Region darstellen. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings ermöglicht die manuelle Konfiguration von Erkennungsqualität und -geschwindigkeit. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Stellt eine Erkennungsabbruch‑Ausnahme dar, die bei Überschreitung des Zeitlimits während der Erkennung mit BarCodeReader ausgelöst wird. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Einzelner Decodierungstyp. |

## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Öffentliche Schnittstelle für die Dekodierung des Customer Information Field, die in der AustraliaPost‑Symbolik verwendet wird. |

## Aufzählungen

| Aufzählung | Beschreibung |
| --- | --- |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Enthält das Erkennungs‑Vertrauensniveau |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Enthält Typen des Code128-Subset. |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Definiert den Interpretationstyp (C\_TABLE oder N\_TABLE) der Kundeninformationen für den AustralianPost-Barcode. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
