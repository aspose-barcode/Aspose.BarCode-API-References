---
title: BorderParameters
second_title: Aspose.BarCode for Android via Java API-referens
description: Parametrar för streckkodsbildens kant
type: docs
weight: 18
url: /sv/androidjava/com.aspose.barcode.generation/borderparameters/
---
**Inheritance:**
java.lang.Object
```
public class BorderParameters
```

Parametrar för streckkodsbildens kant
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Kantfärg. |
| [getDashStyle()](#getDashStyle--) | Kantens streckstil. |
| [getVisible()](#getVisible--) | Kantens synlighet. |
| [getWidth()](#getWidth--) | Kantbredd. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColor(int value)](#setColor-int-) | Kantfärg. |
| [setDashStyle(BorderDashStyle value)](#setDashStyle-com.aspose.barcode.generation.BorderDashStyle-) | Kantens streckstil. |
| [setVisible(boolean value)](#setVisible-boolean-) | Kantens synlighet. |
| [setWidth(Unit value)](#setWidth-com.aspose.barcode.generation.Unit-) | Kantbredd. |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta BorderParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beskrivning |
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
### getColor() {#getColor--}
```
public int getColor()
```


Kantfärg. Standardvärde: Color.Black.

**Returns:**
int
### getDashStyle() {#getDashStyle--}
```
public BorderDashStyle getDashStyle()
```


Kantens streckstil. Standardvärde: BorderDashStyle.Solid.

**Returns:**
[BorderDashStyle](../../com.aspose.barcode.generation/borderdashstyle)
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Kantens synlighet. Om falskt så ignoreras parametern Width alltid (0). Standardvärde: false.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public Unit getWidth()
```


Kantbredd. Standardvärde: 0. Ignoreras om Visible är satt till false.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
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




### setColor(int value) {#setColor-int-}
```
public void setColor(int value)
```


Kantfärg. Standardvärde: Color.Black.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDashStyle(BorderDashStyle value) {#setDashStyle-com.aspose.barcode.generation.BorderDashStyle-}
```
public void setDashStyle(BorderDashStyle value)
```


Kantens streckstil. Standardvärde: BorderDashStyle.Solid.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [BorderDashStyle](../../com.aspose.barcode.generation/borderdashstyle) |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Kantens synlighet. Om falskt så ignoreras parametern Width alltid (0). Standardvärde: false.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setWidth(Unit value) {#setWidth-com.aspose.barcode.generation.Unit-}
```
public void setWidth(Unit value)
```


Kantbredd. Standardvärde: 0. Ignoreras om Visible är satt till false.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av detta BorderParameters.

**Returns:**
java.lang.String - En sträng som representerar detta BorderParameters.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

