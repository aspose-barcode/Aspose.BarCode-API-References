---
title: BarCodeGeneratorControl
second_title: Aspose.BarCode för .NET API-referens
description: BarCode Windows Control gå till panelen i verktygslådan och lägg till Aspose.BarCode.dll och du kommer att se BarcodeGeneratorControl visas. Bara dra och släpp den till ditt Windows-formulär. se se
type: docs
weight: 1050
url: /sv/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control, gå till panelen i verktygslådan och lägg till Aspose.BarCode.dll, och du kommer att se BarcodeGeneratorControl visas. Bara dra och släpp den till ditt Windows-formulär. se se

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode) { get; set; } | Hämtar eller ställer in det läge med vilket streckkoden automatiskt ändrar storlek. Standardvärdet är AutoSizeMode.None. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor) { get; set; } | Streckkodsbildens bakgrundsfärg. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight) { get; } | Streckkodsbildhöjd när[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) egenskapen är inställd på AutoSizeMode.Nearest eller AutoSizeMode.Interpolation. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings) { get; } | Hämtar eller ställer in parametrar för streckkodsutfyllnad[`Padding`](../../aspose.barcode.generation/padding) . |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype) { get; set; } | Streckkods kodningstyp (symbologi). Använd[`EncodeTypes`](../../aspose.barcode.generation/encodetypes) för att få aktuell symbolik. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth) { get; } | Streckkodsbildbredd när[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) egenskapen är inställd på AutoSizeMode.Nearest eller AutoSizeMode.Interpolation. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor) { get; set; } | Staplars färg. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight) { get; } | Höjden på 1D-streckkodernas streck. Ignoreras om[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) egenskapen är inställd på AutoSizeMode.Nearest eller AutoSizeMode.Interpolation. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border) { get; } | Hämtar eller ställer in gränsparametrar[`BorderParameters`](../../aspose.barcode.generation/borderparameters) . |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove) { get; } | Bildtext ovanför streckkodsbilden. Ser[`CaptionParameters`](../../aspose.barcode.generation/captionparameters) . |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow) { get; } | Bildtext under streckkodsbilden. Ser[`CaptionParameters`](../../aspose.barcode.generation/captionparameters) . |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow) { get; set; } | Visa alltid kontrollsummans siffra i den mänskliga läsbara texten för Code128 och GS1Code128 streckkoder. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext) { get; set; } | Data som ska kodas, olika typer av streckkoder kan ha olika längdbegränsningar för CodeText. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters) { get; } | Hämtar eller ställer in CodeText-parametrar[`CodetextParameters`](../../aspose.barcode.generation/codetextparameters) . |
| [EnableEscape](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/enableescape) { get; set; } | Anger om tecknet "\" förklaras som ett escape-tecken i CodeText-egenskapen. Används för Pdf417, DataMatrix, Code128 only Om EnableEscape är sant, kommer "\" att förklaras som ett speciellt escape-tecken. Annars fungerar "\" som vanliga tecken. Aspose.BarCode stöder inmatning av decimal ascii-kod och mnemonic för ASCII-kontrollkodstecken. Till exempel, \013 och \\CR står för CR. |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype) { get; set; } | Streckkods kodningstyp (symbologi). Använd[`EncodeTypes`](../../aspose.barcode.generation/encodetypes) för att få aktuell symbolik. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars) { get; set; } | Hämtar eller ställer in ett värde som anger om staplarna är fyllda. Endast för 1D-streckkoder. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled) { get; set; } | Aktivera kontrollsumma under generation 1D streckkoder. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution) { get; set; } | Hämtar eller ställer in upplösningen för streckkodsbilden. Ett värde för båda dimensionerna. Standardvärde: 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle) { get; set; } | BarCode bildrotationsvinkel, mätt i grader, t.ex. RotationAngle = 0 eller RotationAngle = 360 betyder ingen rotation. Om RotationAngle INTE är lika med 90, 180, 270 eller 0, kan det öka svårigheten för skannern att läsa bilden._x000 |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific) { get; } | Specifika parametrar |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect) { get; set; } | Endast för 1D streckkoder. Om kodtexten är felaktig och värdet satt till true - kommer undantag att kastas. Annars kommer kodtexten att korrigeras för att matcha streckkodens specifikation. Undantag kommer alltid att kastas för: Databar symbology om kodtexten är felaktig. Undantag kommer alltid inte att kastas för: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K symbology code12 . |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio) { get; set; } | Breda staplar till smala staplar ratio. Standardvärde: 3, det vill säga breda staplar är 3 gånger så breda som smala staplar. Används för ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, I Italian, DeutschePost25, VIN DeutschePost25, VIN DeutschePost , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension) { get; } | X-dimension är den minsta bredden på enheten för streckkodsstaplar eller mellanslag. Öka detta kommer att öka hela streckkodens bildbredd. Ignoreras om[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) egenskapen är inställd på AutoSizeMode.Nearest eller AutoSizeMode.Interpolation. |

### Se även

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol)
* namnutrymme [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms)
* hopsättning [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
