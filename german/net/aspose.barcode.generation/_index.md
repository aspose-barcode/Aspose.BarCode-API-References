---
title: Aspose.BarCode.Generation
second_title: Aspose.BarCode für .NET-API-Referenz
description: Die Aspose.BarCode.Generation enthält allgemeine Klassen zur Implementierung von Barcode-Erzeugungsfunktionen.
type: docs
weight: 50
url: /de/net/aspose.barcode.generation/
---
Die **Aspose.BarCode.Generation** enthält allgemeine Klassen zur Implementierung von Barcode-Erzeugungsfunktionen.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AustralianPostParameters](./australianpostparameters) | Barcode-Parameter der australischen Post. |
| [AztecParameters](./aztecparameters) | Aztekische Parameter. |
| [BarcodeGenerator](./barcodegenerator) | BarcodeGenerator für die Erstellung von Backend-Barcodebildern. |
| [BarcodeParameters](./barcodeparameters) | Barcode-Generierungsparameter. |
| [BaseEncodeType](./baseencodetype) | Basisklasse für SymbologyEncodeType. |
| [BaseGenerationParameters](./basegenerationparameters) | Barcode-Bilderzeugungsparameter. |
| [BorderParameters](./borderparameters) | Rahmenparameter für Barcode-Bild |
| [CaptionParameters](./captionparameters) | Untertitelparameter. |
| [CodabarParameters](./codabarparameters) | Codabar-Parameter. |
| [CodablockParameters](./codablockparameters) | Codablock-Parameter. |
| [Code16KParameters](./code16kparameters) | Code16K-Parameter. |
| [CodetextParameters](./codetextparameters) | Codetext-Parameter. |
| [CouponParameters](./couponparameters) | Gutscheinparameter. Verwendet für UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarParameters](./databarparameters) | Databar-Parameter. |
| [DataMatrixParameters](./datamatrixparameters) | DataMatrix-Parameter. |
| [DotCodeParameters](./dotcodeparameters) | DotCode-Parameter. |
| [EncodeTypes](./encodetypes) | Gibt den Typ des zu codierenden Barcodes an. |
| [ExtCodetextBuilder](./extcodetextbuilder) | Hilfsklasse zur automatischen Codetextgenerierung des Extended Codetext Mode |
| [FontUnit](./fontunit) | Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stilattribute , wobei Größe in der Einheitswert-Eigenschaft steht. |
| [GS1CompositeBarParameters](./gs1compositebarparameters) | GS1 Composite Bar Parameter. |
| [ITFParameters](./itfparameters) | ITF-Parameter. |
| [MaxiCodeParameters](./maxicodeparameters) | MaxiCode-Parameter. |
| [Padding](./padding) | Füllparameter. |
| [PatchCodeParameters](./patchcodeparameters) | PatchCode-Parameter. |
| [Pdf417Parameters](./pdf417parameters) | PDF417-Parameter. Enthält PDF417-, MacroPDF417- und MicroPDF417-Parameter. MacroPDF417 erfordert zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional. MicroPDF417 im strukturierten Anhängemodus (wie im MacroPDF417-Modus) erfordert zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional. |
| [PostalParameters](./postalparameters) | Postalische Parameter. Verwendet für Postnet, Planet. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder) | Erweiterter Codetext-Generator für 2D-QR-Barcodes für den ExtendedCodetext-Modus des QrEncodeMode |
| [QrParameters](./qrparameters) | QR-Parameter. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters) | Parameter für strukturierte QR-Anhänge. |
| [SupplementParameters](./supplementparameters) | Ergänzungsparameter. Verwendet für Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SymbologyEncodeType](./symbologyencodetype) | Symbologie-Codierungstyp. Siehe EncodeTypes zum Abrufen von instance. |
| [Unit](./unit) | Gibt den Größenwert in verschiedenen Einheiten (Pixel, Zoll usw.) an. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [AutoSizeMode](./autosizemode) | Gibt die verschiedenen Arten von automatischen Größenanpassungsmodi an. |
| [AztecSymbolMode](./aztecsymbolmode) | Gibt den aztekischen Symbolmodus an. |
| [BarcodeClassifications](./barcodeclassifications) | Symbologieklassifizierung |
| [BarCodeImageFormat](./barcodeimageformat) | Gibt das Dateiformat des Bildes an. |
| [BorderDashStyle](./borderdashstyle) | Gibt den Stil der gestrichelten Rahmenlinien an. |
| [CodabarChecksumMode](./codabarchecksummode) | Gibt den Prüfsummenalgorithmus für Codabar an |
| [CodabarSymbol](./codabarsymbol) | Gibt das Start- oder Stoppsymbol der Codabar-Barcodespezifikation an. |
| [Code128Emulation](./code128emulation) | Funktionscodewörter für Code 128-Emulation. Gilt nur für MicroPDF417. Für PDF417- und MacroPDF417-Barcodes ignoriert. |
| [CodeLocation](./codelocation) | Codetext-Position |
| [DataMatrixEccType](./datamatrixecctype) | Geben Sie den Typ des zu codierenden ECC an. |
| [DataMatrixEncodeMode](./datamatrixencodemode) | Kodierungsmodus des DataMatrix-Encoders, standardmäßig Auto |
| [ECIEncodings](./eciencodings) | Erweiterte Kanalinterpretationskennungen. Es wird verwendet, um dem Barcode-Lesegerät Details über die verwendeten Referenzen für die Codierung der Daten im Symbol mitzuteilen. Die aktuelle Implementierung besteht aus allen bekannten Zeichensatzcodierungen. Derzeit wird es nur für QR-2D-Barcodes verwendet. |
| [EnableChecksum](./enablechecksum) | Aktivieren Sie die Prüfsumme während der Generierung für 1D-Barcodes. |
| [FontMode](./fontmode) | Schriftgrößenmodus. |
| [ITF14BorderType](./itf14bordertype) | ITF14-Randtyp des Barcodes |
| [MacroCharacter](./macrocharacter) | Die Werte der Makrozeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Codierung zu erhalten. 05-Makrozeichen werden in „[)&gt;\u001E05\u001D“ als decodierter Datenheader und „\u001E\u0004“ als decodierter Datennachspann übersetzt. 06 Makro Craracter wird in "[)&gt;\u001E06\u001D" als decodierter Datenheader und "\u001E\u0004" als decodierter Datentrailer übersetzt. |
| [PatchFormat](./patchformat) | PatchCode-Format. Wählen Sie PatchOnly, um einen einzelnen PatchCode zu generieren. Seitenformat verwenden, um Patch-Seite mit PatchCodes als border zu generieren |
| [Pdf417CompactionMode](./pdf417compactionmode) | Pdf417-Barcode-Komprimierungsmodus |
| [Pdf417ErrorLevel](./pdf417errorlevel) | Fehlerkorrekturstufe des pdf417-Barcodes, von Stufe 0 bis Stufe 9, Stufe 0 bedeutet keine Fehlerkorrektur, Stufe 9 bedeutet beste Fehlerkorrektur |
| [QREncodeMode](./qrencodemode) | Kodierungsmodus für QR-Barcodes. Es wird empfohlen, Auto mit CodeTextEncoding = Encoding.UTF8 für lateinische Symbole oder Ziffern und Utf8BOM für Unicode-Symbole zu verwenden. |
| [QREncodeType](./qrencodetype) | QR / MicroQR-Wahlmodus. Wählen Sie ForceQR für Standard-QR-Symbole, Auto für MicroQR. ForceMicroQR wird für die strenge Generierung von MicroQR-Symbolen verwendet, wenn dies möglich ist. |
| [QRErrorLevel](./qrerrorlevel) | Level der Reed-Solomon-Fehlerkorrektur. Von niedrig nach hoch: LevelL, LevelM, LevelQ, LevelH. |
| [QRVersion](./qrversion) | Version des QR-Codes. Von Version1 bis Version40 für QR-Code und von M1 bis M4 für MicroQr. |
| [TextAlignment](./textalignment) | Textausrichtung. |
| [TwoDComponentType](./twodcomponenttype) | Art der 2D-Komponente |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
