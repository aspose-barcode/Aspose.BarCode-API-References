---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICSecondaryAndAdditionalDataCodetext class"
linktitle: "HIBCLICSecondaryAndAdditionalDataCodetext"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICSecondaryAndAdditionalDataCodetext クラス。C++ で二次データを格納する HIBC LIC コードに埋め込まれたテキストのエンコードとデコードを行うクラスです。"
type: docs
weight: 1000
url: /ja/cpp/aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
## HIBCLICSecondaryAndAdditionalDataCodetext class


二次データを格納する HIBC LIC コードに埋め込まれたテキストをエンコードおよびデコードするクラス。

```cpp
class HIBCLICSecondaryAndAdditionalDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | このインスタンスが指定された [HIBCLICSecondaryAndAdditionalDataCodetext](./) の値と等しいかどうかを示す値を返します。 |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | バーコードの種類を取得します。HIBC LIC コードテキストは HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC、HIBCQRLIC のエンコードタイプを使用してエンコードできます。既定値: HIBCCode39LIC。 |
| [get_Data](./get_data/)() const | 二次および追加の補足データを識別します。 |
| [get_LinkCharacter](./get_linkcharacter/)() const | リンク文字を識別します。 |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | バーコードの種類を取得します。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | コードテキストを構築します |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | 構築されたコードテキストからインスタンスを初期化します。 |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | バーコードの種類を設定します。HIBC LIC コードテキストは HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC、HIBCQRLIC のエンコードタイプを使用してエンコードできます。既定値: HIBCCode39LIC。 |
| [set_Data](./set_data/)(System::SharedPtr\<SecondaryAndAdditionalData\>) | 二次および追加の補足データを識別します。 |
| [set_LinkCharacter](./set_linkcharacter/)(char16_t) | リンク文字を識別します。 |
## 備考


///

このサンプルは [HIBCLICSecondaryAndAdditionalDataCodetext](./) を使用して HIBC LIC をエンコードおよびデコードする方法を示しています。
```cpp
[C#]
HIBCLICSecondaryAndAdditionalDataCodetext complexCodetext = new HIBCLICSecondaryAndAdditionalDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.LinkCharacter = 'L';
complexCodetext.Data = new SecondaryAndAdditionalData();
complexCodetext.Data.ExpiryDate = DateTime.Now;
complexCodetext.Data.ExpiryDateFormat = HIBCLICDateFormat.MMDDYY;
complexCodetext.Data.Quantity = 30;
complexCodetext.Data.LotNumber = "LOT123";
complexCodetext.Data.SerialNumber = "SERIAL123";
complexCodetext.Data.DateOfManufacture = DateTime.Now;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICSecondaryAndAdditionalDataCodetext result = (HIBCLICSecondaryAndAdditionalDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Expiry date: " + result.Data.ExpiryDate);
        Console.WriteLine("Quantity: " + result.Data.Quantity);
        Console.WriteLine("Lot number: " + result.Data.LotNumber);
        Console.WriteLine("Serial number: " + result.Data.SerialNumber);
        Console.WriteLine("Date of manufacture: " + result.Data.DateOfManufacture);
    }
}
```

## 関連項目

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
