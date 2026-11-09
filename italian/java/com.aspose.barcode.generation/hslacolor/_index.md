---
title: "HslaColor"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Classe per rappresentare il colore HSLA Hue Saturation Lightness Alpha"
type: docs
weight: 49
url: /it/java/com.aspose.barcode.generation/hslacolor/
---
**Inheritance:**
java.lang.Object
```
public class HslaColor
```

Classe per rappresentare il colore HSLA (Tonalità, Saturazione, Luminosità, Alpha)
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HslaColor(int h, int s, int l, float a)](#HslaColor-int-int-int-float-) | Costruttore per HslaColor |
## Campi

| Campo | Descrizione |
| --- | --- |
| [A](#A) | Alpha (opacità) [0.0f, 1.0f] |
| [H](#H) | Tonalità [0, 360] |
| [L](#L) | Luminosità [0, 100] |
| [S](#S) | Saturazione [0, 100] |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [convertHslaToRgba(HslaColor hslaColor)](#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-) | Utilizza https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB |
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


Costruttore per HslaColor

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| h | int | Tonalità [0, 360] |
| s | int | Saturazione [0, 100] |
| l | int | Luminosità [0, 100] |
| a | float | Alpha (opacità) [0.0f, 1.0f] |

### A {#A}
```
public float A
```


Alpha (opacità) [0.0f, 1.0f]

### H {#H}
```
public final int H
```


Tonalità [0, 360]

### L {#L}
```
public final int L
```


Luminosità [0, 100]

### S {#S}
```
public final int S
```


Saturazione [0, 100]

### convertHslaToRgba(HslaColor hslaColor) {#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-}
```
public static Color convertHslaToRgba(HslaColor hslaColor)
```


Utilizza https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hslaColor | [HslaColor](../../com.aspose.barcode.generation/hslacolor) | Colore HSLA da convertire |

**Returns:**
java.awt.Color - Colore con valori RGBA
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

