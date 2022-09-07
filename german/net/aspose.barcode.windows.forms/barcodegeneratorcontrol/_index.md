---
title: BarCodeGeneratorControl
second_title: Aspose.BarCode für .NET-API-Referenz
description: BarCode Windows Control gehen Sie zu Ihrem Toolbox-Panel und fügen Sie Aspose.BarCode.dll hinzu und Sie werden sehen dass BarcodeGeneratorControl erscheint. Ziehen Sie es einfach per Drag amp Drop in Ihr Windows-Formular. siehe siehe
type: docs
weight: 1050
url: /de/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control, gehen Sie zu Ihrem Toolbox-Panel und fügen Sie Aspose.BarCode.dll, hinzu und Sie werden sehen, dass BarcodeGeneratorControl erscheint. Ziehen Sie es einfach per Drag &amp; Drop in Ihr Windows-Formular. siehe siehe

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode) { get; set; } | Ruft den Modus ab oder legt den Modus fest, in dem der Barcode automatisch die Größe ändert. Der Standardwert ist AutoSizeMode.None. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor) { get; set; } | Hintergrundfarbe des Barcodebildes. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight) { get; } | BarCode-Bildhöhe wann[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) Eigenschaft auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation. gesetzt ist |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings) { get; } | Ruft Barcode-Padding-Parameter ab oder legt sie fest[`Padding`](../../aspose.barcode.generation/padding) . |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype) { get; set; } | Codierungstyp des Barcodes (Symbologie). Verwendung[`EncodeTypes`](../../aspose.barcode.generation/encodetypes) um die aktuelle Symbologie zu erhalten. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth) { get; } | Barcodebildbreite wann[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) Eigenschaft auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation. gesetzt ist |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor) { get; set; } | Balkenfarbe. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight) { get; } | Höhe der Striche von 1D-Barcodes. Wird ignoriert, wenn[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) Eigenschaft auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation. gesetzt ist |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border) { get; } | Ruft Rahmenparameter ab oder setzt sie[`BorderParameters`](../../aspose.barcode.generation/borderparameters) . |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove) { get; } | Beschriftung Über dem Barcode-Bild. Sehen[`CaptionParameters`](../../aspose.barcode.generation/captionparameters) . |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow) { get; } | Bildunterschrift Unter dem Barcode-Bild. Sehen[`CaptionParameters`](../../aspose.barcode.generation/captionparameters) . |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow) { get; set; } | Prüfsummenziffer immer im menschenlesbaren Text für Code128- und GS1Code128-Barcodes anzeigen. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext) { get; set; } | Zu codierende Daten, verschiedene Arten von Barcodes können unterschiedliche CodeText-Längenbeschränkungen haben. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters) { get; } | Ruft CodeText-Parameter ab oder setzt sie[`CodetextParameters`](../../aspose.barcode.generation/codetextparameters) . |
| [EnableEscape](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/enableescape) { get; set; } | Gibt an, ob das Zeichen „\“ als Escape-Zeichen in der CodeText-Eigenschaft erklärt wird. Wird nur für Pdf417, DataMatrix, Code128 verwendet Wenn EnableEscape wahr ist, wird "\" als spezielles Escape-Zeichen erklärt. Andernfalls fungiert "\" als normales Zeichen. Aspose.BarCode unterstützt die Eingabe von dezimalem ASCII-Code und Mnemonik für ASCII-Steuercodezeichen. Beispielsweise steht \013 und \\CR für CR. |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype) { get; set; } | Codierungstyp des Barcodes (Symbologie). Verwendung[`EncodeTypes`](../../aspose.barcode.generation/encodetypes) um die aktuelle Symbologie zu erhalten. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars) { get; set; } | Liest oder setzt einen Wert, der angibt, ob Balken gefüllt sind. Nur für 1D-Barcodes. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled) { get; set; } | Aktivieren Sie die Prüfsumme während der Generierung von 1D-Barcodes. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution) { get; set; } | Liest oder setzt die Auflösung des Barcode-Bildes. Ein Wert für beide Dimensionen. Standardwert: 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle) { get; set; } | Rotationswinkel des Barcode-Bildes, gemessen in Grad, z. B. RotationAngle = 0 oder RotationAngle = 360 bedeutet keine Rotation. Wenn RotationAngle NICHT gleich 90, 180, 270 oder 0 ist, kann dies die Schwierigkeit für den Scanner erhöhen, das Bild zu lesen. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific) { get; } | Spezifische Parameter |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect) { get; set; } | Nur für 1D-Barcodes. Wenn der Codetext falsch ist und der Wert auf „true“ gesetzt ist, wird eine Ausnahme ausgelöst. Andernfalls wird der Codetext korrigiert, damit er der Spezifikation des Barcodes entspricht. Ausnahme wird immer ausgelöst für: Databar-Symbologie, wenn Codetext falsch ist. Ausnahme wird immer nicht ausgelöst für: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128 Symbologie, wenn Codetext falsch ist . |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio) { get; set; } | Verhältnis breite Balken zu schmalen Balken. Standardwert: 3, dh breite Balken sind dreimal so breit wie schmale Balken. Verwendet für ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension) { get; } | X-Dimension ist die kleinste Breite der Einheit von Strichcode-Balken oder Zwischenräumen. Vergrößern erhöht die Breite des gesamten Strichcode-Bildes. Ignoriert, wenn[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) Eigenschaft auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation. gesetzt ist |

### Siehe auch

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol)
* namensraum [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms)
* Montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
