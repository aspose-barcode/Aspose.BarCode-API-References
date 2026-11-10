---
title: "类 AztecParameters"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.AztecParameters 类。Aztec 参数"
type: docs
weight: 960
url: /zh/net/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class

Aztec 参数。

```csharp
public class AztecParameters
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/aztecparameters/aspectratio/) { get; set; } | 2D 条码模块的高/宽比。 |
| [ECIEncoding](../../aspose.barcode.generation/aztecparameters/eciencoding/) { get; set; } | 获取或设置 ECI 编码。当 AztecEncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.generation/aztecparameters/encodemode/) { get; set; } | 获取或设置 Aztec 编码模式。默认值：Auto。 |
| [ErrorLevel](../../aspose.barcode.generation/aztecparameters/errorlevel/) { get; set; } | Aztec 条码的错误纠正级别。取值应在 5 到 95 之间。 |
| [IsReaderInitialization](../../aspose.barcode.generation/aztecparameters/isreaderinitialization/) { get; set; } | 用于指示阅读器将符号中包含的数据解释为用于阅读器初始化的程序。 |
| [LayersCount](../../aspose.barcode.generation/aztecparameters/layerscount/) { get; set; } | 获取或设置 Aztec 符号的层数。紧凑模式下层数应在 1 到 3 范围内，完整范围模式下应在 1 到 32 范围内。默认值：0（自动）。 |
| [StructuredAppendBarcodeId](../../aspose.barcode.generation/aztecparameters/structuredappendbarcodeid/) { get; set; } | 结构追加模式下 Aztec 条码的条码 ID。条码 ID 应在 1 到条码总数范围内。默认值：0。 |
| [StructuredAppendBarcodesCount](../../aspose.barcode.generation/aztecparameters/structuredappendbarcodescount/) { get; set; } | Aztec 条形码的结构追加模式的条码计数。条码计数应在 1 到 26 的范围内。默认值：0 |
| [StructuredAppendFileId](../../aspose.barcode.generation/aztecparameters/structuredappendfileid/) { get; set; } | Aztec 条形码结构追加模式的文件 ID（可选字段）。文件 ID 不应包含空格。默认值：空字符串 |
| [SymbolMode](../../aspose.barcode.generation/aztecparameters/symbolmode/) { get; set; } | 获取或设置 Aztec 符号模式。默认值：AztecSymbolMode.Auto。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/aztecparameters/tostring/)() | 返回此 `AztecParameters` 的人类可读字符串表示形式。 |

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


