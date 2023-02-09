---
title: MaxiCodeStructuredCodetext
second_title: Aspose.BarCode for.NETAPIリファレンス
description: モード 2 および 3 の MaxiCode コードに埋め込まれたテキストをエンコードおよびデコードするための基本クラス
type: docs
weight: 560
url: /ja/net/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class

モード 2 および 3 の MaxiCode コードに埋め込まれたテキストをエンコードおよびデコードするための基本クラス。

```csharp
public abstract class MaxiCodeStructuredCodetext : MaxiCodeCodetext
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CountryCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/countrycode/) { get; set; } | 3 桁の国コードを識別します。 |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | ECI エンコーディングを取得または設定します。 MaxiCodeEncodeMode が Auto の場合に使用されます。 デフォルト値: ISO-8859-1 |
| [MaxiCodeEncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/maxicodeencodemode/) { get; set; } | MaxiCode エンコード モードを取得または設定します。 デフォルト値: Auto. |
| [PostalCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/postalcode/) { get; set; } | 郵便番号を識別します。モード 2 または では 9 桁でなければなりません モード 3 では 6 つの英数字記号. |
| [SecondMessage](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/secondmessage/) { get; set; } | バーコードの 2 番目のメッセージを識別します。 |
| [ServiceCategory](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/servicecategory/) { get; set; } | 3 桁のサービス カテゴリを識別します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/equals/)(object) | このインスタンスが指定された値と等しいかどうかを示す値を返します`MaxiCodeStructuredCodetext`値. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | バーコードの種類を取得します。 |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/getconstructedcodetext/)() | を構築します codetext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/gethashcode/)() | このインスタンスのハッシュ コードを返します。 |
| abstract [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetext/getmode/)() | MaxiCode モードを取得します。 |
| override [InitFromString](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/initfromstring/)(string) | 構築されたコードテキストからインスタンスを初期化します. |

### 例

このサンプルは、生の MaxiCode コードテキストを MaxiCodeStructuredCodetext インスタンスにデコードする方法を示しています。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeStructuredCodetext){
            MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
        }
    }
}
```

### 関連項目

* class [MaxiCodeCodetext](../maxicodecodetext/)
* 名前空間 [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* 組み立て [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->