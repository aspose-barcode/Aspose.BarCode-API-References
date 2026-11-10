---
title: "类 Mailmark2DCodetext"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.ComplexBarcode.Mailmark2DCodetext 类。用于对嵌入在 Royal Mail 2D Mailmark 代码中的文本进行编码和解码的类。"
type: docs
weight: 650
url: /zh/net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class

用于对嵌入在 Royal Mail 2D Mailmark 代码中的文本进行编码和解码的类.

```csharp
public sealed class Mailmark2DCodetext : IComplexCodetext
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Mailmark2DCodetext](mailmark2dcodetext/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmark2dcodetext/class/) { get; set; } | 识别项目的类。 |
| [CustomerContent](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontent/) { get; set; } | 供客户使用的可选空间。 |
| [CustomerContentEncodeMode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontentencodemode/) { get; set; } | Datamatrix 条码的编码模式。默认值：EncodeMode.C40。 |
| [DataMatrixType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/datamatrixtype/) { get; set; } | 2D Mailmark 类型定义 Data Matrix 条码的尺寸。 |
| [DestinationPostCodeAndDPS](../../aspose.barcode.complexbarcode/mailmark2dcodetext/destinationpostcodeanddps/) { get; set; } | 包含带有 DPS 的收货地址邮编。如果在内陆，邮编/DP 包含以下字符数：地区（1 或 2 个字符） 区（1 或 2 个字符） 扇区（1 个字符） 单元（2 个字符） DPS（2 个字符）。邮编和 DPS 必须符合有效的 PAF® 格式。 |
| [InformationTypeID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/informationtypeid/) { get; set; } | 标识每种产品类型的皇家邮政 Mailmark 条码负载。 |
| [ItemID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/itemid/) { get; set; } | 标识供应链 ID 中的唯一项目。每个 Mailmark 条码必须携带一个 ID，以便在至少 90 天内唯一识别。最大值：99999999。 |
| [ReturnToSenderPostCode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/returntosenderpostcode/) { get; set; } | 包含退回发件人邮编，但不含 DPS。没有 DPS 的邮编（PC）必须符合 PAF® 格式。 |
| [RTSFlag](../../aspose.barcode.complexbarcode/mailmark2dcodetext/rtsflag/) { get; set; } | 指示请求的退回发件人服务级别的标志。 |
| [SupplyChainID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/supplychainid/) { get; set; } | 标识参与邮件投递的唯一客户组。最大值：9999999。 |
| [UPUCountryID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/upucountryid/) { get; set; } | 标识 UPU 国家 ID。最大长度：4 个字符。 |
| [VersionID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/versionid/) { get; set; } | 标识与每个信息类型 ID 相关的条码版本。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getbarcodetype/)() | 获取条形码类型。 |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getconstructedcodetext/)() | 从 Mailmark 数据构建编码文本。 |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmark2dcodetext/initfromstring/)(string) | 从构建的编码文本初始化 Mailmark 数据。 |

### 另见

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


