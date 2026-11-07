---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode3 クラス"
linktitle: "MaxiCodeCodetextMode3"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode3 クラス。モード3のMaxiCodeコードに埋め込まれたテキストのエンコードとデコードを行うクラス（C++）。"
type: docs
weight: 1800
url: /ja/cpp/aspose.barcode.complexbarcode/maxicodecodetextmode3/
---
## MaxiCodeCodetextMode3 class


モード3用のMaxiCodeコードに埋め込まれたテキストをエンコードおよびデコードするクラスです。

```cpp
class MaxiCodeCodetextMode3 : public Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Equals](../maxicodestructuredcodetext/equals/)(System::SharedPtr\<System::Object\>) override | このインスタンスが指定された [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/) の値と等しいかどうかを示す値を返します。 |
| [get_CountryCode](../maxicodestructuredcodetext/get_countrycode/)() const | 3桁の国コードを識別します。 |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | ECIエンコーディングを取得します。MaxiCodeEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | MaxiCode エンコードモードを取得します。デフォルト値: Auto。 |
| [get_PostalCode](../maxicodestructuredcodetext/get_postalcode/)() const | 郵便番号を識別します。モード2では9桁、モード3では6文字の英数字である必要があります。 |
| [get_SecondMessage](../maxicodestructuredcodetext/get_secondmessage/)() const | バーコードの第2メッセージを識別します。 |
| [get_ServiceCategory](../maxicodestructuredcodetext/get_servicecategory/)() const | 3桁のサービスカテゴリを識別します。 |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | バーコードの種類を取得します。 |
| [GetConstructedCodetext](../maxicodestructuredcodetext/getconstructedcodetext/)() override | コードテキストを構築します |
| [GetHashCode](../maxicodestructuredcodetext/gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [GetMode](./getmode/)() const override | MaxiCode モードを取得します。 |
| [InitFromString](../maxicodestructuredcodetext/initfromstring/)(System::String) override | 構築されたコードテキストからインスタンスを初期化します。 |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/)() |  |
| [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/maxicodestructuredcodetext/)() |  |
| [set_CountryCode](../maxicodestructuredcodetext/set_countrycode/)(int32_t) | 3桁の国コードを識別します。 |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | ECIエンコーディングを設定します。MaxiCodeEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | MaxiCode エンコードモードを設定します。デフォルト値: Auto。 |
| [set_PostalCode](../maxicodestructuredcodetext/set_postalcode/)(System::String) | 郵便番号を識別します。モード2では9桁、モード3では6文字の英数字である必要があります。 |
| [set_SecondMessage](../maxicodestructuredcodetext/set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | バーコードの第2メッセージを識別します。 |
| [set_ServiceCategory](../maxicodestructuredcodetext/set_servicecategory/)(int32_t) | 3桁のサービスカテゴリを識別します。 |
## 備考


このサンプルは、モード3の MaxiCode コードテキストをエンコードおよびデコードする方法を示します。
```cpp
[C#]
//標準第2メッセージ付きモード3
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//構造化第2メッセージ付きモード3
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//標準第2メッセージで生のコードテキストをデコード
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode3){
            MaxiCodeCodetextMode3 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode3)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStandardSecondMessage){
                MaxiCodeStandardSecondMessage secondMessage = (MaxiCodeStandardSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message: " + secondMessage.Message);
            }
        }
    }
}
//構造化第2メッセージで生のコードテキストをデコード
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode3){
            MaxiCodeCodetextMode3 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode3)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStructuredSecondMessage){
                MaxiCodeStructuredSecondMessage secondMessage = (MaxiCodeStructuredSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message:");
                foreach (var identifier in secondMessage.Identifiers){
                    Console.WriteLine(identifier);
                }
            }
        }
    }
}
```

## 関連項目

* Class [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
