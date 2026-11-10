---
title: "类 QrExtCodetextBuilder"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.QrExtCodetextBuilder 类。用于 EncodeMode 的 ExtendedCodetext 模式的 2D QR 条码的扩展代码文本生成器"
type: docs
weight: 1630
url: /zh/net/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class

用于 EncodeMode 的 ExtendedCodetext 模式的 2D QR 条码的扩展代码文本生成器

使用 BarcodeGenerator 的 TwoDDisplayText 属性来设置可见文本，以去除管理字符。

```csharp
public class QrExtCodetextBuilder : ExtCodetextBuilder
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [QrExtCodetextBuilder](qrextcodetextbuilder/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddCodetextWithCompactionMode](../../aspose.barcode.generation/qrextcodetextbuilder/addcodetextwithcompactionmode/)(QrExtCompactionMode, string) | 将使用指定的 QR 压缩模式的代码文本添加到扩展代码文本项中。 |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | 添加带有扩展通道标识符的码文本 |
| [AddFNC1FirstPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1firstposition/)() | 在第一位置设置 FNC1。如果之前已设置其他 FNC1 模式，则会被替换。 |
| [AddFNC1GroupSeparator](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1groupseparator/)() | 向扩展代码文本项添加组分隔符 (GS - '\\u001D') |
| [AddFNC1SecondPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1secondposition/)(string) | 在第二位置设置 FNC1。如果之前已设置其他 FNC1 模式，则会被替换。 |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | 向扩展码文本项添加普通码文本 |
| override [Clear](../../aspose.barcode.generation/qrextcodetextbuilder/clear/)() | 清除扩展码文本项 |
| override [GetExtendedCodetext](../../aspose.barcode.generation/qrextcodetextbuilder/getextendedcodetext/)() | 从扩展码文本列表生成扩展码文本。 |

## 示例

此示例展示了如何在扩展模式中使用 FNC1 的第一位置。

```csharp
[C#]
//创建代码文本
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//生成代码文本
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

```csharp
[C#]
//创建代码文本
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456"); 

//生成代码文本
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

```csharp
[C#]
//创建代码文本
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//生成代码文本
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

### 另见

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


