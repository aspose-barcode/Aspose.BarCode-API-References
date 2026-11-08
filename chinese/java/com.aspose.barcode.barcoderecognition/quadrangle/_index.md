---
title: "Quadrangle"
second_title: "Aspose.BarCode for Java API Reference"
description: "存储一组四个点，表示一个 Quadrangle 区域。"
type: docs
weight: 39
url: /zh/java/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

存储一组四个 Point，表示一个 Quadrangle 区域。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-) | 使用描述点初始化 Quadrangle 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [EMPTY](#EMPTY) | 表示一个 Quadrangle 类，其属性保持未初始化状态。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | 确定指定的 Quadrangle 是否被包含或与此 Quadrangle 类相交。 |
| [contains(int x, int y)](#contains-int-int-) | 确定指定的点是否位于此 Quadrangle 类内部。 |
| [contains(Point pt)](#contains-java.awt.Point-) | 确定指定的 Point 是否位于此 Quadrangle 类内部。 |
| [contains(Rectangle rect)](#contains-java.awt.Rectangle-) | 确定指定的 Rectangle 是否被包含或与此 Quadrangle 类相交。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的 Quadrangle 值。 |
| [getBoundingRectangle()](#getBoundingRectangle--) | 创建包围此 Quadrangle 的 Rectangle。 |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | 获取 Quadrangle 区域的左下角 Point。 |
| [getLeftTop()](#getLeftTop--) | 获取 Quadrangle 区域的左上角 Point。 |
| [getRightBottom()](#getRightBottom--) | 获取 Quadrangle 区域的右下角 Point。 |
| [getRightTop()](#getRightTop--) | 获取 Quadrangle 区域的右上角 Point。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isEmpty()](#isEmpty--) | 测试此 Quadrangle 的所有 Point 是否全部为零值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-java.awt.Point-) | 获取 Quadrangle 区域的左下角 Point。 |
| [setLeftTop(Point value)](#setLeftTop-java.awt.Point-) | 获取 Quadrangle 区域的左上角 Point。 |
| [setRightBottom(Point value)](#setRightBottom-java.awt.Point-) | 获取 Quadrangle 区域的右下角 Point。 |
| [setRightTop(Point value)](#setRightTop-java.awt.Point-) | 获取 Quadrangle 区域的右上角 Point。 |
| [toString()](#toString--) | 返回此 Quadrangle 的人类可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


使用描述点初始化 Quadrangle 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| leftTop | java.awt.Point | 一个表示 Quadrangle 左上角的 Point。 |
| rightTop | java.awt.Point | 一个表示 Quadrangle 右上角的 Point。 |
| rightBottom | java.awt.Point | 一个表示 Quadrangle 右下角的 Point。 |
| leftBottom | java.awt.Point | 一个表示 Quadrangle 左下角的 Point。 |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


表示一个 Quadrangle 类，其属性保持未初始化状态。

值: Quadrangle

### clone() {#clone--}
```
public Quadrangle clone()
```




**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


确定指定的 Quadrangle 是否被包含或与此 Quadrangle 类相交。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | 要测试的 Quadrangle。 |

**Returns:**
boolean - 如果 Quadrangle 包含或与此 Quadrangle 类相交，则返回 **true**；否则返回 **false**。
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


确定指定的点是否位于此 Quadrangle 类内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | x 点坐标。 |
| y | int | y 点坐标。 |

**Returns:**
boolean - 如果点包含在此 Quadrangle 类中，则返回 **true**；否则返回 **false**。
### contains(Point pt) {#contains-java.awt.Point-}
```
public boolean contains(Point pt)
```


确定指定的 Point 是否位于此 Quadrangle 类内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | java.awt.Point | 要测试的 Point。 |

**Returns:**
boolean - 如果 Point 包含在此 Quadrangle 类中，则返回 **true**；否则返回 **false**。
### contains(Rectangle rect) {#contains-java.awt.Rectangle-}
```
public boolean contains(Rectangle rect)
```


确定指定的 Rectangle 是否被包含或与此 Quadrangle 类相交。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 要测试的 Rectangle。 |

**Returns:**
boolean - 如果 Rectangle 包含或与此 Quadrangle 类相交，则返回 **true**；否则返回 **false**。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的 Quadrangle 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要与此实例比较的 Quadrangle 值。 |

**Returns:**
boolean -  **true**  如果 obj 与此实例具有相同的值；否则，  **false** 。
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


创建包围此 Quadrangle 的 Rectangle。

**Returns:**
java.awt.Rectangle - 返回 包围此 Quadrangle 的 Rectangle
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


获取 Quadrangle 区域的左下角 Point。

值：Quadrangle 区域的左下角 Point

**Returns:**
java.awt.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


获取 Quadrangle 区域的左上角 Point。

值：Quadrangle 区域的左上角 Point

**Returns:**
java.awt.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


获取 Quadrangle 区域的右下角 Point。

值：Quadrangle 区域的右下角 Point

**Returns:**
java.awt.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


获取 Quadrangle 区域的右上角 Point。

值：Quadrangle 区域的右上角 Point

**Returns:**
java.awt.Point
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


测试此 Quadrangle 的所有 Point 是否全部为零值。

值：如果此 Quadrangle 的所有 Point 的值为零，则返回 **true**；否则返回 **false**。

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




### setLeftBottom(Point value) {#setLeftBottom-java.awt.Point-}
```
public void setLeftBottom(Point value)
```


获取 Quadrangle 区域的左下角 Point。

值：Quadrangle 区域的左下角 Point

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Point |  |

### setLeftTop(Point value) {#setLeftTop-java.awt.Point-}
```
public void setLeftTop(Point value)
```


获取 Quadrangle 区域的左上角 Point。

值：Quadrangle 区域的左上角 Point

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Point |  |

### setRightBottom(Point value) {#setRightBottom-java.awt.Point-}
```
public void setRightBottom(Point value)
```


获取 Quadrangle 区域的右下角 Point。

值：Quadrangle 区域的右下角 Point

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Point |  |

### setRightTop(Point value) {#setRightTop-java.awt.Point-}
```
public void setRightTop(Point value)
```


获取 Quadrangle 区域的右上角 Point。

值：Quadrangle 区域的右上角 Point

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Point |  |

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
public final native void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

