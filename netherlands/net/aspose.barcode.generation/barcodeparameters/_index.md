---
title: "Klasse BarcodeParameters"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.BarcodeParameters klasse. Barcode-generatieparameters"
type: docs
weight: 1010
url: /nl/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

Barcode‑generatie‑parameters.

```csharp
public class BarcodeParameters
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost/) { get; } | AustralianPost barcode‑parameters. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec/) { get; } | Aztec‑parameters. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor/) { get; set; } | Kleur van de staven. Standaardwaarde: Color.Black. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight/) { get; set; } | Hoogte van de staven van 1D-barcode in [`Unit`](../unit/) waarde. Genegeerd als de eigenschap [`AutoSizeMode`](../basegenerationparameters/autosizemode/) is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction/) { get; set; } | Haalt of stelt de reductiewaarde van de staven in die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren. Standaardwaarde: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow/) { get; set; } | Toon altijd het controlecijfer in de menselijk leesbare tekst voor Code128- en GS1Code128-streepjescodes. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar/) { get; } | Codabar‑parameters. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock/) { get; } | Codablock‑parameters. |
| [Code128](../../aspose.barcode.generation/barcodeparameters/code128/) { get; } | Code128‑parameters. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k/) { get; } | Code16K‑parameters. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters/) { get; } | Codetekst‑parameters. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon/) { get; } | Coupon‑parameters. Gebruikt voor UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar/) { get; } | Databar‑parameters. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix/) { get; } | DataMatrix-parameters. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode/) { get; } | DotCode-parameters. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars/) { get; set; } | Haalt of stelt een waarde in die aangeeft of de staven gevuld zijn. Alleen voor 1D-barcode. Standaardwaarde: true. |
| [GS1](../../aspose.barcode.generation/barcodeparameters/gs1/) { get; } | GS1-parameters. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar/) { get; set; } | GS1 Composite Bar parameters. |
| [HanXin](../../aspose.barcode.generation/barcodeparameters/hanxin/) { get; } | HanXin parameters. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled/) { get; set; } | Checksum inschakelen tijdens het genereren van 1D-barcodes. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf/) { get; } | ITF-parameters. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode/) { get; } | MaxiCode-parameters. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding/) { get; } | Barcode opvullingen. Standaardwaarde: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode/) { get; } | PatchCode-parameters. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417/) { get; } | PDF417 parameters. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal/) { get; } | Postale parameters. Gebruikt voor Postnet, Planet. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr/) { get; } | QR, MicroQR en RectMicroQR parameters. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement/) { get; } | Supplement-parameters. Gebruikt voor Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect/) { get; set; } | Alleen voor 1D-barcode. Als de codetekst onjuist is en de waarde is ingesteld op true - wordt een uitzondering gegooid. Anders wordt de codetekst gecorrigeerd om te voldoen aan de specificatie van de barcode. Een uitzondering wordt altijd gegooid voor: Databar-symbool als de codetekst onjuist is. Een uitzondering wordt nooit gegooid voor: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128-symbool als de codetekst onjuist is. |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio/) { get; set; } | Verhouding brede strepen tot smalle strepen. Standaardwaarde: 3, dat wil zeggen, brede strepen zijn 3 keer zo breed als smalle strepen. Gebruikt voor ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension/) { get; set; } | x-dimension is de kleinste breedte van de eenheid van BarCode-staven of -spaties. Het verhogen hiervan zal de totale breedte van de barcode-afbeelding vergroten. Genegeerd als de eigenschap [`AutoSizeMode`](../basegenerationparameters/autosizemode/) is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


