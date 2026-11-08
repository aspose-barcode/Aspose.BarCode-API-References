---
title: "BaseGenerationParameters"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "معلمات توليد صورة الباركود."
type: docs
weight: 17
url: /ar/java/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

معلمات توليد صورة الباركود.
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | يحدد الأنواع المختلفة لأوضاع التحجيم التلقائي. |
| [getBackColor()](#getBackColor--) | لون الخلفية لصورة الباركود. |
| [getBarcode()](#getBarcode--) | يحصل على BarcodeParameters التي تحتوي على جميع خصائص الباركود. |
| [getBorder()](#getBorder--) | يحصل على BorderParameters التي تحتوي على جميع خصائص التكوين لإطار الباركود. |
| [getCaptionAbove()](#getCaptionAbove--) | التسمية أعلى صورة الباركود. |
| [getCaptionBelow()](#getCaptionBelow--) | التسمية التوضيحية أسفل صورة BarCode. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | معلمات الصورة. |
| [getImageHeight()](#getImageHeight--) | ارتفاع صورة BarCode عندما تكون خاصية AutoSizeMode مضبوطة على AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getImageWidth--) | عرض صورة BarCode عندما تكون خاصية AutoSizeMode مضبوطة على AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getResolution--) | يحصل على دقة صورة الباركود. |
| [getRotationAngle()](#getRotationAngle--) | زاوية دوران صورة الباركود، مقاسة بالدرجة، مثال. |
| [getUseAntiAlias()](#getUseAntiAlias--) | يحصل على قيمة تشير إلى ما إذا تم استخدام وضع مضاد التعرجات لتصيير الصورة |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | يحدد الأنواع المختلفة لأوضاع التحجيم التلقائي. |
| [setBackColor(Color value)](#setBackColor-java.awt.Color-) | لون الخلفية لصورة الباركود. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | ارتفاع صورة BarCode عندما تكون خاصية AutoSizeMode مضبوطة على AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | عرض صورة BarCode عندما تكون خاصية AutoSizeMode مضبوطة على AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. |
| [setResolution(float value)](#setResolution-float-) | يضبط دقة صورة الباركود. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | زاوية دوران صورة الباركود، مقاسة بالدرجة، مثال. |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | يضبط قيمة تشير إلى ما إذا كان يتم استخدام وضع مضاد التعرج لتصوير الصورة |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
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
public Color getBackColor()
```


لون الخلفية لصورة الباركود. القيمة الافتراضية: Color.White. راجع Color.

**Returns:**
java.awt.Color
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


يحصل على BarcodeParameters التي تحتوي على جميع خصائص الباركود.

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


يحصل على BorderParameters التي تحتوي على جميع خصائص التكوين لإطار الباركود.

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


التسمية التوضيحية فوق صورة الباركود. راجع CaptionParameters.

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


التسمية التوضيحية أسفل صورة الباركود. راجع CaptionParameters.

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


ارتفاع صورة BarCode عندما تكون خاصية AutoSizeMode مضبوطة على AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


عرض صورة BarCode عندما تكون خاصية AutoSizeMode مضبوطة على AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


يحصل على دقة صورة الباركود. قيمة واحدة لكلا البعدين. القيمة الافتراضية: 96 dpi.

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


زاوية دوران صورة الباركود، مقاسة بالدرجة، مثال: RotationAngle = 0 أو RotationAngle = 360 يعني عدم وجود دوران. إذا لم تكن RotationAngle مساوية لـ 90 أو 180 أو 270 أو 0، قد يزيد ذلك من صعوبة قراءة الصورة بواسطة الماسح. القيمة الافتراضية: 0.

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


يحصل على قيمة تشير إلى ما إذا تم استخدام وضع مضاد التعرجات لتصيير الصورة

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


يحدد الأنواع المختلفة لأوضاع التحجيم التلقائي. القيمة الافتراضية: AutoSizeMode.NONE.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(Color value) {#setBackColor-java.awt.Color-}
```
public void setBackColor(Color value)
```


لون الخلفية لصورة الباركود. القيمة الافتراضية: Color.White. راجع Color.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.awt.Color |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


ارتفاع صورة BarCode عندما تكون خاصية AutoSizeMode مضبوطة على AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


عرض صورة BarCode عندما تكون خاصية AutoSizeMode مضبوطة على AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


يضبط دقة صورة الباركود. قيمة واحدة لكلا البعدين. القيمة الافتراضية: 96 نقطة في البوصة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


زاوية دوران صورة الباركود، مقاسة بالدرجة، مثال: RotationAngle = 0 أو RotationAngle = 360 يعني عدم وجود دوران. إذا لم تكن RotationAngle مساوية لـ 90 أو 180 أو 270 أو 0، قد يزيد ذلك من صعوبة قراءة الصورة بواسطة الماسح. القيمة الافتراضية: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان يتم استخدام وضع مضاد التعرج لتصوير الصورة

**Parameters:**
| معامل | النوع | الوصف |
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
public final native void wait(long arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

