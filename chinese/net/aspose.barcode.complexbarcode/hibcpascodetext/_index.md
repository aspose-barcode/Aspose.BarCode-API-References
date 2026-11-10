---
title: "类 HIBCPASCodetext"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.ComplexBarcode.HIBCPASCodetext 类。用于对嵌入在 HIBC PAS 代码中的文本进行编码和解码的类"
type: docs
weight: 600
url: /zh/net/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class

用于对嵌入在 HIBC PAS 代码中的文本进行编码和解码的类.

```csharp
public class HIBCPASCodetext : IComplexCodetext
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [HIBCPASCodetext](hibcpascodetext/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/barcodetype/) { get; set; } | 获取或设置条码类型。HIBC PAS 代码文本可以使用 HIBCCode39PAS、HIBCCode128PAS、HIBCAztec:PAS、HIBCDataMatrixPAS 和 HIBCQRPAS 编码类型进行编码。默认值：HIBCCode39PAS。 |
| [DataLocation](../../aspose.barcode.complexbarcode/hibcpascodetext/datalocation/) { get; set; } | 标识数据位置。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord_1)(HIBCPASRecord) | 添加新记录 |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord)(HIBCPASDataType, string) | 添加新记录 |
| [Clear](../../aspose.barcode.complexbarcode/hibcpascodetext/clear/)() | 清除记录列表 |
| override [Equals](../../aspose.barcode.complexbarcode/hibcpascodetext/equals/)(object) | 返回一个值，指示此实例是否等于指定的 `HIBCPASCodetext` 值。 |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/getbarcodetype/)() | 获取条形码类型。 |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcpascodetext/getconstructedcodetext/)() | 构造编码文本 |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibcpascodetext/gethashcode/)() | 返回此实例的哈希码。 |
| [GetRecords](../../aspose.barcode.complexbarcode/hibcpascodetext/getrecords/)() | 获取记录列表 |
| [InitFromString](../../aspose.barcode.complexbarcode/hibcpascodetext/initfromstring/)(string) | 从构造的编码文本初始化实例。 |

## 示例

此示例展示了如何使用 HIBCPASCodetext 对 HIBC PAS 进行编码和解码。

```csharp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText; 
		HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
		Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

### 另见

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


