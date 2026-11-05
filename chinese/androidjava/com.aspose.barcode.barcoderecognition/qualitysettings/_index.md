---
title: "QualitySettings"
second_title: "Aspose.BarCode for Android via Java API 参考"
description: "QualitySettings 允许手动配置识别质量和速度。"
type: docs
weight: 42
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class QualitySettings implements Parcelable
```

QualitySettings 允许手动配置识别质量和速度。您可以使用内置预设快速设置 QualitySettings：HighPerformance、NormalQuality、HighQuality、MaxQuality，或手动配置各个选项。QualitySettings 的默认值为 NormalQuality。

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
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [QualitySettings()](#QualitySettings--) | QualitySettings 构造函数 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | 允许引擎识别校验和或数值不正确的条码。 |
| [getBarcodeQuality()](#getBarcodeQuality--) | 启用使用所选质量识别条码元素的方法的模式。 |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | 在彩色图像上启用或禁用对彩色条码额外识别的模式。 |
| [getDeconvolution()](#getDeconvolution--) | 去卷积（图像恢复）模式，用于定义图像退化的程度。 |
| [getHighPerformance()](#getHighPerformance--) | HighPerformance 识别质量预设。 |
| [getHighQuality()](#getHighQuality--) | HighQuality 识别质量预设。 |
| [getImageScalingMode()](#getImageScalingMode--) | 允许使用特定的 ImageScaleMode 缩放图像 |
| [getInverseImage()](#getInverseImage--) | 此模式可启用或禁用对颜色反转（亮度）图像上条形码的额外识别。 |
| [getMaxQuality()](#getMaxQuality--) | MaxQuality 识别质量预设。 |
| [getMinimalXDimension()](#getMinimalXDimension--) | 使用 UseMinimalXDimension 时的 XDimension 最小像素尺寸。 |
| [getNormalQuality()](#getNormalQuality--) | NormalQuality 识别质量预设。 |
| [getXDimension()](#getXDimension--) | 识别模式，用于设置条形码最小元素（矩阵单元或条）的大小（从 1 到无限）。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | 允许引擎识别校验和或数值不正确的条码。 |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | 启用使用所选质量识别条码元素的方法的模式。 |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | 在彩色图像上启用或禁用对彩色条码额外识别的模式。 |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | 去卷积（图像恢复）模式，用于定义图像退化的程度。 |
| [setImageScalingMode(ImageScalingMode value)](#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-) | 允许使用特定的 ImageScaleMode 值来缩放图像： |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | 此模式可启用或禁用对颜色反转（亮度）图像上条形码的额外识别。 |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | 使用 UseMinimalXDimension 时的 XDimension 最小像素尺寸。 |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | 识别模式，用于设置条形码最小元素（矩阵单元或条）的大小（从 1 到无限）。 |
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
整数
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


允许引擎识别校验和或数值不正确的条形码。此模式可用于识别文本错误的损坏条形码。

值：允许引擎识别不正确的条形码。

**Returns:**
布尔
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


此模式启用使用所选质量识别条形码元素的方法。质量较低的条形码元素需要更复杂的方法，导致识别速度变慢。

值：启用使用所选质量识别条形码元素的方法的模式。

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


在彩色图像上启用或禁用对彩色条码额外识别的模式。

值：对彩色图像中的彩色条形码进行额外识别。

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


去卷积（图像恢复）模式，用于定义图像退化程度。去卷积最初是一种能够恢复因自然函数（如模糊）在相机拍摄过程中导致的退化（卷积）图像的功能。由于我们无法检测导致图像损坏的函数，只能检查最常见的函数，如锐化或数学形态学。

值：定义图像退化程度的去卷积模式。

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


HighPerformance 识别质量预设。在此模式下，高质量条形码能够得到良好识别。

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


HighQuality 识别质量预设。此预设针对低质量条形码而开发，能够检测高度损坏的条形码。

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


此模式可启用或禁用对颜色反转（亮度）图像上条形码的额外识别。

值：对颜色反转图像上的条形码进行额外识别

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


MaxQuality 识别质量预设。此预设旨在识别所有可能的条形码，甚至是不正确的条形码。

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

值：使用 UseMinimalXDimension 时的 XDimension 最小像素尺寸。

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


NormalQuality 识别质量预设。适用于大多数条形码

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


识别模式，用于设置条形码最小元素（矩阵单元或条）的大小（从 1 到无限）。

值：条形码最小元素的大小（从 1 到无限），即矩阵单元或条。

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
整数
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


允许引擎识别校验和或数值不正确的条形码。此模式可用于识别文本错误的损坏条形码。

值：允许引擎识别不正确的条形码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


此模式启用使用所选质量识别条形码元素的方法。质量较低的条形码元素需要更复杂的方法，导致识别速度变慢。

值：启用使用所选质量识别条形码元素的方法的模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


在彩色图像上启用或禁用对彩色条码额外识别的模式。

值：对彩色图像中的彩色条形码进行额外识别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


去卷积（图像恢复）模式，用于定义图像退化程度。去卷积最初是一种能够恢复因自然函数（如模糊）在相机拍摄过程中导致的退化（卷积）图像的功能。由于我们无法检测导致图像损坏的函数，只能检查最常见的函数，如锐化或数学形态学。

值：定义图像退化程度的去卷积模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setImageScalingMode(ImageScalingMode value) {#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-}
```
public void setImageScalingMode(ImageScalingMode value)
```


允许使用特定的 ImageScaleMode 值来缩放图像：

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | com.aspose.barcode.barcoderecognition.ImageScalingMode | ImageScalingMode 值 |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


此模式可启用或禁用对颜色反转（亮度）图像上条形码的额外识别。

值：对颜色反转图像上的条形码进行额外识别

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


使用 UseMinimalXDimension 时的 XDimension 最小像素尺寸。

值：使用 UseMinimalXDimension 时的 XDimension 最小像素尺寸。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


识别模式，用于设置条形码最小元素（矩阵单元或条）的大小（从 1 到无限）。

值：条形码最小元素的大小（从 1 到无限），即矩阵单元或条。

**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | 整数 |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | 整数 |  |

