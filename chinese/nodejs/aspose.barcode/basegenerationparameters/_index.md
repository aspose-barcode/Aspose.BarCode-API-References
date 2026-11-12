---
title: "BaseGenerationParameters"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "条形码图像生成参数。"
type: docs
weight: 160
url: /zh/nodejs/aspose.barcode/basegenerationparameters/
---

## BaseGenerationParameters class

条形码图像生成参数。

```js
new BaseGenerationParameters()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getAutoSizeMode()](#getautosizemode) | 指定不同类型的自动尺寸模式。默认值：AutoSizeMode.NONE。 |
| [getBackColor()](#getbackcolor) | 条形码图像的背景颜色。默认值：#FFFFFF |
| [getBarcode()](#getbarcode) | 获取包含所有条形码属性的 BarcodeParameters。 |
| [getBorder()](#getborder) | 获取包含条形码边框所有配置属性的 BorderParameters。 |
| [getCaptionAbove()](#getcaptionabove) | BarCode 图像上方的标题。参见 CaptionParameters。 |
| [getCaptionBelow()](#getcaptionbelow) | BarCode 图像下方的标题。参见 CaptionParameters。 |
| [getImage()](#getimage) | 图像参数。参见 ImageParameters。 |
| [getImageHeight()](#getimageheight) | 当 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 时的 BarCode 图像高度。 |
| [getImageWidth()](#getimagewidth) | 当 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 时的 BarCode 图像宽度。 |
| [getResolution()](#getresolution) | 获取 BarCode 图像的分辨率。两个维度使用同一数值。默认值：96 dpi。Resolution 参数 |
| [getRotationAngle()](#getrotationangle) | BarCode 图像旋转角度，以度为单位，例如 RotationAngle = 0 或 RotationAngle = 360 表示不旋转。如果 Ro |
| [getUseAntiAlias()](#getuseantialias) | 获取一个值，指示是否使用抗锯齿模式渲染图像 |
| [setAutoSizeMode()](#setautosizemode) | 指定不同类型的自动尺寸模式。默认值：AutoSizeMode.NONE。 |
| [setBackColor()](#setbackcolor) | 条形码图像的背景颜色。默认值：#FFFFFF |
| [setImageHeight()](#setimageheight) | 当 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 时的 BarCode 图像高度。 |
| [setImageWidth()](#setimagewidth) | 当 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 时的 BarCode 图像宽度。 |
| [setResolution()](#setresolution) | 设置 BarCode 图像的分辨率。两个维度使用同一数值。默认值：96 dpi。Resolution 参数 |
| [setRotationAngle()](#setrotationangle) | BarCode 图像旋转角度，以度为单位，例如 RotationAngle = 0 或 RotationAngle = 360 表示不旋转。如果 Ro |
| [setUseAntiAlias()](#setuseantialias) | 设置一个值，指示是否在渲染图像时使用抗锯齿模式 |

### getAutoSizeMode() {#getautosizemode}

指定不同类型的自动尺寸模式。默认值：AutoSizeMode.NONE。

### getBackColor() {#getbackcolor}

条形码图像的背景颜色。默认值：#FFFFFF

### getBarcode() {#getbarcode}

获取包含所有条形码属性的 BarcodeParameters。

### getBorder() {#getborder}

获取包含条形码边框所有配置属性的 BorderParameters。

### getCaptionAbove() {#getcaptionabove}

BarCode 图像上方的标题。参见 CaptionParameters。

### getCaptionBelow() {#getcaptionbelow}

BarCode 图像下方的标题。参见 CaptionParameters。

### getImage() {#getimage}

图像参数。参见 ImageParameters。

**Returns:** ImageParameters

### getImageHeight() {#getimageheight}

当 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 时的 BarCode 图像高度。

### getImageWidth() {#getimagewidth}

当 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 时的 BarCode 图像宽度。

### getResolution() {#getresolution}

获取条形码图像的分辨率。两个维度使用相同的值。默认值：96 dpi。Resolution 参数值小于或等于 0。

### getRotationAngle() {#getrotationangle}

条形码图像的旋转角度，以度为单位，例如 RotationAngle = 0 或 RotationAngle = 360 表示不旋转。如果 RotationAngle 不等于 90、180、270 或 0，可能会增加扫描仪读取图像的难度。默认值：0。

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### getUseAntiAlias() {#getuseantialias}

获取一个值，指示是否使用抗锯齿模式渲染图像

### setAutoSizeMode() {#setautosizemode}

指定不同类型的自动尺寸模式。默认值：AutoSizeMode.NONE。

### setBackColor() {#setbackcolor}

条形码图像的背景颜色。默认值：#FFFFFF

### setImageHeight() {#setimageheight}

当 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 时的 BarCode 图像高度。

### setImageWidth() {#setimagewidth}

当 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 时的 BarCode 图像宽度。

### setResolution() {#setresolution}

设置条形码图像的分辨率。两个维度使用相同的值。默认值：96 dpi。Resolution 参数值小于或等于 0。

### setRotationAngle() {#setrotationangle}

条形码图像的旋转角度，以度为单位，例如 RotationAngle = 0 或 RotationAngle = 360 表示不旋转。如果 RotationAngle 不等于 90、180、270 或 0，可能会增加扫描仪读取图像的难度。默认值：0。

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### setUseAntiAlias() {#setuseantialias}

设置一个值，指示是否在渲染图像时使用抗锯齿模式
