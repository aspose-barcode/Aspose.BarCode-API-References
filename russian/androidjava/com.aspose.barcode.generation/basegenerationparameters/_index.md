---
title: "BaseGenerationParameters"
second_title: "Справочник API Aspose.BarCode для Android через Java"
description: "Параметры генерации изображений штрихкода."
type: docs
weight: 17
url: /ru/androidjava/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

Параметры генерации изображений штрихкода.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | Указывает различные типы режимов автоматического масштабирования. |
| [getBackColor()](#getBackColor--) | Фоновый цвет изображения штрихкода. |
| [getBarcode()](#getBarcode--) | Получает  BarcodeParameters  , содержащий все свойства штрихкода. |
| [getBorder()](#getBorder--) | Получает  BorderParameters  , содержащий все свойства конфигурации границы штрихкода. |
| [getCaptionAbove()](#getCaptionAbove--) | Подпись над изображением штрихкода. |
| [getCaptionBelow()](#getCaptionBelow--) | Подпись под изображением штрихкода. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | Параметры изображения. |
| [getImageHeight()](#getImageHeight--) | Высота изображения штрихкода, когда свойство  AutoSizeMode  установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getImageWidth--) | Ширина изображения штрихкода, когда свойство  AutoSizeMode  установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getResolution--) | Получает разрешение изображения штрихкода. |
| [getRotationAngle()](#getRotationAngle--) | Угол поворота изображения штрихкода, измеряется в градусах, например. |
| [getUseAntiAlias()](#getUseAntiAlias--) | Получает значение, указывающее, используется ли режим сглаживания при рендеринге изображения |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | Указывает различные типы режимов автоматического масштабирования. |
| [setBackColor(int value)](#setBackColor-int-) | Фоновый цвет изображения штрихкода. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | Высота изображения штрихкода, когда свойство  AutoSizeMode  установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | Ширина изображения штрихкода, когда свойство  AutoSizeMode  установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. |
| [setResolution(float value)](#setResolution-float-) | Устанавливает разрешение изображения штрихкода. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Угол поворота изображения штрихкода, измеряется в градусах, например. |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | Устанавливает значение, указывающее, используется ли режим сглаживания при рендеринге изображения |
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


Фоновый цвет изображения штрихкода. Значение по умолчанию: Color.White. См.  Color .

**Returns:**
int
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


Получает  BarcodeParameters  , содержащий все свойства штрихкода.

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


Получает  BorderParameters  , содержащий все свойства конфигурации границы штрихкода.

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


Подпись над изображением штрихкода. См.  CaptionParameters .

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


Подпись под изображением штрихкода. См.  CaptionParameters .

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


Параметры изображения. См. .

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


Высота изображения штрихкода, когда свойство  AutoSizeMode  установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


Ширина изображения штрихкода, когда свойство  AutoSizeMode  установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


Получает разрешение изображения штрихкода. Одно значение для обеих измерений. Значение по умолчанию: 96 dpi.

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


Угол поворота изображения штрихкода, измеряется в градусах, например RotationAngle = 0 или RotationAngle = 360 означает отсутствие вращения. Если RotationAngle НЕ равен 90, 180, 270 или 0, это может усложнить сканеру чтение изображения. Значение по умолчанию: 0.

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


Получает значение, указывающее, используется ли режим сглаживания при рендеринге изображения

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


Указывает различные типы режимов автоматического масштабирования. Значение по умолчанию: AutoSizeMode.NONE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(int value) {#setBackColor-int-}
```
public void setBackColor(int value)
```


Фоновый цвет изображения штрихкода. Значение по умолчанию: Color.White. См.  Color .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


Высота изображения штрихкода, когда свойство  AutoSizeMode  установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


Ширина изображения штрихкода, когда свойство  AutoSizeMode  установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Устанавливает разрешение изображения штрихкода. Одно значение для обеих измерений. Значение по умолчанию: 96 dpi.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


Угол поворота изображения штрихкода, измеряется в градусах, например RotationAngle = 0 или RotationAngle = 360 означает отсутствие вращения. Если RotationAngle НЕ равен 90, 180, 270 или 0, это может усложнить сканеру чтение изображения. Значение по умолчанию: 0.

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


Устанавливает значение, указывающее, используется ли режим сглаживания при рендеринге изображения

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

