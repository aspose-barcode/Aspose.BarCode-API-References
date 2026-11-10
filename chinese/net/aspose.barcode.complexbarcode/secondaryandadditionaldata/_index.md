---
title: "类 SecondaryAndAdditionalData"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.ComplexBarcode.SecondaryAndAdditionalData 类。用于存储 HIBC LIC 次要和附加数据的类"
type: docs
weight: 770
url: /zh/net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class

用于存储 HIBC LIC 次要和附加数据的类.

```csharp
public class SecondaryAndAdditionalData
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SecondaryAndAdditionalData](secondaryandadditionaldata/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DateOfManufacture](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/dateofmanufacture/) { get; set; } | 标识制造日期。可以将制造日期设置为 DateTime.MinValue 以不使用此字段。默认值：DateTime.MinValue |
| [ExpiryDate](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydate/) { get; set; } | 标识到期日期。如果 ExpiryDateFormat 未设置为 None，则会使用此字段。 |
| [ExpiryDateFormat](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydateformat/) { get; set; } | 标识到期日期格式。 |
| [LotNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/lotnumber/) { get; set; } | 标识批号或批次号。批号/批次号必须是最长为 18 个字符的字母数字字符串。 |
| [Quantity](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/quantity/) { get; set; } | 标识数量，必须是 0 到 500 的整数。数量可以设置为 -1 以表示不使用此字段。默认值：-1 |
| [SerialNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/serialnumber/) { get; set; } | 标识序列号。序列号必须是最长为 18 个字符的字母数字字符串。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/equals/)(object) | 返回一个值，指示此实例是否等于指定的 `SecondaryAndAdditionalData` 值。 |
| override [GetHashCode](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/gethashcode/)() | 返回此实例的哈希码。 |
| [ParseFromString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/parsefromstring/)(string) | 根据 HIBC LIC 规范，从字符串格式实例化二级和附加补充数据。 |
| override [ToString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/tostring/)() | 根据 HIBC LIC 规范，将数据转换为字符串格式。 |

### 另见

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


