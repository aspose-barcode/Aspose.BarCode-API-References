---
title: "Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder 类"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API 参考"
description: "如何在 C++ 中使用 Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder 类。"
type: docs
weight: 1900
url: /zh/cpp/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class




```cpp
class DataMatrixExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [AddCodetextWithEncodeMode](./addcodetextwithencodemode/)(DataMatrixEncodeMode, System::String) | 将具有定义的编码模式的 codetext 添加到扩展 codetext 项目中 |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | 添加带有扩展通道标识符的码文本 |
| [AddECICodetextWithEncodeMode](./addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, System::String) | 使用定义的编码模式将带有扩展通道标识符的 codetext 添加 |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | 向扩展码文本项添加普通码文本 |
| virtual [Clear](../extcodetextbuilder/clear/)() | 清除扩展码文本项 |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | 从扩展码文本列表生成扩展码文本。 |
## 备注


用于 EncodeMode 的 ExtendedCodetext 模式的 2D DataMatrix 条码的扩展 codetext 生成器


```cpp
[C#]
//扩展码文本模式

//创建码文本
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//生成码文本
string codetext = textBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## 另见

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
