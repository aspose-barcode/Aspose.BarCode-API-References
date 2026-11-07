---
title: "Aspose::BarCode::BarCodeRecognition::Quadrangle クラス"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::Quadrangle クラス。C++ で Quadrangle 領域を表す 4 つの Point のセットを格納します。"
type: docs
weight: 3000
url: /ja/cpp/aspose.barcode.barcoderecognition/quadrangle/
---
## Quadrangle class


4 つの [Point](../) をセットで格納し、[Quadrangle](./) 領域を表します。

```cpp
class Quadrangle : public System::IEquatable<System::SharedPtr<Quadrangle>>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Contains](./contains/)(System::Drawing::Point) | 指定された [Point](../) がこの [Quadrangle](./) クラスに含まれているかどうかを判定します。 |
| [Contains](./contains/)(int32_t, int32_t) | 指定された点がこの [Quadrangle](./) クラスに含まれているかどうかを判断します。 |
| [Contains](./contains/)(System::SharedPtr\<Quadrangle\>) | 指定された [Quadrangle](./) がこの [Quadrangle](./) クラスに含まれるか、または交差するかどうかを判断します。 |
| [Contains](./contains/)(System::Drawing::Rectangle) | 指定された [Rectangle](../) がこの [Quadrangle](./) クラスに含まれるか、または交差するかどうかを判断します。 |
| [Equals](./equals/)(System::SharedPtr\<Quadrangle\>) override | このインスタンスが指定された [Quadrangle](./) の値と等しいかどうかを示す値を返します。 |
| [get_BoundingRectangle](./get_boundingrectangle/)() | この [Quadrangle](./) を囲む [Rectangle](../) を取得します |
| [get_IsEmpty](./get_isempty/)() | **Tests** この [Quadrangle](./) のすべての [Point](../) がゼロの値かどうかを確認します。 |
| [get_LeftBottom](./get_leftbottom/)() const | [Quadrangle](./) 領域の左下隅の [Point](../) を取得します |
| [get_LeftTop](./get_lefttop/)() const | [Quadrangle](./) 領域の左上隅の [Point](../) を取得します |
| [get_RightBottom](./get_rightbottom/)() const | [Quadrangle](./) 領域の右下隅の [Point](../) を取得します |
| [get_RightTop](./get_righttop/)() const | [Quadrangle](./) 領域の右上隅の [Point](../) を取得します |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [Quadrangle](./quadrangle/)() | [Quadrangle](./) クラスの新しい空のインスタンスを初期化します。 |
| [Quadrangle](./quadrangle/)(System::Drawing::Point, System::Drawing::Point, System::Drawing::Point, System::Drawing::Point) | [Quadrangle](./) クラスの新しいインスタンスを、記述ポイントで初期化します。 |
| [set_LeftBottom](./set_leftbottom/)(System::Drawing::Point) | [Quadrangle](./) 領域の左下隅の [Point](../) を取得します |
| [set_LeftTop](./set_lefttop/)(System::Drawing::Point) | [Quadrangle](./) 領域の左上隅の [Point](../) を取得します |
| [set_RightBottom](./set_rightbottom/)(System::Drawing::Point) | [Quadrangle](./) 領域の右下隅の [Point](../) を取得します |
| [set_RightTop](./set_righttop/)(System::Drawing::Point) | [Quadrangle](./) 領域の右上隅の [Point](../) を取得します |
| [ToString](./tostring/)() const override | この [Quadrangle](./) の人間が読みやすい文字列表現を返します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| static [Empty](./empty/) | プロパティが未初期化のままの [Quadrangle](./) クラスを表します。 |
## 関連項目

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
