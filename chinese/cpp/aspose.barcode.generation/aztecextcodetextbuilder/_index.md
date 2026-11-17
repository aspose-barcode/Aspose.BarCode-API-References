---
title: "Aspose::BarCode::Generation::AztecExtCodetextBuilder 类"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API 参考"
description: "如何在 C++ 中使用 Aspose::BarCode::Generation::AztecExtCodetextBuilder 类。"
type: docs
weight: 200
url: /zh/cpp/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class




```cpp
class AztecExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | 添加带有扩展通道标识符的码文本 |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | 向扩展码文本项添加普通码文本 |
| virtual [Clear](../extcodetextbuilder/clear/)() | 清除扩展码文本项 |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | 从扩展码文本列表生成扩展码文本。 |
## 备注


用于 Aztec 条形码的扩展码文本生成器，适用于 AztecEncodeMode 的 ExtendedCodetext 模式

使用 [BarcodeGenerator](../barcodegenerator/) 的 TwoDDisplayText 属性来设置可见文本，以去除管理字符。

此示例展示了如何在扩展模式中使用 [AztecExtCodetextBuilder](./)。
```cpp
[C#]
//创建码文本
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//生成码文本
string codetext = textBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## 另见

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
