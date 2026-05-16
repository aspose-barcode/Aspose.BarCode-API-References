---
title: CMYKColor
second_title: Aspose.BarCode for Android via Java API Reference
description: CMYK 색상에 대한 클래스.
type: docs
weight: 19
url: /ko/androidjava/com.aspose.barcode.generation/cmykcolor/
---
**Inheritance:**
java.lang.Object
```
public class CMYKColor
```

Class for CMYK color. Null means CMYK is not used, default RGB color is in use.
## Constructors

| Constructor | 설명 |
| --- | --- |
| [CMYKColor(int c, int m, int y, int k)](#CMYKColor-int-int-int-int-) | Initializes a new instance of the  CMYKColor  class from CMYK values. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [C](#C) |  |
| [K](#K) |  |
| [M](#M) |  |
| [Y](#Y) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Compares if values of colors are the same |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Hash code of CMYKColor |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CMYKColor(int c, int m, int y, int k) {#CMYKColor-int-int-int-int-}
```
public CMYKColor(int c, int m, int y, int k)
```


Initializes a new instance of the  CMYKColor  class from CMYK values. CMYK values are 0-100.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| c | int | Cyan value [0, 100] |
| m | int | Magenta value [0, 100] |
| y | int | Yellow value [0, 100] |
| k | int | Black value [0, 100] |

### C {#C}
```
public float C
```


### K {#K}
```
public float K
```


### M {#M}
```
public float M
```


### Y {#Y}
```
public float Y
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Compares if values of colors are the same

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | CMYKColor to compare |

**Returns:**
boolean - Are values the same
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash code of CMYKColor

**Returns:**
int - Hash code of CMYKColor
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
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

