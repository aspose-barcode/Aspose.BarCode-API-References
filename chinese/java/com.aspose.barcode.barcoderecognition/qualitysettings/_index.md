---
title: "QualitySettings"
second_title: "Aspose.BarCode for Java API Reference"
description: "QualitySettings 允许手动配置识别质量和速度。"
type: docs
weight: 40
url: /zh/java/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object
```
public final class QualitySettings
```

QualitySettings 允许手动配置识别质量和速度。您可以使用内置预设快速设置 QualitySettings：HighPerformance、NormalQuality、HighQuality、MaxQuality，或者手动配置各个选项。QualitySettings 的默认值为 NormalQuality。

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  //set HighPerformance recogition mode
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighQuality recognition mode
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighQuality());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low sized barcodes
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low quality barcodes
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | 允许引擎识别具有错误校验和或错误数值的条形码。 |
| [getBarcodeQuality()](#getBarcodeQuality--) | 启用方法以所选质量识别条码元素的模式。 |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | 在彩色图像上启用或禁用彩色条码的额外识别模式。 |
| [getDeconvolution()](#getDeconvolution--) | 去卷积（图像恢复）模式，定义图像退化的程度。 |
| [getHighPerformance()](#getHighPerformance--) | HighPerformance 识别质量预设。 |
| [getHighQuality()](#getHighQuality--) | HighQuality 识别质量预设。 |
| [getInverseImage()](#getInverseImage--) | 在颜色反转（亮度）图像上启用或禁用条码额外识别的模式。 |
| [getMaxQuality()](#getMaxQuality--) | MaxQuality 识别质量预设。 |
| [getMinimalXDimension()](#getMinimalXDimension--) | 与 UseMinimalXDimension 一起使用的 XDimension 的最小像素尺寸。 |
| [getNormalQuality()](#getNormalQuality--) | NormalQuality 识别质量预设。 |
| [getXDimension()](#getXDimension--) | 设置条码最小元素（矩阵单元或条）的大小（从 1 到无限）的识别模式。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | 允许引擎识别具有错误校验和或错误数值的条形码。 |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | 启用方法以所选质量识别条码元素的模式。 |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | 在彩色图像上启用或禁用彩色条码的额外识别模式。 |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | 去卷积（图像恢复）模式，定义图像退化的程度。 |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | 在颜色反转（亮度）图像上启用或禁用条码额外识别的模式。 |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | 与 UseMinimalXDimension 一起使用的 XDimension 的最小像素尺寸。 |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | 设置条码最小元素（矩阵单元或条）的大小（从 1 到无限）的识别模式。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


允许引擎识别具有错误校验和或错误数值的条码。该模式可用于识别文本错误的损坏条码。

Value: 允许引擎识别错误的条码。

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


启用方法以所选质量识别条码元素的模式。质量较低的条码元素需要更复杂的方法，从而减慢识别速度。

Value: 启用方法以所选质量识别条码元素的模式。

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


在彩色图像上启用或禁用彩色条码的额外识别模式。

Value: 对彩色图像上彩色条码的额外识别。

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


去卷积（图像恢复）模式，定义图像退化的程度。最初，去卷积是一种函数，可恢复因任何自然函数（如模糊）在相机拍摄图像时导致的退化（卷积）图像。由于我们无法检测导致图像损坏的函数，只能检查最常见的函数，如 sharp 或数学形态学。

值：去卷积模式，定义图像退化的程度。

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


HighPerformance 识别质量预设。在此模式下，高质量条码能够被很好地识别。

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


HighQuality 识别质量预设。此预设针对低质量条码开发。能够检测高度损坏的条码。

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
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


在颜色反转（亮度）图像上启用或禁用条码额外识别的模式。

值：对颜色相反的图像中的条码进行额外识别

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


MaxQuality 识别质量预设。此预设用于识别所有可能的条码，甚至是错误的条码。

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


与 UseMinimalXDimension 一起使用的 XDimension 的最小像素尺寸。

值：与 UseMinimalXDimension 一起使用的 XDimension 的最小像素尺寸。

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


NormalQuality 识别质量预设。适用于大多数条码。

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


设置条码最小元素（矩阵单元或条）的大小（从 1 到无限）的识别模式。

值：条码最小元素的大小（从 1 到无穷大）：矩阵单元或条。

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


允许引擎识别具有错误校验和或错误数值的条码。该模式可用于识别文本错误的损坏条码。

Value: 允许引擎识别错误的条码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


启用方法以所选质量识别条码元素的模式。质量较低的条码元素需要更复杂的方法，从而减慢识别速度。

Value: 启用方法以所选质量识别条码元素的模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


在彩色图像上启用或禁用彩色条码的额外识别模式。

Value: 对彩色图像上彩色条码的额外识别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


去卷积（图像恢复）模式，定义图像退化的程度。最初，去卷积是一种函数，可恢复因任何自然函数（如模糊）在相机拍摄图像时导致的退化（卷积）图像。由于我们无法检测导致图像损坏的函数，只能检查最常见的函数，如 sharp 或数学形态学。

值：去卷积模式，定义图像退化的程度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


在颜色反转（亮度）图像上启用或禁用条码额外识别的模式。

值：对颜色相反的图像中的条码进行额外识别

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


与 UseMinimalXDimension 一起使用的 XDimension 的最小像素尺寸。

值：与 UseMinimalXDimension 一起使用的 XDimension 的最小像素尺寸。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


设置条码最小元素（矩阵单元或条）的大小（从 1 到无限）的识别模式。

值：条码最小元素的大小（从 1 到无穷大）：矩阵单元或条。

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
public final native void wait(long arg0)
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
| arg1 | int |  |

