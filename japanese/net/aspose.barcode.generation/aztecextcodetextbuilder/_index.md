---
title: "クラス AztecExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.Generation.AztecExtCodetextBuilder クラス。AztecEncodeMode の ExtendedCodetext モード用の Aztec バーコード向け拡張コードテキストジェネレータ"
type: docs
weight: 950
url: /ja/net/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class

AztecEncodeMode の ExtendedCodetext モード用の Aztec バーコード向け拡張コードテキストジェネレータ

BarcodeGenerator の TwoDDisplayText プロパティを使用して、管理文字を除去した表示テキストを設定します。

```csharp
public class AztecExtCodetextBuilder : ExtCodetextBuilder
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [AztecExtCodetextBuilder](aztecextcodetextbuilder/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | 拡張チャネル識別子付きのコードテキストを追加します |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | プレーンコードテキストを拡張コードテキスト項目に追加します |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | 拡張コードテキスト項目をクリアします |
| override [GetExtendedCodetext](../../aspose.barcode.generation/aztecextcodetextbuilder/getextendedcodetext/)() | 拡張コードテキストリストから拡張コードテキストを生成します。 |

## 例

このサンプルは、拡張モードで AztecExtCodetextBuilder を使用する方法を示しています。

```csharp
[C#]
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
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### 関連項目

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


