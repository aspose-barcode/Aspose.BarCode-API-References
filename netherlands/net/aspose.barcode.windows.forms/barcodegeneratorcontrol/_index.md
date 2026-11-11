---
title: "Klasse BarCodeGeneratorControl"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Windows.Forms.BarCodeGeneratorControl klasse. BarCode Windows‑control ga naar je toolbox‑paneel en voeg Aspose.BarCode.dll toe en je zult zien dat BarCodeGeneratorControl verschijnt. Sleep het gewoon en zet het in je Windows‑formulier. zie  zie"
type: docs
weight: 1800
url: /nl/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows‑besturingselement, ga naar uw toolbox‑paneel en voeg Aspose.BarCode.dll toe, en u zult zien dat BarcodeGeneratorControl verschijnt. Sleep het gewoon naar uw Windows‑formulier en laat het vallen. zie  zie

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode/) { get; set; } | Haalt de modus op waarmee de barcode automatisch van grootte verandert of stelt deze in. Standaardwaarde is AutoSizeMode.None. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor/) { get; set; } | Achtergrondkleur van de barcode-afbeelding. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight/) { get; } | BarCode-beeldhoogte wanneer de eigenschap [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings/) { get; } | Haalt of stelt Barcode‑opvulparameters [`Padding`](../../aspose.barcode.generation/padding/) in. |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype/) { get; set; } | Encode-type van BarCode (symboliek). Gebruik [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) om de huidige symboliek op te halen. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth/) { get; } | BarCode-beeldbreedte wanneer de eigenschap [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor/) { get; set; } | Streepkleur. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight/) { get; } | Hoogte van de strepen van 1D-barcodes. Genegeerd als de eigenschap [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border/) { get; } | Haalt of stelt randparameters [`BorderParameters`](../../aspose.barcode.generation/borderparameters/) in. |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove/) { get; } | Bijschrift boven het BarCode‑beeld. Zie [`CaptionUI`](../captionui/). |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow/) { get; } | Bijschrift onder het BarCode‑beeld. Zie [`CaptionUI`](../captionui/). |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow/) { get; set; } | Toon altijd het controlecijfer in de menselijk leesbare tekst voor Code128- en GS1Code128-streepjescodes. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext/) { get; set; } | Gegevens die gecodeerd moeten worden, verschillende typen BarCode kunnen verschillende CodeText‑lengtebeperkingen hebben. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters/) { get; } | Haalt of stelt CodeText‑parameters [`CodetextParametersUI`](../codetextparametersui/) in. |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype/) { get; set; } | Encode-type van BarCode (symboliek). Gebruik [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) om de huidige symboliek op te halen. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars/) { get; set; } | Haalt of stelt een waarde in die aangeeft of strepen gevuld zijn. Alleen voor 1D-barcodes. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled/) { get; set; } | Checksum inschakelen tijdens het genereren van 1D-barcodes. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution/) { get; set; } | Haalt of stelt de resolutie van het BarCode‑beeld in. Eén waarde voor beide dimensies. Standaardwaarde: 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle/) { get; set; } | BarCode-afbeeldingsrotatiehoek, gemeten in graden, bijv. RotationAngle = 0 of RotationAngle = 360 betekent geen rotatie. Als RotationAngle NIET gelijk is aan 90, 180, 270 of 0, kan dit de moeilijkheid voor de scanner om de afbeelding te lezen verhogen. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific/) { get; } | Specifieke parameters |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect/) { get; set; } | Alleen voor 1D-barcodes. Als codetext onjuist is en de waarde is ingesteld op true - wordt er een uitzondering gegooid. Anders wordt codetext gecorrigeerd om te voldoen aan de specificatie van de barcode. Een uitzondering wordt altijd gegooid voor: Databar symbology als codetext onjuist is. Een uitzondering wordt nooit gegooid voor: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128 symbology als codetext onjuist is. |
| [UseAntiAlias](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/useantialias/) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of anti-aliasing-modus wordt gebruikt om de afbeelding weer te geven. |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio/) { get; set; } | Verhouding brede strepen tot smalle strepen. Standaardwaarde: 3, dat wil zeggen, brede strepen zijn 3 keer zo breed als smalle strepen. Gebruikt voor ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension/) { get; } | X-dimensie is de kleinste breedte van de eenheid van BarCode-strepen of -ruimtes. Het verhogen hiervan vergroot de totale breedte van de barcode-afbeelding. Genegeerd als de eigenschap [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |

### Zie ook

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol/)
* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


