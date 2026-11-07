---
title: "Aspose::BarCode::Generation::ITFParameters クラス"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::ITFParameters クラス。C++ の ITF パラメータです。"
type: docs
weight: 3300
url: /ja/cpp/aspose.barcode.generation/itfparameters/
---
## ITFParameters class


ITF パラメータ。

```cpp
class ITFParameters : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_BorderThickness](./get_borderthickness/)() const | [Unit](../unit/) の値で ITF 境界（ベアラーバー）の厚さを取得します。デフォルト値: 12pt。 |
| [get_BorderType](./get_bordertype/)() const | ITF バーコードのボーダータイプです。デフォルト値: [ITF14BorderType.Bar](../itf14bordertype/)。 |
| [get_QuietZoneCoef](./get_quietzonecoef/)() const | xDimension におけるクワイエットゾーンのサイズです。デフォルト値: 10、つまり xDimension = 2px の場合、クワイエットゾーンは 20px になります。 |
| [set_BorderThickness](./set_borderthickness/)(System::SharedPtr\<Unit\>) | ITF ボーダー（ベアラーバー）の厚さを [Unit](../unit/) の値で設定します。デフォルト値: 12pt。 |
| [set_BorderType](./set_bordertype/)(ITF14BorderType) | ITF バーコードのボーダータイプです。デフォルト値: [ITF14BorderType.Bar](../itf14bordertype/)。 |
| [set_QuietZoneCoef](./set_quietzonecoef/)(int32_t) | xDimension におけるクワイエットゾーンのサイズです。デフォルト値: 10、つまり xDimension = 2px の場合、クワイエットゾーンは 20px になります。 |
| [ToString](./tostring/)() const override | この [ITFParameters](./) の人間が読める文字列表現を返します。 |
## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
