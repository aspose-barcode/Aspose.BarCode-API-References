---
title: QualitySettings
second_title: Aspose.BarCode for Java API Reference
description: QualitySettings allows to configure recognition quality and speed manually.
type: docs
weight: 35
url: /java/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object
```
public final class QualitySettings
```

QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality.

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  for(BarCodeResult result : reader.readBarCodes())
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>  //normal quality mode is set by default
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>  //set high quality mode with low speed recognition
>  reader.setQualitySettings(QualitySettings.getHighQuality());
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>  //set max barcodes mode, which tries to find all possible barcodes, even incorrect. The slowest recognition mode
>  reader.setQualitySettings(QualitySettings.getMaxBarCodes());
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  //set separate options
>  reader.getQualitySettings().setAllowMedianSmoothing(true);
>  reader.getQualitySettings().setMedianSmoothingWindowSize(5);
>  for(BarCodeResult result : reader.readBarCodes())
>        System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>  //default mode is NormalQuality
>  //set separate options
>  reader.getQualitySettings().setAllowMedianSmoothing(true);
>  reader.getQualitySettings().setMedianSmoothingWindowSize(5);
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [QualitySettings()](#QualitySettings--) | QualitySettings constructor |
| [QualitySettings(QualitySettings Settings)](#QualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | QualitySettings copy constructor |
## Methods

| Method | Description |
| --- | --- |
| [applyAll(QualitySettings Src)](#applyAll-com.aspose.barcode.barcoderecognition.QualitySettings-) | Function apply all values from Src setting to this |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowComplexBackground()](#getAllowComplexBackground--) | Allows engine to recognize color barcodes on color background as additional scan. |
| [getAllowDatamatrixIndustrialBarcodes()](#getAllowDatamatrixIndustrialBarcodes--) | Allows engine for Datamatrix to recognize dashed industrial Datamatrix barcodes. |
| [getAllowDecreasedImage()](#getAllowDecreasedImage--) | Allows engine to recognize decreased image as additional scan. |
| [getAllowDetectScanGap()](#getAllowDetectScanGap--) | Allows engine to use gap between scans to increase recognition speed. |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. |
| [getAllowInvertImage()](#getAllowInvertImage--) | Allows engine to recognize inverse color image as additional scan. |
| [getAllowMedianSmoothing()](#getAllowMedianSmoothing--) | Allows engine to enable median smoothing as additional scan. |
| [getAllowMicroWhiteSpotsRemoving()](#getAllowMicroWhiteSpotsRemoving--) | Allows engine for Postal barcodes to recognize slightly noised images. |
| [getAllowOneDAdditionalScan()](#getAllowOneDAdditionalScan--) | Allows engine for 1D barcodes to recognize regular image with different params as additional scan. |
| [getAllowOneDFastBarcodesDetector()](#getAllowOneDFastBarcodesDetector--) | Allows engine for 1D barcodes to quickly recognize high quality barcodes which fill almost whole image. |
| [getAllowOneDWipedBarsRestoration()](#getAllowOneDWipedBarsRestoration--) | Allows engine for 1D barcodes to recognize barcodes with single wiped/glued bars in pattern. |
| [getAllowQRMicroQrRestoration()](#getAllowQRMicroQrRestoration--) | Allows engine for QR/MicroQR to recognize damaged MicroQR barcodes. |
| [getAllowRegularImage()](#getAllowRegularImage--) | Allows engine to recognize regular image without any restorations as main scan. |
| [getAllowSaltAndPaperFiltering()](#getAllowSaltAndPaperFiltering--) | Allows engine to recognize barcodes with salt and paper noise type. |
| [getAllowWhiteSpotsRemoving()](#getAllowWhiteSpotsRemoving--) | Allows engine to recognize image without small white spots as additional scan. |
| [getCheckMore1DVariants()](#getCheckMore1DVariants--) | Allows engine to recognize 1D barcodes with checksum by checking more recognition variants. |
| [getClass()](#getClass--) |  |
| [getDetectorSettings()](#getDetectorSettings--) | Barcode detector settings. |
| [getFastScanOnly()](#getFastScanOnly--) | Allows engine for 1D barcodes to quickly recognize middle slice of an image and return result without using any time-consuming algorithms. |
| [getHighPerformance()](#getHighPerformance--) | HighPerformance recognition quality preset. |
| [getHighQuality()](#getHighQuality--) | HighQuality recognition quality preset. |
| [getHighQualityDetection()](#getHighQualityDetection--) | HighQualityDetection recognition quality preset. |
| [getMaxBarCodes()](#getMaxBarCodes--) | MaxBarCodes recognition quality preset. |
| [getMaxQualityDetection()](#getMaxQualityDetection--) | MaxQualityDetection recognition quality preset. |
| [getMedianSmoothingWindowSize()](#getMedianSmoothingWindowSize--) | Window size for median smoothing. |
| [getNormalQuality()](#getNormalQuality--) | NormalQuality recognition quality preset. |
| [getReadTinyBarcodes()](#getReadTinyBarcodes--) | Allows engine to recognize tiny barcodes on large images. |
| [getUseOldBarcodeDetector()](#getUseOldBarcodeDetector--) | Switches to the old barcode detector. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowComplexBackground(boolean value)](#setAllowComplexBackground-boolean-) | Allows engine to recognize color barcodes on color background as additional scan. |
| [setAllowDatamatrixIndustrialBarcodes(boolean value)](#setAllowDatamatrixIndustrialBarcodes-boolean-) | Allows engine for Datamatrix to recognize dashed industrial Datamatrix barcodes. |
| [setAllowDecreasedImage(boolean value)](#setAllowDecreasedImage-boolean-) | Allows engine to recognize decreased image as additional scan. |
| [setAllowDetectScanGap(boolean value)](#setAllowDetectScanGap-boolean-) | Allows engine to use gap between scans to increase recognition speed. |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. |
| [setAllowInvertImage(boolean value)](#setAllowInvertImage-boolean-) | Allows engine to recognize inverse color image as additional scan. |
| [setAllowMedianSmoothing(boolean value)](#setAllowMedianSmoothing-boolean-) | Allows engine to enable median smoothing as additional scan. |
| [setAllowMicroWhiteSpotsRemoving(boolean value)](#setAllowMicroWhiteSpotsRemoving-boolean-) | Allows engine for Postal barcodes to recognize slightly noised images. |
| [setAllowOneDAdditionalScan(boolean value)](#setAllowOneDAdditionalScan-boolean-) | Allows engine for 1D barcodes to recognize regular image with different params as additional scan. |
| [setAllowOneDFastBarcodesDetector(boolean value)](#setAllowOneDFastBarcodesDetector-boolean-) | Allows engine for 1D barcodes to quickly recognize high quality barcodes which fill almost whole image. |
| [setAllowOneDWipedBarsRestoration(boolean value)](#setAllowOneDWipedBarsRestoration-boolean-) | Allows engine for 1D barcodes to recognize barcodes with single wiped/glued bars in pattern. |
| [setAllowQRMicroQrRestoration(boolean value)](#setAllowQRMicroQrRestoration-boolean-) | Allows engine for QR/MicroQR to recognize damaged MicroQR barcodes. |
| [setAllowRegularImage(boolean value)](#setAllowRegularImage-boolean-) | Allows engine to recognize regular image without any restorations as main scan. |
| [setAllowSaltAndPaperFiltering(boolean value)](#setAllowSaltAndPaperFiltering-boolean-) | Allows engine to recognize barcodes with salt and paper noise type. |
| [setAllowWhiteSpotsRemoving(boolean value)](#setAllowWhiteSpotsRemoving-boolean-) | Allows engine to recognize image without small white spots as additional scan. |
| [setCheckMore1DVariants(boolean value)](#setCheckMore1DVariants-boolean-) | Allows engine to recognize 1D barcodes with checksum by checking more recognition variants. |
| [setDetectorSettings(BarcodeSvmDetectorSettings value)](#setDetectorSettings-com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings-) | Barcode detector settings. |
| [setFastScanOnly(boolean value)](#setFastScanOnly-boolean-) | Allows engine for 1D barcodes to quickly recognize middle slice of an image and return result without using any time-consuming algorithms. |
| [setMedianSmoothingWindowSize(int value)](#setMedianSmoothingWindowSize-int-) | Window size for median smoothing. |
| [setReadTinyBarcodes(boolean value)](#setReadTinyBarcodes-boolean-) | Allows engine to recognize tiny barcodes on large images. |
| [setUseOldBarcodeDetector(boolean value)](#setUseOldBarcodeDetector-boolean-) | Switches to the old barcode detector. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QualitySettings() {#QualitySettings--}
```
public QualitySettings()
```


QualitySettings constructor

### QualitySettings(QualitySettings Settings) {#QualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public QualitySettings(QualitySettings Settings)
```


QualitySettings copy constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Settings | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) | The source of the data |

### applyAll(QualitySettings Src) {#applyAll-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public void applyAll(QualitySettings Src)
```


Function apply all values from Src setting to this

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Src | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) | source settings |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllowComplexBackground() {#getAllowComplexBackground--}
```
public boolean getAllowComplexBackground()
```


Allows engine to recognize color barcodes on color background as additional scan. Extremely slow mode.

Value: Allows engine to recognize color barcodes on color background.

**Returns:**
boolean
### getAllowDatamatrixIndustrialBarcodes() {#getAllowDatamatrixIndustrialBarcodes--}
```
public boolean getAllowDatamatrixIndustrialBarcodes()
```


Allows engine for Datamatrix to recognize dashed industrial Datamatrix barcodes. Slow mode which helps only for dashed barcodes which consist from spots.

Value: Allows engine for Datamatrix to recognize dashed industrial barcodes.

**Returns:**
boolean
### getAllowDecreasedImage() {#getAllowDecreasedImage--}
```
public boolean getAllowDecreasedImage()
```


Allows engine to recognize decreased image as additional scan. Size for decreasing is selected by internal engine algorithms. Mode helps to recognize barcodes which are noised and blurred but captured with high resolution.

Value: Allows engine to recognize decreased image

**Returns:**
boolean
### getAllowDetectScanGap() {#getAllowDetectScanGap--}
```
public boolean getAllowDetectScanGap()
```


Allows engine to use gap between scans to increase recognition speed. Mode can make recognition problems with low height barcodes.

Value: Allows engine to use gap between scans to increase recognition speed.

**Returns:**
boolean
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize damaged barcodes with incorrect text.

Value: Allows engine to recognize incorrect barcodes.

**Returns:**
boolean
### getAllowInvertImage() {#getAllowInvertImage--}
```
public boolean getAllowInvertImage()
```


Allows engine to recognize inverse color image as additional scan. Mode can be used when barcode is white on black background.

Value: Allows engine to recognize inverse color image.

**Returns:**
boolean
### getAllowMedianSmoothing() {#getAllowMedianSmoothing--}
```
public boolean getAllowMedianSmoothing()
```


Allows engine to enable median smoothing as additional scan. Mode helps to recognize noised barcodes.

Value: Allows engine to enable median smoothing.

**Returns:**
boolean
### getAllowMicroWhiteSpotsRemoving() {#getAllowMicroWhiteSpotsRemoving--}
```
public boolean getAllowMicroWhiteSpotsRemoving()
```


Allows engine for Postal barcodes to recognize slightly noised images. Mode helps to recognize sligtly damaged Postal barcodes.

Value: Allows engine for Postal barcodes to recognize slightly noised images.

**Returns:**
boolean
### getAllowOneDAdditionalScan() {#getAllowOneDAdditionalScan--}
```
public boolean getAllowOneDAdditionalScan()
```


Allows engine for 1D barcodes to recognize regular image with different params as additional scan. Mode helps to recongize low height 1D barcodes.

Value: Allows engine for 1D barcodes to run additional scan.

**Returns:**
boolean
### getAllowOneDFastBarcodesDetector() {#getAllowOneDFastBarcodesDetector--}
```
public boolean getAllowOneDFastBarcodesDetector()
```


Allows engine for 1D barcodes to quickly recognize high quality barcodes which fill almost whole image. Mode helps to quickly recognize generated barcodes from Internet.

Value: Allows engine for 1D barcodes to quickly recognize high quality barcodes.

**Returns:**
boolean
### getAllowOneDWipedBarsRestoration() {#getAllowOneDWipedBarsRestoration--}
```
public boolean getAllowOneDWipedBarsRestoration()
```


Allows engine for 1D barcodes to recognize barcodes with single wiped/glued bars in pattern.

Value: Allows engine for 1D barcodes to recognize barcodes with single wiped/glued bars in pattern.

**Returns:**
boolean
### getAllowQRMicroQrRestoration() {#getAllowQRMicroQrRestoration--}
```
public boolean getAllowQRMicroQrRestoration()
```


Allows engine for QR/MicroQR to recognize damaged MicroQR barcodes.

Value: Allows engine for QR/MicroQR to recognize damaged MicroQR barcodes.

**Returns:**
boolean
### getAllowRegularImage() {#getAllowRegularImage--}
```
public boolean getAllowRegularImage()
```


Allows engine to recognize regular image without any restorations as main scan. Mode to recognize image as is.

Value: Allows to recognize regular image without any restorations.

**Returns:**
boolean
### getAllowSaltAndPaperFiltering() {#getAllowSaltAndPaperFiltering--}
```
public boolean getAllowSaltAndPaperFiltering()
```


Allows engine to recognize barcodes with salt and paper noise type. Mode can remove small noise with white and black dots.

Value: Allows engine to recognize barcodes with salt and paper noise type.

**Returns:**
boolean
### getAllowWhiteSpotsRemoving() {#getAllowWhiteSpotsRemoving--}
```
public boolean getAllowWhiteSpotsRemoving()
```


Allows engine to recognize image without small white spots as additional scan. Mode helps to recognize noised image as well as median smoothing filtering.

Value: Allows engine to recognize image without small white spots.

**Returns:**
boolean
### getCheckMore1DVariants() {#getCheckMore1DVariants--}
```
public boolean getCheckMore1DVariants()
```


Allows engine to recognize 1D barcodes with checksum by checking more recognition variants. Default value: False.

**Returns:**
boolean - If True, allows engine to recognize 1D barcodes with checksum.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDetectorSettings() {#getDetectorSettings--}
```
public BarcodeSvmDetectorSettings getDetectorSettings()
```


Barcode detector settings.

**Returns:**
[BarcodeSvmDetectorSettings](../../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings)
### getFastScanOnly() {#getFastScanOnly--}
```
public boolean getFastScanOnly()
```


Allows engine for 1D barcodes to quickly recognize middle slice of an image and return result without using any time-consuming algorithms.

**Returns:**
boolean - Allows engine for 1D barcodes to quickly recognize high quality barcodes.
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


HighPerformance recognition quality preset. High quality barcodes are recognized well in this mode.

```
BarCodeReader reader = new BarCodeReader("test.png");
  reader.setQualitySettings(QualitySettings.getHighPerformance());
```

Value: HighPerformance recognition quality preset.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


HighQuality recognition quality preset. This preset is developed for low quality barcodes. Allows to detect diagonal and highly damaged barcodes.

```
BarCodeReader reader = new BarCodeReader("test.png");
 reader.setQualitySettings(QualitySettings.getHighQuality());
```

Value: HighQuality recognition quality preset.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQualityDetection() {#getHighQualityDetection--}
```
public static QualitySettings getHighQualityDetection()
```


HighQualityDetection recognition quality preset. Same as NormalQuality but with high quality  DetectorSettings 

```
BarCodeReader reader = new BarCodeReader("test.png");
 reader.setQualitySettings(QualitySettings.getHighQualityDetection());
```

Value: HighQualityDetection recognition quality preset.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMaxBarCodes() {#getMaxBarCodes--}
```
public static QualitySettings getMaxBarCodes()
```


MaxBarCodes recognition quality preset. This preset is developed to recognize all possible barcodes, even incorrect barcodes.

```
BarCodeReader reader = new BarCodeReader("test.png");
 reader.setQualitySettings(QualitySettings.getMaxBarCodes());
```

Value: MaxBarCodes recognition quality preset.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMaxQualityDetection() {#getMaxQualityDetection--}
```
public static QualitySettings getMaxQualityDetection()
```


MaxQualityDetection recognition quality preset. Same as NormalQuality but with highest quality  DetectorSettings . Allows to detect diagonal and damaged barcodes.

```
BarCodeReader reader = new BarCodeReader("test.png");
 reader.setQualitySettings(QualitySettings.getMaxQualityDetection());
```

Value: MaxQualityDetection recognition quality preset.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMedianSmoothingWindowSize() {#getMedianSmoothingWindowSize--}
```
public int getMedianSmoothingWindowSize()
```


Window size for median smoothing. Typical values are 3 or 4. Default value is 3. AllowMedianSmoothing must be set.

Value: Window size for median smoothing.

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


NormalQuality recognition quality preset. Suitable for the most of barcodes

```
BarCodeReader reader = new BarCodeReader("test.png");
 reader.setQualitySettings(QualitySettings.getNormalQuality());
```

Value: NormalQuality recognition quality preset.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getReadTinyBarcodes() {#getReadTinyBarcodes--}
```
public boolean getReadTinyBarcodes()
```


Allows engine to recognize tiny barcodes on large images. Ignored if  is set to True. Default value: False.

**Returns:**
boolean - If True, allows engine to recognize tiny barcodes on large images.
### getUseOldBarcodeDetector() {#getUseOldBarcodeDetector--}
```
public boolean getUseOldBarcodeDetector()
```


Switches to the old barcode detector.

Value: Switches to the old barcode detector.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAllowComplexBackground(boolean value) {#setAllowComplexBackground-boolean-}
```
public void setAllowComplexBackground(boolean value)
```


Allows engine to recognize color barcodes on color background as additional scan. Extremely slow mode.

Value: Allows engine to recognize color barcodes on color background.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAllowDatamatrixIndustrialBarcodes(boolean value) {#setAllowDatamatrixIndustrialBarcodes-boolean-}
```
public void setAllowDatamatrixIndustrialBarcodes(boolean value)
```


Allows engine for Datamatrix to recognize dashed industrial Datamatrix barcodes. Slow mode which helps only for dashed barcodes which consist from spots.

Value: Allows engine for Datamatrix to recognize dashed industrial barcodes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAllowDecreasedImage(boolean value) {#setAllowDecreasedImage-boolean-}
```
public void setAllowDecreasedImage(boolean value)
```


Allows engine to recognize decreased image as additional scan. Size for decreasing is selected by internal engine algorithms. Mode helps to recognize barcodes which are noised and blurred but captured with high resolution.

Value: Allows engine to recognize decreased image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAllowDetectScanGap(boolean value) {#setAllowDetectScanGap-boolean-}
```
public void setAllowDetectScanGap(boolean value)
```


Allows engine to use gap between scans to increase recognition speed. Mode can make recognition problems with low height barcodes.

Value: Allows engine to use gap between scans to increase recognition speed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAllowIncorrectBarcodes(boolean value) {#setAllowIncorrectBarcodes-boolean-}
```
public void setAllowIncorrectBarcodes(boolean value)
```


Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize damaged barcodes with incorrect text.

Value: Allows engine to recognize incorrect barcodes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAllowInvertImage(boolean value) {#setAllowInvertImage-boolean-}
```
public void setAllowInvertImage(boolean value)
```


Allows engine to recognize inverse color image as additional scan. Mode can be used when barcode is white on black background.

Value: Allows engine to recognize inverse color image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAllowMedianSmoothing(boolean value) {#setAllowMedianSmoothing-boolean-}
```
public void setAllowMedianSmoothing(boolean value)
```


Allows engine to enable median smoothing as additional scan. Mode helps to recognize noised barcodes.

Value: Allows engine to enable median smoothing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAllowMicroWhiteSpotsRemoving(boolean value) {#setAllowMicroWhiteSpotsRemoving-boolean-}
```
public void setAllowMicroWhiteSpotsRemoving(boolean value)
```


Allows engine for Postal barcodes to recognize slightly noised images. Mode helps to recognize sligtly damaged Postal barcodes.

Value: Allows engine for Postal barcodes to recognize slightly noised images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAllowOneDAdditionalScan(boolean value) {#setAllowOneDAdditionalScan-boolean-}
```
public void setAllowOneDAdditionalScan(boolean value)
```


Allows engine for 1D barcodes to recognize regular image with different params as additional scan. Mode helps to recongize low height 1D barcodes.

Value: Allows engine for 1D barcodes to run additional scan.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAllowOneDFastBarcodesDetector(boolean value) {#setAllowOneDFastBarcodesDetector-boolean-}
```
public void setAllowOneDFastBarcodesDetector(boolean value)
```


Allows engine for 1D barcodes to quickly recognize high quality barcodes which fill almost whole image. Mode helps to quickly recognize generated barcodes from Internet.

Value: Allows engine for 1D barcodes to quickly recognize high quality barcodes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAllowOneDWipedBarsRestoration(boolean value) {#setAllowOneDWipedBarsRestoration-boolean-}
```
public void setAllowOneDWipedBarsRestoration(boolean value)
```


Allows engine for 1D barcodes to recognize barcodes with single wiped/glued bars in pattern.

Value: Allows engine for 1D barcodes to recognize barcodes with single wiped/glued bars in pattern.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAllowQRMicroQrRestoration(boolean value) {#setAllowQRMicroQrRestoration-boolean-}
```
public void setAllowQRMicroQrRestoration(boolean value)
```


Allows engine for QR/MicroQR to recognize damaged MicroQR barcodes.

Value: Allows engine for QR/MicroQR to recognize damaged MicroQR barcodes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAllowRegularImage(boolean value) {#setAllowRegularImage-boolean-}
```
public void setAllowRegularImage(boolean value)
```


Allows engine to recognize regular image without any restorations as main scan. Mode to recognize image as is.

Value: Allows to recognize regular image without any restorations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAllowSaltAndPaperFiltering(boolean value) {#setAllowSaltAndPaperFiltering-boolean-}
```
public void setAllowSaltAndPaperFiltering(boolean value)
```


Allows engine to recognize barcodes with salt and paper noise type. Mode can remove small noise with white and black dots.

Value: Allows engine to recognize barcodes with salt and paper noise type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAllowWhiteSpotsRemoving(boolean value) {#setAllowWhiteSpotsRemoving-boolean-}
```
public void setAllowWhiteSpotsRemoving(boolean value)
```


Allows engine to recognize image without small white spots as additional scan. Mode helps to recognize noised image as well as median smoothing filtering.

Value: Allows engine to recognize image without small white spots.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setCheckMore1DVariants(boolean value) {#setCheckMore1DVariants-boolean-}
```
public void setCheckMore1DVariants(boolean value)
```


Allows engine to recognize 1D barcodes with checksum by checking more recognition variants. Default value: False.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | If True, allows engine to recognize 1D barcodes with checksum. |

### setDetectorSettings(BarcodeSvmDetectorSettings value) {#setDetectorSettings-com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings-}
```
public void setDetectorSettings(BarcodeSvmDetectorSettings value)
```


Barcode detector settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BarcodeSvmDetectorSettings](../../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) |  |

### setFastScanOnly(boolean value) {#setFastScanOnly-boolean-}
```
public void setFastScanOnly(boolean value)
```


Allows engine for 1D barcodes to quickly recognize middle slice of an image and return result without using any time-consuming algorithms.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | Allows engine for 1D barcodes to quickly recognize high quality barcodes. |

### setMedianSmoothingWindowSize(int value) {#setMedianSmoothingWindowSize-int-}
```
public void setMedianSmoothingWindowSize(int value)
```


Window size for median smoothing. Typical values are 3 or 4. Default value is 3. AllowMedianSmoothing must be set.

Value: Window size for median smoothing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setReadTinyBarcodes(boolean value) {#setReadTinyBarcodes-boolean-}
```
public void setReadTinyBarcodes(boolean value)
```


Allows engine to recognize tiny barcodes on large images. Ignored if  is set to True. Default value: False.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | If True, allows engine to recognize tiny barcodes on large images. |

### setUseOldBarcodeDetector(boolean value) {#setUseOldBarcodeDetector-boolean-}
```
public void setUseOldBarcodeDetector(boolean value)
```


Switches to the old barcode detector.

Value: Switches to the old barcode detector.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

