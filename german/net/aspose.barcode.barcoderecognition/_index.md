---
title: "Aspose.BarCode.BarCodeRecognition"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Die Aspose.BarCode.BarCodeRecognition enthält Werkzeuge zur Erkennung von 1D/2D‑Barcodes."
type: docs
weight: 20
url: /de/net/aspose.barcode.barcoderecognition/
---
Das **Aspose.BarCode.BarCodeRecognition** enthält Werkzeuge zur Erkennung von 1D/2D-Barcodes.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost‑Dekodierungsparameter. Enthält Parameter, die Einfluss auf die erkannten Daten der AustraliaPost‑Symbolik haben. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Speichert spezielle Daten des erkannten Aztec‑Barcodes. |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Speichert erweiterte Parameter des erkannten Barcodes. |
| [BarCodeReader](./barcodereader/) | BarCodeReader kapselt ein Bild, das einen oder mehrere Barcodes enthalten kann, und kann anschließend die ReadBarCodes‑Operation ausführen, um Barcodes zu erkennen. |
| [BarCodeRecognitionException](./barcoderecognitionexception/) | Allgemeine Ausnahme, die von BarCodeReader ausgelöst wird und von BarCodeException erbt. |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Stellt die Region des erkannten Barcodes und den Barcode‑Winkel dar. |
| [BarCodeResult](./barcoderesult/) | Speichert erkannte Barcode‑Daten wie den Typ [`SingleDecodeType`](../aspose.barcode.barcoderecognition/singledecodetype/), den String‑Codetext, die Region [`BarCodeRegionParameters`](../aspose.barcode.barcoderecognition/barcoderegionparameters/) und weitere Parameter. |
| [BarcodeSettings](./barcodesettings/) | Die Haupt‑BarCode‑Dekodierungsparameter. Enthält Parameter, die Einfluss auf die erkannten Daten haben. |
| [BaseDecodeType](./basedecodetype/) | Basisklasse für MultiDecodeType und SingleDecodeType. |
| [BaseExtendedParameters](./baseextendedparameters/) | Grundklasse für das Speichern erweiterter Parameter des erkannten Barcodes. |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Speichert zusätzliche Informationen des erkannten Codabar‑Barcodes. |
| [Code128DataPortion](./code128dataportion/) | Enthält die Daten des Subtyps für den Code128‑Barcode. |
| [Code128ExtendedParameters](./code128extendedparameters/) | Speichert spezielle Daten des erkannten Code128‑Barcodes. |
| [DataBarExtendedParameters](./databarextendedparameters/) | Speichert zusätzliche Informationen des erkannten DataBar‑Barcodes. |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Speichert spezielle Daten des erkannten DataMatrix‑Barcodes. |
| [DecodeType](./decodetype/) | Geben Sie den zu lesenden Barcode‑Typ an. |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Speichert spezielle Daten des erkannten DotCode‑Barcodes. |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Speichert spezielle Daten des erkannten Strichcodes **GS1 Composite Bar** |
| [Iso15416Quality](./iso15416quality/) | Speichert Barcode-Qualitätsstufen, die gemäß dem ISO/IEC‑15416‑Standard für 1D‑Barcodes berechnet wurden. |
| [IsoSymbolQuality](./isosymbolquality/) | Speichert die Ergebnisse der Qualitätsbewertung von Barcode‑Symbolen gemäß ISO/IEC‑Standards. |
| [LuminanceFrame](./luminanceframe/) | Stellt einen 8‑Bit‑Graustufen‑Bildrahmen dar. Jeder Pixel wird durch ein Byte repräsentiert, das seinen Luminanzwert enthält. |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Speichert zusätzliche MaxiCode‑Informationen des erkannten Barcodes. |
| [MultiDecodeType](./multidecodetype/) | Composite‑Dekodierungstyp. |
| [OneDExtendedParameters](./onedextendedparameters/) | Speichert spezielle Daten des erkannten 1D‑Barcodes, wie separaten Codetext und Prüfsumme. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Speichert Metadateninformationen des erkannten MacroPdf417‑Barcodes. |
| [QRExtendedParameters](./qrextendedparameters/) | Speichert QR‑Structured‑Append‑Informationen des erkannten Barcodes. |
| [Quadrangle](./quadrangle/) | Speichert ein Set von vier Punkten, die eine [`Quadrangle`](../aspose.barcode.barcoderecognition/quadrangle/)‑Region darstellen. |
| [QualitySettings](./qualitysettings/) | QualitySettings ermöglicht es, die Erkennungsqualität und -geschwindigkeit manuell zu konfigurieren. Sie können QualitySettings schnell mit eingebetteten Voreinstellungen einrichten: HighPerformance, NormalQuality, HighQuality, MaxQuality, oder Sie können die einzelnen Optionen manuell konfigurieren. Der Standardwert von QualitySettings ist NormalQuality. |
| [RecognitionAbortedException](./recognitionabortedexception/) | Stellt eine Erkennungsabbruch‑Ausnahme dar, die bei Überschreitung des Zeitlimits während der Erkennung mit BarCodeReader ausgelöst wird. |
| [SingleDecodeType](./singledecodetype/) | Einzelner Dekodierungstyp. Siehe Dekodierungstyp, um eine Instanz zu erhalten. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | Öffentliche Schnittstelle für die Dekodierung des Customer Information Field, die in der AustraliaPost‑Symbolik verwendet wird. Die Implementierung sollte vom Benutzer bereitgestellt werden. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [BarCodeConfidence](./barcodeconfidence/) | Enthält das Erkennungs‑Vertrauensniveau. |
| [BarcodeQualityMode](./barcodequalitymode/) | Modus, der Methoden aktiviert, um Barcode‑Elemente mit der ausgewählten Qualität zu erkennen. Ein Barcode‑Element mit niedrigerer Qualität erfordert aufwändigere Methoden, was die Erkennung verlangsamt. |
| [ChecksumValidation](./checksumvalidation/) | Aktiviert die Prüfsummenvalidierung während der Erkennung für 1D‑ und Post‑Barcodes. |
| [Code128SubType](./code128subtype/) | Enthält Typen des Code128‑Subset. |
| [ComplexBackgroundMode](./complexbackgroundmode/) | Modus, der die zusätzliche Erkennung von Farbbarcodes in Farbbildern ein- oder ausschaltet. |
| [DeconvolutionMode](./deconvolutionmode/) | Deconvolution‑Modus (Bildrestaurierung), der das Niveau der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion, die ein durch eine natürliche Funktion wie Unschärfe (Blur) degradierte (konvolutierte) Bild wiederherstellen kann, das bei der Aufnahme mit einer Kamera entsteht. Da wir die Bildfunktion, die das Bild beschädigt, nicht erkennen können, müssen wir die am besten bekannten Funktionen wie Schärfen oder mathematische Morphologie prüfen. |
| [InverseImageMode](./inverseimagemode/) | Modus, der die zusätzliche Erkennung von Barcodes in Bildern mit invertierten Farben (Luminanz) ein- oder ausschaltet. |
| [XDimensionMode](./xdimensionmode/) | Erkennungsmodus, der die Größe (von 1 bis unendlich) des minimalen Barcode‑Elements festlegt: Matrixzelle oder Strich. |


