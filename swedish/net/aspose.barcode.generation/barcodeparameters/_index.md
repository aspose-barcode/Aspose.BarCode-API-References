---
title: BarcodeParameters
second_title: Aspose.BarCode för .NET API-referens
description: Parametrar för generering av streckkoder.
type: docs
weight: 500
url: /sv/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

Parametrar för generering av streckkoder.

```csharp
public class BarcodeParameters
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost) { get; } | AustralianPost streckkodsparametrar. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec) { get; } | Aztec parametrar. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor) { get; set; } | Staplar färg. Standardvärde: Color.Black. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight) { get; set; } | Höjden på 1D-streckkodernas streck in[`Unit`](../unit) värde. Ignoreras omAutoSizeMode egenskapen är inställd på AutoSizeMode.Nearest eller AutoSizeMode.Interpolation. |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction) { get; set; } | Hämta eller ställer in streckreduktionsvärde som används för att kompensera bläckspridning under utskrift. Standardvärde: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow) { get; set; } | Visa alltid kontrollsummans siffra i den mänskliga läsbara texten för Code128 och GS1Code128 streckkoder. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar) { get; } | Codabar-parametrar. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock) { get; } | Codablock parametrar. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k) { get; } | Code16K parametrar. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters) { get; } | Kodtextparametrar. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon) { get; } | Kupongparametrar. Används för UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar) { get; } | Datafältsparametrar. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix) { get; } | DataMatrix parametrar. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode) { get; } | DotCode parametrar. |
| [EnableEscape](../../aspose.barcode.generation/barcodeparameters/enableescape) { get; set; } | Anger om tecknet "\" förklaras som ett escape-tecken i CodeText-egenskapen. Används för Pdf417, DataMatrix, Code128 only Om EnableEscape är sant, kommer "\" att förklaras som ett speciellt escape-tecken. Annars fungerar "\" som vanliga tecken. Aspose.BarCode stöder inmatning av decimal ascii-kod och mnemonic för ASCII-kontrollkodstecken. Till exempel, \013 och \\CR står för CR. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars) { get; set; } | Hämtar eller ställer in ett värde som anger om staplarna är fyllda. Endast för 1D streckkoder. Standardvärde: true. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar) { get; set; } | GS1 Composite Bar parametrar. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled) { get; set; } | Aktivera kontrollsumma under generation 1D streckkoder. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf) { get; } | ITF-parametrar. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode) { get; } | MaxiCode parametrar. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding) { get; } | Streckkodsutfyllnad. Standardvärde: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode) { get; } | PatchCode parametrar. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417) { get; } | PDF417 parametrar. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal) { get; } | Postparametrar. Används för Postnet, Planet. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr) { get; } | QR-parametrar. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement) { get; } | Tilläggsparametrar. Används för Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect) { get; set; } | Endast för 1D streckkoder. Om kodtexten är felaktig och värdet satt till true - kommer undantag att kastas. Annars kommer kodtexten att korrigeras för att matcha streckkodens specifikation. Undantag kommer alltid att kastas för: Databar symbology om kodtexten är felaktig. Undantag kommer alltid inte att kastas för: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K symbology code12 . |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio) { get; set; } | Breda staplar till smala staplar ratio. Standardvärde: 3, det vill säga breda staplar är 3 gånger så breda som smala staplar. Används för ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, I Italian, DeutschePost25, VIN DeutschePost25, VIN DeutschePost , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension) { get; set; } | x-dimension är den minsta bredden på enheten för streckkodsstaplar eller mellanslag. Öka detta kommer att öka hela streckkodens bildbredd. Ignoreras omAutoSizeMode egenskapen är inställd på AutoSizeMode.Nearest eller AutoSizeMode.Interpolation. |

### Se även

* namnutrymme [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* hopsättning [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
