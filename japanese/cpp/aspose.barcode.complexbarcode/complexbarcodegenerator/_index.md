---
title: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator class"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator class. C++ でバックエンドの複合バーコード（例: SwissQR）画像生成のための ComplexBarcodeGenerator。"
type: docs
weight: 300
url: /ja/cpp/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class


[ComplexBarcodeGenerator](./) for backend complex barcode (e.g. SwissQR) images generation.

```cpp
class ComplexBarcodeGenerator : public System::IDisposable
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/)(System::SharedPtr\<IComplexCodetext\>) | [ComplexBarcodeGenerator](./) のインスタンスを作成します。 |
| [Dispose](./dispose/)() override | 使用中のリソースをクリーンアップします。 |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | 現在の設定で複合バーコード画像を生成します。 |
| [get_Parameters](./get_parameters/)() | [Generation](../../aspose.barcode.generation/) パラメーター。 |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, Generation::BarCodeImageFormat) | 現在の設定で複合バーコード画像を生成し、保存します。 |
| [Save](./save/)(System::String, Generation::BarCodeImageFormat) | 現在の設定で複合バーコード画像を生成し、保存します。 |
| [Save](./save/)(System::String) | 現在の設定で複合バーコード画像を生成し、保存します。 |
## 備考


このサンプルは SwissQR 画像の作成と保存方法を示しています。
```cpp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // 残りのフィールドを初期化します
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

## 関連項目

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
