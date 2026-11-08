---
title: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for Java API Reference"
description: "用于存储 HIBC LIC 次要和附加数据的类。"
type: docs
weight: 34
url: /zh/java/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

用于存储 HIBC LIC 次要和附加数据的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的  SecondaryAndAdditionalData  值。 |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | 识别生产日期。 |
| [getExpiryDate()](#getExpiryDate--) | 识别有效期。 |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | 识别有效期格式。 |
| [getLotNumber()](#getLotNumber--) | 识别批号或批次号。 |
| [getQuantity()](#getQuantity--) | 识别数量，必须是 0 到 500 的整数值。 |
| [getSerialNumber()](#getSerialNumber--) | 识别序列号。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | 根据 HIBC LIC 规范，从字符串格式实例化二次和附加补充数据。 |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | 识别生产日期。 |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | 识别有效期。 |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | 识别有效期格式。 |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | 识别批号或批次号。 |
| [setQuantity(int value)](#setQuantity-int-) | 识别数量，必须是 0 到 500 的整数值。 |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | 识别序列号。 |
| [toString()](#toString--) | 根据 HIBC LIC 规范，将数据转换为字符串格式。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SecondaryAndAdditionalData() {#SecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


返回一个值，指示此实例是否等于指定的  SecondaryAndAdditionalData  值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 一个用于与此实例比较的 SecondaryAndAdditionalData 值。 |

**Returns:**
boolean -  **true**  如果 obj 与此实例具有相同的值；否则，  **false** 。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDateOfManufacture() {#getDateOfManufacture--}
```
public LocalDateTime getDateOfManufacture()
```


识别生产日期。生产日期可以设置为 DateTime.MinValue 以不使用此字段。默认值：DateTime.MinValue

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


识别有效期。如果 ExpiryDateFormat 未设置为 None，则将使用此值。

**Returns:**
java.time.LocalDateTime
### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public HIBCLICDateFormat getExpiryDateFormat()
```


识别有效期格式。

**Returns:**
[HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat)
### getLotNumber() {#getLotNumber--}
```
public String getLotNumber()
```


识别批号或批次号。批号/批次号必须是最长 18 个字符的字母数字字符串。

**Returns:**
java.lang.String
### getQuantity() {#getQuantity--}
```
public int getQuantity()
```


识别数量，必须是 0 到 500 的整数值。数量可以设置为 -1 以不使用此字段。默认值：-1

**Returns:**
int
### getSerialNumber() {#getSerialNumber--}
```
public String getSerialNumber()
```


识别序列号。序列号必须是最长 18 个字符的字母数字字符串。

**Returns:**
java.lang.String
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




### parseFromString(String secondaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String secondaryDataCodetext)
```


根据 HIBC LIC 规范，从字符串格式实例化二次和附加补充数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | 格式化字符串。 |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


识别生产日期。生产日期可以设置为 DateTime.MinValue 以不使用此字段。默认值：DateTime.MinValue

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


识别有效期。如果 ExpiryDateFormat 未设置为 None，则将使用此值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


识别有效期格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


识别批号或批次号。批号/批次号必须是最长 18 个字符的字母数字字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


识别数量，必须是 0 到 500 的整数值。数量可以设置为 -1 以不使用此字段。默认值：-1

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


识别序列号。序列号必须是最长 18 个字符的字母数字字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

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

