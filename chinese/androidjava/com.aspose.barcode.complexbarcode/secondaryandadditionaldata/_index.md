---
title: SecondaryAndAdditionalData
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 用于存储 HIBC LIC 次要和附加数据的类。
type: docs
weight: 35
url: /zh/androidjava/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

用于存储 HIBC LIC 次要和附加数据的类。
## Constructors

| Constructor | 描述 |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 返回一个值，指示此实例是否等于指定的  SecondaryAndAdditionalData  值。 |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | 标识生产日期。 |
| [getExpiryDate()](#getExpiryDate--) | 标识有效期。 |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | 标识有效期格式。 |
| [getLotNumber()](#getLotNumber--) | 标识批号或批次号。 |
| [getQuantity()](#getQuantity--) | 标识数量，必须是 0 到 500 的整数值。 |
| [getSerialNumber()](#getSerialNumber--) | 标识序列号。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | 根据 HIBC LIC 规范，从字符串格式实例化二次和附加补充数据。 |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | 标识生产日期。 |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | 标识有效期。 |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | 标识有效期格式。 |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | 标识批号或批次号。 |
| [setQuantity(int value)](#setQuantity-int-) | 标识数量，必须是 0 到 500 的整数值。 |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | 标识序列号。 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的  SecondaryAndAdditionalData  值。 |

**Returns:**
boolean -  **true**  如果 obj 与此实例具有相同的值；否则， **false** 。
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


标识生产日期。可以将生产日期设置为 DateTime.MinValue 以不使用此字段。默认值：DateTime.MinValue。

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


标识有效期。如果 ExpiryDateFormat 未设置为 None，则将使用此值。

**Returns:**
java.time.LocalDateTime
### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public HIBCLICDateFormat getExpiryDateFormat()
```


标识有效期格式。

**Returns:**
[HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat)
### getLotNumber() {#getLotNumber--}
```
public String getLotNumber()
```


标识批号或批次号。批号/批次号必须是最长 18 个字符的字母数字字符串。

**Returns:**
java.lang.String
### getQuantity() {#getQuantity--}
```
public int getQuantity()
```


标识数量，必须是 0 到 500 的整数值。数量可以设置为 -1 以不使用此字段。默认值：-1。

**Returns:**
int
### getSerialNumber() {#getSerialNumber--}
```
public String getSerialNumber()
```


标识序列号。序列号必须是最长 18 个字符的字母数字字符串。

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | 格式化字符串。 |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


标识生产日期。可以将生产日期设置为 DateTime.MinValue 以不使用此字段。默认值：DateTime.MinValue。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


标识有效期。如果 ExpiryDateFormat 未设置为 None，则将使用此值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


标识有效期格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


标识批号或批次号。批号/批次号必须是最长 18 个字符的字母数字字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


标识数量，必须是 0 到 500 的整数值。数量可以设置为 -1 以不使用此字段。默认值：-1。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


标识序列号。序列号必须是最长 18 个字符的字母数字字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

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

