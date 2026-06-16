---
title: Quadrangle
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 存储一组四个点，表示一个 Quadrangle 区域。
type: docs
weight: 43
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

存储一组四个 Point，表示一个 Quadrangle 区域。
## Constructors

| Constructor | 描述 |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | 使用描述点初始化 Quadrangle 结构的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [EMPTY](#EMPTY) | 表示一个 Quadrangle 类，其属性保持未初始化。 |
## Methods

| Method | 描述 |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | 确定指定的 Point 是否包含在此 Quadrangle 类中。 |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | 确定指定的 Rectangle 是否包含或与此 Quadrangle 类相交。 |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | 确定指定的 Quadrangle 是否包含或与此 Quadrangle 类相交。 |
| [contains(int x, int y)](#contains-int-int-) | 确定指定的点是否包含在此 Quadrangle 类中。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的 Quadrangle 值。 |
| [getBoundingRectangle()](#getBoundingRectangle--) | 创建包围此 Quadrangle 的 Rectangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | 获取 Quadrangle 区域的左下角 Point |
| [getLeftTop()](#getLeftTop--) | 获取 Quadrangle 区域的左上角 Point |
| [getRightBottom()](#getRightBottom--) | 获取 Quadrangle 区域的右下角 Point |
| [getRightTop()](#getRightTop--) | 获取 Quadrangle 区域的右上角 Point |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isEmpty()](#isEmpty--) | 测试此 Quadrangle 的所有 Point 是否全部为零。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | 获取 Quadrangle 区域的左下角 Point |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | 获取 Quadrangle 区域的左上角 Point |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | 获取 Quadrangle 区域的右下角 Point |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | 获取 Quadrangle 区域的右上角 Point |
| [toString()](#toString--) | 返回此 Quadrangle 的人类可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


使用描述点初始化 Quadrangle 结构的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| leftTop | android.graphics.Point | 表示 Quadrangle 左上角的 Point。 |
| rightTop | android.graphics.Point | 表示 Quadrangle 右上角的 Point。 |
| rightBottom | android.graphics.Point | 表示 Quadrangle 右下角的 Point。 |
| leftBottom | android.graphics.Point | 表示 Quadrangle 左下角的 Point。 |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


表示一个 Quadrangle 类，其属性保持未初始化。

值：Quadrangle

### clone() {#clone--}
```
public Quadrangle clone()
```




**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### contains(Point pt) {#contains-android.graphics.Point-}
```
public boolean contains(Point pt)
```


确定指定的 Point 是否包含在此 Quadrangle 类中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pt | android.graphics.Point | 要测试的 Point。 |

**Returns:**
布尔值 - 如果 Point 位于此 Quadrangle 类中则返回 **true**，否则返回 **false**。
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


确定指定的 Rectangle 是否包含或与此 Quadrangle 类相交。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | android.graphics.Rect | 要测试的 Rectangle。 |

**Returns:**
布尔值 - 如果 Rectangle 包含在此 Quadrangle 类中或与之相交则返回 **true**，否则返回 **false**。
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


确定指定的 Quadrangle 是否包含或与此 Quadrangle 类相交。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | 要测试的 Quadrangle。 |

**Returns:**
布尔值 - 如果 Quadrangle 包含在此 Quadrangle 类中或与之相交则返回 **true**，否则返回 **false**。
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


确定指定的点是否包含在此 Quadrangle 类中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | int | x 点坐标。 |
| y | int | y 轴点坐标。 |

**Returns:**
boolean - 如果点位于此 Quadrangle 类中则返回 **true**，否则返回 **false**。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的 Quadrangle 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 Quadrangle 值。 |

**Returns:**
boolean -  **true**  如果 obj 与此实例具有相同的值；否则， **false** 。
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


创建包围此 Quadrangle 的 Rectangle

**Returns:**
android.graphics.Rect - 返回 包围此 Quadrangle 的 Rectangle。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLeftBottom() {#getLeftBottom--}
```
public Point getLeftBottom()
```


获取 Quadrangle 区域的左下角 Point

值：Quadrangle 区域的左下角 Point。

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


获取 Quadrangle 区域的左上角 Point

值：Quadrangle 区域的左上角 Point。

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


获取 Quadrangle 区域的右下角 Point

值：Quadrangle 区域的右下角 Point。

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


获取 Quadrangle 区域的右上角 Point

值：Quadrangle 区域的右上角 Point。

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 32 位有符号整数哈希码。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


测试此 Quadrangle 的所有 Point 是否全部为零。

值：如果此 Quadrangle 的所有 Point 的值均为零则返回 **true**，否则返回 **false**。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLeftBottom(Point value) {#setLeftBottom-android.graphics.Point-}
```
public void setLeftBottom(Point value)
```


获取 Quadrangle 区域的左下角 Point

值：Quadrangle 区域的左下角 Point。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


获取 Quadrangle 区域的左上角 Point

值：Quadrangle 区域的左上角 Point。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


获取 Quadrangle 区域的右下角 Point

值：Quadrangle 区域的右下角 Point。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


获取 Quadrangle 区域的右上角 Point

值：Quadrangle 区域的右上角 Point。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


返回此 Quadrangle 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此 Quadrangle 的字符串。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

