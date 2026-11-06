---
title: "Aspose::BarCode::Generation::DotCodeExtCodetextBuilder 类"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API 参考"
description: "如何在 C++ 中使用 Aspose::BarCode::Generation::DotCodeExtCodetextBuilder 类。"
type: docs
weight: 2100
url: /zh/cpp/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class




```cpp
class DotCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | 添加带有扩展通道标识符的码文本 |
| [AddFNC1FormatIdentifier](./addfnc1formatidentifier/)() | 向扩展代码文本项添加 FNC1 格式标识符 |
| [AddFNC3ReaderInitialization](./addfnc3readerinitialization/)() | 向扩展代码文本项添加 FNC3 读取器初始化 |
| [AddFNC3SymbolSeparator](./addfnc3symbolseparator/)() | 向扩展代码文本项添加 FNC3 符号分隔符 |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | 向扩展码文本项添加普通码文本 |
| [AddStructuredAppendMode](./addstructuredappendmode/)(int32_t, int32_t) | 向扩展代码文本项添加结构化追加模式 |
| virtual [Clear](../extcodetextbuilder/clear/)() | 清除扩展码文本项 |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | 从扩展码文本列表生成扩展码文本。 |
## 备注


用于 DotCodeEncodeMode 的 ExtendedCodetext 模式的 2D DotCode 条码的扩展代码文本生成器


```cpp
[C#]
//扩展码文本模式
//创建码文本
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC3ReaderInitialization();
textBuilder.AddPlainCodetext("Reader initialization info");

//生成码文本
string codetext = textBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## 另见

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
