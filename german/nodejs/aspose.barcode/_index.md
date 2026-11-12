---
title: "aspose.barcode"
linktitle: "aspose.barcode"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Der aspose.barcode‑Namespace bietet Klassen und Aufzählungen zum Erstellen, Anpassen und Dekodieren einer breiten Palette von Barcode‑Typen in Node.js über Java."
type: docs
weight: 10
url: /de/nodejs/aspose.barcode/
---
Verwenden Sie diese Typen, um Einstellungen für die Barcode‑Erstellung zu konfigurieren, wie Adressformatierung, regionale Vorgaben und erweiterte Parameter für Aztec und andere Symbologien. Der Namespace enthält Hilfsfunktionen zum Erstellen erweiterter Code‑Texte und zum Umgang mit speziellen Poststandards.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Address](./address/) | Adresse des Gläubigers oder Schuldners. Sie können entweder Straße, Hausnummer, Postleitzahl und Ort (typ strukturierte Adresse) festlegen o |
| [AlternativeScheme](./alternativescheme/) | Anweisungen zum alternativen Zahlungsschema |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost‑Dekodierungsparameter. Enthält Parameter, die Einfluss auf die erkannten Daten der AustraliaPost‑Symbologie haben |
| [AustralianPostParameters](./australianpostparameters/) | AustralianPost‑Barcode‑Parameter. |
| [AztecExtCodetextBuilder](./aztecextcodetextbuilder/) | Erweiterter Codetext‑Generator für Aztec‑Barcodes für den ExtendedCodetext‑Modus von AztecEncodeMode. Verwenden Sie die Eigenschaft TwoDDisplayText. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Speichert spezielle Daten des erkannten Aztec‑Barcodes. Dieses Beispiel zeigt, wie man rohe Aztec‑Werte erhält, let generator = new Barcod |
| [AztecParameters](./aztecparameters/) | Aztec‑Parameter. |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Speichert erweiterte Parameter des erkannten Barcodes |
| [BarCodeReader](./barcodereader/) | BarCodeReader kapselt ein Bild, das einen oder mehrere Barcodes enthalten kann, und kann anschließend ReadBarCodes‑Operationen ausführen |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Stellt die Region und den Winkel des erkannten Barcodes dar |
| [BarCodeResult](./barcoderesult/) | Speichert erkannte Barcode‑Daten wie den Typ SingleDecodeType, `string` Codetext, BarCodeRegionParameters‑Region und andere p |
| [BarcodeException](./barcodeexception/) |  |
| [BarcodeGenerator](./barcodegenerator/) | BarcodeGenerator zur Erzeugung von Barcode‑Bildern im Backend. Unterstützte Symbologien: 1D: Codabar, Code11, Code128, Code39Stand |
| [BarcodeParameters](./barcodeparameters/) | Barcode-Generierungsparameter. |
| [BarcodeSettings](./barcodesettings/) | Die Haupt-Barcode-Dekodierungsparameter. Enthält Parameter, die Einfluss auf erkannte Daten haben. |
| [BaseGenerationParameters](./basegenerationparameters/) | Parameter zur Barcode-Bilderzeugung. |
| [BorderParameters](./borderparameters/) | Parameter für den Barcode-Bildrand |
| [CMYKColor](./cmykcolor/) | Klasse für CMYK-Farbe. Eine Null-Instanz bedeutet, dass CMYK nicht verwendet wird und die Standard-RGB-Farbe verwendet wird. |
| [CaptionParameters](./captionparameters/) | Beschriftungsparameter. |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Speichert zusätzliche Informationen des erkannten Codabar-Barcodes. |
| [CodabarParameters](./codabarparameters/) | Codabar-Parameter. |
| [CodablockParameters](./codablockparameters/) | Codablock-Parameter. |
| [Code128DataPortion](./code128dataportion/) | Enthält die Daten des Subtyps für den Code128-Barcode. |
| [Code128ExtendedParameters](./code128extendedparameters/) | Speichert spezielle Daten des erkannten Code128-Barcodes. Stellt die Region des erkannten Barcodes und den Barcode-Winkel dar. |
| [Code128Parameters](./code128parameters/) | Code128-Parameter. |
| [Code16KParameters](./code16kparameters/) | Code16K-Parameter. |
| [CodetextParameters](./codetextparameters/) | Codetext-Parameter. |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | ComplexBarcodeGenerator zur Erzeugung von Backend-Komplexbarcode (z. B. SwissQR)-Bildern. |
| [ComplexCodetextReader](./complexcodetextreader/) | ComplexCodetextReader dekodiert Codetext in den angegebenen komplexen Barcode-Typ. |
| [CouponParameters](./couponparameters/) | Coupon-Parameter. Verwendet für UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarExtendedParameters](./databarextendedparameters/) | Speichert zusätzliche Informationen des erkannten DataBar-Barcodes. |
| [DataBarParameters](./databarparameters/) | Databar-Parameter. |
| [DataElement](./dataelement/) | Stellt ein jurisdictionsspezifisches Datenfeld dar, das in Dokumenten verwendet wird, zum Beispiel ElementID = "ZVA" mit Wert = "01". |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/) | Erweiterter Codetext-Generator für 2D DataMatrix-Barcodes für den ExtendedCodetext-Modus von DataMatrixEncodeMode //Extended code |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Speichert spezielle Daten des erkannten DataMatrix-Barcodes. Dieses Beispiel zeigt, wie man rohe DataMatrix-Werte erhält, let generator = |
| [DataMatrixParameters](./datamatrixparameters/) | DataMatrix-Parameter. |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | Erweiterter Codetext-Generator für 2D DotCode-Barcodes für den ExtendedCodetext-Modus von DotCodeEncodeMode |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Speichert spezielle Daten des erkannten DotCode-Barcodes. Dieses Beispiel zeigt, wie man rohe DotCode-Werte erhält |
| [DotCodeParameters](./dotcodeparameters/) | DotCode-Parameter. |
| [ExtCodetextBuilder](./extcodetextbuilder/) | Hilfsklasse für die automatische Codetext-Generierung des Extended Codetext Mode |
| [FontUnit](./fontunit/) | Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stil‑Attribute, wobei die Größe in der Unit‑value‑Eigenschaft angegeben ist. |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Speichert spezielle Daten des erkannten Strichcodes `GS1 Composite Bar ` |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | GS1 Composite Bar-Parameter. |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | Klasse zum Kodieren und Dekodieren des in den HIBC LIC‑Code eingebetteten Textes, der primäre und sekundäre Daten speichert. Dieses Beispiel |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | Basisklasse zum Kodieren und Dekodieren des in den HIBC LIC‑Code eingebetteten Textes. Dieses Beispiel zeigt, wie rohe HIBC LI dekodiert werden. |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | Klasse zum Kodieren und Dekodieren des in den HIBC LIC‑Code eingebetteten Textes, der primäre Daten speichert. Dieses Beispiel zeigt, wie |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | Klasse zum Kodieren und Dekodieren des in den HIBC LIC‑Code eingebetteten Textes, der sekundäre Daten speichert. |
| [HIBCPASCodetext](./hibcpascodetext/) | Klasse zum Kodieren und Dekodieren des in den HIBC PAS‑Code eingebetteten Textes. |
| [HIBCPASRecord](./hibcpasrecord/) | Klasse zum Speichern des HIBC PAS‑Datensatzes. |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/) | Erweiterter Codetext‑Generator für Han‑Xin‑Code für den erweiterten Modus von HanXinEncodeMode //Extended codetext mode //create cod |
| [HanXinParameters](./hanxinparameters/) | Han‑Xin-Parameter. |
| [HslaColor](./hslacolor/) | Klasse zur Darstellung von HSLA‑Farbe (Hue, Saturation, Lightness, Alpha) |
| [IComplexCodetext](./icomplexcodetext/) | Schnittstelle für komplexen Codetext, verwendet mit ComplexBarcodeGenerator. |
| [ITFParameters](./itfparameters/) | ITF-Parameter. |
| [ImageParameters](./imageparameters/) | Bild‑Parameter. |
| [License](./license/) | Stellt Methoden zur Lizenzierung der Komponente bereit. |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | Klasse zum Kodieren und Dekodieren des in den Royal Mail 2D Mailmark‑Code eingebetteten Textes. |
| [MailmarkCodetext](./mailmarkcodetext/) | Klasse zum Kodieren und Dekodieren des in den 4‑State‑Royal‑Mailmark‑Code eingebetteten Textes. |
| [MandatoryFields](./mandatoryfields/) | Obligatorische Elemente (Felder) der Karte |
| [MaxiCodeCodetext](./maxicodecodetext/) | Basisklasse zum Kodieren und Dekodieren des in den MaxiCode‑Code eingebetteten Textes. Dieses Beispiel zeigt, wie rohe MaxiCod dekodiert werden |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | Klasse zum Kodieren und Dekodieren des in den MaxiCode‑Code eingebetteten Textes für Modus 2. |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | Klasse zum Kodieren und Dekodieren des in den MaxiCode‑Code eingebetteten Textes für Modus 3. Dieses Beispiel zeigt, wie kodiert und |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | Erweiterter Codetext‑Generator für MaxiCode‑Barcodes für den ExtendedCodetext‑Modus von MaxiCodeEncodeMode Use TwoDDisplayText pr |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Speichert zusätzliche Informationen zu einem erkannten MaxiCode-Barcode |
| [MaxiCodeParameters](./maxicodeparameters/) | MaxiCode-Parameter. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | Klasse zum Kodieren und Dekodieren von MaxiCode-Codetext für die Modi 4, 5 und 6. |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | Klasse zum Kodieren und Dekodieren von MaxiCode-Codetext für die Modi 4, 5 und 6. |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | Klasse zum Kodieren und Dekodieren der Standard‑Zweitnachricht für MaxiCode‑Barcodes. |
| [MaxiCodeStandartSecondMessage](./maxicodestandartsecondmessage/) | Klasse zum Kodieren und Dekodieren der Standard‑Zweitnachricht für MaxiCode‑Barcodes. |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | Basisklasse zum Kodieren und Dekodieren des im MaxiCode-Code eingebetteten Textes für die Modi 2 und 3. |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | Klasse zum Kodieren und Dekodieren strukturierter Zweitnachrichten für MaxiCode‑Barcodes. |
| [OneDExtendedParameters](./onedextendedparameters/) | Speichert spezielle Daten eines erkannten 1D‑Barcodes, wie separaten Codetext und Prüfsumme. |
| [OptionalFields](./optionalfields/) | Optionale Elemente (Felder) der Karte. |
| [Padding](./padding/) | Padding-Parameter. |
| [PatchCodeParameters](./patchcodeparameters/) | PatchCode-Parameter. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Speichert Metadateninformationen von MacroPdf417 für einen erkannten Barcode. |
| [Pdf417Parameters](./pdf417parameters/) | PDF417-Parameter. Enthält Parameter für PDF417, MacroPDF417, MicroPDF417 und GS1MicroPdf417. MacroPDF417 erfordert zwei Felder. |
| [PdfParameters](./pdfparameters/) | PDF-Parameter-Wrapper. Erwartet eine zugrunde liegende `mwObject`-Instanz, die die entsprechenden Getter/Setter-Methoden bereitstellt. |
| [PostalParameters](./postalparameters/) | Postale Parameter. Verwendet für Postnet, Planet. |
| [PrimaryData](./primarydata/) | Klasse zum Speichern primärer HIBC‑LIC-Daten. |
| [QRExtendedParameters](./qrextendedparameters/) | Speichert Structured‑Append-Informationen eines erkannten QR‑Barcodes. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/) | Erweiterter Codetext-Generator für 2D‑QR‑Barcodes im ExtendedCodetext‑Modus von QREncodeMode. Verwenden Sie die Display2DText‑Eigenschaft von B. |
| [QrParameters](./qrparameters/) | QR-Parameter. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters/) | QR Structured‑Append-Parameter. |
| [Quadrangle](./quadrangle/) | Speichert ein Set von vier Punkten, das ein Quadrangle‑Gebiet darstellt. |
| [QualitySettings](./qualitysettings/) | QualitySettings ermöglicht die manuelle Konfiguration von Erkennungsqualität und -geschwindigkeit. Sie können QualitySettings schnell einrichten, indem Sie ... |
| [RecognitionAbortedException](./recognitionabortedexception/) | Stellt die Erkennungsabbruch‑Exception dar, die bei Überschreitung des Zeitlimits während der Erkennung mit BarCodeReader ausgelöst wird. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | Klasse zum Speichern sekundärer und zusätzlicher HIBC‑LIC-Daten. |
| [SubfileProperties](./subfileproperties/) | USA‑DL-Unterdateieigenschaften, Offset und Länge werden automatisch gesetzt. |
| [SupplementParameters](./supplementparameters/) | Ergänzende Parameter. Verwendet für Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SvgParameters](./svgparameters/) | SVG-Parameter. |
| [SwissQRBill](./swissqrbill/) | SwissQR-Rechnungsdaten |
| [SwissQRCodetext](./swissqrcodetext/) | Klasse zum Kodieren und Dekodieren des im SwissQR-Code eingebetteten Textes. |
| [USADriveIdCodetext](./usadriveidcodetext/) | Klasse zum Kodieren und Dekodieren des im USA Driving License PDF417-Code eingebetteten Textes. |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | Klasse für jurisdictionsspezifische Felder für USA DL |
| [Unit](./unit/) | Gibt den Größenwert in verschiedenen Einheiten an (Pixel, Zoll usw.). |
