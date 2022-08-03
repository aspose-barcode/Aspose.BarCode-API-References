---
title: BarcodeParameters
second_title: Aspose.BarCode für .NET-API-Referenz
description: Barcode-Generierungsparameter.
type: docs
weight: 500
url: /de/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

Barcode-Generierungsparameter.

```csharp
public class BarcodeParameters
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost) { get; } | Barcode-Parameter der australischen Post. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec) { get; } | Aztekische Parameter. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor) { get; set; } | Balkenfarbe. Standardwert: Farbe.Schwarz. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight) { get; set; } | Höhe der Balken von 1D-Barcodes in[`Unit`](../unit) Wert. Ignoriert, wennAutoSizeMode Eigenschaft auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation. gesetzt ist |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction) { get; set; } | Abrufen oder Festlegen des Balkenreduzierungswerts, der zum Kompensieren der Tintenverteilung während des Druckens verwendet wird. Standardwert: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow) { get; set; } | Prüfsummenziffer immer im menschenlesbaren Text für Code128- und GS1Code128-Barcodes anzeigen. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar) { get; } | Codabar-Parameter. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock) { get; } | Codablock-Parameter. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k) { get; } | Code16K-Parameter. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters) { get; } | Codetext-Parameter. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon) { get; } | Gutscheinparameter. Verwendet für UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar) { get; } | Databar-Parameter. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix) { get; } | DataMatrix-Parameter. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode) { get; } | DotCode-Parameter. |
| [EnableEscape](../../aspose.barcode.generation/barcodeparameters/enableescape) { get; set; } | Gibt an, ob das Zeichen „\“ als Escape-Zeichen in der CodeText-Eigenschaft erklärt wird. Wird nur für Pdf417, DataMatrix, Code128 verwendet Wenn EnableEscape wahr ist, wird "\" als spezielles Escape-Zeichen erklärt. Andernfalls fungiert "\" als normales Zeichen. Aspose.BarCode unterstützt die Eingabe von dezimalem ASCII-Code und Mnemonik für ASCII-Steuercodezeichen. Beispielsweise steht \013 und \\CR für CR. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars) { get; set; } | Liest oder setzt einen Wert, der angibt, ob Balken gefüllt sind. Nur für 1D-Barcodes. Standardwert: wahr. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar) { get; set; } | GS1 Composite Bar Parameter. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled) { get; set; } | Aktivieren Sie die Prüfsumme während der Generierung von 1D-Barcodes. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf) { get; } | ITF-Parameter. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode) { get; } | MaxiCode-Parameter. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding) { get; } | Barcode-Paddings. Standardwert: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode) { get; } | PatchCode-Parameter. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417) { get; } | PDF417-Parameter. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal) { get; } | Postalische Parameter. Verwendet für Postnet, Planet. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr) { get; } | QR-Parameter. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement) { get; } | Ergänzungsparameter. Verwendet für Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect) { get; set; } | Nur für 1D-Barcodes. Wenn der Codetext falsch ist und der Wert auf „true“ gesetzt ist, wird eine Ausnahme ausgelöst. Andernfalls wird der Codetext korrigiert, damit er der Spezifikation des Barcodes entspricht. Ausnahme wird immer ausgelöst für: Databar-Symbologie, wenn Codetext falsch ist. Ausnahme wird immer nicht ausgelöst für: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128 Symbologie, wenn Codetext falsch ist . |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio) { get; set; } | Verhältnis breite Balken zu schmalen Balken. Standardwert: 3, dh breite Balken sind dreimal so breit wie schmale Balken. Verwendet für ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension) { get; set; } | x-Dimension ist die kleinste Breite der Einheit von Strichcode-Balken oder Zwischenräumen. Vergrößern erhöht die Breite des gesamten Strichcode-Bildes. Ignoriert, wennAutoSizeMode Eigenschaft auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation. gesetzt ist |

### Siehe auch

* namensraum [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* Montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
