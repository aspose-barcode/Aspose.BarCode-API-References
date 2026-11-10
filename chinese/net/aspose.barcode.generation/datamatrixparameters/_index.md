---
title: "类 DataMatrixParameters"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.DataMatrixParameters 类。DataMatrix 参数"
type: docs
weight: 1220
url: /zh/net/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class

DataMatrix 参数。

```csharp
public class DataMatrixParameters
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/datamatrixparameters/aspectratio/) { get; set; } | 2D 条码模块的高/宽比。 |
| [EccType](../../aspose.barcode.generation/datamatrixparameters/ecctype/) { get; set; } | 获取或设置 Datamatrix ECC 类型。默认值：DataMatrixEccType.Ecc200。 |
| [ECIEncoding](../../aspose.barcode.generation/datamatrixparameters/eciencoding/) { get; set; } | 获取或设置 ECI 编码。当 EncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.generation/datamatrixparameters/encodemode/) { get; set; } | Datamatrix 条码的编码模式。默认值：EncodeMode.Auto。 |
| [IsReaderProgramming](../../aspose.barcode.generation/datamatrixparameters/isreaderprogramming/) { get; set; } | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。默认值：false |
| [MacroCharacters](../../aspose.barcode.generation/datamatrixparameters/macrocharacters/) { get; set; } | 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 DataMatrixEccType.Ecc200 或 DataMatrixEccType.EccAuto 一起使用。不能与 EncodeTypes.GS1DataMatrix 一起使用。默认值：MacroCharacters.None。 |
| [StructuredAppendBarcodeId](../../aspose.barcode.generation/datamatrixparameters/structuredappendbarcodeid/) { get; set; } | Datamatrix 条形码的结构追加模式的条形码 ID。默认值：0 |
| [StructuredAppendBarcodesCount](../../aspose.barcode.generation/datamatrixparameters/structuredappendbarcodescount/) { get; set; } | Datamatrix 条形码的结构追加模式的条形码计数。默认值：0 |
| [StructuredAppendFileId](../../aspose.barcode.generation/datamatrixparameters/structuredappendfileid/) { get; set; } | Datamatrix 条形码的结构追加模式的文件 ID。默认值：0 |
| [Version](../../aspose.barcode.generation/datamatrixparameters/version/) { get; set; } | 获取或设置 Datamatrix 符号大小。默认值：Version.Auto。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/datamatrixparameters/tostring/)() | 返回此 `DataMatrixParameters` 的人类可读字符串表示。 |

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


