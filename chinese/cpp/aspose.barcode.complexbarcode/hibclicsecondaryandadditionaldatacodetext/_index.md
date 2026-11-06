---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICSecondaryAndAdditionalDataCodetext 类"
linktitle: "HIBCLICSecondaryAndAdditionalDataCodetext"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICSecondaryAndAdditionalDataCodetext 类。用于在 C++ 中对嵌入 HIBC LIC 代码的文本进行编码和解码的类，该代码存储次要数据。"
type: docs
weight: 1000
url: /zh/cpp/aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
## HIBCLICSecondaryAndAdditionalDataCodetext class


用于对嵌入 HIBC LIC 代码中、存储次要数据的文本进行编码和解码的类。

```cpp
class HIBCLICSecondaryAndAdditionalDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 返回一个值，指示此实例是否等于指定的 [HIBCLICSecondaryAndAdditionalDataCodetext](./) 值。 |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | 获取条形码类型。HIBC LIC 编码文本可以使用 HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC 和 HIBCQRLIC 编码类型进行编码。默认值：HIBCCode39LIC。 |
| [get_Data](./get_data/)() const | 标识次要和附加的补充数据。 |
| [get_LinkCharacter](./get_linkcharacter/)() const | 标识链接字符。 |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | 获取条形码类型。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 构造编码文本 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | 从构造的编码文本初始化实例。 |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | 设置条形码类型。HIBC LIC 编码文本可以使用 HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC 和 HIBCQRLIC 编码类型进行编码。默认值：HIBCCode39LIC。 |
| [set_Data](./set_data/)(System::SharedPtr\<SecondaryAndAdditionalData\>) | 标识次要和附加的补充数据。 |
| [set_LinkCharacter](./set_linkcharacter/)(char16_t) | 标识链接字符。 |
## 备注


///

此示例展示了如何使用 [HIBCLICSecondaryAndAdditionalDataCodetext](./) 对 HIBC LIC 进行编码和解码。
```cpp
[C#]
HIBCLICSecondaryAndAdditionalDataCodetext complexCodetext = new HIBCLICSecondaryAndAdditionalDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.LinkCharacter = 'L';
complexCodetext.Data = new SecondaryAndAdditionalData();
complexCodetext.Data.ExpiryDate = DateTime.Now;
complexCodetext.Data.ExpiryDateFormat = HIBCLICDateFormat.MMDDYY;
complexCodetext.Data.Quantity = 30;
complexCodetext.Data.LotNumber = "LOT123";
complexCodetext.Data.SerialNumber = "SERIAL123";
complexCodetext.Data.DateOfManufacture = DateTime.Now;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICSecondaryAndAdditionalDataCodetext result = (HIBCLICSecondaryAndAdditionalDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Expiry date: " + result.Data.ExpiryDate);
        Console.WriteLine("Quantity: " + result.Data.Quantity);
        Console.WriteLine("Lot number: " + result.Data.LotNumber);
        Console.WriteLine("Serial number: " + result.Data.SerialNumber);
        Console.WriteLine("Date of manufacture: " + result.Data.DateOfManufacture);
    }
}
```

## 另见

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
