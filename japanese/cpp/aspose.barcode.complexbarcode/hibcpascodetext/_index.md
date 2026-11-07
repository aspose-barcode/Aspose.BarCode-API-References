---
title: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext クラス"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext クラス。C++ で HIBC PAS コードに埋め込まれたテキストのエンコードとデコードを行うクラス。"
type: docs
weight: 1100
url: /ja/cpp/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class


HIBC PAS コードに埋め込まれたテキストをエンコードおよびデコードするクラス。

```cpp
class HIBCPASCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [AddRecord](./addrecord/)(HIBCPASDataType, System::String) | 新しいレコードを追加します |
| [AddRecord](./addrecord/)(System::SharedPtr\<HIBCPASRecord\>) | 新しいレコードを追加します |
| [Clear](./clear/)() | レコード一覧をクリアします |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | このインスタンスが指定された [HIBCPASCodetext](./) の値と等しいかどうかを示す値を返します。 |
| [get_BarcodeType](./get_barcodetype/)() const | バーコードの種類を取得します。HIBC PAS コードテキストは HIBCCode39PAS、HIBCCode128PAS、HIBCAztec:PAS、HIBCDataMatrixPAS、HIBCQRPAS のエンコードタイプでエンコードできます。既定値: HIBCCode39PAS。 |
| [get_DataLocation](./get_datalocation/)() const | データの位置を識別します。 |
| [GetBarcodeType](./getbarcodetype/)() override | バーコードの種類を取得します。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | コードテキストを構築します |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [GetRecords](./getrecords/)() | レコード一覧を取得します |
| [HIBCPASCodetext](./hibcpascodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | 構築されたコードテキストからインスタンスを初期化します。 |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | バーコードの種類を設定します。HIBC PAS コードテキストは HIBCCode39PAS、HIBCCode128PAS、HIBCAztec:PAS、HIBCDataMatrixPAS、HIBCQRPAS のエンコードタイプでエンコードできます。既定値: HIBCCode39PAS。 |
| [set_DataLocation](./set_datalocation/)(HIBCPASDataLocation) | データの位置を識別します。 |
## 備考


このサンプルは、[HIBCPASCodetext](./) を使用して HIBC PAS をエンコードおよびデコードする方法を示します。
```cpp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
            HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
        Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

## 関連項目

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
