---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext 类"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext 类。用于在 C++ 中对嵌入 MaxiCode 代码的文本进行编码和解码的基类。"
type: docs
weight: 1600
url: /zh/cpp/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class


用于对嵌入在 MaxiCode 代码中的文本进行编码和解码的基类。

```cpp
class MaxiCodeCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | 获取 MaxiCode 编码模式。默认值：Auto。 |
| [get_EncodeMode](./get_encodemode/)() const | 标识邮政编码。模式 2 时必须为 9 位数字，模式 3 时必须为 6 个字母数字符号。 |
| [GetBarcodeType](./getbarcodetype/)() override | 获取条形码类型。 |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | 构造编码文本 |
| virtual [GetMode](./getmode/)() const | 设置 ECI 编码。当 MaxiCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| virtual [InitFromString](./initfromstring/)(System::String) | 从构造的编码文本初始化实例。 |
| [MaxiCodeCodetext](./maxicodecodetext/)() |  |
| [set_ECIEncoding](./set_eciencoding/)(Generation::ECIEncodings) | 设置 MaxiCode 编码模式。默认值：Auto。 |
| [set_EncodeMode](./set_encodemode/)(Generation::MaxiCodeEncodeMode) | 此示例展示了如何将原始 MaxiCode 代码文本解码为 [MaxiCodeStructuredCodetext](./) 实例。 |
## 备注


此示例展示了如何将原始 MaxiCode 编码文本解码为 [MaxiCodeCodetext](./) 实例。
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## 另见

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
