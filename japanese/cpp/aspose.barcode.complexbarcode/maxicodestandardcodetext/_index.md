---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext クラス"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext クラス. C++ でモード4、5、6用の MaxiCode コードテキストのエンコードおよびデコードを行うクラス。"
type: docs
weight: 2000
url: /ja/cpp/aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
## MaxiCodeStandardCodetext class


モード4、5、6用のMaxiCodeコードテキストをエンコードおよびデコードするクラスです。

```cpp
class MaxiCodeStandardCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | このインスタンスが指定された [MaxiCodeStandardCodetext](./) の値と等しいかどうかを示す値を返します。 |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | ECIエンコーディングを取得します。MaxiCodeEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | MaxiCode エンコードモードを取得します。デフォルト値: Auto。 |
| [get_Message](./get_message/)() const | メッセージを取得します。 |
| [get_Mode](./get_mode/)() | MaxiCode モードを取得します。標準のコードテキストはモード4、5、6でのみ使用できます。 |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | バーコードの種類を取得します。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | コードテキストを構築します |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [GetMode](./getmode/)() const override | MaxiCode モードを取得します。 |
| [InitFromString](./initfromstring/)(System::String) override | 構築されたコードテキストからインスタンスを初期化します。 |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/)() |  |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | ECIエンコーディングを設定します。MaxiCodeEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | MaxiCode エンコードモードを設定します。デフォルト値: Auto。 |
| [set_Message](./set_message/)(System::String) | メッセージを設定します。 |
| [set_Mode](./set_mode/)(Generation::MaxiCodeMode) | MaxiCode モードを設定します。標準のコードテキストはモード4、5、6でのみ使用できます。 |
## 備考


//モード 4 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode4; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //モード 5 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode5; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //モード 6 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode6; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); }
## 関連項目

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
