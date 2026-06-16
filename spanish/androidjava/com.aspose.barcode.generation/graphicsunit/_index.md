---
title: GraphicsUnit
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Especifica la unidad de medida para los datos proporcionados.
type: docs
weight: 88
url: /es/androidjava/com.aspose.barcode.generation/graphicsunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum GraphicsUnit extends Enum<GraphicsUnit>
```

Especifica la unidad de medida para los datos proporcionados.
## Campos

| Campo | Descripción |
| --- | --- |
| [DISPLAY](#DISPLAY) | Especifica la unidad de medida del dispositivo de pantalla. |
| [DOCUMENT](#DOCUMENT) | Especifica la unidad de documento (1/300 de pulgada) como la unidad de medida. |
| [INCH](#INCH) | Especifica la pulgada como la unidad de medida. |
| [MILLIMETER](#MILLIMETER) | Especifica el milímetro como la unidad de medida. |
| [PIXEL](#PIXEL) | Especifica un píxel del dispositivo como la unidad de medida. |
| [POINT](#POINT) | Especifica el punto de una impresora (1/72 de pulgada) como la unidad de medida. |
| [WORLD](#WORLD) | Especifica la unidad del sistema de coordenadas mundial como la unidad de medida. |
## Methods

| Method | Descripción |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getGraphicsUnitName(int graphicsUnit)](#getGraphicsUnitName-int-) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DISPLAY {#DISPLAY}
```
public static final GraphicsUnit DISPLAY
```


Especifica la unidad de medida del dispositivo de pantalla. Normalmente píxeles para pantallas de video y 1/100 de pulgada para impresoras.

### DOCUMENT {#DOCUMENT}
```
public static final GraphicsUnit DOCUMENT
```


Especifica la unidad de documento (1/300 de pulgada) como la unidad de medida.

### INCH {#INCH}
```
public static final GraphicsUnit INCH
```


Especifica la pulgada como la unidad de medida.

### MILLIMETER {#MILLIMETER}
```
public static final GraphicsUnit MILLIMETER
```


Especifica el milímetro como la unidad de medida.

### PIXEL {#PIXEL}
```
public static final GraphicsUnit PIXEL
```


Especifica un píxel del dispositivo como la unidad de medida.

### POINT {#POINT}
```
public static final GraphicsUnit POINT
```


Especifica el punto de una impresora (1/72 de pulgada) como la unidad de medida.

### WORLD {#WORLD}
```
public static final GraphicsUnit WORLD
```


Especifica la unidad del sistema de coordenadas mundial como la unidad de medida.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getGraphicsUnitName(int graphicsUnit) {#getGraphicsUnitName-int-}
```
public static String getGraphicsUnitName(int graphicsUnit)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| graphicsUnit | int |  |

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static GraphicsUnit valueOf(String name)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[GraphicsUnit](../../com.aspose.barcode.generation/graphicsunit)
### values() {#values--}
```
public static GraphicsUnit[] values()
```




**Returns:**
com.aspose.barcode.generation.GraphicsUnit[]
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

