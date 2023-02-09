---
title: Mailmark2DCodetext
second_title: Aspose.BarCode for .NET API 参考
description: 用于对嵌入皇家邮政二维邮戳代码中的文本进行编码和解码的类
type: docs
weight: 360
url: /zh/net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class

用于对嵌入皇家邮政二维邮戳代码中的文本进行编码和解码的类。

```csharp
public sealed class Mailmark2DCodetext : IComplexCodetext
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Mailmark2DCodetext](mailmark2dcodetext)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmark2dcodetext/class) { get; set; } | 标识项目的类别。 |
| [CustomerContent](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontent) { get; set; } | 供客户使用的可选空间。 |
| [CustomerContentEncodeMode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontentencodemode) { get; set; } | Datamatrix条码的编码模式。 默认值：DataMatrixEncodeMode.C40. |
| [DataMatrixType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/datamatrixtype) { get; set; } | 2D Mailmark Type 定义 Data Matrix 条形码的大小。 |
| [DestinationPostCodeAndDPS](../../aspose.barcode.complexbarcode/mailmark2dcodetext/destinationpostcodeanddps) { get; set; } | 包含 DPS 的收货地址的邮政编码 如果内陆，邮政编码/DP 包含以下字符数。 区域（1 或 2 个字符） 地区（1 或 2 个字符） 部门（1 个字符） 单位（2 个字符） DPS （2 个字符）. 邮政编码和 DPS 必须符合有效的 PAF® 格式。 |
| [InformationTypeID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/informationtypeid) { get; set; } | 标识每种产品类型的 Royal Mail Mailmark 条形码有效负载。 |
| [ItemID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/itemid) { get; set; } | 标识供应链 ID 中的唯一项目。 每个 Mailmark 条码都需要携带一个 ID ，因此它可以被唯一标识至少 90 天。 最大值：99999999. |
| [ReturnToSenderPostCode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/returntosenderpostcode) { get; set; } | 包含退回发件人邮政编码，但没有 DPS。 PC（无 DPS）必须符合 PAF® 格式。 |
| [RTSFlag](../../aspose.barcode.complexbarcode/mailmark2dcodetext/rtsflag) { get; set; } | 指示正在请求返回发件人服务级别的标志。 |
| [SupplyChainID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/supplychainid) { get; set; } | 标识参与邮寄的唯一客户组。 最大值：9999999。 |
| [UPUCountryID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/upucountryid) { get; set; } | 标识 UPU 国家 ID。最大长度：4 个字符。 |
| [VersionID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/versionid) { get; set; } | 标识与每个信息类型 ID 相关的条形码版本。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getbarcodetype)() | 获取条码类型。 |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getconstructedcodetext)() | 从 Mailmark 数据构造代码文本。 |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmark2dcodetext/initfromstring)(string) | 从构造的代码文本初始化 Mailmark 数据。 |

### 也可以看看

* interface [IComplexCodetext](../icomplexcodetext)
* 命名空间 [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode)
* 部件 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->