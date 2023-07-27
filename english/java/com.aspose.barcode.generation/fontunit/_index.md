---
title: FontUnit
second_title: Aspose.BarCode for Java API Reference
description: Defines a particular format for text including font face size and style attributes  where size in Unit value property.
type: docs
weight: 37
url: /java/com.aspose.barcode.generation/fontunit/
---
**Inheritance:**
java.lang.Object
```
public final class FontUnit
```

Defines a particular format for text, including font face, size, and style attributes where size in Unit value property.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          generator.getCodeTextStyle().getFont().setStyle(FontStyle.ITALIC);
>          generator.getCodeTextStyle().getFont().getSize().setPoint(18);
>          generator.save("test.png");
> ```
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFamilyName()](#getFamilyName--) | Gets the face name of this Font. |
| [getFont()](#getFont--) |  |
| [getSize()](#getSize--) | Gets size of this FontUnit in Unit value. |
| [getStateHash()](#getStateHash--) |  |
| [getStyle()](#getStyle--) | Gets style information for this FontUnit. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | Sets the face name of this Font. |
| [setStyle(int value)](#setStyle-int-) | Sets style information for this FontUnit. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Gets the face name of this Font.

**Returns:**
java.lang.String
### getFont() {#getFont--}
```
public System.Drawing.Font getFont()
```




**Returns:**
com.aspose.ms.System.Drawing.Font
### getSize() {#getSize--}
```
public Unit getSize()
```


Gets size of this FontUnit in Unit value.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getStateHash() {#getStateHash--}
```
public int getStateHash()
```




**Returns:**
int
### getStyle() {#getStyle--}
```
public int getStyle()
```


Gets style information for this FontUnit.

**Returns:**
int
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




### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


Sets the face name of this Font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Sets style information for this FontUnit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

