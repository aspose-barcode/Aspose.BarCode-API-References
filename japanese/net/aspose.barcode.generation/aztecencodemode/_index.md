---
title: "列挙型 AztecEncodeMode"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.Generation.AztecEncodeMode 列挙型。Aztec バーコードのエンコーディングモード"
type: docs
weight: 940
url: /ja/net/aspose.barcode.generation/aztecencodemode/
---
## AztecEncodeMode enumeration

Aztec バーコードのエンコーディングモード。

```csharp
public enum AztecEncodeMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Auto | `0` | Autoモードでは、CodeTextは最大のデータ圧縮でエンコードされます。Unicode文字は、指定されたECIEncodingで再エンコードされ、ECI識別子が挿入されます。選択されたECIエンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。 |
| Extended | `3` | マルチECIモードをサポートする拡張モードです。 |
| Binary | `4` | Binaryモードでは、CodeTextは最大のデータ圧縮でエンコードされます。Unicode文字が見つかった場合、例外がスローされます。 |
| ECI | `5` | ECIモードでは、メッセージ全体が指定されたECIEncodingで再エンコードされ、ECI識別子が挿入されます。選択されたECIエンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。なお、一部の古い（2006年以前の）スキャナーはこのモードをサポートしていない可能性があります。 |

## 例

```csharp
[C#]
//Autoモード
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Extendedモード
//コードテキストを作成する
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//コードテキストを生成する
string codetext = textBuilder.GetExtendedCodetext();    

//生成する
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### 関連項目

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


