---
title: "枚举 DataMatrixEncodeMode"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.DataMatrixEncodeMode 枚举。DataMatrix 编码器的编码模式默认设置为 Auto"
type: docs
weight: 1200
url: /zh/net/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

DataMatrix 编码器的编码模式，默认自动。

```csharp
public enum DataMatrixEncodeMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | `0` | 在 Auto 模式下，CodeText 以最高的数据紧凑度进行编码。Unicode 字符会在指定的 ECIEncoding 编码中重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则会抛出异常。 |
| ASCII | `1` | 每字节编码一个字母数字字符或两个数字字符 |
| C40 | `8` | 使用 C40 编码。编码大写字母数字字符、 小写字母以及特殊字符 |
| Text | `9` | 使用 Text 编码。编码小写字母数字字符、大写字母以及特殊字符 |
| EDIFACT | `10` | 使用 EDIFACT 编码。每字符使用六位，编码数字、大写字母和许多标点符号，但不支持小写字母。 |
| ANSIX12 | `11` | 使用 ANSI X12 编码。 |
| Extended | `13` | ExtendedCodetext 模式允许在代码文本中手动切换编码方案和 ECI 编码。 |
| Base256 | `14` | 编码 8 位值 |
| Binary | `15` | 在 Binary 模式下，CodeText 以最高的数据紧凑度进行编码。如果发现 Unicode 字符，则会抛出异常。 |
| ECI | `16` | 在 ECI 模式下，整个消息会在指定的 ECIEncoding 编码中重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则会抛出异常。请注意，某些旧的（2006 年前）扫描仪可能不支持此模式。 |

## 示例

此示例展示了如何在 Extended 模式下进行代码文本处理。

```csharp
[C#]
//Auto 模式
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Bytes 模式
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


//Extended codetext 模式
//创建代码文本
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//生成代码文本
string codetext = textBuilder.GetExtendedCodetext();    

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
	generator.Save("test.bmp");
}
```

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


