---
title: QualitySettings Class
linktitle: QualitySettings
articleTitle: QualitySettings
second_title: Aspose.BarCode for Node.js via Java
description: "QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality."
type: docs
weight: 1350
url: /nodejs/qualitysettings/
---
## QualitySettings class

QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality.

```javascript
public class QualitySettings : joint.BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [QualitySettings](./qualitysettings/#constructor)(*object*) | Initializes a new instance of the QualitySettings class. |

## Methods

| Name | Description |
| --- | --- |
| [getAllowIncorrectBarcodes](./getallowincorrectbarcodes/) | Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize damaged barcodes with incorrect text. |
| [getBarcodeQuality](./getbarcodequality/) | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows the recognition. |
| [getComplexBackground](./getcomplexbackground/) | Mode which enables or disables additional recognition of color barcodes on color images. |
| [getDeconvolution](./getdeconvolution/) | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the... |
| [getHighPerformance](./gethighperformance/) | HighPerformance recognition quality preset. High quality barcodes are recognized well in this mode. |
| [getHighQuality](./gethighquality/) | HighQuality recognition quality preset. This preset is developed for low quality barcodes. |
| [getInverseImage](./getinverseimage/) | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). |
| [getMaxQuality](./getmaxquality/) | MaxQuality recognition quality preset. This preset is developed to recognize all possible barcodes, even incorrect barcodes. |
| [getMinimalXDimension](./getminimalxdimension/) | Minimal size of XDimension in pixels which is used with UseMinimalXDimension. |
| [getNormalQuality](./getnormalquality/) | NormalQuality recognition quality preset. Suitable for the most of barcodes. |
| [getXDimension](./getxdimension/) | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. |
| [init](./init/) |  |
| [initQualitySettings](./initqualitysettings/) |  |
| [setAllowIncorrectBarcodes](./setallowincorrectbarcodes/)(*object*) | Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize damaged barcodes with incorrect text. |
| [setBarcodeQuality](./setbarcodequality/)(*object*) | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows the recognition. |
| [setComplexBackground](./setcomplexbackground/)(*object*) | Mode which enables or disables additional recognition of color barcodes on color images. |
| [setDeconvolution](./setdeconvolution/)(*object*) | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the... |
| [setInverseImage](./setinverseimage/)(*object*) | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). |
| [setMinimalXDimension](./setminimalxdimension/)(*object*) | Minimal size of XDimension in pixels which is used with UseMinimalXDimension. |
| [setXDimension](./setxdimension/)(*object*) | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. |

## Examples

```javascript
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

```javascript
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//normal quality mode is set by default
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode CodeText: " + result.getCodeText());
}
```

```javascript
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high quality mode with low speed recognition
reader.setQualitySettings(QualitySettings.getHighQuality());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode CodeText: " + result.getCodeText());
}
```

```javascript
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set max barcodes mode, which tries to find all possible barcodes, even incorrect. The slowest recognition mode
reader.setQualitySettings(QualitySettings.getMaxBarCodes());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode CodeText: " + result.getCodeText());
}
```

```javascript
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
//set separate options
reader.getQualitySettings().setAllowMedianSmoothing(true);
reader.getQualitySettings().setMedianSmoothingWindowSize(5);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode CodeText: " + result.getCodeText());
}
```

```javascript
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//default mode is NormalQuality
//set separate options
reader.getQualitySettings().setAllowMedianSmoothing(true);
reader.getQualitySettings().setMedianSmoothingWindowSize(5);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode CodeText: " + result.getCodeText());
}
```

### See Also

* assembly [Aspose.BarCode](../)

