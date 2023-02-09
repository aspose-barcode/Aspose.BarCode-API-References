---
title: BarcodeParameters
second_title: Aspose.BarCode voor .NET API-referentie
description: Parameters voor het genereren van streepjescodes.
type: docs
weight: 710
url: /nl/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

Parameters voor het genereren van streepjescodes.

```csharp
public class BarcodeParameters
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost/) { get; } | AustralianPost-barcodeparameters. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec/) { get; } | Azteekse parameters. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor/) { get; set; } | Balken color. Standaardwaarde: Color.Black. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight/) { get; set; } | Hoogte van 1D streepjescodes' bars in[`Unit`](../unit/) waarde. Genegeerd alsAutoSizeMode eigenschap is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction/) { get; set; } | Verkrijg of stel de reductiewaarde in die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren. Standaardwaarde: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow/) { get; set; } | Geef altijd het checksum-cijfer weer in de voor mensen leesbare tekst voor Code128- en GS1Code128-streepjescodes. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar/) { get; } | Codabar-parameters. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock/) { get; } | Codablock-parameters. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k/) { get; } | Code16K-parameters. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters/) { get; } | Codetekstparameters. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon/) { get; } | Couponparameters. Gebruikt voor UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar/) { get; } | Gegevensbalkparameters. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix/) { get; } | DataMatrix-parameters. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode/) { get; } | DotCode-parameters. |
| [EnableEscape](../../aspose.barcode.generation/barcodeparameters/enableescape/) { get; set; } | Geeft aan of het teken "\" wordt uitgelegd als een escape-teken in de eigenschap CodeText. Alleen gebruikt voor Pdf417, DataMatrix, Code128 Als EnableEscape waar is, wordt "\" uitgelegd als een speciaal escape-teken. Anders fungeert "\" als normale tekens. Aspose.BarCode ondersteunt het invoeren van decimale ascii-code en geheugensteuntje voor ASCII-besturingscodetekens. \013 en \\CR staan bijvoorbeeld voor CR. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars/) { get; set; } | Haalt of stelt een waarde in die aangeeft of staven gevuld zijn. Alleen voor 1D-streepjescodes. Standaardwaarde: true. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar/) { get; set; } | GS1 Samengestelde staafparameters. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled/) { get; set; } | Controlesom inschakelen tijdens het genereren van 1D-streepjescodes. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf/) { get; } | ITF-parameters. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode/) { get; } | MaxiCode-parameters. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding/) { get; } | Streepjescodevullingen. Standaardwaarde: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode/) { get; } | PatchCode-parameters. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417/) { get; } | PDF417-parameters. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal/) { get; } | Postparameters. Gebruikt voor Postnet, Planet. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr/) { get; } | QR-parameters. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement/) { get; } | Aanvullende parameters. Gebruikt voor Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect/) { get; set; } | Alleen voor 1D-streepjescodes. Als codetekst onjuist is en de waarde is ingesteld op waar, wordt er een uitzondering gegenereerd. Anders wordt de codetekst gecorrigeerd zodat deze overeenkomt met de specificatie van de streepjescode. Uitzondering wordt altijd gegenereerd voor: Databalk-symboliek als codetekst onjuist is. Uitzondering wordt niet altijd gegenereerd voor: AustraliaPost, SingaporePost, Code39Extended, Code93Extended, Code16K, Code128-symboliek als codetekst onjuist is . |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio/) { get; set; } | Verhouding tussen brede balken en smalle balken. Standaardwaarde: 3, dat wil zeggen brede balken zijn 3 keer zo breed als smalle balken. Gebruikt voor ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension/) { get; set; } | x-dimensie is de kleinste breedte van de eenheid van streepjescodestrepen of spaties. Verhogen dit zal de gehele breedte van het streepjescodebeeld vergroten. Genegeerd alsAutoSizeMode eigenschap is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |

### Zie ook

* naamruimte [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
