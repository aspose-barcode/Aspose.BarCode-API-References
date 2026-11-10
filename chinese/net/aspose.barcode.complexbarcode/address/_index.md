---
title: "类 Address"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.ComplexBarcode.Address 类。债权人或债务人的地址。"
type: docs
weight: 480
url: /zh/net/aspose.barcode.complexbarcode/address/
---
## Address class

债权人或债务人的地址。

您可以设置街道、门牌号、邮政编码和城镇（结构化地址类型），或设置地址行 1 和 2（组合地址元素类型）。一旦设置任何这些字段，类型会自动确定。设置字段之前，地址类型为未确定。如果同时设置两种类型的字段，地址类型将变为冲突。除非所有字段均为空，否则必须始终设置名称和国家代码。

```csharp
public sealed class Address : IEquatable<Address>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Address](address/)() | 创建 Address 实例 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AddressLine1](../../aspose.barcode.complexbarcode/address/addressline1/) { get; set; } | 获取或设置地址行 1。 |
| [AddressLine2](../../aspose.barcode.complexbarcode/address/addressline2/) { get; set; } | 获取或设置地址行 2。 |
| [CountryCode](../../aspose.barcode.complexbarcode/address/countrycode/) { get; set; } | 获取或设置两字母 ISO 国家代码。 |
| [HouseNo](../../aspose.barcode.complexbarcode/address/houseno/) { get; set; } | 获取或设置门牌号。 |
| [Name](../../aspose.barcode.complexbarcode/address/name/) { get; set; } | 获取或设置名称，可以是自然人的名和姓，或法人的公司名称。 |
| [PostalCode](../../aspose.barcode.complexbarcode/address/postalcode/) { get; set; } | 获取或设置邮政编码。 |
| [Street](../../aspose.barcode.complexbarcode/address/street/) { get; set; } | 获取或设置街道。 |
| [Town](../../aspose.barcode.complexbarcode/address/town/) { get; set; } | 获取或设置城镇或城市。 |
| [Type](../../aspose.barcode.complexbarcode/address/type/) { get; } | 获取地址类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clear](../../aspose.barcode.complexbarcode/address/clear/)() | 清除所有字段并将类型设置为未确定。 |
| [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals)(Address) | 确定指定的地址是否等于当前地址。 |
| override [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals_1)(object) | 确定指定的对象是否等于当前对象。 |
| override [GetHashCode](../../aspose.barcode.complexbarcode/address/gethashcode/)() | 获取此实例的哈希码。 |

### 另见

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


