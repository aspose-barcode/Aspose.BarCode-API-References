---
title: "类 PrimaryData"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.ComplexBarcode.PrimaryData 类。用于存储 HIBC LIC 主数据的类"
type: docs
weight: 760
url: /zh/net/aspose.barcode.complexbarcode/primarydata/
---
## PrimaryData class

用于存储 HIBC LIC 主数据的类.

```csharp
public class PrimaryData
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PrimaryData](primarydata/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [LabelerIdentificationCode](../../aspose.barcode.complexbarcode/primarydata/labeleridentificationcode/) { get; set; } | 标识标签者识别码的日期。标签者识别码必须是 4 个字符的字母数字字符串，且首字符必须为字母。 |
| [ProductOrCatalogNumber](../../aspose.barcode.complexbarcode/primarydata/productorcatalognumber/) { get; set; } | 标识产品或目录编号。产品或目录编号必须是最长为 18 个字符的字母数字字符串。 |
| [UnitOfMeasureID](../../aspose.barcode.complexbarcode/primarydata/unitofmeasureid/) { get; set; } | 标识计量单位 ID。计量单位 ID 必须是 0 到 9 的整数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/primarydata/equals/)(object) | 返回一个值，指示此实例是否等于指定的 `PrimaryData` 值。 |
| override [GetHashCode](../../aspose.barcode.complexbarcode/primarydata/gethashcode/)() | 返回此实例的哈希码。 |
| [ParseFromString](../../aspose.barcode.complexbarcode/primarydata/parsefromstring/)(string) | 根据 HIBC LIC 规范，从字符串格式实例化主数据。 |
| override [ToString](../../aspose.barcode.complexbarcode/primarydata/tostring/)() | 根据 HIBC LIC 规范，将数据转换为字符串格式。 |

### 另见

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


