---
title: "Namespace Aspose::BarCode::BarCodeRecognition"
linktitle: "Aspose::BarCode::BarCodeRecognition"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Wie man den Namespace Aspose::BarCode::BarCodeRecognition in C++ verwendet."
type: docs
weight: 200
url: /de/cpp/aspose.barcode.barcoderecognition/
---



## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | Öffentliche Schnittstelle für die Dekodierung des Customer Information Field, das in der AustraliaPost-Symbologie verwendet wird. Die Implementierung sollte vom Benutzer bereitgestellt werden. |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost-Dekodierungsparameter. Enthält Parameter, die Einfluss auf die erkannten Daten der AustraliaPost-Symbologie haben. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Speichert spezielle Daten des erkannten Aztec-Barcode |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Speichert erweiterte Parameter des erkannten Barcodes |
| [BarCodeReader](./barcodereader/) | [BarCodeReader](./barcodereader/) kapselt ein Bild, das einen oder mehrere Barcodes enthalten kann, und kann anschließend die Operation ReadBarCodes ausführen, um Barcodes zu erkennen. |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Stellt die Region des erkannten Barcodes und den Barcode-Winkel dar |
| [BarCodeResult](./barcoderesult/) | Speichert erkannte Barcode-Daten wie den Typ [SingleDecodeType](./singledecodetype/), **System::String** Codetext, die Region [BarCodeRegionParameters](./barcoderegionparameters/) und weitere Parameter |
| [BarcodeSettings](./barcodesettings/) | Die Hauptdekodierungsparameter für [BarCode](../aspose.barcode/). Enthält Parameter, die Einfluss auf die erkannten Daten haben. |
| [BaseDecodeType](./basedecodetype/) | Basisklasse für [MultiDecodeType](./multidecodetype/) und [SingleDecodeType](./singledecodetype/). |
| [BaseExtendedParameters](./baseextendedparameters/) | Grundklasse für erweiterte Parameter zur Speicherung erkannter Barcodes |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Speichert zusätzliche Informationen eines Codabar des erkannten Barcodes |
| [Code128DataPortion](./code128dataportion/) | Enthält die Daten des Subtyps für den Code128-Barcode |
| [Code128ExtendedParameters](./code128extendedparameters/) | Speichert spezielle Daten des erkannten Code128-Barcodes |
| [DataBarExtendedParameters](./databarextendedparameters/) | Speichert zusätzliche Informationen eines DataBar des erkannten Barcodes |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Speichert spezielle Daten des erkannten [DataMatrix](../aspose.barcode.barcoderecognition.datamatrix/)-Barcodes |
| [DecodeType](./decodetype/) | Geben Sie den zu lesenden Barcode-Typ an. |
| [Details_BarCodeRecognitionException](./details_barcoderecognitionexception/) | Allgemeine Ausnahme, die von [BarCodeReader](./barcodereader/) ausgelöst wird und von BarCodeException erbt |
| [Details_RecognitionAbortedException](./details_recognitionabortedexception/) | Stellt die Erkennungsabbruch-Ausnahme dar, die bei Überschreitung des Zeitlimits während der Erkennung mit [BarCodeReader](./barcodereader/) ausgelöst wird. |
| [Details_RecognitionEngineException](./details_recognitionengineexception/) |  |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Speichert spezielle Daten des erkannten DotCode-Barcodes |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Speichert spezielle Daten des erkannten **GS1 Composite Bar**-Barcodes |
| [Iso15416Quality](./iso15416quality/) | Speichert Barcode-Qualitätsstufen, die gemäß dem ISO/IEC‑15416‑Standard für 1D‑Barcodes berechnet wurden. |
| [IsoSymbolQuality](./isosymbolquality/) | Speichert die Ergebnisse der Qualitätsbewertung von Barcode‑Symbolen gemäß ISO/IEC‑Standards. |
| [LuminanceFrame](./luminanceframe/) | Stellt einen 8‑Bit‑Graustufen‑Bildrahmen dar. Jeder Pixel wird durch ein Byte repräsentiert, das seinen Luminanzwert enthält. |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Speichert zusätzliche MaxiCode‑Informationen des erkannten Barcodes. |
| [MultiDecodeType](./multidecodetype/) | Zusammengesetzter Decodetyp. |
| [OneDExtendedParameters](./onedextendedparameters/) | Speichert spezielle Daten des erkannten 1D‑Barcodes, wie separaten Codetext und Prüfsumme. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Speichert Metadateninformationen von MacroPdf417 des erkannten Barcodes. |
| [QRExtendedParameters](./qrextendedparameters/) | Speichert eine [QR](../aspose.barcode.barcoderecognition.qr/) Structured‑Append‑Information des erkannten Barcodes. |
| [Quadrangle](./quadrangle/) | Speichert ein Set von vier [Point](../)s, die eine [Quadrangle](./quadrangle/)‑Region darstellen. |
| [QualitySettings](./qualitysettings/) | [QualitySettings](./qualitysettings/) ermöglicht es, die Erkennungsqualität und -geschwindigkeit manuell zu konfigurieren. Sie können [QualitySettings](./qualitysettings/) schnell mit eingebetteten Voreinstellungen einrichten: HighPerformance, NormalQuality, HighQuality, MaxQuality, oder Sie können die einzelnen Optionen manuell konfigurieren. Der Standardwert von [QualitySettings](./qualitysettings/) ist NormalQuality. |
| [SingleDecodeType](./singledecodetype/) | Einzelner Decodetyp. Siehe Decodetyp, um eine Instanz zu erhalten. |
## Enums

| Aufzählung | Beschreibung |
| --- | --- |
| [ChecksumValidation](./checksumvalidation/) |  |
| [Code128SubType](./code128subtype/) | Enthält Typen des Code128‑Subset. |
| [BarCodeConfidence](./barcodeconfidence/) | Enthält das Erkennungs‑Vertrauensniveau. |
| [BarcodeQualityMode](./barcodequalitymode/) |  |
| [ComplexBackgroundMode](./complexbackgroundmode/) |  |
| [DeconvolutionMode](./deconvolutionmode/) |  |
| [InverseImageMode](./inverseimagemode/) |  |
| [XDimensionMode](./xdimensionmode/) |  |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [BarCodeRecognitionException](./barcoderecognitionexception/) |  |
| [RecognitionEngineException](./recognitionengineexception/) |  |
| [RecognitionAbortedException](./recognitionabortedexception/) |  |
