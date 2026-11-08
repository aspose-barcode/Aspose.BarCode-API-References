---
title: "HslaColor"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "Klasse zur Darstellung der HSLA-Farbe Hue Saturation Lightness Alpha"
type: docs
weight: 49
url: /de/java/com.aspose.barcode.generation/hslacolor/
---
**Inheritance:**
java.lang.Object
```
public class HslaColor
```

Klasse zur Darstellung von HSLA-Farben (Farbton, Sättigung, Helligkeit, Alpha)
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HslaColor(int h, int s, int l, float a)](#HslaColor-int-int-int-float-) | Konstruktor für HslaColor |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [A](#A) | Alpha (Transparenz) [0.0f, 1.0f] |
| [H](#H) | Farbton [0, 360] |
| [L](#L) | Helligkeit [0, 100] |
| [S](#S) | Sättigung [0, 100] |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [convertHslaToRgba(HslaColor hslaColor)](#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-) | Verwendet https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB |
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


Konstruktor für HslaColor

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| h | int | Farbton [0, 360] |
| s | int | Sättigung [0, 100] |
| l | int | Helligkeit [0, 100] |
| a | float | Alpha (Transparenz) [0.0f, 1.0f] |

### A {#A}
```
public float A
```


Alpha (Transparenz) [0.0f, 1.0f]

### H {#H}
```
public final int H
```


Farbton [0, 360]

### L {#L}
```
public final int L
```


Helligkeit [0, 100]

### S {#S}
```
public final int S
```


Sättigung [0, 100]

### convertHslaToRgba(HslaColor hslaColor) {#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-}
```
public static Color convertHslaToRgba(HslaColor hslaColor)
```


Verwendet https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hslaColor | [HslaColor](../../com.aspose.barcode.generation/hslacolor) | HSLA-Farbe zum Konvertieren |

**Returns:**
java.awt.Color - Farbe mit RGBA-Werten
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolesch
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

