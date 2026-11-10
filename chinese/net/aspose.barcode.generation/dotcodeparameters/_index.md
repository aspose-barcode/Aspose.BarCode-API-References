---
title: "类 DotCodeParameters"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.DotCodeParameters 类。DotCode 参数"
type: docs
weight: 1260
url: /zh/net/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class

DotCode 参数。

```csharp
public class DotCodeParameters
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/dotcodeparameters/aspectratio/) { get; set; } | 2D 条码模块的高/宽比。 |
| [Columns](../../aspose.barcode.generation/dotcodeparameters/columns/) { get; set; } | 标识列数。DotCode 符号的行数与列数之和必须为奇数。列数必须至少为 5。默认值：-1 |
| [ECIEncoding](../../aspose.barcode.generation/dotcodeparameters/eciencoding/) { get; set; } | 标识 ECI 编码。当 DotCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.generation/dotcodeparameters/encodemode/) { get; set; } | 标识 DotCode 编码模式。默认值：Auto。 |
| [IsReaderInitialization](../../aspose.barcode.generation/dotcodeparameters/isreaderinitialization/) { get; set; } | 指示代码是否用于指示读取器将以下数据解释为条码读取器的初始化或重新编程指令。默认值为 false。 |
| [Rows](../../aspose.barcode.generation/dotcodeparameters/rows/) { get; set; } | 标识行数。DotCode 符号的行数与列数之和必须为奇数。行数必须至少为 5。默认值：-1 |
| [StructuredAppendModeBarcodeId](../../aspose.barcode.generation/dotcodeparameters/structuredappendmodebarcodeid/) { get; set; } | 标识 DotCode 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。默认值为 -1。 |
| [StructuredAppendModeBarcodesCount](../../aspose.barcode.generation/dotcodeparameters/structuredappendmodebarcodescount/) { get; set; } | 标识 DotCode 结构化追加模式条码的数量。默认值为 -1。计数必须在 1 到 35 之间。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/dotcodeparameters/tostring/)() | 返回此 `DotCodeParameters` 的可读字符串表示。 |

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


