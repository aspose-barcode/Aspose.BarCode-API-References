---
title: "クラス DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.Generation.DataMatrixExtCodetextBuilder クラス。ExtendedCodetext Mode of EncodeMode 用の 2D DataMatrix バーコード向け拡張コードテキストジェネレータ"
type: docs
weight: 1210
url: /ja/net/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class

ExtendedCodetext Mode of EncodeMode 用の 2D DataMatrix バーコード向け拡張コードテキストジェネレータ

```csharp
public class DataMatrixExtCodetextBuilder : ExtCodetextBuilder
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DataMatrixExtCodetextBuilder](datamatrixextcodetextbuilder/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddCodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addcodetextwithencodemode/)(DataMatrixEncodeMode, string) | 定義されたエンコードモードでコードテキストを拡張コードテキスト項目に追加します |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | 拡張チャネル識別子付きのコードテキストを追加します |
| [AddECICodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, string) | 定義されたエンコードモードで拡張チャネル識別子付きコードテキストを追加します |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | プレーンコードテキストを拡張コードテキスト項目に追加します |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | 拡張コードテキスト項目をクリアします |
| override [GetExtendedCodetext](../../aspose.barcode.generation/datamatrixextcodetextbuilder/getextendedcodetext/)() | 拡張コードテキストリストから拡張コードテキストを生成します。 |

## 例

```csharp
[C#]
//拡張コードテキストモード

//コードテキストを作成する
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//コードテキストを生成する
string codetext = textBuilder.GetExtendedCodetext();    

//生成する
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### 関連項目

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


