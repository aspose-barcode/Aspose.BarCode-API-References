---
title: "HslaColor"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Clase para representar el color HSLA Hue Saturation Lightness Alpha"
type: docs
weight: 49
url: /es/java/com.aspose.barcode.generation/hslacolor/
---
**Inheritance:**
java.lang.Object
```
public class HslaColor
```

Clase para representar color HSLA (Matiz, Saturación, Luminosidad, Alfa)
## Constructores

| Constructor | Descripción |
| --- | --- |
| [HslaColor(int h, int s, int l, float a)](#HslaColor-int-int-int-float-) | Constructor de HslaColor |
## Campos

| Campo | Descripción |
| --- | --- |
| [A](#A) | Alpha (opacidad) [0.0f, 1.0f] |
| [H](#H) | Matiz [0, 360] |
| [L](#L) | Luminosidad [0, 100] |
| [S](#S) | Saturación [0, 100] |
## Métodos

| Método | Descripción |
| --- | --- |
| [convertHslaToRgba(HslaColor hslaColor)](#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-) | Utiliza https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HslaColor(int h, int s, int l, float a) {#HslaColor-int-int-int-float-}
```
public HslaColor(int h, int s, int l, float a)
```


Constructor de HslaColor

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| h | int | Matiz [0, 360] |
| s | int | Saturación [0, 100] |
| l | int | Luminosidad [0, 100] |
| a | float | Alpha (opacidad) [0.0f, 1.0f] |

### A {#A}
```
public float A
```


Alpha (opacidad) [0.0f, 1.0f]

### H {#H}
```
public final int H
```


Matiz [0, 360]

### L {#L}
```
public final int L
```


Luminosidad [0, 100]

### S {#S}
```
public final int S
```


Saturación [0, 100]

### convertHslaToRgba(HslaColor hslaColor) {#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-}
```
public static Color convertHslaToRgba(HslaColor hslaColor)
```


Utiliza https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hslaColor | [HslaColor](../../com.aspose.barcode.generation/hslacolor) | Color HSLA a convertir |

**Returns:**
java.awt.Color - Color con valores RGBA
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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

