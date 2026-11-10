---
title: "Klasse BarcodeParameters"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.BarcodeParameters Klasse. Parameter zur Barcode-Generierung"
type: docs
weight: 1010
url: /de/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

Barcode‑Generierungsparameter.

```csharp
public class BarcodeParameters
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost/) { get; } | AustralianPost‑Barcode‑Parameter. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec/) { get; } | Aztec‑Parameter. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor/) { get; set; } | Farbe der Balken. Standardwert: Color.Black. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight/) { get; set; } | Höhe der Balken von 1D-Barcodes im [`Unit`](../unit/) Wert. Ignoriert, wenn die [`AutoSizeMode`](../basegenerationparameters/autosizemode/) Eigenschaft auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist. |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction/) { get; set; } | Liest oder setzt den Reduktionswert der Balken, der zum Ausgleich der Tintenverbreitung beim Drucken verwendet wird. Standardwert: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow/) { get; set; } | Checksumme immer im menschenlesbaren Text für Code128- und GS1Code128-Barcodes anzeigen. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar/) { get; } | Codabar‑Parameter. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock/) { get; } | Codablock‑Parameter. |
| [Code128](../../aspose.barcode.generation/barcodeparameters/code128/) { get; } | Code128‑Parameter. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k/) { get; } | Code16K‑Parameter. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters/) { get; } | Codetext‑Parameter. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon/) { get; } | Coupon‑Parameter. Verwendet für UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar/) { get; } | Databar‑Parameter. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix/) { get; } | DataMatrix-Parameter. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode/) { get; } | DotCode-Parameter. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die Balken gefüllt sind. Nur für 1D-Barcodes. Standardwert: true. |
| [GS1](../../aspose.barcode.generation/barcodeparameters/gs1/) { get; } | GS1-Parameter. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar/) { get; set; } | GS1 Composite Bar-Parameter. |
| [HanXin](../../aspose.barcode.generation/barcodeparameters/hanxin/) { get; } | HanXin-Parameter. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled/) { get; set; } | Prüfsumme während der Erzeugung von 1D-Barcodes aktivieren. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf/) { get; } | ITF-Parameter. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode/) { get; } | MaxiCode-Parameter. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding/) { get; } | Barcode-Abstände. Standardwert: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode/) { get; } | PatchCode-Parameter. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417/) { get; } | PDF417-Parameter. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal/) { get; } | Postale Parameter. Verwendet für Postnet, Planet. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr/) { get; } | QR-, MicroQR- und RectMicroQR-Parameter. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement/) { get; } | Supplement-Parameter. Verwendet für Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect/) { get; set; } | Nur für 1D-Barcodes. Wenn der Codetext inkorrekt ist und der Wert auf true gesetzt wird, wird eine Ausnahme ausgelöst. Andernfalls wird der Codetext korrigiert, um der Spezifikation des Barcodes zu entsprechen. Eine Ausnahme wird immer ausgelöst für: Databar-Symbologie, wenn der Codetext inkorrekt ist. Eine Ausnahme wird niemals ausgelöst für: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128-Symbologie, wenn der Codetext inkorrekt ist. |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio/) { get; set; } | Verhältnis von breiten zu schmalen Balken. Standardwert: 3, das heißt, breite Balken sind dreimal so breit wie schmale Balken. Verwendet für ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension/) { get; set; } | x-dimension ist die kleinste Breite der Einheit von Barcode‑Balken oder -Lücken. Eine Erhöhung dieses Werts vergrößert die gesamte Barcode‑Bildbreite. Ignoriert, wenn die [`AutoSizeMode`](../basegenerationparameters/autosizemode/)‑Eigenschaft auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist. |

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


