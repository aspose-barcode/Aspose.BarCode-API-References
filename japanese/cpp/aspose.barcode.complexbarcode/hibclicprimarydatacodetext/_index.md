---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext クラス"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext クラス。C++ で一次データを格納する HIBC LIC コードに埋め込まれたテキストのエンコードとデコードを行うクラスです。"
type: docs
weight: 900
url: /ja/cpp/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class


一次データを格納する HIBC LIC コードに埋め込まれたテキストをエンコードおよびデコードするクラス。

```cpp
class HIBCLICPrimaryDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | このインスタンスが指定された [HIBCLICPrimaryDataCodetext](./) の値と等しいかどうかを示す値を返します。 |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | バーコードの種類を取得します。HIBC LIC コードテキストは HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC、HIBCQRLIC のエンコードタイプを使用してエンコードできます。既定値: HIBCCode39LIC。 |
| [get_Data](./get_data/)() const | 一次データを識別します。 |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | バーコードの種類を取得します。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | コードテキストを構築します |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | 構築されたコードテキストからインスタンスを初期化します。 |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | バーコードの種類を設定します。HIBC LIC コードテキストは HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC、HIBCQRLIC のエンコードタイプを使用してエンコードできます。既定値: HIBCCode39LIC。 |
| [set_Data](./set_data/)(System::SharedPtr\<PrimaryData\>) | 一次データを識別します。 |
## 備考


このサンプルは、[HIBCLICPrimaryDataCodetext](./) を使用して HIBC LIC をエンコードおよびデコードする方法を示しています。
```cpp
[C#]
HIBCLICPrimaryDataCodetext complexCodetext  = new HIBCLICPrimaryDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.Data = new PrimaryData();
complexCodetext.Data.ProductOrCatalogNumber = "12345";
complexCodetext.Data.LabelerIdentificationCode = "A999";
complexCodetext.Data.UnitOfMeasureID = 1;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICPrimaryDataCodetext result = (HIBCLICPrimaryDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.Data.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.Data.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.Data.UnitOfMeasureID);
    }
}
```

## 関連項目

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
