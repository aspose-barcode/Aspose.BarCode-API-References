---
title: "单位"
second_title: "Aspose.BarCode for Android via Java API 参考"
description: "指定以不同单位（像素、英寸等）的尺寸值。"
type: docs
weight: 67
url: /zh/androidjava/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

指定不同单位（像素、英寸等）下的尺寸值。

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定此实例与指定对象（该对象也必须是  Unit  对象）是否具有相同的值。 |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | 获取文档单位中的尺寸值。 |
| [getInches()](#getInches--) | 获取以英寸为单位的尺寸值。 |
| [getMillimeters()](#getMillimeters--) | 获取以毫米为单位的尺寸值。 |
| [getPixels()](#getPixels--) | 获取以像素为单位的尺寸值。 |
| [getPoint()](#getPoint--) | 获取以点为单位的尺寸值。 |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | 返回此对象的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | 设置文档单位中的尺寸值。 |
| [setInches(float value)](#setInches-float-) | 设置以英寸为单位的尺寸值。 |
| [setMillimeters(float value)](#setMillimeters-float-) | 设置以毫米为单位的尺寸值。 |
| [setPixels(float value)](#setPixels-float-) | 设置以像素为单位的尺寸值。 |
| [setPoint(float value)](#setPoint-float-) | 设置以点为单位的尺寸值。 |
| [toString()](#toString--) | 返回此 Unit 的人类可读字符串表示。 |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定此实例与指定对象（该对象也必须是  Unit  对象）是否具有相同的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 Unit。 |

**Returns:**
boolean - 如果 obj 是一个 Unit 且其值与此实例相同，则返回 true；否则返回 false。如果 obj 为 null，方法返回 false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public float getDocument()
```


获取文档单位中的尺寸值。

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


获取以英寸为单位的尺寸值。

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


获取以毫米为单位的尺寸值。

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


获取以像素为单位的尺寸值。

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


获取以点为单位的尺寸值。

**Returns:**
float
### getResolution() {#getResolution--}
```
public float getResolution()
```




**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此对象的哈希码。

**Returns:**
int - 32 位有符号整数哈希码。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDocument(float value) {#setDocument-float-}
```
public void setDocument(float value)
```


设置文档单位中的尺寸值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


设置以英寸为单位的尺寸值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


设置以毫米为单位的尺寸值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


设置以像素为单位的尺寸值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


设置以点为单位的尺寸值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### toString() {#toString--}
```
public String toString()
```


返回此 Unit 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此 Unit 的字符串。
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dpi | float |  |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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
| arg1 | 整数 |  |

