---
title: PrimaryData
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 用于存储 HIBC LIC 主数据的类。
type: docs
weight: 34
url: /zh/androidjava/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

用于存储 HIBC LIC 主数据的类。
## Constructors

| Constructor | 描述 |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的  PrimaryData  值。 |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | 标识标签者识别代码的日期。 |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | 标识产品或目录编号。 |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | 标识计量单位 ID。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | 根据 HIBC LIC 规范从字符串格式实例化主数据。 |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | 标识标签者识别代码的日期。 |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | 标识产品或目录编号。 |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | 标识计量单位 ID。 |
| [toString()](#toString--) | 根据 HIBC LIC 规范，将数据转换为字符串格式。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrimaryData() {#PrimaryData--}
```
public PrimaryData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的  PrimaryData  值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 PrimaryData 值。 |

**Returns:**
boolean -  **true**  如果 obj 与此实例具有相同的值；否则， **false** 。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public String getLabelerIdentificationCode()
```


标识标签者识别码的日期。标签者识别码必须是 4 位字母数字字符串，且首字符必须为字母。

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


标识产品或目录编号。产品或目录编号必须是最长 18 位的字母数字字符串。

**Returns:**
java.lang.String
### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public int getUnitOfMeasureID()
```


标识计量单位 ID。计量单位 ID 必须是 0 到 9 的整数值。

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

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




### parseFromString(String primaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String primaryDataCodetext)
```


根据 HIBC LIC 规范从字符串格式实例化主数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | 格式化字符串。 |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


标识标签者识别码的日期。标签者识别码必须是 4 位字母数字字符串，且首字符必须为字母。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


标识产品或目录编号。产品或目录编号必须是最长 18 位的字母数字字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


标识计量单位 ID。计量单位 ID 必须是 0 到 9 的整数值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### toString() {#toString--}
```
public String toString()
```


根据 HIBC LIC 规范，将数据转换为字符串格式。

**Returns:**
java.lang.String - 格式化字符串。
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

