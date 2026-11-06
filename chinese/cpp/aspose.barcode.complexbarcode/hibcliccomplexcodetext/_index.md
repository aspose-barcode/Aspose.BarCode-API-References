---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext 类"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext 类。用于在 C++ 中对嵌入 HIBC LIC 代码的文本进行编码和解码的基类。"
type: docs
weight: 800
url: /zh/cpp/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class


用于对嵌入 HIBC LIC 代码中的文本进行编码和解码的基类。

```cpp
class HIBCLICComplexCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_BarcodeType](./get_barcodetype/)() const | 获取条形码类型。HIBC LIC 编码文本可以使用 HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC 和 HIBCQRLIC 编码类型进行编码。默认值：HIBCCode39LIC。 |
| [GetBarcodeType](./getbarcodetype/)() override | 获取条形码类型。 |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | 构造编码文本 |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/)() |  |
| virtual [InitFromString](./initfromstring/)(System::String) | 从构造的编码文本初始化实例。 |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | 设置条形码类型。HIBC LIC 编码文本可以使用 HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC 和 HIBCQRLIC 编码类型进行编码。默认值：HIBCCode39LIC。 |
## 备注


此示例展示了如何将原始 HIBC LIC 代码文本解码为 [HIBCLICComplexCodetext](./) 实例。
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.HIBCAztecLIC))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.TryDecodeHIBCLIC(result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## 另见

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
