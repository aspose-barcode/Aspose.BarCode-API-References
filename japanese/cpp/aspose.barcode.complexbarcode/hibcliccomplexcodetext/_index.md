---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext クラス"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext クラス。C++ における HIBC LIC コードに埋め込まれたテキストのエンコードとデコードのための基底クラスです。"
type: docs
weight: 800
url: /ja/cpp/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class


HIBC LIC コードに埋め込まれたテキストをエンコードおよびデコードするための基底クラス。

```cpp
class HIBCLICComplexCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_BarcodeType](./get_barcodetype/)() const | バーコードの種類を取得します。HIBC LIC コードテキストは HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC、HIBCQRLIC のエンコードタイプを使用してエンコードできます。既定値: HIBCCode39LIC。 |
| [GetBarcodeType](./getbarcodetype/)() override | バーコードの種類を取得します。 |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | コードテキストを構築します |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/)() |  |
| virtual [InitFromString](./initfromstring/)(System::String) | 構築されたコードテキストからインスタンスを初期化します。 |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | バーコードの種類を設定します。HIBC LIC コードテキストは HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC、HIBCQRLIC のエンコードタイプを使用してエンコードできます。既定値: HIBCCode39LIC。 |
## 備考


このサンプルは、生の HIBC LIC コードテキストを [HIBCLICComplexCodetext](./) インスタンスにデコードする方法を示しています。
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.HIBCAztecLIC))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.TryDecodeHIBCLIC(result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## 関連項目

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
