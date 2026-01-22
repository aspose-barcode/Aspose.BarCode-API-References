---
title: Class BaseGenerationParameters
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.BaseGenerationParameters class. Barcode image generation parameters
type: docs
weight: 950
url: /net/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class

Barcode image generation parameters.

```csharp
public class BaseGenerationParameters
```

## Properties

| Name | Description |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.generation/basegenerationparameters/autosizemode/) { get; set; } | Specifies the different types of automatic sizing modes. Default value: AutoSizeMode.None. |
| [BackColor](../../aspose.barcode.generation/basegenerationparameters/backcolor/) { get; set; } | Background color of the barcode image. Default value: Color.White. See Color. |
| [Barcode](../../aspose.barcode.generation/basegenerationparameters/barcode/) { get; } | Gets the [`BarcodeParameters`](../barcodeparameters/) that contains all barcode properties. |
| [Border](../../aspose.barcode.generation/basegenerationparameters/border/) { get; } | Gets the [`BorderParameters`](../borderparameters/) that contains all configuration properties for barcode border. |
| [CaptionAbove](../../aspose.barcode.generation/basegenerationparameters/captionabove/) { get; } | Caption Above the BarCode image. See [`CaptionParameters`](../captionparameters/). |
| [CaptionBelow](../../aspose.barcode.generation/basegenerationparameters/captionbelow/) { get; } | Caption Below the BarCode image. See [`CaptionParameters`](../captionparameters/). |
| [Image](../../aspose.barcode.generation/basegenerationparameters/image/) { get; } | Image parameters. See [`ImageParameters`](../imageparameters/). |
| [ImageHeight](../../aspose.barcode.generation/basegenerationparameters/imageheight/) { get; set; } | BarCode image height when [`AutoSizeMode`](./autosizemode/) property is set to AutoSizeMode.Nearest or AutoSizeMode.Interpolation. |
| [ImageWidth](../../aspose.barcode.generation/basegenerationparameters/imagewidth/) { get; set; } | BarCode image width when [`AutoSizeMode`](./autosizemode/) property is set to AutoSizeMode.Nearest or AutoSizeMode.Interpolation. |
| [Resolution](../../aspose.barcode.generation/basegenerationparameters/resolution/) { get; set; } | Gets or sets the resolution of the BarCode image. One value for both dimensions. Default value: 96 dpi. |
| [RotationAngle](../../aspose.barcode.generation/basegenerationparameters/rotationangle/) { get; set; } | BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0. |
| [UseAntiAlias](../../aspose.barcode.generation/basegenerationparameters/useantialias/) { get; set; } | Gets or sets a value indicating whether is used anti-aliasing mode to render image |

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


