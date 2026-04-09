---
title: BaseGenerationParameters
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Parámetros de generación de imágenes de códigos de barras.
type: docs
weight: 17
url: /es/androidjava/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

Parámetros de generación de imágenes de códigos de barras.
## Methods

| Method | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | Especifica los diferentes tipos de modos de dimensionado automático. |
| [getBackColor()](#getBackColor--) | Background color of the barcode image. |
| [getBarcode()](#getBarcode--) | Gets the  BarcodeParameters  that contains all barcode properties. |
| [getBorder()](#getBorder--) | Gets the  BorderParameters  that contains all configuration properties for barcode border. |
| [getCaptionAbove()](#getCaptionAbove--) | Leyenda encima de la imagen del BarCode. |
| [getCaptionBelow()](#getCaptionBelow--) | Leyenda debajo de la imagen del BarCode. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | Parámetros de imagen. |
| [getImageHeight()](#getImageHeight--) | Altura de la imagen del BarCode cuando la propiedad AutoSizeMode está establecida en AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getImageWidth--) | Ancho de la imagen del BarCode cuando la propiedad AutoSizeMode está establecida en AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getResolution--) | Obtiene la resolución de la imagen del BarCode. |
| [getRotationAngle()](#getRotationAngle--) | Ángulo de rotación de la imagen del BarCode, medido en grados, p. ej. |
| [getUseAntiAlias()](#getUseAntiAlias--) | Obtiene un valor que indica si se utiliza el modo anti-aliasing para renderizar la imagen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | Especifica los diferentes tipos de modos de dimensionado automático. |
| [setBackColor(int value)](#setBackColor-int-) | Background color of the barcode image. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | Altura de la imagen del BarCode cuando la propiedad AutoSizeMode está establecida en AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | Ancho de la imagen del BarCode cuando la propiedad AutoSizeMode está establecida en AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [setResolution(float value)](#setResolution-float-) | Establece la resolución de la imagen del BarCode. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Ángulo de rotación de la imagen del BarCode, medido en grados, p. ej. |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | Establece un valor que indica si se utiliza el modo anti-aliasing para renderizar la imagen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


Especifica los diferentes tipos de modos de dimensionado automático. Valor predeterminado: AutoSizeMode.NONE.

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public int getBackColor()
```


Color de fondo de la imagen del barcode. Valor predeterminado: Color.White. Ver Color.

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


Leyenda encima de la imagen del BarCode. Ver CaptionParameters.

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


Leyenda debajo de la imagen del BarCode. Ver CaptionParameters.

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


Parámetros de imagen. Ver.

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


Altura de la imagen del BarCode cuando la propiedad AutoSizeMode está establecida en AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


Ancho de la imagen del BarCode cuando la propiedad AutoSizeMode está establecida en AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


Obtiene la resolución de la imagen del BarCode. Un valor para ambas dimensiones. Valor predeterminado: 96 dpi.

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


Ángulo de rotación de la imagen del BarCode, medido en grados, p. ej. RotationAngle = 0 o RotationAngle = 360 significa sin rotación. Si RotationAngle NO es igual a 90, 180, 270 o 0, puede aumentar la dificultad para que el escáner lea la imagen. Valor predeterminado: 0.

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


Obtiene un valor que indica si se utiliza el modo anti-aliasing para renderizar la imagen.

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


Especifica los diferentes tipos de modos de dimensionado automático. Valor predeterminado: AutoSizeMode.NONE.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(int value) {#setBackColor-int-}
```
public void setBackColor(int value)
```


Color de fondo de la imagen del barcode. Valor predeterminado: Color.White. Ver Color.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


Altura de la imagen del BarCode cuando la propiedad AutoSizeMode está establecida en AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


Ancho de la imagen del BarCode cuando la propiedad AutoSizeMode está establecida en AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Establece la resolución de la imagen del BarCode. Un valor para ambas dimensiones. Valor predeterminado: 96 dpi.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


Ángulo de rotación de la imagen del BarCode, medido en grados, p. ej. RotationAngle = 0 o RotationAngle = 360 significa sin rotación. Si RotationAngle NO es igual a 90, 180, 270 o 0, puede aumentar la dificultad para que el escáner lea la imagen. Valor predeterminado: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


Establece un valor que indica si se utiliza el modo anti-aliasing para renderizar la imagen.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

