---
title: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext 类"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext 类。用于在 C++ 中对嵌入 HIBC PAS 代码的文本进行编码和解码的类。"
type: docs
weight: 1100
url: /zh/cpp/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class


用于对嵌入 HIBC PAS 代码中的文本进行编码和解码的类。

```cpp
class HIBCPASCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [AddRecord](./addrecord/)(HIBCPASDataType, System::String) | 添加新记录 |
| [AddRecord](./addrecord/)(System::SharedPtr\<HIBCPASRecord\>) | 添加新记录 |
| [Clear](./clear/)() | 清除记录列表 |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 返回一个值，指示此实例是否等于指定的 [HIBCPASCodetext](./) 值。 |
| [get_BarcodeType](./get_barcodetype/)() const | 获取条形码类型。HIBC PAS 文本可以使用 HIBCCode39PAS、HIBCCode128PAS、HIBCAztec:PAS、HIBCDataMatrixPAS 和 HIBCQRPAS 编码类型进行编码。默认值：HIBCCode39PAS。 |
| [get_DataLocation](./get_datalocation/)() const | 标识数据位置。 |
| [GetBarcodeType](./getbarcodetype/)() override | 获取条形码类型。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 构造编码文本 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [GetRecords](./getrecords/)() | 获取记录列表 |
| [HIBCPASCodetext](./hibcpascodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | 从构造的编码文本初始化实例。 |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | 设置条形码类型。HIBC PAS 文本可以使用 HIBCCode39PAS、HIBCCode128PAS、HIBCAztec:PAS、HIBCDataMatrixPAS 和 HIBCQRPAS 编码类型进行编码。默认值：HIBCCode39PAS。 |
| [set_DataLocation](./set_datalocation/)(HIBCPASDataLocation) | 标识数据位置。 |
## 备注


此示例展示了如何使用 [HIBCPASCodetext](./) 对 HIBC PAS 进行编码和解码。
```cpp
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

## 另见

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
