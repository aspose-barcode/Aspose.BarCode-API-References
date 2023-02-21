---
title: TextMeasurer
second_title: Aspose.BarCode for Android via Java API Reference
description: Represents text measurer.
type: docs
weight: 53
url: /androidjava/com.aspose.barcode.generation/textmeasurer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.barcode.internal.ITextMeasurer, com.aspose.ms.System.IDisposable
```
public class TextMeasurer implements ITextMeasurer, System.IDisposable
```

Represents text measurer. Full Framework implementation. TODO: Cache bitmap and graphics
## Constructors

| Constructor | Description |
| --- | --- |
| [TextMeasurer(float dpiX, float dpiY)](#TextMeasurer-float-float-) | Initializes new instance of class TextMeasurer. |
## Methods

| Method | Description |
| --- | --- |
| [dispose()](#dispose--) | Disposes measurer and internal resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [measureString(String str, float width, TextPaint font)](#measureString-java.lang.String-float-android.text.TextPaint-) | Measure string with specified width, font and with resolution from Builder. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextMeasurer(float dpiX, float dpiY) {#TextMeasurer-float-float-}
```
public TextMeasurer(float dpiX, float dpiY)
```


Initializes new instance of class TextMeasurer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dpiX | float | Dpi X of target canvas |
| dpiY | float | Dpi Y of target canvas |

### dispose() {#dispose--}
```
public void dispose()
```


Disposes measurer and internal resources.

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
### measureString(String str, float width, TextPaint font) {#measureString-java.lang.String-float-android.text.TextPaint-}
```
public System.Drawing.SizeF measureString(String str, float width, TextPaint font)
```


Measure string with specified width, font and with resolution from Builder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String | A string |
| width | float | A width |
| font | android.text.TextPaint | A font |

**Returns:**
com.aspose.ms.System.Drawing.SizeF - Size of a string
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

