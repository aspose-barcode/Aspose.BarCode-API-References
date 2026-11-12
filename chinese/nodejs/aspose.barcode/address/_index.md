---
title: "地址"
linktitle: "地址"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "债权人或债务人的地址。"
type: docs
weight: 10
url: /zh/nodejs/aspose.barcode/address/
---

## Address class

债权人或债务人的地址。您可以设置街道、门牌号、邮政编码和城镇（结构化地址类型），或设置地址行 1 和 2（组合地址元素类型）。一旦设置了任意这些字段，地址类型会自动确定。设置字段之前，地址类型为未确定。如果同时设置了两种类型的字段，地址类型将变为冲突。除非所有字段均为空，否则必须始终设置姓名和国家代码。

```js
new Address()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [clear()](#clear) | 清除所有字段并将类型设置为 AddressType.UNDETERMINED。 |
| [equals(obj)](#equals) | 确定指定的对象是否等于当前对象。 |
| [getAddressLine1()](#getaddressline1) | 获取地址行 1。地址行 1 包含街道名称、门牌号或邮政信箱。设置此字段会设置 addr |
| [getAddressLine2()](#getaddressline2) | 获取地址行 2。地址行 2 包含邮政编码和城镇。设置此字段会将地址类型设置为 Addre |
| [getCountryCode()](#getcountrycode) | 获取两字母 ISO 国家代码。除非整个地址为 null 或为空值，否则国家代码是必填的。 |
| [getHouseNo()](#gethouseno) | 获取门牌号。设置此字段会将地址类型设置为 AddressType.STRUCTURED，除非它已经是 AddressTyp |
| [getName()](#getname) | 获取姓名，可为自然人的名和姓，或法人的公司名称。 |
| [getPostalCode()](#getpostalcode) | 获取邮政编码。设置此字段会将地址类型设置为 AddressType.STRUCTURED，除非它已经是 AddressType |
| [getStreet()](#getstreet) | 获取街道。街道必须在不包含门牌号的情况下指定。设置此字段会将地址类型设置为 AddressT |
| [getTown()](#gettown) | 获取城镇或城市。设置此字段会将地址类型设置为 AddressType.STRUCTURED，除非它已经是 AddressTyp |
| [getType()](#gettype) | 获取地址类型。地址类型会在设置街道/门牌号或地址行 1 时自动确定 a |
| [hashCode()](#hashcode) | 获取此实例的哈希码。 |
| [setAddressLine1(value:)](#setaddressline1) | 设置地址行 1。地址行 1 包含街道名称、门牌号或邮政信箱。设置此字段会设置 addr |
| [setAddressLine2(value:)](#setaddressline2) | 设置地址行 2。地址行 2 包含邮政编码和城镇。设置此字段会将地址类型设置为 Addre |
| [setCountryCode(value)](#setcountrycode) | 设置两字母 ISO 国家代码。除非整个地址包含 null 或 emtpy val，否则该国家代码是必需的。 |
| [setHouseNo(value:)](#sethouseno) | 设置门牌号。设置此字段会将地址类型设置为 AddressType.STRUCTURED，除非它已经是 AddressTyp |
| [setName(value:)](#setname) | 设置名称，可以是自然人的名字和姓氏，或法人的公司名称。 |
| [setPostalCode(value)](#setpostalcode) | 设置邮政编码。设置此字段会将地址类型设置为 AddressType.STRUCTURED，除非它已经是 AddressType。 |
| [setStreet(value:)](#setstreet) | 设置街道。街道必须在不包含门牌号的情况下指定。设置此字段会将地址类型设置为 AddressT |
| [setTown(value)](#settown) | 设置城镇或城市。设置此字段会将地址类型设置为 AddressType.STRUCTURED，除非它已经是 AddressTyp。 |

### clear() {#clear}

清除所有字段并将类型设置为 AddressType.UNDETERMINED。

### equals(obj) {#equals}

确定指定的对象是否等于当前对象。

| 参数 | 描述 |
| --- | --- |
| obj | 与当前对象比较的对象。 |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAddressLine1() {#getaddressline1}

获取地址行 1。地址行 1 包含街道名称、门牌号或邮政信箱。设置此字段会将地址类型设置为 AddressType.COMBINED_ELEMENTS，除非它已经是 AddressType.STRUCTURED，在这种情况下会变为 AddressType.CONFLICTING。此字段仅用于组合元素地址，且为可选项。

**Returns:** The address line 1.

### getAddressLine2() {#getaddressline2}

获取地址行 2。地址行 2 包含邮政编码和城镇。设置此字段会将地址类型设置为 AddressType.COMBINED_ELEMENTS，除非它已经是 AddressType.STRUCTURED，在这种情况下会变为 AddressType.CONFLICTING。此字段仅用于组合元素地址。对于此类型，它是必需的。

**Returns:** The address line 2.

### getCountryCode() {#getcountrycode}

获取两字母 ISO 国家代码。除非整个地址包含 null 或 emtpy values，否则该国家代码是必需的。

**Returns:** The ISO country code.

### getHouseNo() {#gethouseno}

获取门牌号。设置此字段会将地址类型设置为 AddressType.STRUCTURED，除非它已经是 AddressType.COMBINED_ELEMENTS，在这种情况下会变为 AddressType.CONFLICTING。此字段仅用于结构化地址，且为可选项。

**Returns:** The house number.

### getName() {#getname}

获取姓名，可为自然人的名和姓，或法人的公司名称。

**Returns:** The name.

### getPostalCode() {#getpostalcode}

获取邮政编码。设置此字段会将地址类型设置为 AddressType.STRUCTURED，除非它已经是 AddressType.COMBINED_ELEMENTS，在这种情况下会变为 AddressType.CONFLICTING。此字段仅用于结构化地址。对于此类型，它是必需的。

**Returns:** The postal code.

### getStreet() {#getstreet}

获取街道。街道必须在不包含门牌号的情况下指定。设置此字段会将地址类型设置为 AddressType.STRUCTURED，除非它已经是 AddressType.COMBINED_ELEMENTS，在这种情况下会变为 AddressType.CONFLICTING。此字段仅用于结构化地址，且为可选项。

**Returns:** The street.

### getTown() {#gettown}

获取城镇或城市。设置此字段会将地址类型设置为 AddressType.STRUCTURED，除非它已经是 AddressType.COMBINED_ELEMENTS，在这种情况下会变为 AddressType.CONFLICTING。此字段仅用于结构化地址。对于此类型，它是必需的。

**Returns:** The town or city.

### getType() {#gettype}

获取地址类型。地址类型会通过设置街道/门牌号或地址行 1 和 2 自动设置。在设置字段之前，地址类型为 Undetermined。如果两种类型的字段都被设置，地址类型将变为 Conflicting。

**Returns:** The address type.

### hashCode() {#hashcode}

获取此实例的哈希码。

**Returns:** A hash code for the current object .

### setAddressLine1(value:) {#setaddressline1}

设置地址行 1。地址行 1 包含街道名称、门牌号或邮政信箱。设置此字段会将地址类型设置为 AddressType.COMBINED_ELEMENTS，除非它已经是 AddressType.STRUCTURED，在这种情况下会变为 AddressType.CONFLICTING。此字段仅用于组合元素地址，且为可选项。

| 参数 | 描述 |
| --- | --- |
| 值： | 地址行 1。 |

### setAddressLine2(value:) {#setaddressline2}

设置地址行 2。地址行 2 包含邮政编码和城镇。设置此字段会将地址类型设置为 AddressType.COMBINED_ELEMENTS，除非它已经是 AddressType.STRUCTURED，在这种情况下会变为 AddressType.CONFLICTING。此字段仅用于组合元素地址。对于此类型，它是必需的。

| 参数 | 描述 |
| --- | --- |
| 值： | 地址行 2。 |

### setCountryCode(value) {#setcountrycode}

设置两字母 ISO 国家代码。除非整个地址包含 null 或 emtpy values，否则该国家代码是必需的。

| 参数 | 描述 |
| --- | --- |
| 值 | ISO 国家代码。 |

### setHouseNo(value:) {#sethouseno}

设置门牌号。设置此字段会将地址类型设置为 AddressType.STRUCTURED，除非它已经是 AddressType.COMBINED_ELEMENTS，在这种情况下会变为 AddressType.CONFLICTING。此字段仅用于结构化地址，且为可选项。

| 参数 | 描述 |
| --- | --- |
| 值： | 门牌号。 |

### setName(value:) {#setname}

设置名称，可以是自然人的名字和姓氏，或法人的公司名称。

| 参数 | 描述 |
| --- | --- |
| 值： | 名称。 |

### setPostalCode(value) {#setpostalcode}

设置邮政编码。设置此字段会将地址类型设为 AddressType.STRUCTURED，除非它已经是 AddressType.COMBINED_ELEMENTS，此时会变为 AddressType.CONFLICTING。此字段仅用于结构化地址。对于此类型，它是必填的。

| 参数 | 描述 |
| --- | --- |
| 值 | 邮政编码。 |

### setStreet(value:) {#setstreet}

设置街道。街道必须在不包含门牌号的情况下指定。设置此字段会将地址类型设为 AddressType.STRUCTURED，除非它已经是 AddressType.COMBINED_ELEMENTS，此时会变为 AddressType.CONFLICTING。此字段仅用于结构化地址，且为可选项。

| 参数 | 描述 |
| --- | --- |
| 值： | 街道。 |

### setTown(value) {#settown}

设置城镇或城市。设置此字段会将地址类型设为 AddressType.STRUCTURED，除非它已经是 AddressType.COMBINED_ELEMENTS，此时会变为 AddressType.CONFLICTING。此字段仅用于结构化地址。对于此类型，它是必填的。

| 参数 | 描述 |
| --- | --- |
| 值 | 城镇或城市。 |
