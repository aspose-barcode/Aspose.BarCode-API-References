---
title: "HslaColor"
second_title: "Aspose.BarCode για Java Αναφορά API"
description: "Κλάση για την αναπαράσταση του χρώματος HSLA Hue Saturation Lightness Alpha"
type: docs
weight: 49
url: /el/java/com.aspose.barcode.generation/hslacolor/
---
**Inheritance:**
java.lang.Object
```
public class HslaColor
```

Κλάση για την αναπαράσταση χρώματος HSLA (Hue, Saturation, Lightness, Alpha).
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [HslaColor(int h, int s, int l, float a)](#HslaColor-int-int-int-float-) | Κατασκευαστής για HslaColor |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [A](#A) | Alpha (διαφάνεια) [0.0f, 1.0f] |
| [H](#H) | Απόχρωση [0, 360] |
| [L](#L) | Φωτεινότητα [0, 100] |
| [S](#S) | Κορεσμός [0, 100] |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [convertHslaToRgba(HslaColor hslaColor)](#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-) | Χρησιμοποιεί https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB |
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


Κατασκευαστής για HslaColor

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| h | int | Απόχρωση [0, 360] |
| s | int | Κορεσμός [0, 100] |
| l | int | Φωτεινότητα [0, 100] |
| a | float | Alpha (διαφάνεια) [0.0f, 1.0f] |

### A {#A}
```
public float A
```


Alpha (διαφάνεια) [0.0f, 1.0f]

### H {#H}
```
public final int H
```


Απόχρωση [0, 360]

### L {#L}
```
public final int L
```


Φωτεινότητα [0, 100]

### S {#S}
```
public final int S
```


Κορεσμός [0, 100]

### convertHslaToRgba(HslaColor hslaColor) {#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-}
```
public static Color convertHslaToRgba(HslaColor hslaColor)
```


Χρησιμοποιεί https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hslaColor | [HslaColor](../../com.aspose.barcode.generation/hslacolor) | Χρώμα HSLA για μετατροπή |

**Returns:**
java.awt.Color - Χρώμα με τιμές RGBA
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

