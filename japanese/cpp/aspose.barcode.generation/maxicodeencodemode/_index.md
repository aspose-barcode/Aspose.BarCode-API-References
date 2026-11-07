---
title: "enum"
linktitle: "MaxiCodeEncodeMode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " 列挙型。C++ における MaxiCode バーコードのエンコーディングモード。"
type: docs
weight: 7500
url: /ja/cpp/aspose.barcode.generation/maxicodeencodemode/
---
## MaxiCodeEncodeMode enum


MaxiCode バーコードのエンコーディングモード。

```cpp
enum class MaxiCodeEncodeMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| 自動 | 0 | Auto モードでは、CodeText が最大限のデータ圧縮でエンコードされます。Unicode 文字は、指定された ECIEncoding で再エンコードされ、ECI 識別子が挿入されます。選択された ECI エンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。 |
| 拡張 | 3 |  |
| バイナリ | 4 | バイナリモードでは、CodeText が最大限のデータ圧縮でエンコードされます。Unicode 文字が見つかった場合、例外がスローされます。 |
| ECI | 5 | ECI モードでは、メッセージ全体が指定された ECIEncoding で再エンコードされ、ECI 識別子が挿入されます。選択された ECI エンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。なお、一部の古い（2006 年以前の）スキャナーはこのモードをサポートしていない可能性があります。 |

## 備考



```cpp
[C#]
//Auto モード
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//バイトモード
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//拡張コードテキストモード
//コードテキストを作成
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//コードテキストを生成
string codetext = textBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
