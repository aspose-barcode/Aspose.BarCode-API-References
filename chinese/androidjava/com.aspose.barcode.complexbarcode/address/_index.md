---
title: 地址
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 债权人或债务人的地址。
type: docs
weight: 10
url: /zh/androidjava/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

债权人或债务人的地址。

您可以设置街道、门牌号、邮政编码和城镇（类型 *structured address*）或地址行 1 和 2（类型 *combined address elements*）。一旦设置了任意这些字段，类型会自动设置。设置字段之前，地址类型为 *undetermined*。如果同时设置了两种类型的字段，地址类型将变为 *conflicting*。除非所有字段均为空，否则必须始终设置姓名和国家代码。
## Constructors

| Constructor | 描述 |
| --- | --- |
| [Address()](#Address--) | 创建 Address 实例 |
## Methods

| Method | 描述 |
| --- | --- |
| [clear()](#clear--) | 清除所有字段并将类型设置为  AddressType.Undetermined 。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的对象是否等于当前对象。 |
| [getAddressLine1()](#getAddressLine1--) | 获取地址行 1。 |
| [getAddressLine2()](#getAddressLine2--) | 获取地址行 2。 |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | 获取两字母 ISO 国家代码。 |
| [getHouseNo()](#getHouseNo--) | 获取门牌号。 |
| [getName()](#getName--) | 获取名称，可为自然人的姓名（名和姓）或法人的公司名称。 |
| [getPostalCode()](#getPostalCode--) | 获取邮政编码。 |
| [getStreet()](#getStreet--) | 获取街道。 |
| [getTown()](#getTown--) | 获取城镇或城市。 |
| [getType()](#getType--) | 获取地址类型。 |
| [hashCode()](#hashCode--) | 获取此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | 设置地址行 1。 |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | 设置地址行 2。 |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | 设置两字母 ISO 国家代码。 |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | 设置门牌号。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称，可为自然人的姓名（名和姓）或法人的公司名称。 |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | 设置邮政编码。 |
| [setStreet(String value)](#setStreet-java.lang.String-) | 设置街道。 |
| [setTown(String value)](#setTown-java.lang.String-) | 设置城镇或城市。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


创建 Address 实例

### clear() {#clear--}
```
public void clear()
```


清除所有字段并将类型设置为  AddressType.Undetermined 。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的对象是否等于当前对象。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与当前对象比较的对象。 |

**Returns:**
boolean - 如果指定的对象等于当前对象则为 true；否则为 false。
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


获取地址行 1。

地址行 1 包含街道名称、门牌号或邮政信箱。

设置此字段会将地址类型设置为  AddressType.CombinedElements ，除非它已经是  AddressType.Structured ，此时会变为  AddressType.Conflicting 。

此字段仅用于组合元素地址，且为可选项。

值：地址行 1。

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


获取地址行 2。

地址行 2 包含邮政编码和城镇。

设置此字段会将地址类型设置为  AddressType.CombinedElements ，除非它已经是  AddressType.Structured ，此时会变为  AddressType.Conflicting 。

此字段仅用于组合元素地址。对于此类型，它是必填项。

值：地址行 2。

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryCode() {#getCountryCode--}
```
public String getCountryCode()
```


获取两字母 ISO 国家代码。

除非整个地址包含  null  或空值，否则国家代码是必填的。

值：ISO 国家代码。

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


获取门牌号。

设置此字段会将地址类型设为  AddressType.Structured ，除非它已经是  AddressType.CombinedElements ，在这种情况下它会变为  AddressType.Conflicting 。

此字段仅用于结构化地址，且为可选项。

值：门牌号。

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


获取名称，可为自然人的姓名（名和姓）或法人的公司名称。

值：名称。

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


获取邮政编码。

设置此字段会将地址类型设为  AddressType.Structured ，除非它已经是  AddressType.CombinedElements ，在这种情况下它会变为  AddressType.Conflicting 。

此字段仅用于结构化地址。对于此类型，它是必填的。

值：邮政编码。

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


获取街道。

街道必须在不包含门牌号的情况下指定。

设置此字段会将地址类型设为  AddressType.Structured ，除非它已经是  AddressType.CombinedElements ，在这种情况下它会变为  AddressType.Conflicting 。

此字段仅用于结构化地址，且为可选项。

值：街道。

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


获取城镇或城市。

设置此字段会将地址类型设为  AddressType.Structured ，除非它已经是  AddressType.CombinedElements ，在这种情况下它会变为  AddressType.Conflicting 。

此字段仅用于结构化地址。对于此类型，它是必填的。

值：城镇或城市。

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


获取地址类型。

地址类型会通过设置街道/门牌号或地址行 1 和 2 自动确定。在设置字段之前，地址类型为  *Undetermined* 。如果同时设置了两种类型的字段，地址类型将变为  *Conflicting* 。

值：地址类型。

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取此实例的哈希码。

**Returns:**
int - 当前对象的哈希码。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public void setAddressLine1(String value)
```


设置地址行 1。

地址行 1 包含街道名称、门牌号或邮政信箱。

设置此字段会将地址类型设置为  AddressType.CombinedElements ，除非它已经是  AddressType.Structured ，此时会变为  AddressType.Conflicting 。

此字段仅用于组合元素地址，且为可选项。

值：地址行 1。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


设置地址行 2。

地址行 2 包含邮政编码和城镇。

设置此字段会将地址类型设置为  AddressType.CombinedElements ，除非它已经是  AddressType.Structured ，此时会变为  AddressType.Conflicting 。

此字段仅用于组合元素地址。对于此类型，它是必填项。

值：地址行 2。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


设置两字母 ISO 国家代码。

除非整个地址包含  null  或空值，否则国家代码是必填的。

值：ISO 国家代码。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


设置门牌号。

设置此字段会将地址类型设为  AddressType.Structured ，除非它已经是  AddressType.CombinedElements ，在这种情况下它会变为  AddressType.Conflicting 。

此字段仅用于结构化地址，且为可选项。

值：门牌号。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称，可为自然人的姓名（名和姓）或法人的公司名称。

值：名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


设置邮政编码。

设置此字段会将地址类型设为  AddressType.Structured ，除非它已经是  AddressType.CombinedElements ，在这种情况下它会变为  AddressType.Conflicting 。

此字段仅用于结构化地址。对于此类型，它是必填的。

值：邮政编码。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


设置街道。

街道必须在不包含门牌号的情况下指定。

设置此字段会将地址类型设为  AddressType.Structured ，除非它已经是  AddressType.CombinedElements ，在这种情况下它会变为  AddressType.Conflicting 。

此字段仅用于结构化地址，且为可选项。

值：街道。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


设置城镇或城市。

设置此字段会将地址类型设为  AddressType.Structured ，除非它已经是  AddressType.CombinedElements ，在这种情况下它会变为  AddressType.Conflicting 。

此字段仅用于结构化地址。对于此类型，它是必填的。

值：城镇或城市。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

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

