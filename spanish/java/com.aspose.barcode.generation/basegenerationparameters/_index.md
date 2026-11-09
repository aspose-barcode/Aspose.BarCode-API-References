---
title: "BaseGenerationParameters"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Parámetros de generación de imágenes de códigos de barras."
type: docs
weight: 17
url: /es/java/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

Parámetros de generación de imágenes de códigos de barras.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | Especifica los diferentes tipos de modos de dimensionado automático. |
| [getBackColor()](#getBackColor--) | Color de fondo de la imagen del código de barras. |
| [getBarcode()](#getBarcode--) | Obtiene los  BarcodeParameters  que contienen todas las propiedades del código de barras. |
| [getBorder()](#getBorder--) | Obtiene los  BorderParameters  que contienen todas las propiedades de configuración del borde del código de barras. |
| [getCaptionAbove()](#getCaptionAbove--) | Título encima de la imagen del código de barras. |
| [getCaptionBelow()](#getCaptionBelow--) | Subtítulo debajo de la imagen del BarCode. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | Parámetros de imagen. |
| [getImageHeight()](#getImageHeight--) | Altura de la imagen del BarCode cuando la propiedad AutoSizeMode está configurada a AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getImageWidth--) | Anchura de la imagen del BarCode cuando la propiedad AutoSizeMode está configurada a AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getResolution--) | Obtiene la resolución de la imagen del código de barras. |
| [getRotationAngle()](#getRotationAngle--) | Ángulo de rotación de la imagen del código de barras, medido en grados, p.ej. |
| [getUseAntiAlias()](#getUseAntiAlias--) | Obtiene un valor que indica si se utiliza el modo anti-aliasing para renderizar la imagen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | Especifica los diferentes tipos de modos de dimensionado automático. |
| [setBackColor(Color value)](#setBackColor-java.awt.Color-) | Color de fondo de la imagen del código de barras. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | Altura de la imagen del BarCode cuando la propiedad AutoSizeMode está configurada a AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | Anchura de la imagen del BarCode cuando la propiedad AutoSizeMode está configurada a AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [setResolution(float value)](#setResolution-float-) | Establece la resolución de la imagen del código de barras. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Ángulo de rotación de la imagen del código de barras, medido en grados, p.ej. |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | Establece un valor que indica si se utiliza el modo de antialiasing para renderizar la imagen |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
public Color getBackColor()
```


Color de fondo de la imagen del código de barras. Valor predeterminado: Color.White. Ver  Color .

**Returns:**
java.awt.Color
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


Obtiene los  BarcodeParameters  que contienen todas las propiedades del código de barras.

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


Obtiene los  BorderParameters  que contienen todas las propiedades de configuración del borde del código de barras.

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


Leyenda encima de la imagen del código de barras. Ver  CaptionParameters .

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


Leyenda debajo de la imagen del código de barras. Ver  CaptionParameters .

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


Parámetros de imagen. Ver .

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


Altura de la imagen del BarCode cuando la propiedad AutoSizeMode está configurada a AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


Anchura de la imagen del BarCode cuando la propiedad AutoSizeMode está configurada a AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


Obtiene la resolución de la imagen BarCode. Un valor para ambas dimensiones. Valor predeterminado: 96 dpi.

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


Ángulo de rotación de la imagen del código de barras, medido en grados, p. ej. RotationAngle = 0 o RotationAngle = 360 significa sin rotación. Si RotationAngle NO es igual a 90, 180, 270 o 0, puede aumentar la dificultad para que el escáner lea la imagen. Valor predeterminado: 0.

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


Especifica los diferentes tipos de modos de dimensionado automático. Valor predeterminado: AutoSizeMode.NONE.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(Color value) {#setBackColor-java.awt.Color-}
```
public void setBackColor(Color value)
```


Color de fondo de la imagen del código de barras. Valor predeterminado: Color.White. Ver  Color .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.Color |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


Altura de la imagen del BarCode cuando la propiedad AutoSizeMode está configurada a AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


Anchura de la imagen del BarCode cuando la propiedad AutoSizeMode está configurada a AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Establece la resolución de la imagen del código de barras. Un valor para ambas dimensiones. Valor predeterminado: 96 ppp.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


Ángulo de rotación de la imagen del código de barras, medido en grados, p. ej. RotationAngle = 0 o RotationAngle = 360 significa sin rotación. Si RotationAngle NO es igual a 90, 180, 270 o 0, puede aumentar la dificultad para que el escáner lea la imagen. Valor predeterminado: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


Establece un valor que indica si se utiliza el modo de antialiasing para renderizar la imagen

**Parameters:**
| Parámetro | Tipo | Descripción |
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
public final native void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

