---
title: "Klasse BaseGenerationParameters"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.BaseGenerationParameters Klasse. Parameter zur Barcode‑Bildgenerierung"
type: docs
weight: 1030
url: /de/net/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class

Parameter zur Barcode‑Bildgenerierung.

```csharp
public class BaseGenerationParameters
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.generation/basegenerationparameters/autosizemode/) { get; set; } | Gibt die verschiedenen Typen automatischer Größeneinstellungsmodi an. Standardwert: AutoSizeMode.None. |
| [BackColor](../../aspose.barcode.generation/basegenerationparameters/backcolor/) { get; set; } | Hintergrundfarbe des Barcode‑Bildes. Standardwert: Color.White. Siehe Color. |
| [Barcode](../../aspose.barcode.generation/basegenerationparameters/barcode/) { get; } | Ruft die [`BarcodeParameters`](../barcodeparameters/) ab, die alle Barcode‑Eigenschaften enthält. |
| [Border](../../aspose.barcode.generation/basegenerationparameters/border/) { get; } | Ruft die [`BorderParameters`](../borderparameters/) ab, die alle Konfigurationseigenschaften für den Barcode‑Rand enthält. |
| [CaptionAbove](../../aspose.barcode.generation/basegenerationparameters/captionabove/) { get; } | Beschriftung über dem BarCode-Bild. Siehe [`CaptionParameters`](../captionparameters/). |
| [CaptionBelow](../../aspose.barcode.generation/basegenerationparameters/captionbelow/) { get; } | Beschriftung unter dem BarCode-Bild. Siehe [`CaptionParameters`](../captionparameters/). |
| [Image](../../aspose.barcode.generation/basegenerationparameters/image/) { get; } | Bildparameter. Siehe [`ImageParameters`](../imageparameters/). |
| [ImageHeight](../../aspose.barcode.generation/basegenerationparameters/imageheight/) { get; set; } | BarCode-Bildhöhe, wenn die [`AutoSizeMode`](./autosizemode/) Eigenschaft auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist. |
| [ImageWidth](../../aspose.barcode.generation/basegenerationparameters/imagewidth/) { get; set; } | BarCode-Bildbreite, wenn die [`AutoSizeMode`](./autosizemode/) Eigenschaft auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist. |
| [Resolution](../../aspose.barcode.generation/basegenerationparameters/resolution/) { get; set; } | Liest oder setzt die Auflösung des BarCode‑Bildes. Ein Wert für beide Dimensionen. Standardwert: 96 dpi. |
| [RotationAngle](../../aspose.barcode.generation/basegenerationparameters/rotationangle/) { get; set; } | BarCode-Bilddrehwinkel, gemessen in Grad, z. B. RotationAngle = 0 oder RotationAngle = 360 bedeutet keine Drehung. Wenn RotationAngle NICHT gleich 90, 180, 270 oder 0 ist, kann dies die Schwierigkeit für den Scanner erhöhen, das Bild zu lesen. Standardwert: 0. |
| [UseAntiAlias](../../aspose.barcode.generation/basegenerationparameters/useantialias/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob ein Anti-Aliasing-Modus zum Rendern des Bildes verwendet wird. |

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


