---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICCombinedCodetext クラス"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICCombinedCodetext クラス。 C++ で一次データと二次データを格納する HIBC LIC コードに埋め込まれたテキストをエンコードおよびデコードするクラスです。"
type: docs
weight: 700
url: /ja/cpp/aspose.barcode.complexbarcode/hibcliccombinedcodetext/
---
## HIBCLICCombinedCodetext class


一次データと二次データを格納する HIBC LIC コードに埋め込まれたテキストをエンコードおよびデコードするクラス。

```cpp
class HIBCLICCombinedCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | このインスタンスが指定された [HIBCLICCombinedCodetext](./) の値と等しいかどうかを示す値を返します。 |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | バーコードの種類を取得します。HIBC LIC コードテキストは HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC、HIBCQRLIC のエンコードタイプを使用してエンコードできます。既定値: HIBCCode39LIC。 |
| [get_PrimaryData](./get_primarydata/)() const | 一次データを識別します。 |
| [get_SecondaryAndAdditionalData](./get_secondaryandadditionaldata/)() const | 二次データおよび追加の補足データを識別します。 |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | バーコードの種類を取得します。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | コードテキストを構築します |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | 構築されたコードテキストからインスタンスを初期化します。 |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | バーコードの種類を設定します。HIBC LIC コードテキストは HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC、HIBCQRLIC のエンコードタイプを使用してエンコードできます。既定値: HIBCCode39LIC。 |
| [set_PrimaryData](./set_primarydata/)(System::SharedPtr\<Aspose::BarCode::ComplexBarcode::PrimaryData\>) | 一次データを識別します。 |
| [set_SecondaryAndAdditionalData](./set_secondaryandadditionaldata/)(System::SharedPtr\<Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData\>) | 二次データおよび追加の補足データを識別します。 |
## 備考


このサンプルは、[HIBCLICCombinedCodetext](./) を使用して HIBC LIC をエンコードおよびデコードする方法を示しています。
```cpp
[C#]
HIBCLICCombinedCodetext combinedCodetext = new HIBCLICCombinedCodetext();
combinedCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
combinedCodetext.PrimaryData = new PrimaryData();
combinedCodetext.PrimaryData.ProductOrCatalogNumber = "12345";
combinedCodetext.PrimaryData.LabelerIdentificationCode = "A999";
combinedCodetext.PrimaryData.UnitOfMeasureID = 1;
combinedCodetext.SecondaryAndAdditionalData = new SecondaryAndAdditionalData();
combinedCodetext.SecondaryAndAdditionalData.ExpiryDate = DateTime.Now;
combinedCodetext.SecondaryAndAdditionalData.ExpiryDateFormat = HIBCLICDateFormat.MMDDYY;
combinedCodetext.SecondaryAndAdditionalData.Quantity = 30;
combinedCodetext.SecondaryAndAdditionalData.LotNumber = "LOT123";
combinedCodetext.SecondaryAndAdditionalData.SerialNumber = "SERIAL123";
combinedCodetext.SecondaryAndAdditionalData.DateOfManufacture = DateTime.Now;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICCombinedCodetext result = (HIBCLICCombinedCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.PrimaryData.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.PrimaryData.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.PrimaryData.UnitOfMeasureID);
        Console.WriteLine("Expiry date: " + result.SecondaryAndAdditionalData.ExpiryDate);
        Console.WriteLine("Quantity: " + result.SecondaryAndAdditionalData.Quantity);
        Console.WriteLine("Lot number: " + result.SecondaryAndAdditionalData.LotNumber);
        Console.WriteLine("Serial number: " + result.SecondaryAndAdditionalData.SerialNumber);
        Console.WriteLine("Date of manufacture: " + result.SecondaryAndAdditionalData.DateOfManufacture);
    }
}
```

## 関連項目

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
