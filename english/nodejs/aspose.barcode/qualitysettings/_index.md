---
title: "QualitySettings"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "QualitySettings allows to configure recognition quality and speed manually."
type: docs
weight: 860
url: /nodejs/aspose.barcode/qualitysettings/
---

## QualitySettings class

QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality.

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

## Methods

| Name | Description |
| --- | --- |
| [getHighPerformance()](#gethighperformance) *(static)* | HighPerformance recognition quality preset. High quality barcodes are recognized well in this mode. |
| [getHighQuality()](#gethighquality) *(static)* | HighQuality recognition quality preset. This preset is developed for low quality barcodes. |
| [getMaxQuality()](#getmaxquality) *(static)* | MaxQuality recognition quality preset. This preset is developed to recognize all possible barcodes, even incorrect barco |
| [getNormalQuality()](#getnormalquality) *(static)* | NormalQuality recognition quality preset. Suitable for the most of barcodes |
| [getAllowIncorrectBarcodes()](#getallowincorrectbarcodes) | Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize dam |
| [getBarcodeQuality()](#getbarcodequality) | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality r |
| [getComplexBackground()](#getcomplexbackground) | Mode which enables or disables additional recognition of color barcodes on color images. |
| [getDeconvolution()](#getdeconvolution) | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function |
| [getInverseImage()](#getinverseimage) | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). |
| [getMinimalXDimension()](#getminimalxdimension) | Minimal size of XDimension in pixels which is used with UseMinimalXDimension. |
| [getXDimension()](#getxdimension) | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. |
| [setAllowIncorrectBarcodes(value)](#setallowincorrectbarcodes) | Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize dam |
| [setBarcodeQuality(value)](#setbarcodequality) | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality r |
| [setComplexBackground(value)](#setcomplexbackground) | Mode which enables or disables additional recognition of color barcodes on color images. |
| [setDeconvolution(value)](#setdeconvolution) | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function |
| [setInverseImage(value)](#setinverseimage) | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). |
| [setMinimalXDimension(value)](#setminimalxdimension) | Minimal size of XDimension in pixels which is used with UseMinimalXDimension. |
| [setXDimension(value)](#setxdimension) | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. |

### getHighPerformance() (static) {#gethighperformance}

HighPerformance recognition quality preset. High quality barcodes are recognized well in this mode.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighPerformance());
```

### getHighQuality() (static) {#gethighquality}

HighQuality recognition quality preset. This preset is developed for low quality barcodes.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighQuality());
```

### getMaxQuality() (static) {#getmaxquality}

MaxQuality recognition quality preset. This preset is developed to recognize all possible barcodes, even incorrect barcodes. This sample shows how to use MaxQuality mode reader = new BarCodeReader("test.png"null, null, DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128); { reader.setQualitySettings(QualitySettings.getMaxQuality()); for(let i = 0; i < reader.readBarCodes().length; i++) echo (reader.getFoundBarcodes()[i].getCodeText()); } Value: MaxQuality recognition quality preset.

### getNormalQuality() (static) {#getnormalquality}

NormalQuality recognition quality preset. Suitable for the most of barcodes

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getNormalQuality());
```

### getAllowIncorrectBarcodes() {#getallowincorrectbarcodes}

Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize damaged barcodes with incorrect text.

**Returns:** Allows engine to recognize incorrect barcodes.

### getBarcodeQuality() {#getbarcodequality}

Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows the recognition.

**Returns:** Mode which enables methods to recognize barcode elements with the selected quality.

### getComplexBackground() {#getcomplexbackground}

Mode which enables or disables additional recognition of color barcodes on color images.

**Returns:** Additional recognition of color barcodes on color images.

### getDeconvolution() {#getdeconvolution}

Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the image, we have to check most well know functions like sharp or mathematical morphology.

**Returns:** Deconvolution mode which defines level of image degradation.

### getInverseImage() {#getinverseimage}

Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance).

**Returns:** Additional recognition of barcodes on images with inverse colors

### getMinimalXDimension() {#getminimalxdimension}

Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

**Returns:** Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

### getXDimension() {#getxdimension}

Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

**Returns:** size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

### setAllowIncorrectBarcodes(value) {#setallowincorrectbarcodes}

Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize damaged barcodes with incorrect text.

| Parameter | Description |
| --- | --- |
| value | Allows engine to recognize incorrect barcodes. |

### setBarcodeQuality(value) {#setbarcodequality}

Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows the recognition.

| Parameter | Description |
| --- | --- |
| value | Mode which enables methods to recognize barcode elements with the selected quality. |

### setComplexBackground(value) {#setcomplexbackground}

Mode which enables or disables additional recognition of color barcodes on color images.

| Parameter | Description |
| --- | --- |
| value | Additional recognition of color barcodes on color images. |

### setDeconvolution(value) {#setdeconvolution}

Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the image, we have to check most well know functions like sharp or mathematical morphology.

| Parameter | Description |
| --- | --- |
| value | Deconvolution mode which defines level of image degradation. |

### setInverseImage(value) {#setinverseimage}

Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance).

| Parameter | Description |
| --- | --- |
| value | Additional recognition of barcodes on images with inverse colors |

### setMinimalXDimension(value) {#setminimalxdimension}

Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

| Parameter | Description |
| --- | --- |
| value | Minimal size of XDimension in pixels which is used with UseMinimalXDimension. |

### setXDimension(value) {#setxdimension}

Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

| Parameter | Description |
| --- | --- |
| value | (from 1 to infinity) of barcode minimal element: matrix cell or bar. |
