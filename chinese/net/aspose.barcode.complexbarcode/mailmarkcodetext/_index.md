---
title: "类 MailmarkCodetext"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.ComplexBarcode.MailmarkCodetext 类。用于对嵌入在 4 状态 Royal Mailmark 代码中的文本进行编码和解码的类。"
type: docs
weight: 670
url: /zh/net/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class

用于对嵌入在 4 状态 Royal Mailmark 代码中的文本进行编码和解码的类.

```csharp
public sealed class MailmarkCodetext : IComplexCodetext
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MailmarkCodetext](mailmarkcodetext/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmarkcodetext/class/) { get; set; } | \"0\" - 空或测试 \"1\" - 1C（零售） \"2\" - 2C（零售） \"3\" - 3C（零售） \"4\" - 高级（RetailPublishing Mail）（供未来使用） \"5\" - 延迟（零售）（供未来使用） \"6\" - 空运（零售）（供未来使用） \"7\" - 地面（零售）（供未来使用） \"8\" - 高级（网络访问） \"9\" - 标准（网络访问） |
| [DestinationPostCodePlusDPS](../../aspose.barcode.complexbarcode/mailmarkcodetext/destinationpostcodeplusdps/) { get; set; } | PC 和 DP 必须符合 PAF 格式。九字符字符串表示国际 \"XY11 \"（注意后面的 5 个空格）或表示国内分拣代码的字符模式。国内分拣代码由外部邮编、内部邮编和投递点后缀组成。 |
| [Format](../../aspose.barcode.complexbarcode/mailmarkcodetext/format/) { get; set; } | \"0\" – 空或测试 \"1\" – 信件 \"2\" – 大信件 |
| [ItemID](../../aspose.barcode.complexbarcode/mailmarkcodetext/itemid/) { get; set; } | 最大值为 99999999。 |
| [SupplychainID](../../aspose.barcode.complexbarcode/mailmarkcodetext/supplychainid/) { get; set; } | Barcode C 的最大值为 99，Barcode L 的最大值为 999999。 |
| [VersionID](../../aspose.barcode.complexbarcode/mailmarkcodetext/versionid/) { get; set; } | 当前 \"1\" – 用于 Mailmark 条形码（0 以及 2 到 9 和 A 到 Z 预留供未来使用） |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmarkcodetext/getbarcodetype/)() | 获取条形码类型。 |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmarkcodetext/getconstructedcodetext/)() | 从 Mailmark 数据构建编码文本。 |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmarkcodetext/initfromstring/)(string) | 从构建的编码文本初始化 Mailmark 数据。 |

### 另见

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


