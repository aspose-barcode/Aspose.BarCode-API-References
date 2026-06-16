---
title: BaseGenerationParameters
second_title: Справочник API Aspose.BarCode для Android через Java
description: Параметры генерации изображения штрихкода.
type: docs
weight: 17
url: /ru/androidjava/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

Параметры генерации изображения штрихкода.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | Указывает различные типы режимов автоматического масштабирования. |
| [getBackColor()](#getBackColor--) | Background color of the barcode image. |
| [getBarcode()](#getBarcode--) | Gets the  BarcodeParameters  that contains all barcode properties. |
| [getBorder()](#getBorder--) | Gets the  BorderParameters  that contains all configuration properties for barcode border. |
| [getCaptionAbove()](#getCaptionAbove--) | Подпись над изображением BarCode. |
| [getCaptionBelow()](#getCaptionBelow--) | Подпись под изображением BarCode. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | Параметры изображения. |
| [getImageHeight()](#getImageHeight--) | Высота изображения BarCode, когда свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getImageWidth--) | Ширина изображения BarCode, когда свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getResolution--) | Получает разрешение изображения BarCode. |
| [getRotationAngle()](#getRotationAngle--) | Угол поворота изображения BarCode, измеряемый в градусах, например. |
| [getUseAntiAlias()](#getUseAntiAlias--) | Получает значение, указывающее, используется ли режим anti-aliasing для рендеринга изображения. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | Указывает различные типы режимов автоматического масштабирования. |
| [setBackColor(int value)](#setBackColor-int-) | Background color of the barcode image. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | Высота изображения BarCode, когда свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | Ширина изображения BarCode, когда свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. |
| [setResolution(float value)](#setResolution-float-) | Устанавливает разрешение изображения BarCode. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Угол поворота изображения BarCode, измеряемый в градусах, например. |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | Устанавливает значение, указывающее, используется ли режим anti-aliasing для рендеринга изображения. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


Указывает различные типы режимов автоматического масштабирования. Значение по умолчанию: AutoSizeMode.NONE.

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public int getBackColor()
```


Цвет фона изображения штрихкода. Значение по умолчанию: Color.White. См. Color.

**Returns:**
int
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


Gets the  BarcodeParameters  that contains all barcode properties.

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


Gets the  BorderParameters  that contains all configuration properties for barcode border.

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


Подпись над изображением BarCode. См. CaptionParameters.

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


Подпись под изображением BarCode. См. CaptionParameters.

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


Параметры изображения. См.

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


Высота изображения BarCode, когда свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


Ширина изображения BarCode, когда свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


Получает разрешение изображения BarCode. Одно значение для обеих измерений. Значение по умолчанию: 96 dpi.

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


Угол поворота изображения BarCode, измеряемый в градусах, например RotationAngle = 0 или RotationAngle = 360 означает отсутствие вращения. Если RotationAngle НЕ равен 90, 180, 270 или 0, это может усложнить сканеру чтение изображения. Значение по умолчанию: 0.

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


Получает значение, указывающее, используется ли режим anti-aliasing для рендеринга изображения.

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


Указывает различные типы режимов автоматического масштабирования. Значение по умолчанию: AutoSizeMode.NONE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(int value) {#setBackColor-int-}
```
public void setBackColor(int value)
```


Цвет фона изображения штрихкода. Значение по умолчанию: Color.White. См. Color.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


Высота изображения BarCode, когда свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


Ширина изображения BarCode, когда свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Устанавливает разрешение изображения BarCode. Одно значение для обеих измерений. Значение по умолчанию: 96 dpi.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


Угол поворота изображения BarCode, измеряемый в градусах, например RotationAngle = 0 или RotationAngle = 360 означает отсутствие вращения. Если RotationAngle НЕ равен 90, 180, 270 или 0, это может усложнить сканеру чтение изображения. Значение по умолчанию: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


Устанавливает значение, указывающее, используется ли режим anti-aliasing для рендеринга изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

