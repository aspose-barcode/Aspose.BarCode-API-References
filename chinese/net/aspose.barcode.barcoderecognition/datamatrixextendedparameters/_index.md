---
title: "类 DataMatrixExtendedParameters"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.DataMatrixExtendedParameters 类。存储 DataMatrix 已识别条码的特殊数据"
type: docs
weight: 220
url: /zh/net/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class

存储已识别 DataMatrix 条码的特殊数据。

```csharp
public sealed class DataMatrixExtendedParameters : BaseExtendedParameters
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | 测试所有参数是否仅具有默认值 |
| [IsReaderProgramming](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/isreaderprogramming/) { get; } | 指示代码是否用于指示读取器将以下数据解释为条码读取器的初始化或重新编程指令。默认值为 false。 |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodeid/) { get; } | 获取 DataMatrix 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。默认值为 -1。 |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodescount/) { get; } | 获取 DataMatrix 结构化追加模式条码的数量。默认值为 -1。计数必须在 1 到 35 之间。 |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendfileid/) { get; } | 获取 DataMatrix 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。默认值为 -1。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/equals/)(object) | 返回一个值，指示此实例是否等于指定的 `DataMatrixExtendedParameters` 值。 |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/gethashcode/)() | 返回此实例的哈希码。 |
| override [ToString](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/tostring/)() | 返回此 `DataMatrixExtendedParameters` 的人类可读字符串表示形式。 |
| [operator ==](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_equality/) | 返回一个值，指示第一个 `DataMatrixExtendedParameters` 值是否等于第二个。 |
| [operator !=](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_inequality/) | 返回一个值，指示第一个 `DataMatrixExtendedParameters` 值是否与第二个不同。 |

## 示例

此示例展示如何获取 DataMatrix 原始值

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

### 另见

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


