---
title: BaseGenerationParameters
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: معلمات توليد صورة الباركود.
type: docs
weight: 17
url: /ar/androidjava/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

معلمات توليد صورة الباركود.
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | يحدد الأنواع المختلفة لأوضاع التحجيم التلقائي. |
| [getBackColor()](#getBackColor--) | لون الخلفية لصورة الباركود. |
| [getBarcode()](#getBarcode--) | يحصل على  BarcodeParameters  التي تحتوي على جميع خصائص الباركود. |
| [getBorder()](#getBorder--) | يحصل على  BorderParameters  التي تحتوي على جميع خصائص التكوين لحدود الباركود. |
| [getCaptionAbove()](#getCaptionAbove--) | التسمية التوضيحية فوق صورة BarCode. |
| [getCaptionBelow()](#getCaptionBelow--) | التسمية التوضيحية أسفل صورة BarCode. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | معلمات الصورة. |
| [getImageHeight()](#getImageHeight--) | ارتفاع صورة BarCode عندما يتم تعيين خاصية AutoSizeMode إلى AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getImageWidth--) | عرض صورة BarCode عندما يتم تعيين خاصية AutoSizeMode إلى AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getResolution--) | يحصل على دقة صورة BarCode. |
| [getRotationAngle()](#getRotationAngle--) | زاوية دوران صورة BarCode، مقاسة بالدرجة، على سبيل المثال. |
| [getUseAntiAlias()](#getUseAntiAlias--) | يحصل على قيمة تشير إلى ما إذا كان يتم استخدام وضع مضاد التعرجات لتصيير الصورة. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | يحدد الأنواع المختلفة لأوضاع التحجيم التلقائي. |
| [setBackColor(int value)](#setBackColor-int-) | لون الخلفية لصورة الباركود. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | ارتفاع صورة BarCode عندما يتم تعيين خاصية AutoSizeMode إلى AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | عرض صورة BarCode عندما يتم تعيين خاصية AutoSizeMode إلى AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. |
| [setResolution(float value)](#setResolution-float-) | يضبط دقة صورة BarCode. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | زاوية دوران صورة BarCode، مقاسة بالدرجة، على سبيل المثال. |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | يضبط قيمة تشير إلى ما إذا كان يتم استخدام وضع مضاد التعرجات لتصيير الصورة. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


يحدد الأنواع المختلفة لأوضاع التحجيم التلقائي. القيمة الافتراضية: AutoSizeMode.NONE.

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public int getBackColor()
```


لون الخلفية لصورة barcode. القيمة الافتراضية: Color.White. راجع Color.

**Returns:**
int
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


يحصل على  BarcodeParameters  التي تحتوي على جميع خصائص الباركود.

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


يحصل على  BorderParameters  التي تحتوي على جميع خصائص التكوين لحدود الباركود.

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


التسمية التوضيحية فوق صورة BarCode. راجع CaptionParameters.

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


التسمية التوضيحية أسفل صورة BarCode. راجع CaptionParameters.

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


معلمات الصورة. راجع .

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


ارتفاع صورة BarCode عندما يتم تعيين خاصية AutoSizeMode إلى AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


عرض صورة BarCode عندما يتم تعيين خاصية AutoSizeMode إلى AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


يحصل على دقة صورة BarCode. قيمة واحدة لكلا البعدين. القيمة الافتراضية: 96 dpi.

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


زاوية دوران صورة BarCode، مقاسة بالدرجة، على سبيل المثال RotationAngle = 0 أو RotationAngle = 360 تعني عدم وجود دوران. إذا لم تكن RotationAngle مساوية لـ 90 أو 180 أو 270 أو 0، قد يزيد ذلك من صعوبة قراءة الماسح الضوئي للصورة. القيمة الافتراضية: 0.

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


يحصل على قيمة تشير إلى ما إذا كان يتم استخدام وضع مضاد التعرجات لتصيير الصورة.

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




### setAutoSizeMode(AutoSizeMode value) {#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-}
```
public void setAutoSizeMode(AutoSizeMode value)
```


يحدد الأنواع المختلفة لأوضاع التحجيم التلقائي. القيمة الافتراضية: AutoSizeMode.NONE.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(int value) {#setBackColor-int-}
```
public void setBackColor(int value)
```


لون الخلفية لصورة barcode. القيمة الافتراضية: Color.White. راجع Color.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


ارتفاع صورة BarCode عندما يتم تعيين خاصية AutoSizeMode إلى AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


عرض صورة BarCode عندما يتم تعيين خاصية AutoSizeMode إلى AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


يضبط دقة صورة BarCode. قيمة واحدة لكلا البعدين. القيمة الافتراضية: 96 dpi.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


زاوية دوران صورة BarCode، مقاسة بالدرجة، على سبيل المثال RotationAngle = 0 أو RotationAngle = 360 تعني عدم وجود دوران. إذا لم تكن RotationAngle مساوية لـ 90 أو 180 أو 270 أو 0، قد يزيد ذلك من صعوبة قراءة الماسح الضوئي للصورة. القيمة الافتراضية: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان يتم استخدام وضع مضاد التعرجات لتصيير الصورة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

