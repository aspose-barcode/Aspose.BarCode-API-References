---
title: BarCodeGeneratorControl
second_title: Aspose.BarCode voor .NET API-referentie
description: BarCode Windows Control ga naar je toolboxpaneel en voeg Aspose.BarCode.dll toe en je zult zien dat BarcodeGeneratorControl verschijnt. Sleep het gewoon naar je Windowsformulier. zie zien
type: docs
weight: 1320
url: /nl/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control, ga naar je toolbox-paneel en voeg Aspose.BarCode.dll, toe en je zult zien dat BarcodeGeneratorControl verschijnt. Sleep het gewoon naar je Windows-formulier. zie zien

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol/)() | De standaard constructeur. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode/) { get; set; } | Hiermee wordt de modus opgehaald of ingesteld waarmee de barcode automatisch wordt aangepast. Standaardwaarde is AutoSizeMode.None. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor/) { get; set; } | Achtergrondkleur van de streepjescodeafbeelding. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight/) { get; } | BarCode afbeelding hoogte wanneer[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) eigenschap is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings/) { get; } | Haalt of stelt parameters voor streepjescodevulling in[`Padding`](../../aspose.barcode.generation/padding/) . |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype/) { get; set; } | BarCode's coderingstype (symbologie). Gebruik[`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) om de huidige symbologie te krijgen. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth/) { get; } | BarCode afbeelding breedte wanneer[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) eigenschap is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor/) { get; set; } | Kleur balken. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight/) { get; } | Hoogte van de staven van 1D-streepjescodes. Genegeerd indien[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) eigenschap is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border/) { get; } | Hiermee worden grensparameters opgehaald of ingesteld[`BorderParameters`](../../aspose.barcode.generation/borderparameters/) . |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove/) { get; } | Bijschrift Boven de streepjescodeafbeelding. Zien[`CaptionParameters`](../../aspose.barcode.generation/captionparameters/) . |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow/) { get; } | Bijschrift Onder de streepjescodeafbeelding. Zien[`CaptionParameters`](../../aspose.barcode.generation/captionparameters/) . |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow/) { get; set; } | Geef altijd het checksum-cijfer weer in de voor mensen leesbare tekst voor Code128- en GS1Code128-streepjescodes. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext/) { get; set; } | Te coderen gegevens, verschillende soorten streepjescodes kunnen verschillende CodeText-lengtebeperkingen hebben. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters/) { get; } | Haalt CodeText-parameters op of stelt deze in[`CodetextParameters`](../../aspose.barcode.generation/codetextparameters/) . |
| [EnableEscape](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/enableescape/) { get; set; } | Geeft aan of het teken "\" wordt uitgelegd als een escape-teken in de eigenschap CodeText. Alleen gebruikt voor Pdf417, DataMatrix, Code128 Als EnableEscape waar is, wordt "\" uitgelegd als een speciaal escape-teken. Anders fungeert "\" als normale tekens. Aspose.BarCode ondersteunt het invoeren van decimale ascii-code en geheugensteuntje voor ASCII-besturingscodetekens. \013 en \\CR staan bijvoorbeeld voor CR. |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype/) { get; set; } | BarCode's coderingstype (symbologie). Gebruik[`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) om de huidige symbologie te krijgen. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars/) { get; set; } | Haalt of stelt een waarde in die aangeeft of staven gevuld zijn. Alleen voor 1D-streepjescodes. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled/) { get; set; } | Controlesom inschakelen tijdens het genereren van 1D-streepjescodes. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution/) { get; set; } | Hiermee wordt de resolutie van de streepjescodeafbeelding opgehaald of ingesteld. Eén waarde voor beide dimensies. Standaardwaarde: 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle/) { get; set; } | Rotatiehoek streepjescodebeeld, gemeten in graden, bijv. RotationAngle = 0 of RotationAngle = 360 betekent geen rotatie. Als RotationAngle NIET gelijk is aan 90, 180, 270 of 0, kan het voor de scanner moeilijker worden om het beeld te lezen. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific/) { get; } | Specifieke parameters |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect/) { get; set; } | Alleen voor 1D-streepjescodes. Als codetekst onjuist is en de waarde is ingesteld op waar, wordt er een uitzondering gegenereerd. Anders wordt de codetekst gecorrigeerd zodat deze overeenkomt met de specificatie van de streepjescode. Uitzondering wordt altijd gegenereerd voor: Databalk-symboliek als codetekst onjuist is. Uitzondering wordt niet altijd gegenereerd voor: AustraliaPost, SingaporePost, Code39Extended, Code93Extended, Code16K, Code128-symboliek als codetekst onjuist is . |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio/) { get; set; } | Verhouding tussen brede balken en smalle balken. Standaardwaarde: 3, dat wil zeggen brede balken zijn 3 keer zo breed als smalle balken. Gebruikt voor ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension/) { get; } | X-dimensie is de kleinste breedte van de eenheid van streepjescodestrepen of spaties. Verhogen dit zal de gehele breedte van het streepjescodebeeld vergroten. Genegeerd als[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) eigenschap is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |

### Zie ook

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol/)
* naamruimte [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
