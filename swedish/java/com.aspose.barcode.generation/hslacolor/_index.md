---
title: "HslaColor"
second_title: "Aspose.BarCode för Java API-referens"
description: "Klass för att representera HSLA-färgen Hue Saturation Lightness Alpha"
type: docs
weight: 49
url: /sv/java/com.aspose.barcode.generation/hslacolor/
---
**Inheritance:**
java.lang.Object
```
public class HslaColor
```

Klass för att representera HSLA-färg (Hue, Saturation, Lightness, Alpha)
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [HslaColor(int h, int s, int l, float a)](#HslaColor-int-int-int-float-) | Konstruktor för HslaColor |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [A](#A) | Alpha (opacitet) [0.0f, 1.0f] |
| [H](#H) | Nyans [0, 360] |
| [L](#L) | Ljusstyrka [0, 100] |
| [S](#S) | Mättnad [0, 100] |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [convertHslaToRgba(HslaColor hslaColor)](#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-) | Använder https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB |
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


Konstruktor för HslaColor

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| h | int | Nyans [0, 360] |
| s | int | Mättnad [0, 100] |
| l | int | Ljusstyrka [0, 100] |
| a | float | Alpha (opacitet) [0.0f, 1.0f] |

### A {#A}
```
public float A
```


Alpha (opacitet) [0.0f, 1.0f]

### H {#H}
```
public final int H
```


Nyans [0, 360]

### L {#L}
```
public final int L
```


Ljusstyrka [0, 100]

### S {#S}
```
public final int S
```


Mättnad [0, 100]

### convertHslaToRgba(HslaColor hslaColor) {#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-}
```
public static Color convertHslaToRgba(HslaColor hslaColor)
```


Använder https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hslaColor | [HslaColor](../../com.aspose.barcode.generation/hslacolor) | HSLA-färg att konvertera |

**Returns:**
java.awt.Color - Färg med RGBA-värden
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

