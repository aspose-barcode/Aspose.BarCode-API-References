---
title: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode for Android via Java API 参考"
description: "美国驾照司法辖区特定字段的类"
type: docs
weight: 38
url: /zh/androidjava/com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile/
---
**Inheritance:**
java.lang.Object
```
public class USADriveIdJurisdSubfile
```

美国驾照司法辖区特定字段的类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [USADriveIdJurisdSubfile()](#USADriveIdJurisdSubfile--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addOrReplace(USADriveIdJurisdSubfile.DataElement node)](#addOrReplace-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | 添加新的 DataElement，或在 ElementID 已存在时替换它。 |
| [addOrReplace(String id, String value)](#addOrReplace-java.lang.String-java.lang.String-) | 添加一个具有指定标识符和数值的新 DataElement，或在已存在具有相同 ElementID 的条目时替换现有元素。 |
| [clear()](#clear--) | 清除所有数据元素 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findDataElement(String id, boolean isOpenOrCreate)](#findDataElement-java.lang.String-boolean-) | 按 3 字母 id 搜索数据元素 |
| [get(int index)](#get-int-) | 按索引号进行索引 |
| [get(String id)](#get-java.lang.String-) | 按 3 字母元素 id 进行索引 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [insert(int index, USADriveIdJurisdSubfile.DataElement node)](#insert-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | 在给定索引处插入指定的 DataElement。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(int index)](#remove-int-) | 尝试删除索引处的元素 |
| [remove(String id)](#remove-java.lang.String-) | 尝试删除具有 3 字母 id 的元素 |
| [set(int index, USADriveIdJurisdSubfile.DataElement value)](#set-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | 按索引号进行索引 |
| [set(String id, USADriveIdJurisdSubfile.DataElement value)](#set-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | 按 3 字母元素 id 进行索引 |
| [size()](#size--) | 返回数据元素的数量 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### USADriveIdJurisdSubfile() {#USADriveIdJurisdSubfile--}
```
public USADriveIdJurisdSubfile()
```


### addOrReplace(USADriveIdJurisdSubfile.DataElement node) {#addOrReplace-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final USADriveIdJurisdSubfile.DataElement addOrReplace(USADriveIdJurisdSubfile.DataElement node)
```


添加新的 DataElement，或在 ElementID 已存在时替换它。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | 要添加的 DataElement |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Added/replaced data element
### addOrReplace(String id, String value) {#addOrReplace-java.lang.String-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement addOrReplace(String id, String value)
```


添加一个具有指定标识符和数值的新 DataElement，或在已存在具有相同 ElementID 的条目时替换现有元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | java.lang.String | 唯一指定司法相关数据元素的 3 字母标识符。 |
| 值 | java.lang.String | 分配给数据元素的文本值；如果该元素已存在，此值将覆盖已有值。 |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - The DataElement instance that was added to the collection or updated in place.
### clear() {#clear--}
```
public final void clear()
```


清除所有数据元素

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### findDataElement(String id, boolean isOpenOrCreate) {#findDataElement-java.lang.String-boolean-}
```
public final USADriveIdJurisdSubfile.DataElement findDataElement(String id, boolean isOpenOrCreate)
```


按 3 字母 id 搜索数据元素

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | java.lang.String | 3 字母 id |
| isOpenOrCreate | 布尔 | 如果为 true，则在未找到时创建。 |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Found data element
### get(int index) {#get-int-}
```
public final USADriveIdJurisdSubfile.DataElement get(int index)
```


按索引号进行索引

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | 整数 | 元素索引（int） |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Corresponding DataElement
### get(String id) {#get-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement get(String id)
```


按 3 字母元素 id 进行索引

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | java.lang.String | 3 字母元素 id |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Corresponding DataElement
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
整数
### insert(int index, USADriveIdJurisdSubfile.DataElement node) {#insert-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final USADriveIdJurisdSubfile.DataElement insert(int index, USADriveIdJurisdSubfile.DataElement node)
```


在给定索引处插入指定的 DataElement。如果已存在具有相同 ElementID 的 DataElement，则会被替换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | 整数 | 应插入元素的零基索引。 |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | 要在目标位置插入或替换的 DataElement 实例。 |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - The DataElement that was inserted or used to replace an existing entry.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(int index) {#remove-int-}
```
public final boolean remove(int index)
```


尝试删除索引处的元素

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | 整数 | 索引号 |

**Returns:**
布尔值 - 成功为 true，超出范围为 false
### remove(String id) {#remove-java.lang.String-}
```
public final boolean remove(String id)
```


尝试删除具有 3 字母 id 的元素

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | java.lang.String | 3 字母 id |

**Returns:**
布尔值 - 成功为 true，若不存在此 id 为 false
### set(int index, USADriveIdJurisdSubfile.DataElement value) {#set-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set(int index, USADriveIdJurisdSubfile.DataElement value)
```


按索引号进行索引

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | 整数 | 元素索引（int） |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

### set(String id, USADriveIdJurisdSubfile.DataElement value) {#set-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set(String id, USADriveIdJurisdSubfile.DataElement value)
```


按 3 字母元素 id 进行索引

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | java.lang.String | 3 字母元素 id |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

### size() {#size--}
```
public final int size()
```


返回数据元素的数量

**Returns:**
整数
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

