---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext 类"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext 类。用于对嵌入 HIBC LIC 代码中、在 C++ 中存储主数据的文本进行编码和解码的类。"
type: docs
weight: 900
url: /zh/cpp/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class


用于对嵌入 HIBC LIC 代码中、存储主数据的文本进行编码和解码的类。

```cpp
class HIBCLICPrimaryDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 返回一个值，指示此实例是否等于指定的 [HIBCLICPrimaryDataCodetext](./) 值。 |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | 获取条形码类型。HIBC LIC 编码文本可以使用 HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC 和 HIBCQRLIC 编码类型进行编码。默认值：HIBCCode39LIC。 |
| [get_Data](./get_data/)() const | 标识主数据。 |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | 获取条形码类型。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 构造编码文本 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | 从构造的编码文本初始化实例。 |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | 设置条形码类型。HIBC LIC 编码文本可以使用 HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC 和 HIBCQRLIC 编码类型进行编码。默认值：HIBCCode39LIC。 |
| [set_Data](./set_data/)(System::SharedPtr\<PrimaryData\>) | 标识主数据。 |
## 备注


此示例展示了如何使用 [HIBCLICPrimaryDataCodetext](./) 对 HIBC LIC 进行编码和解码。
```cpp
[C#]
HIBCLICPrimaryDataCodetext complexCodetext  = new HIBCLICPrimaryDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.Data = new PrimaryData();
complexCodetext.Data.ProductOrCatalogNumber = "12345";
complexCodetext.Data.LabelerIdentificationCode = "A999";
complexCodetext.Data.UnitOfMeasureID = 1;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICPrimaryDataCodetext result = (HIBCLICPrimaryDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.Data.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.Data.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.Data.UnitOfMeasureID);
    }
}
```

## 另见

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
