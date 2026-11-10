---
title: "类 DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.DotCodeExtCodetextBuilder 类。用于 2D DotCode 条形码的扩展码文本生成器，适用于 DotCodeEncodeMode 的 ExtendedCodetext 模式。"
type: docs
weight: 1250
url: /zh/net/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class

用于 DotCodeEncodeMode 的 ExtendedCodetext 模式的 2D DotCode 条码的扩展代码文本生成器

```csharp
public class DotCodeExtCodetextBuilder : ExtCodetextBuilder
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DotCodeExtCodetextBuilder](dotcodeextcodetextbuilder/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | 添加带有扩展通道标识符的码文本 |
| [AddFNC1FormatIdentifier](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc1formatidentifier/)() | 向扩展码文本项添加 FNC1 格式标识符 |
| [AddFNC3ReaderInitialization](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3readerinitialization/)() | 向扩展码文本项添加 FNC3 读取器初始化 |
| [AddFNC3SymbolSeparator](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3symbolseparator/)() | 向扩展码文本项添加 FNC3 符号分隔符 |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | 向扩展码文本项添加普通码文本 |
| [AddStructuredAppendMode](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addstructuredappendmode/)(int, int) | 向扩展码文本项添加结构化追加模式 |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | 清除扩展码文本项 |
| override [GetExtendedCodetext](../../aspose.barcode.generation/dotcodeextcodetextbuilder/getextendedcodetext/)() | 从扩展码文本列表生成扩展码文本。 |

## 示例

```csharp
[C#]
//Extended codetext 模式
//创建代码文本
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

//生成代码文本
string codetext = textBuilder.GetExtendedCodetext();    

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### 另见

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


