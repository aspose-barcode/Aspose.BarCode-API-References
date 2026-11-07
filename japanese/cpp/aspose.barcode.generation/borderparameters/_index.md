---
title: "Aspose::BarCode::Generation::BorderParameters クラス"
linktitle: "BorderParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::BorderParameters クラス。C++ のバーコード画像の境界パラメータ。"
type: docs
weight: 800
url: /ja/cpp/aspose.barcode.generation/borderparameters/
---
## BorderParameters class


バーコード画像の境界パラメータ

```cpp
class BorderParameters : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Color](./get_color/)() const | 境界色。デフォルト値: Color.Black。 |
| [get_DashStyle](./get_dashstyle/)() const | 境界の破線スタイル。デフォルト値: [BorderDashStyle.Solid](../borderdashstyle/)。 |
| [get_Visible](./get_visible/)() const | ボーダーの表示。false の場合、パラメーター Width は常に無視されます (0)。デフォルト値: false。 |
| [get_Width](./get_width/)() const | ボーダー幅。デフォルト値: 0。Visible が false に設定されている場合は無視されます。 |
| [set_Color](./set_color/)(System::Drawing::Color) | 境界色。デフォルト値: Color.Black。 |
| [set_DashStyle](./set_dashstyle/)(BorderDashStyle) | 境界の破線スタイル。デフォルト値: [BorderDashStyle.Solid](../borderdashstyle/)。 |
| [set_Visible](./set_visible/)(bool) | ボーダーの表示。false の場合、パラメーター Width は常に無視されます (0)。デフォルト値: false。 |
| [set_Width](./set_width/)(System::SharedPtr\<Unit\>) | ボーダー幅。デフォルト値: 0。Visible が false に設定されている場合は無視されます。 |
| [ToString](./tostring/)() const override | この [BorderParameters](./) の人間が読みやすい文字列表現を返します。 |
## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
