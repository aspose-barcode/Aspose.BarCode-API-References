---
title: BorderParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Barcode image border parameters
type: docs
weight: 18
url: /ja/androidjava/com.aspose.barcode.generation/borderparameters/
---
**Inheritance:**
java.lang.Object
```
public class BorderParameters
```

Barcode image border parameters
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 境界線の色。 |
| [getDashStyle()](#getDashStyle--) | 境界線の破線スタイル。 |
| [getVisible()](#getVisible--) | 境界線の可視性。 |
| [getWidth()](#getWidth--) | 境界線の幅。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColor(int value)](#setColor-int-) | 境界線の色。 |
| [setDashStyle(BorderDashStyle value)](#setDashStyle-com.aspose.barcode.generation.BorderDashStyle-) | 境界線の破線スタイル。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 境界線の可視性。 |
| [setWidth(Unit value)](#setWidth-com.aspose.barcode.generation.Unit-) | 境界線の幅。 |
| [toString()](#toString--) | この BorderParameters の人間が読める文字列表現を返します。 |
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
### getColor() {#getColor--}
```
public int getColor()
```


境界線の色。デフォルト値: Color.Black。

**Returns:**
int
### getDashStyle() {#getDashStyle--}
```
public BorderDashStyle getDashStyle()
```


境界線の破線スタイル。デフォルト値: BorderDashStyle.Solid。

**Returns:**
[BorderDashStyle](../../com.aspose.barcode.generation/borderdashstyle)
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


境界線の可視性。false の場合、パラメーター Width は常に無視されます (0)。デフォルト値: false。

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public Unit getWidth()
```


境界線の幅。デフォルト値: 0。Visible が false に設定されている場合は無視されます。

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


境界線の色。デフォルト値: Color.Black。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setDashStyle(BorderDashStyle value) {#setDashStyle-com.aspose.barcode.generation.BorderDashStyle-}
```
public void setDashStyle(BorderDashStyle value)
```


境界線の破線スタイル。デフォルト値: BorderDashStyle.Solid。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderDashStyle](../../com.aspose.barcode.generation/borderdashstyle) |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


境界線の可視性。false の場合、パラメーター Width は常に無視されます (0)。デフォルト値: false。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | boolean |  |

### setWidth(Unit value) {#setWidth-com.aspose.barcode.generation.Unit-}
```
public void setWidth(Unit value)
```


境界線の幅。デフォルト値: 0。Visible が false に設定されている場合は無視されます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### toString() {#toString--}
```
public String toString()
```


この BorderParameters の人間が読める文字列表現を返します。

**Returns:**
java.lang.String - この BorderParameters を表す文字列。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

