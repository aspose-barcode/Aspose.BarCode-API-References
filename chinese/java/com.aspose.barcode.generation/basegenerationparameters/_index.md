---
title: "BaseGenerationParameters"
second_title: "Aspose.BarCode for Java API Reference"
description: "条形码图像生成参数。"
type: docs
weight: 17
url: /zh/java/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

条形码图像生成参数。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | 指定自动尺寸模式的不同类型。 |
| [getBackColor()](#getBackColor--) | 条形码图像的背景颜色。 |
| [getBarcode()](#getBarcode--) | 获取包含所有条码属性的 BarcodeParameters。 |
| [getBorder()](#getBorder--) | 获取包含条码边框所有配置属性的 BorderParameters。 |
| [getCaptionAbove()](#getCaptionAbove--) | 条形码图像上方的标题。 |
| [getCaptionBelow()](#getCaptionBelow--) | 条码图像下方的标题。 |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | 图像参数。 |
| [getImageHeight()](#getImageHeight--) | 当 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 时的条码图像高度。 |
| [getImageWidth()](#getImageWidth--) | 当 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 时的条码图像宽度。 |
| [getResolution()](#getResolution--) | 获取条形码图像的分辨率。 |
| [getRotationAngle()](#getRotationAngle--) | 条形码图像的旋转角度，以度数衡量，例如。 |
| [getUseAntiAlias()](#getUseAntiAlias--) | 获取指示是否使用抗锯齿模式渲染图像的值 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | 指定自动尺寸模式的不同类型。 |
| [setBackColor(Color value)](#setBackColor-java.awt.Color-) | 条形码图像的背景颜色。 |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | 当 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 时的条码图像高度。 |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | 当 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 时的条码图像宽度。 |
| [setResolution(float value)](#setResolution-float-) | 设置条形码图像的分辨率。 |
| [setRotationAngle(float value)](#setRotationAngle-float-) | 条形码图像的旋转角度，以度数衡量，例如。 |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | 设置指示是否使用抗锯齿模式渲染图像的值 |
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
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


指定自动大小模式的不同类型。默认值：AutoSizeMode.NONE。

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public Color getBackColor()
```


条形码图像的背景颜色。默认值：Color.White。参见 Color。

**Returns:**
java.awt.Color
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


获取包含所有条码属性的 BarcodeParameters。

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


获取包含条码边框所有配置属性的 BorderParameters。

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


条码图像上方的标题。参见 CaptionParameters。

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


条码图像下方的标题。参见 CaptionParameters。

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getImage() {#getImage--}
```
public ImageParameters getImage()
```


图像参数。参见。

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


当 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 时的条码图像高度。

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


当 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 时的条码图像宽度。

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


获取 BarCode 图像的分辨率。两个维度使用相同的值。默认值：96 dpi。

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


条码图像的旋转角度，以度为单位，例如 RotationAngle = 0 或 RotationAngle = 360 表示不旋转。如果 RotationAngle 不等于 90、180、270 或 0，可能会增加扫描仪读取图像的难度。默认值：0。

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Returns:**
float
### getUseAntiAlias() {#getUseAntiAlias--}
```
public boolean getUseAntiAlias()
```


获取指示是否使用抗锯齿模式渲染图像的值

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setAutoSizeMode(AutoSizeMode value) {#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-}
```
public void setAutoSizeMode(AutoSizeMode value)
```


指定自动大小模式的不同类型。默认值：AutoSizeMode.NONE。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(Color value) {#setBackColor-java.awt.Color-}
```
public void setBackColor(Color value)
```


条形码图像的背景颜色。默认值：Color.White。参见 Color。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Color |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


当 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 时的条码图像高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


当 AutoSizeMode 属性设置为 AutoSizeMode.NEAREST 或 AutoSizeMode.INTERPOLATION 时的条码图像宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


设置条码图像的分辨率。两个维度使用相同的值。默认值：96 dpi。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


条码图像的旋转角度，以度为单位，例如 RotationAngle = 0 或 RotationAngle = 360 表示不旋转。如果 RotationAngle 不等于 90、180、270 或 0，可能会增加扫描仪读取图像的难度。默认值：0。

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


设置指示是否使用抗锯齿模式渲染图像的值

**Parameters:**
| 参数 | 类型 | 描述 |
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

