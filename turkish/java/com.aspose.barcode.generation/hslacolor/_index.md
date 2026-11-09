---
title: "HslaColor"
second_title: "Aspose.BarCode for Java API Referansı"
description: "HSLA rengi Hue Saturation Lightness Alpha temsil eden sınıf"
type: docs
weight: 49
url: /tr/java/com.aspose.barcode.generation/hslacolor/
---
**Inheritance:**
java.lang.Object
```
public class HslaColor
```

HSLA rengini (Ton, Doygunluk, Açıklık, Alfa) temsil eden sınıf
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HslaColor(int h, int s, int l, float a)](#HslaColor-int-int-int-float-) | HslaColor için yapıcı |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [A](#A) | Alfa (opaklık) [0.0f, 1.0f] |
| [H](#H) | Ton [0, 360] |
| [L](#L) | Açıklık [0, 100] |
| [S](#S) | Doygunluk [0, 100] |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [convertHslaToRgba(HslaColor hslaColor)](#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-) | Kullanır https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB |
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


HslaColor için yapıcı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| h | int | Ton [0, 360] |
| s | int | Doygunluk [0, 100] |
| l | int | Açıklık [0, 100] |
| a | float | Alfa (opaklık) [0.0f, 1.0f] |

### A {#A}
```
public float A
```


Alfa (opaklık) [0.0f, 1.0f]

### H {#H}
```
public final int H
```


Ton [0, 360]

### L {#L}
```
public final int L
```


Açıklık [0, 100]

### S {#S}
```
public final int S
```


Doygunluk [0, 100]

### convertHslaToRgba(HslaColor hslaColor) {#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-}
```
public static Color convertHslaToRgba(HslaColor hslaColor)
```


Kullanır https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hslaColor | [HslaColor](../../com.aspose.barcode.generation/hslacolor) | Dönüştürülecek HSLA rengi |

**Returns:**
java.awt.Color - RGBA değerlerine sahip renk
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

