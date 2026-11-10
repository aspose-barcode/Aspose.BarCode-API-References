---
title: "类 AztecExtCodetextBuilder"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.AztecExtCodetextBuilder 类。用于 Aztec 条码的扩展码文本生成器，适用于 AztecEncodeMode 的 ExtendedCodetext 模式。"
type: docs
weight: 950
url: /zh/net/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class

Aztec 条形码的扩展代码文本生成器，用于 AztecEncodeMode 的 ExtendedCodetext 模式。

使用 BarcodeGenerator 的 TwoDDisplayText 属性来设置可见文本，以去除管理字符。

```csharp
public class AztecExtCodetextBuilder : ExtCodetextBuilder
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [AztecExtCodetextBuilder](aztecextcodetextbuilder/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | 添加带有扩展通道标识符的码文本 |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | 向扩展码文本项添加普通码文本 |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | 清除扩展码文本项 |
| override [GetExtendedCodetext](../../aspose.barcode.generation/aztecextcodetextbuilder/getextendedcodetext/)() | 从扩展码文本列表生成扩展码文本。 |

## 示例

此示例展示了如何在扩展模式下使用 AztecExtCodetextBuilder。

```csharp
[C#]
//创建代码文本
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//生成代码文本
string codetext = textBuilder.GetExtendedCodetext();    

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### 另见

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


