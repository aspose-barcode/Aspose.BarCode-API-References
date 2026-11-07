---
title: "Aspose::BarCode::Generation::Unit クラス"
linktitle: "Unit"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::Unit クラス。C++ で異なる単位（ピクセル、インチなど）でサイズ値を指定します。"
type: docs
weight: 5000
url: /ja/cpp/aspose.barcode.generation/unit/
---
## Unit class


さまざまな単位（ピクセル、インチなど）でサイズ値を指定します。

```cpp
class Unit : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | このインスタンスと、[Unit](./) オブジェクトである必要がある指定されたオブジェクトが同じ値かどうかを判断します。 |
| [get_Document](./get_document/)() | 文書単位でサイズ値を取得します。 |
| [get_Inches](./get_inches/)() | インチ単位でサイズ値を取得します。 |
| [get_Millimeters](./get_millimeters/)() | ミリメートル単位でサイズ値を取得します。 |
| [get_Pixels](./get_pixels/)() | ピクセル単位でサイズ値を取得します。 |
| [get_Point](./get_point/)() | ポイント単位でサイズ値を取得します。 |
| [get_Resolution](./get_resolution/)() const | 解像度 |
| [GetHashCode](./gethashcode/)() const override | このオブジェクトのハッシュコードを返します。 |
| [set_Document](./set_document/)(float) | 文書単位でサイズ値を設定します。 |
| [set_Inches](./set_inches/)(float) | インチ単位でサイズ値を設定します。 |
| [set_Millimeters](./set_millimeters/)(float) | ミリメートル単位でサイズ値を設定します。 |
| [set_Pixels](./set_pixels/)(float) | ピクセル単位でサイズ値を設定します。 |
| [set_Point](./set_point/)(float) | ポイント単位でサイズ値を設定します。 |
| [ToString](./tostring/)() const override | この [Unit](./) の人間が読める文字列表現を返します。 |
## 備考


このサンプルは、[BarCode](../../aspose.barcode/) 画像を作成して保存する方法を示しています。
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
