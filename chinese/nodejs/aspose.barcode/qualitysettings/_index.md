---
title: "QualitySettings"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "QualitySettings 允许手动配置识别质量和速度。"
type: docs
weight: 860
url: /zh/nodejs/aspose.barcode/qualitysettings/
---

## QualitySettings class

QualitySettings 允许手动配置识别质量和速度。您可以通过内置预设快速设置 QualitySettings：HighPerformance、NormalQuality、HighQuality、MaxBarCodes，或手动配置各个选项。QualitySettings 的默认值是 NormalQuality。

```js
new QualitySettings()
```

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getHighPerformance()](#gethighperformance) *(static)* | HighPerformance 识别质量预设。在此模式下，高质量条形码能够得到良好识别。 |
| [getHighQuality()](#gethighquality) *(static)* | HighQuality 识别质量预设。此预设针对低质量条形码而开发。 |
| [getMaxQuality()](#getmaxquality) *(static)* | MaxQuality 识别质量预设。此预设旨在识别所有可能的条形码，即使是错误的条形码。 |
| [getNormalQuality()](#getnormalquality) *(static)* | NormalQuality 识别质量预设。适用于大多数条形码。 |
| [getAllowIncorrectBarcodes()](#getallowincorrectbarcodes) | 允许引擎识别具有错误校验和或错误数值的条形码。此模式可用于识别损坏的条形码。 |
| [getBarcodeQuality()](#getbarcodequality) | 启用方法以使用所选质量识别条码元素的模式。质量较低的条码元素 r |
| [getComplexBackground()](#getcomplexbackground) | 此模式启用或禁用对彩色图像中彩色条形码的额外识别。 |
| [getDeconvolution()](#getdeconvolution) | 去卷积（图像恢复）模式，定义图像退化的程度。最初去卷积是一个函数 |
| [getInverseImage()](#getinverseimage) | 启用或禁用对颜色反转（亮度）图像中条形码的额外识别的模式。 |
| [getMinimalXDimension()](#getminimalxdimension) | 与 UseMinimalXDimension 一起使用的 XDimension 的最小像素尺寸。 |
| [getXDimension()](#getxdimension) | 设置条形码最小元素（矩阵单元或条）的大小（从 1 到无穷大）的识别模式。 |
| [setAllowIncorrectBarcodes(value)](#setallowincorrectbarcodes) | 允许引擎识别具有错误校验和或错误数值的条形码。此模式可用于识别损坏的条形码。 |
| [setBarcodeQuality(value)](#setbarcodequality) | 启用方法以使用所选质量识别条码元素的模式。质量较低的条码元素 r |
| [setComplexBackground(value)](#setcomplexbackground) | 此模式启用或禁用对彩色图像中彩色条形码的额外识别。 |
| [setDeconvolution(value)](#setdeconvolution) | 去卷积（图像恢复）模式，定义图像退化的程度。最初去卷积是一个函数 |
| [setInverseImage(value)](#setinverseimage) | 启用或禁用对颜色反转（亮度）图像中条形码的额外识别的模式。 |
| [setMinimalXDimension(value)](#setminimalxdimension) | 与 UseMinimalXDimension 一起使用的 XDimension 的最小像素尺寸。 |
| [setXDimension(value)](#setxdimension) | 设置条形码最小元素（矩阵单元或条）的大小（从 1 到无穷大）的识别模式。 |

### getHighPerformance() (static) {#gethighperformance}

HighPerformance 识别质量预设。在此模式下，高质量条形码能够得到良好识别。

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighPerformance());
```

### getHighQuality() (static) {#gethighquality}

HighQuality 识别质量预设。此预设针对低质量条形码而开发。

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighQuality());
```

### getMaxQuality() (static) {#getmaxquality}

MaxQuality 识别质量预设。此预设旨在识别所有可能的条形码，即使是错误的条形码。此示例展示了如何使用 MaxQuality 模式：reader = new BarCodeReader(\"test.png\"null, null, DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128); { reader.setQualitySettings(QualitySettings.getMaxQuality()); for(let i = 0; i < reader.readBarCodes().length; i++) echo (reader.getFoundBarcodes()[i].getCodeText()); } 值：MaxQuality 识别质量预设。

### getNormalQuality() (static) {#getnormalquality}

NormalQuality 识别质量预设。适用于大多数条形码。

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getNormalQuality());
```

### getAllowIncorrectBarcodes() {#getallowincorrectbarcodes}

允许引擎识别具有错误校验和或错误数值的条形码。此模式可用于识别文本错误的受损条形码。

**Returns:** Allows engine to recognize incorrect barcodes.

### getBarcodeQuality() {#getbarcodequality}

启用使用所选质量识别条形码元素的方法的模式。质量较低的条形码元素需要更复杂的方法，从而减慢识别速度。

**Returns:** Mode which enables methods to recognize barcode elements with the selected quality.

### getComplexBackground() {#getcomplexbackground}

此模式启用或禁用对彩色图像中彩色条形码的额外识别。

**Returns:** Additional recognition of color barcodes on color images.

### getDeconvolution() {#getdeconvolution}

去卷积（图像恢复）模式，用于定义图像退化的程度。去卷积最初是一种能够恢复因自然函数（如模糊）在相机拍摄过程中导致的退化（卷积）图像的功能。由于我们无法检测导致图像损坏的函数，只能检查最常见的函数，如锐化或数学形态学。

**Returns:** Deconvolution mode which defines level of image degradation.

### getInverseImage() {#getinverseimage}

启用或禁用对颜色反转（亮度）图像中条形码的额外识别的模式。

**Returns:** Additional recognition of barcodes on images with inverse colors

### getMinimalXDimension() {#getminimalxdimension}

与 UseMinimalXDimension 一起使用的 XDimension 的最小像素尺寸。

**Returns:** Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

### getXDimension() {#getxdimension}

设置条形码最小元素（矩阵单元或条）的大小（从 1 到无穷大）的识别模式。

**Returns:** size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

### setAllowIncorrectBarcodes(value) {#setallowincorrectbarcodes}

允许引擎识别具有错误校验和或错误数值的条形码。此模式可用于识别文本错误的受损条形码。

| 参数 | 描述 |
| --- | --- |
| 值 | 允许引擎识别错误的条形码。 |

### setBarcodeQuality(value) {#setbarcodequality}

启用使用所选质量识别条形码元素的方法的模式。质量较低的条形码元素需要更复杂的方法，从而减慢识别速度。

| 参数 | 描述 |
| --- | --- |
| 值 | 启用使用所选质量识别条形码元素的方法的模式。 |

### setComplexBackground(value) {#setcomplexbackground}

此模式启用或禁用对彩色图像中彩色条形码的额外识别。

| 参数 | 描述 |
| --- | --- |
| 值 | 对彩色图像中的彩色条形码进行额外识别。 |

### setDeconvolution(value) {#setdeconvolution}

去卷积（图像恢复）模式，用于定义图像退化的程度。去卷积最初是一种能够恢复因自然函数（如模糊）在相机拍摄过程中导致的退化（卷积）图像的功能。由于我们无法检测导致图像损坏的函数，只能检查最常见的函数，如锐化或数学形态学。

| 参数 | 描述 |
| --- | --- |
| 值 | 去卷积模式，用于定义图像退化的程度。 |

### setInverseImage(value) {#setinverseimage}

启用或禁用对颜色反转（亮度）图像中条形码的额外识别的模式。

| 参数 | 描述 |
| --- | --- |
| 值 | 对颜色反转图像中的条形码进行额外识别 |

### setMinimalXDimension(value) {#setminimalxdimension}

与 UseMinimalXDimension 一起使用的 XDimension 的最小像素尺寸。

| 参数 | 描述 |
| --- | --- |
| 值 | 与 UseMinimalXDimension 一起使用的 XDimension 的最小像素尺寸。 |

### setXDimension(value) {#setxdimension}

设置条形码最小元素（矩阵单元或条）的大小（从 1 到无穷大）的识别模式。

| 参数 | 描述 |
| --- | --- |
| 值 | （从 1 到无穷大）条形码最小元素：矩阵单元或条。 |
