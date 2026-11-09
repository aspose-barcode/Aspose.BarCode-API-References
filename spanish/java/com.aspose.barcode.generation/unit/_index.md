---
title: "Unit"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Especifica el valor de tamaño en diferentes unidades Pixel Inches etc.."
type: docs
weight: 67
url: /es/java/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

Especifica el valor de tamaño en diferentes unidades (píxel, pulgadas, etc.).

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si esta instancia y un objeto especificado, que también debe ser un objeto  Unit , tienen el mismo valor. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Obtiene el valor de tamaño en unidades del documento. |
| [getInches()](#getInches--) | Obtiene el valor de tamaño en pulgadas. |
| [getMillimeters()](#getMillimeters--) | Obtiene el valor de tamaño en milímetros. |
| [getPixels()](#getPixels--) | Obtiene el valor de tamaño en píxeles. |
| [getPoint()](#getPoint--) | Obtiene el valor de tamaño en puntos. |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | Devuelve el código hash de este objeto. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | Establece el valor de tamaño en unidades del documento. |
| [setInches(float value)](#setInches-float-) | Establece el valor de tamaño en pulgadas. |
| [setMillimeters(float value)](#setMillimeters-float-) | Establece el valor de tamaño en milímetros. |
| [setPixels(float value)](#setPixels-float-) | Establece el valor de tamaño en píxeles. |
| [setPoint(float value)](#setPoint-float-) | Establece el valor de tamaño en puntos. |
| [toString()](#toString--) | Devuelve una representación de cadena legible por humanos de este  Unit . |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si esta instancia y un objeto especificado, que también debe ser un objeto  Unit , tienen el mismo valor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El  Unit  para comparar con esta instancia. |

**Returns:**
boolean - verdadero si obj es un  Unit  y su valor es el mismo que esta instancia; de lo contrario, falso. Si obj es nulo, el método devuelve falso.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public float getDocument()
```


Obtiene el valor de tamaño en unidades del documento.

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


Obtiene el valor de tamaño en pulgadas.

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


Obtiene el valor de tamaño en milímetros.

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


Obtiene el valor de tamaño en píxeles.

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


Obtiene el valor de tamaño en puntos.

**Returns:**
float
### getResolution() {#getResolution--}
```
public float getResolution()
```




**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash de este objeto.

**Returns:**
int - Un código hash entero con signo de 32 bits.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDocument(float value) {#setDocument-float-}
```
public void setDocument(float value)
```


Establece el valor de tamaño en unidades del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


Establece el valor de tamaño en pulgadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


Establece el valor de tamaño en milímetros.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


Establece el valor de tamaño en píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


Establece el valor de tamaño en puntos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### toString() {#toString--}
```
public String toString()
```


Devuelve una representación de cadena legible por humanos de este  Unit .

**Returns:**
java.lang.String - Una cadena que representa este  Unit .
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dpi | float |  |

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

