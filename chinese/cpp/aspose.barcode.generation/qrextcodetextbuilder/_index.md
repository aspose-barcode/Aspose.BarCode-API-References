---
title: "Aspose::BarCode::Generation::QrExtCodetextBuilder 类"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API 参考"
description: "如何在 C++ 中使用 Aspose::BarCode::Generation::QrExtCodetextBuilder 类。"
type: docs
weight: 4300
url: /zh/cpp/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class




```cpp
class QrExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [AddCodetextWithCompactionMode](./addcodetextwithcompactionmode/)(QrExtCompactionMode, System::String) | 将具有指定 QR 压缩模式的代码文本添加到扩展代码文本项中。 |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | 添加带有扩展通道标识符的码文本 |
| [AddFNC1FirstPosition](./addfnc1firstposition/)() | 在第一位置设置 FNC1。若之前已设置其他 FNC1 模式，则会被替换。 |
| [AddFNC1GroupSeparator](./addfnc1groupseparator/)() | 向扩展码文本项添加组分隔符 (GS - '\u001D') |
| [AddFNC1SecondPosition](./addfnc1secondposition/)(System::String) | 在第二位置设置 FNC1。若之前已设置其他 FNC1 模式，则会被替换。 |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | 向扩展码文本项添加普通码文本 |
| [Clear](./clear/)() override | 清除扩展码文本项 |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | 从扩展码文本列表生成扩展码文本。 |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/)() |  |
## 备注


用于 EncodeMode 的 ExtendedCodetext 模式的二维 QR 条码扩展码文本生成器

使用 [BarcodeGenerator](../barcodegenerator/) 的 TwoDDisplayText 属性来设置可见文本，以去除管理字符。

此示例展示了如何在扩展模式中使用 FNC1 的第一位置。
```cpp
[C#]
//创建码文本
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//生成码文本
string codetext = TextBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


此示例展示了如何在扩展模式中使用 FNC1 的第二位置。
```cpp
[C#]
//创建码文本
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456");

//生成码文本
string codetext = TextBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


此示例展示了如何在扩展模式中使用多 ECI 模式。
```cpp
[C#]
//创建码文本
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//生成码文本
string codetext = TextBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## 另见

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
