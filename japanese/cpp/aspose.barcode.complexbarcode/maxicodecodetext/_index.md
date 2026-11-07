---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext クラス"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext クラス。 C++ で MaxiCode コードに埋め込まれたテキストをエンコードおよびデコードするための基底クラスです。"
type: docs
weight: 1600
url: /ja/cpp/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class


MaxiCodeコードに埋め込まれたテキストをエンコードおよびデコードする基底クラスです。

```cpp
class MaxiCodeCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | ECIエンコーディングを取得します。MaxiCodeEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | MaxiCode エンコードモードを取得します。デフォルト値: Auto。 |
| [GetBarcodeType](./getbarcodetype/)() override | バーコードの種類を取得します。 |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | コードテキストを構築します |
| virtual [GetMode](./getmode/)() const | MaxiCode モードを取得します。 |
| virtual [InitFromString](./initfromstring/)(System::String) | 構築されたコードテキストからインスタンスを初期化します。 |
| [MaxiCodeCodetext](./maxicodecodetext/)() |  |
| [set_ECIEncoding](./set_eciencoding/)(Generation::ECIEncodings) | ECIエンコーディングを設定します。MaxiCodeEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(Generation::MaxiCodeEncodeMode) | MaxiCode エンコードモードを設定します。デフォルト値: Auto。 |
## 備考


このサンプルは、生の MaxiCode コードテキストを [MaxiCodeCodetext](./) インスタンスにデコードする方法を示しています。
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## 関連項目

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
