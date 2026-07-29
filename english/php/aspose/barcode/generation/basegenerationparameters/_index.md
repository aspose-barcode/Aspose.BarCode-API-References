---
title: "BaseGenerationParameters Class"
linktitle: "BaseGenerationParameters"
articleTitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode for PHP via Java"
description: "Barcode image generation parameters."
type: docs
weight: 10
url: /php/aspose/barcode/generation/basegenerationparameters/
---

## BaseGenerationParameters class

**Namespace:** `Aspose.Barcode.Generation`


Barcode image generation parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](/php/aspose/barcode/generation/basegenerationparameters/basegenerationparameters/) |  |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [AutoSizeMode](/php/aspose/barcode/generation/basegenerationparameters/autosizemode/) | Read/Write | Specifies the different types of automatic sizing modes. Default value: AutoSizeMode::NONE. |
| [BackColor](/php/aspose/barcode/generation/basegenerationparameters/backcolor/) | Read/Write | Background color of the barcode image. Default value: #FFFFFF |
| [Barcode](/php/aspose/barcode/generation/basegenerationparameters/barcode/) | Read/Write | Gets the BarcodeParameters that contains all barcode properties. |
| [Border](/php/aspose/barcode/generation/basegenerationparameters/border/) | Read-only | Gets the BorderParameters that contains all configuration properties for barcode border. |
| [CaptionAbove](/php/aspose/barcode/generation/basegenerationparameters/captionabove/) | Read/Write | Caption Above the BarCode image. |
| [CaptionBelow](/php/aspose/barcode/generation/basegenerationparameters/captionbelow/) | Read/Write | Caption Below the BarCode image. |
| [Image](/php/aspose/barcode/generation/basegenerationparameters/image/) | Read-only | Image parameters. See ImageParameters. |
| [ImageHeight](/php/aspose/barcode/generation/basegenerationparameters/imageheight/) | Read/Write | BarCode image height when AutoSizeMode property is set to AutoSizeMode::NEAREST or AutoSizeMode::INTERPOLATION. |
| [ImageWidth](/php/aspose/barcode/generation/basegenerationparameters/imagewidth/) | Read/Write | BarCode image width when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode::INTERPOLATION. |
| [Resolution](/php/aspose/barcode/generation/basegenerationparameters/resolution/) | Read/Write | Gets the resolution of the BarCode image. One value for both dimensions. Default value: 96 dpi. |
| [RotationAngle](/php/aspose/barcode/generation/basegenerationparameters/rotationangle/) | Read/Write | BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0. This sample shows how to create and save a BarCode image. |
| [UseAntiAlias](/php/aspose/barcode/generation/basegenerationparameters/useantialias/) | Read/Write | Gets a value indicating whether is used anti-aliasing mode to render image |
