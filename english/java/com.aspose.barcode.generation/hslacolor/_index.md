---
title: HslaColor
second_title: Aspose.BarCode for Java API Reference
description: Class for representing HSLA color Hue Saturation Lightness Alpha
type: docs
weight: 46
url: /java/com.aspose.barcode.generation/hslacolor/
---
**Inheritance:**
java.lang.Object
```
public class HslaColor
```

Class for representing HSLA color (Hue, Saturation, Lightness, Alpha)
## Constructors

| Constructor | Description |
| --- | --- |
| [HslaColor(int h, int s, int l, float a)](#HslaColor-int-int-int-float-) | Constructor for HslaColor |
## Fields

| Field | Description |
| --- | --- |
| [A](#A) | Alpha (opacity) [0.0f, 1.0f] |
| [H](#H) | Hue [0, 360] |
| [L](#L) | Lightness [0, 100] |
| [S](#S) | Saturation [0, 100] |
## Methods

| Method | Description |
| --- | --- |
| [convertHslaToRgba(HslaColor hslaColor)](#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-) | Uses https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB |
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


Constructor for HslaColor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| h | int | Hue [0, 360] |
| s | int | Saturation [0, 100] |
| l | int | Lightness [0, 100] |
| a | float | Alpha (opacity) [0.0f, 1.0f] |

### A {#A}
```
public float A
```


Alpha (opacity) [0.0f, 1.0f]

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


Uses https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hslaColor | com.aspose.barcode.generation.HslaColor | HSLA color to convert |

**Returns:**
java.awt.Color - Color with RGBA values
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

