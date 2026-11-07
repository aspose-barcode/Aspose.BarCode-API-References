---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext クラス"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext クラス。モード2および3のMaxiCodeコードに埋め込まれたテキストのエンコードとデコードのための基底クラス（C++）。"
type: docs
weight: 2200
url: /ja/cpp/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class


モード2および3用のMaxiCodeコードに埋め込まれたテキストをエンコードおよびデコードする基底クラスです。

```cpp
class MaxiCodeStructuredCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | このインスタンスが指定された [MaxiCodeStructuredCodetext](./) の値と等しいかどうかを示す値を返します。 |
| [get_CountryCode](./get_countrycode/)() const | 3桁の国コードを識別します。 |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | ECIエンコーディングを取得します。MaxiCodeEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | MaxiCode エンコードモードを取得します。デフォルト値: Auto。 |
| [get_PostalCode](./get_postalcode/)() const | 郵便番号を識別します。モード2では9桁、モード3では6文字の英数字である必要があります。 |
| [get_SecondMessage](./get_secondmessage/)() const | バーコードの第2メッセージを識別します。 |
| [get_ServiceCategory](./get_servicecategory/)() const | 3桁のサービスカテゴリを識別します。 |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | バーコードの種類を取得します。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | コードテキストを構築します |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| virtual [GetMode](../maxicodecodetext/getmode/)() const | MaxiCode モードを取得します。 |
| [InitFromString](./initfromstring/)(System::String) override | 構築されたコードテキストからインスタンスを初期化します。 |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/)() |  |
| [set_CountryCode](./set_countrycode/)(int32_t) | 3桁の国コードを識別します。 |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | ECIエンコーディングを設定します。MaxiCodeEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | MaxiCode エンコードモードを設定します。デフォルト値: Auto。 |
| [set_PostalCode](./set_postalcode/)(System::String) | 郵便番号を識別します。モード2では9桁、モード3では6文字の英数字である必要があります。 |
| [set_SecondMessage](./set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | バーコードの第2メッセージを識別します。 |
| [set_ServiceCategory](./set_servicecategory/)(int32_t) | 3桁のサービスカテゴリを識別します。 |
## 備考


このサンプルは、生の MaxiCode コードテキストを [MaxiCodeStructuredCodetext](./) インスタンスにデコードする方法を示します。
```cpp
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

## 関連項目

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
