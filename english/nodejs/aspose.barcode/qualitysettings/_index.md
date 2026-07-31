---
title: "QualitySettings Class"
linktitle: "QualitySettings"
articleTitle: "QualitySettings"
second_title: "Aspose.BarCode for Node.js via Java"
description: "QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, Norm..."
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
| [getHighPerformance()](./gethighperformance/) *(static)* | HighPerformance recognition quality preset. High quality barcodes are recognized well in this mode. |
| [getHighQuality()](./gethighquality/) *(static)* | HighQuality recognition quality preset. This preset is developed for low quality barcodes. |
| [getMaxQuality()](./getmaxquality/) *(static)* | MaxQuality recognition quality preset. This preset is developed to recognize all possible barcodes, even incorrect barco |
| [getNormalQuality()](./getnormalquality/) *(static)* | NormalQuality recognition quality preset. Suitable for the most of barcodes |
| [getAllowIncorrectBarcodes()](./getallowincorrectbarcodes/) | Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize dam |
| [getBarcodeQuality()](./getbarcodequality/) | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality r |
| [getComplexBackground()](./getcomplexbackground/) | Mode which enables or disables additional recognition of color barcodes on color images. |
| [getDeconvolution()](./getdeconvolution/) | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function |
| [getInverseImage()](./getinverseimage/) | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). |
| [getMinimalXDimension()](./getminimalxdimension/) | Minimal size of XDimension in pixels which is used with UseMinimalXDimension. |
| [getXDimension()](./getxdimension/) | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. |
| [setAllowIncorrectBarcodes(value)](./setallowincorrectbarcodes/) | Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize dam |
| [setBarcodeQuality(value)](./setbarcodequality/) | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality r |
| [setComplexBackground(value)](./setcomplexbackground/) | Mode which enables or disables additional recognition of color barcodes on color images. |
| [setDeconvolution(value)](./setdeconvolution/) | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function |
| [setInverseImage(value)](./setinverseimage/) | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). |
| [setMinimalXDimension(value)](./setminimalxdimension/) | Minimal size of XDimension in pixels which is used with UseMinimalXDimension. |
| [setXDimension(value)](./setxdimension/) | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. |
