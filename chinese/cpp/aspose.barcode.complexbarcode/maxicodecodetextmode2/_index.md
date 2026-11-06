---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode2 类"
linktitle: "MaxiCodeCodetextMode2"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode2 类。用于在 C++ 中对嵌入 MaxiCode 码的文本进行编码和解码的类，适用于模式 2。"
type: docs
weight: 1700
url: /zh/cpp/aspose.barcode.complexbarcode/maxicodecodetextmode2/
---
## MaxiCodeCodetextMode2 class


用于对嵌入在 MaxiCode 代码（模式 2）中的文本进行编码和解码的类。

```cpp
class MaxiCodeCodetextMode2 : public Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [Equals](../maxicodestructuredcodetext/equals/)(System::SharedPtr\<System::Object\>) override | 此示例展示了如何对模式 3 的 MaxiCode 代码文本进行编码和解码。 |
| [get_CountryCode](../maxicodestructuredcodetext/get_countrycode/)() const | 获取 ECI 编码。当 MaxiCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | 获取 MaxiCode 编码模式。默认值：Auto。 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | 标识邮政编码。模式 2 时必须为 9 位数字，模式 3 时必须为 6 个字母数字符号。 |
| [get_PostalCode](../maxicodestructuredcodetext/get_postalcode/)() const | 标识条形码的第二条消息。 |
| [get_SecondMessage](../maxicodestructuredcodetext/get_secondmessage/)() const | 标识 3 位服务类别。 |
| [get_ServiceCategory](../maxicodestructuredcodetext/get_servicecategory/)() const | 获取 MaxiCode 模式。 |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | 获取条形码类型。 |
| [GetConstructedCodetext](../maxicodestructuredcodetext/getconstructedcodetext/)() override | 构造编码文本 |
| [GetHashCode](../maxicodestructuredcodetext/gethashcode/)() const override | 返回此实例的哈希码。 |
| [GetMode](./getmode/)() const override | 设置 ECI 编码。当 MaxiCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| [InitFromString](../maxicodestructuredcodetext/initfromstring/)(System::String) override | 从构造的编码文本初始化实例。 |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/)() |  |
| [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/maxicodestructuredcodetext/)() |  |
| [set_CountryCode](../maxicodestructuredcodetext/set_countrycode/)(int32_t) | 获取 ECI 编码。当 MaxiCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | 设置 MaxiCode 编码模式。默认值：Auto。 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | 此示例展示了如何将原始 MaxiCode 代码文本解码为 [MaxiCodeStructuredCodetext](./) 实例。 |
| [set_PostalCode](../maxicodestructuredcodetext/set_postalcode/)(System::String) | 标识条形码的第二条消息。 |
| [set_SecondMessage](../maxicodestructuredcodetext/set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | 标识 3 位服务类别。 |
| [set_ServiceCategory](../maxicodestructuredcodetext/set_servicecategory/)(int32_t) | 获取 MaxiCode 模式。 |
## 备注


此示例展示了如何对模式 2 的 MaxiCode 码文本进行编码和解码。
```cpp
[C#]
//模式 2，带标准的第二条消息
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//模式 2，带结构化的第二条消息
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//使用结构化第二条消息解码原始代码文本
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode2){
            MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStandardSecondMessage){
                MaxiCodeStandardSecondMessage secondMessage = (MaxiCodeStandardSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message: " + secondMessage.Message);
            }
        }
    }
}
//使用结构化的第二条消息解码原始代码文本
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode2){
            MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStructuredSecondMessage){
                MaxiCodeStructuredSecondMessage secondMessage = (MaxiCodeStructuredSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message:");
                foreach (var identifier in secondMessage.Identifiers){
                    Console.WriteLine(identifier);
                }
            }
        }
    }
}
```

## 另见

* Class [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
