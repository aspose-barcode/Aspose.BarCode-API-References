---
title: "enum"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "enum。DataMatrix エンコーダのエンコーディングモードで、C++ のデフォルトは Auto です。"
type: docs
weight: 6300
url: /ja/cpp/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enum


DataMatrix エンコーダのエンコーディングモード、デフォルトは Auto

```cpp
enum class DataMatrixEncodeMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| 自動 | 0 | Auto モードでは、CodeText が最大限のデータ圧縮でエンコードされます。Unicode 文字は、指定された ECIEncoding で再エンコードされ、ECI 識別子が挿入されます。選択された ECI エンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。 |
| ASCII | 1 | 1 バイトあたり、英数字 1 文字または数字 2 文字をエンコードします。 |
| C40 | 8 | C40 エンコーディングを使用します。大文字英数字、 小文字および特殊文字をエンコードします。 |
| テキスト | 9 | Text エンコーディングを使用します。小文字英数字、大文字および特殊文字をエンコードします。 |
| EDIFACT | 10 | EDIFACT エンコーディングを使用します。1 文字あたり 6 ビットを使用し、数字、大文字、 多くの句読点をエンコードしますが、小文字はサポートされません。 |
| ANSIX12 | 11 | ANSI X12 エンコーディングを使用します。 |
| 拡張 | 13 |  |
| Base256 | 14 | 8 ビット値をエンコードします |
| バイナリ | 15 | バイナリモードでは、CodeText が最大限のデータ圧縮でエンコードされます。Unicode 文字が見つかった場合、例外がスローされます。 |
| ECI | 16 | ECI モードでは、メッセージ全体が指定された ECIEncoding で再エンコードされ、ECI 識別子が挿入されます。選択された ECI エンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。なお、一部の古い（2006 年以前の）スキャナーはこのモードをサポートしていない可能性があります。 |

## 備考


このサンプルは、拡張モードでコードテキストを使用する方法を示しています。
```cpp
[C#]
//Auto モード
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//バイトモード
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


//拡張コードテキストモード
//コードテキストを作成
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//コードテキストを生成
string codetext = textBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
