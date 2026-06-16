---
title: QualitySettings
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: QualitySettings 允许手动配置识别质量和速度。
type: docs
weight: 44
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class QualitySettings implements Parcelable
```

QualitySettings 允许手动配置识别质量和速度。您可以使用内置预设快速设置 QualitySettings：HighPerformance、NormalQuality、HighQuality、MaxQuality，或者手动配置各个选项。QualitySettings 的默认值是 NormalQuality。

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  //set HighPerformance recogition mode
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighQuality recognition mode
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighQuality());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low sized barcodes
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low quality barcodes
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
> ```
## Constructors

| Constructor | 描述 |
| --- | --- |
| [QualitySettings()](#QualitySettings--) | QualitySettings 构造函数 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | 允许引擎识别校验和错误或数值错误的条码。 |
| [getBarcodeQuality()](#getBarcodeQuality--) | 此模式启用方法以所选质量识别条码元素。 |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | 此模式启用或禁用对彩色图像中彩色条码的额外识别。 |
| [getDeconvolution()](#getDeconvolution--) | 去卷积（图像恢复）模式，用于定义图像退化程度。 |
| [getHighPerformance()](#getHighPerformance--) | HighPerformance 识别质量预设。 |
| [getHighQuality()](#getHighQuality--) | HighQuality 识别质量预设。 |
| [getImageScalingMode()](#getImageScalingMode--) | 允许使用特定的 ImageScaleMode 缩放图像 |
| [getInverseImage()](#getInverseImage--) | 此模式启用或禁用对颜色反转（亮度）图像中条码的额外识别。 |
| [getMaxQuality()](#getMaxQuality--) | MaxQuality 识别质量预设。 |
| [getMinimalXDimension()](#getMinimalXDimension--) | 使用 UseMinimalXDimension 时的 XDimension 最小像素尺寸。 |
| [getNormalQuality()](#getNormalQuality--) | NormalQuality 识别质量预设。 |
| [getXDimension()](#getXDimension--) | 识别模式设置条码最小元素（矩阵单元或条）的大小（从 1 到无限）。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | 允许引擎识别校验和错误或数值错误的条码。 |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | 此模式启用方法以所选质量识别条码元素。 |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | 此模式启用或禁用对彩色图像中彩色条码的额外识别。 |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | 去卷积（图像恢复）模式，用于定义图像退化程度。 |
| [setImageScalingMode(ImageScalingMode value)](#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-) | 允许使用特定的 ImageScaleMode 缩放图像，值： |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | 此模式启用或禁用对颜色反转（亮度）图像中条码的额外识别。 |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | 使用 UseMinimalXDimension 时的 XDimension 最小像素尺寸。 |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | 识别模式设置条码最小元素（矩阵单元或条）的大小（从 1 到无限）。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### QualitySettings() {#QualitySettings--}
```
public QualitySettings()
```


QualitySettings 构造函数

### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<QualitySettings> CREATOR
```


### describeContents() {#describeContents--}
```
public int describeContents()
```




**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


允许引擎识别校验和错误或数值错误的条码。此模式可用于识别文本错误的受损条码。

值：允许引擎识别错误的条码。

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


此模式启用方法以所选质量识别条码元素。质量较低的条码元素需要更复杂的方法，导致识别速度变慢。

值：此模式启用方法以所选质量识别条码元素。

**Returns:**
[BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplexBackground() {#getComplexBackground--}
```
public ComplexBackgroundMode getComplexBackground()
```


此模式启用或禁用对彩色图像中彩色条码的额外识别。

值：对彩色图像中彩色条码的额外识别。

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


去卷积（图像恢复）模式用于定义图像退化程度。去卷积最初是一种函数，可恢复因自然函数（如模糊）在相机拍摄时导致的退化（卷积）图像。由于我们无法检测导致图像损坏的函数，只能检查常见的函数，如锐化或数学形态学。

值：去卷积模式，用于定义图像退化程度。

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


HighPerformance 识别质量预设。在此模式下，高质量条码能够得到良好识别。

--------------------

> ```
> This sample shows how to use HighPerformance mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getHighPerformance());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

值：HighPerformance 识别质量预设。

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


HighQuality 识别质量预设。此预设针对低质量条码而开发。允许检测高度损坏的条码。

--------------------

> ```
> This sample shows how to use HighQuality mode
>   
> 
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getHighQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

值：HighQuality 识别质量预设。

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getImageScalingMode() {#getImageScalingMode--}
```
public ImageScalingMode getImageScalingMode()
```


允许使用特定的 ImageScaleMode 缩放图像

**Returns:**
com.aspose.barcode.barcoderecognition.ImageScalingMode
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


此模式启用或禁用对颜色反转（亮度）图像中条码的额外识别。

值：对颜色反转的图像进行额外的条码识别

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


MaxQuality 识别质量预设。此预设旨在识别所有可能的条码，甚至错误的条码。

--------------------

> ```
> This sample shows how to use MaxQuality mode
>   
> 
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getMaxQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

值：MaxQuality 识别质量预设。

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


使用 UseMinimalXDimension 时的 XDimension 最小像素尺寸。

值：使用 UseMinimalXDimension 时 XDimension 的最小像素尺寸。

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


NormalQuality 识别质量预设。适用于大多数条码

--------------------

> ```
> This sample shows how to use NormalQuality mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getNormalQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

值：NormalQuality 识别质量预设。

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getXDimension() {#getXDimension--}
```
public XDimensionMode getXDimension()
```


识别模式设置条码最小元素（矩阵单元或条）的大小（从 1 到无限）。

值：条码最小元素的尺寸（从 1 到无限），如矩阵单元或条。

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
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




### setAllowIncorrectBarcodes(boolean value) {#setAllowIncorrectBarcodes-boolean-}
```
public void setAllowIncorrectBarcodes(boolean value)
```


允许引擎识别校验和错误或数值错误的条码。此模式可用于识别文本错误的受损条码。

值：允许引擎识别错误的条码。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


此模式启用方法以所选质量识别条码元素。质量较低的条码元素需要更复杂的方法，导致识别速度变慢。

值：此模式启用方法以所选质量识别条码元素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


此模式启用或禁用对彩色图像中彩色条码的额外识别。

值：对彩色图像中彩色条码的额外识别。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


去卷积（图像恢复）模式用于定义图像退化程度。去卷积最初是一种函数，可恢复因自然函数（如模糊）在相机拍摄时导致的退化（卷积）图像。由于我们无法检测导致图像损坏的函数，只能检查常见的函数，如锐化或数学形态学。

值：去卷积模式，用于定义图像退化程度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setImageScalingMode(ImageScalingMode value) {#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-}
```
public void setImageScalingMode(ImageScalingMode value)
```


允许使用特定的 ImageScaleMode 缩放图像，值：

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.barcode.barcoderecognition.ImageScalingMode | ImageScalingMode 值 |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


此模式启用或禁用对颜色反转（亮度）图像中条码的额外识别。

值：对颜色反转的图像进行额外的条码识别

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


使用 UseMinimalXDimension 时的 XDimension 最小像素尺寸。

值：使用 UseMinimalXDimension 时 XDimension 的最小像素尺寸。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


识别模式设置条码最小元素（矩阵单元或条）的大小（从 1 到无限）。

值：条码最小元素的尺寸（从 1 到无限），如矩阵单元或条。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |

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
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| 标志 | int |  |

