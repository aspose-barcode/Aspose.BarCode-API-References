---
title: BaseGenerationParameters Class
linktitle: BaseGenerationParameters
articleTitle: BaseGenerationParameters
second_title: Aspose.BarCode for Node.js via Java
description: "Barcode image generation parameters."
type: docs
weight: 460
url: /nodejs/basegenerationparameters/
---
## BaseGenerationParameters class

Barcode image generation parameters.

```javascript
public class BaseGenerationParameters : joint.BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [BaseGenerationParameters](./basegenerationparameters/#constructor)(*object*) | Initializes a new instance of the BaseGenerationParameters class. |

## Methods

| Name | Description |
| --- | --- |
| [getAutoSizeMode](./getautosizemode/) | Specifies the different types of automatic sizing modes. Default value: AutoSizeMode.NONE. |
| [getBackColor](./getbackcolor/) | Background color of the barcode image. Default value: #FFFFFF. |
| [getBarcode](./getbarcode/) | Gets the BarcodeParameters that contains all barcode properties. |
| [getBorder](./getborder/) | Gets the BorderParameters that contains all configuration properties for barcode border. |
| [getCaptionAbove](./getcaptionabove/) | Caption Above the BarCode image. See CaptionParameters. |
| [getCaptionBelow](./getcaptionbelow/) | Caption Below the BarCode image. See CaptionParameters. |
| [getImage](./getimage/) | Image parameters. See ImageParameters. |
| [getImageHeight](./getimageheight/) | BarCode image height when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
| [getImageWidth](./getimagewidth/) | BarCode image width when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
| [getResolution](./getresolution/) | Gets the resolution of the BarCode image. One value for both dimensions. Default value: 96 dpi. |
| [getRotationAngle](./getrotationangle/) | BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image . Default value: 0. |
| [getUseAntiAlias](./getuseantialias/) | Gets a value indicating whether is used anti-aliasing mode to render image. |
| [init](./init/) |  |
| [setAutoSizeMode](./setautosizemode/)(*object*) | Specifies the different types of automatic sizing modes. Default value: AutoSizeMode.NONE. |
| [setBackColor](./setbackcolor/)(*object*) | Background color of the barcode image. Default value: #FFFFFF. |
| [setImageHeight](./setimageheight/)(*object*) | BarCode image height when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
| [setImageWidth](./setimagewidth/)(*object*) | BarCode image width when AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
| [setResolution](./setresolution/)(*object*) | Sets the resolution of the BarCode image. One value for both dimensions. Default value: 96 dpi. |
| [setRotationAngle](./setrotationangle/)(*object*) | BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0. |
| [setUseAntiAlias](./setuseantialias/)(*object*) | Sets a value indicating whether is used anti-aliasing mode to render image. |

## Fields

| Name | Description |
| --- | --- |
| [barcodeParameters](./barcodeparameters/) |  |
| [borderParameters](./borderparameters/) |  |
| [captionAbove](./captionabove/) |  |
| [captionBelow](./captionbelow/) |  |
| [image](./image/) |  |
| [imageHeight](./imageheight/) |  |
| [imageWidth](./imagewidth/) |  |

### See Also

* assembly [Aspose.BarCode](../)

