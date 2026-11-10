---
title: "Klasse BarCodeGeneratorControl"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Windows.Forms.BarCodeGeneratorControl Klasse. BarCode Windows-Steuerelement, gehen Sie zu Ihrem Toolbox-Panel und fügen Sie Aspose.BarCode.dll hinzu, und Sie werden sehen, dass BarCodeGeneratorControl erscheint. Ziehen Sie es einfach und legen Sie es in Ihrem Windows-Formular ab. see  see"
type: docs
weight: 1800
url: /de/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows‑Steuerung, gehen Sie zu Ihrem Toolbox‑Panel und fügen Sie Aspose.BarCode.dll hinzu, und Sie werden sehen, dass BarcodeGeneratorControl erscheint. Ziehen Sie es einfach auf Ihr Windows‑Formular und lassen Sie es dort fallen. siehe  siehe

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode/) { get; set; } | Liest oder setzt den Modus, in dem der Barcode automatisch die Größe ändert. Standardwert ist AutoSizeMode.None. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor/) { get; set; } | Hintergrundfarbe des Barcode‑Bildes. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight/) { get; } | BarCode-Bildhöhe, wenn die Eigenschaft [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings/) { get; } | Liest oder setzt die Barcode‑Abstandparameter [`Padding`](../../aspose.barcode.generation/padding/). |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype/) { get; set; } | Kodierungstyp des BarCodes (Symbolik). Verwenden Sie [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/), um die aktuelle Symbolik zu erhalten. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth/) { get; } | BarCode-Bildbreite, wenn die Eigenschaft [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor/) { get; set; } | Farbe der Balken. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight/) { get; } | Höhe der Balken von 1D‑Barcodes. Ignoriert, wenn die Eigenschaft [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border/) { get; } | Liest oder setzt die Randparameter [`BorderParameters`](../../aspose.barcode.generation/borderparameters/). |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove/) { get; } | Beschriftung über dem BarCode-Bild. Siehe [`CaptionUI`](../captionui/). |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow/) { get; } | Beschriftung unter dem BarCode-Bild. Siehe [`CaptionUI`](../captionui/). |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow/) { get; set; } | Checksumme immer im menschenlesbaren Text für Code128- und GS1Code128-Barcodes anzeigen. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext/) { get; set; } | Zu codierende Daten, verschiedene BarCode‑Typen können unterschiedliche Längenbeschränkungen für CodeText haben. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters/) { get; } | Liest oder setzt die CodeText‑Parameter [`CodetextParametersUI`](../codetextparametersui/). |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype/) { get; set; } | Kodierungstyp des BarCodes (Symbolik). Verwenden Sie [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/), um die aktuelle Symbolik zu erhalten. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob Balken gefüllt sind. Nur für 1D-Barcodes. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled/) { get; set; } | Prüfsumme während der Erzeugung von 1D-Barcodes aktivieren. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution/) { get; set; } | Liest oder setzt die Auflösung des BarCode‑Bildes. Ein Wert für beide Dimensionen. Standardwert: 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle/) { get; set; } | Drehwinkel des BarCode‑Bildes, gemessen in Grad, z. B. RotationAngle = 0 oder RotationAngle = 360 bedeutet keine Drehung. Wenn RotationAngle NICHT gleich 90, 180, 270 oder 0 ist, kann dies die Schwierigkeit für den Scanner erhöhen, das Bild zu lesen. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific/) { get; } | Spezifische Parameter |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect/) { get; set; } | Nur für 1D-Barcodes. Wenn der Codetext inkorrekt ist und der Wert auf true gesetzt wird, wird eine Ausnahme ausgelöst. Andernfalls wird der Codetext korrigiert, um der Spezifikation des Barcodes zu entsprechen. Eine Ausnahme wird immer ausgelöst für: Databar‑symbology, wenn der Codetext inkorrekt ist. Eine Ausnahme wird niemals ausgelöst für: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128 symbology, wenn der Codetext inkorrekt ist. |
| [UseAntiAlias](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/useantialias/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob ein Anti‑Aliasing‑Modus zum Rendern des Bildes verwendet wird. |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio/) { get; set; } | Verhältnis von breiten zu schmalen Balken. Standardwert: 3, das heißt, breite Balken sind dreimal so breit wie schmale Balken. Verwendet für ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension/) { get; } | Die X‑Dimension ist die kleinste Breite der Einheit von BarCode‑Balken oder -Leerräumen. Eine Erhöhung dieses Werts vergrößert die gesamte Barcode‑Bildbreite. Ignoriert, wenn die Eigenschaft [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist. |

### Siehe auch

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol/)
* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


