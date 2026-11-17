---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext 类"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext 类。用于在 C++ 中对模式 2 和模式 3 的 MaxiCode 代码中嵌入的文本进行编码和解码的基类。"
type: docs
weight: 2200
url: /zh/cpp/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class


用于对嵌入在 MaxiCode 代码（模式 2 和 3）中的文本进行编码和解码的基类。

```cpp
class MaxiCodeStructuredCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 返回一个值，指示此实例是否等于指定的 [MaxiCodeStructuredCodetext](./) 值。 |
| [get_CountryCode](./get_countrycode/)() const | 获取 ECI 编码。当 MaxiCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | 获取 MaxiCode 编码模式。默认值：Auto。 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | 标识邮政编码。模式 2 时必须为 9 位数字，模式 3 时必须为 6 个字母数字符号。 |
| [get_PostalCode](./get_postalcode/)() const | 标识条形码的第二条消息。 |
| [get_SecondMessage](./get_secondmessage/)() const | 标识 3 位服务类别。 |
| [get_ServiceCategory](./get_servicecategory/)() const | 获取 MaxiCode 模式。 |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | 获取条形码类型。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 构造编码文本 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| virtual [GetMode](../maxicodecodetext/getmode/)() const | 设置 ECI 编码。当 MaxiCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| [InitFromString](./initfromstring/)(System::String) override | 从构造的编码文本初始化实例。 |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/)() |  |
| [set_CountryCode](./set_countrycode/)(int32_t) | 获取 ECI 编码。当 MaxiCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | 设置 MaxiCode 编码模式。默认值：Auto。 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | 此示例展示了如何将原始 MaxiCode 代码文本解码为 [MaxiCodeStructuredCodetext](./) 实例。 |
| [set_PostalCode](./set_postalcode/)(System::String) | 标识条形码的第二条消息。 |
| [set_SecondMessage](./set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | 标识 3 位服务类别。 |
| [set_ServiceCategory](./set_servicecategory/)(int32_t) | 获取 MaxiCode 模式。 |
## 备注


Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode3 类
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeStructuredCodetext){
            MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
        }
    }
}
```

## 另见

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
