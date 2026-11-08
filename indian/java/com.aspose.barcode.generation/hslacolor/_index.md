---
title: "HslaColor"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "HSLA रंग Hue Saturation Lightness Alpha को दर्शाने के लिए क्लास"
type: docs
weight: 49
url: /hi/java/com.aspose.barcode.generation/hslacolor/
---
**Inheritance:**
java.lang.Object
```
public class HslaColor
```

HSLA रंग (ह्यू, सैचुरेशन, लाइटनेस, अल्फा) को दर्शाने के लिए क्लास
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [HslaColor(int h, int s, int l, float a)](#HslaColor-int-int-int-float-) | HslaColor के लिए कंस्ट्रक्टर |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [A](#A) | Alpha (अपारदर्शिता) [0.0f, 1.0f] |
| [H](#H) | Hue [0, 360] |
| [L](#L) | Lightness [0, 100] |
| [S](#S) | Saturation [0, 100] |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [convertHslaToRgba(HslaColor hslaColor)](#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-) | उपयोग करता है https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB |
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


HslaColor के लिए कंस्ट्रक्टर

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| h | int | Hue [0, 360] |
| s | int | Saturation [0, 100] |
| l | int | Lightness [0, 100] |
| a | float | Alpha (अपारदर्शिता) [0.0f, 1.0f] |

### A {#A}
```
public float A
```


Alpha (अपारदर्शिता) [0.0f, 1.0f]

### H {#H}
```
public final int H
```


Hue [0, 360]

### L {#L}
```
public final int L
```


Lightness [0, 100]

### S {#S}
```
public final int S
```


Saturation [0, 100]

### convertHslaToRgba(HslaColor hslaColor) {#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-}
```
public static Color convertHslaToRgba(HslaColor hslaColor)
```


उपयोग करता है https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hslaColor | [HslaColor](../../com.aspose.barcode.generation/hslacolor) | परिवर्तित करने के लिए HSLA रंग |

**Returns:**
java.awt.Color - RGBA मानों वाला रंग
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

