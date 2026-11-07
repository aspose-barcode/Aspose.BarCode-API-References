---
title: "Aspose::BarCode::Generation::CodetextParameters クラス"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::CodetextParameters クラス。C++ のコードテキスト パラメータ。"
type: docs
weight: 1500
url: /ja/cpp/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class


コードテキスト パラメータ。

```cpp
class CodetextParameters : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Alignment](./get_alignment/)() const | コードテキストの配置を取得します。デフォルト値: [StringAlignment.Center](../textalignment/)。 |
| [get_Color](./get_color/)() const | 表示する CodeText の色を指定します。デフォルト値: Color.Black。 |
| [get_Font](./get_font/)() const | 表示される CodeText のフォントを指定します。デフォルト値: Arial 5pt regular。FontMode が [FontMode.Auto](../aztecencodemode/) に設定されている場合は無視されます。 |
| [get_FontMode](./get_fontmode/)() const | FontMode を指定します。FontMode が Auto に設定されている場合、フォントサイズは xDimension の値に基づいて自動的に計算されます。[FontMode.Auto](../aztecencodemode/) は、特に [AutoSizeMode.Nearest](../autosizemode/) または [AutoSizeMode.Interpolation](../autosizemode/) で使用することが推奨されます。デフォルト値: [FontMode.Auto](../aztecencodemode/)。 |
| [get_Location](./get_location/)() const | 表示される CodeText の位置を指定します。CodeText を非表示にするには [CodeLocation.None](../codelocation/) を設定します。デフォルト値は、1D バーコードの場合は [CodeLocation.Below](../codelocation/) で、2D バーコードの場合は [CodeLocation.None](../codelocation/) です。 |
| [get_NoWrap](./get_nowrap/)() const | テキスト内の改行（ワードラップ）を指定します。デフォルト値: false。 |
| [get_Space](./get_space/)() const | CodeText と [BarCode](../../aspose.barcode/) の間のスペース（[Unit ](../unit/) 単位）。デフォルト値: 2pt。EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon では無視されます。 |
| [get_TwoDDisplayText](./get_twoddisplaytext/)() const | 2D バーコードで codetext の代わりに表示されるテキスト。使用対象: Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode |
| [set_Alignment](./set_alignment/)(TextAlignment) | コードテキストの配置を設定します。デフォルト値: [StringAlignment.Center](../textalignment/)。 |
| [set_Color](./set_color/)(System::Drawing::Color) | 表示する CodeText の色を指定します。デフォルト値: Color.Black。 |
| [set_FontMode](./set_fontmode/)(Aspose::BarCode::Generation::FontMode) | FontMode を指定します。FontMode が Auto に設定されている場合、フォントサイズは xDimension の値に基づいて自動的に計算されます。[FontMode.Auto](../aztecencodemode/) は、特に [AutoSizeMode.Nearest](../autosizemode/) または [AutoSizeMode.Interpolation](../autosizemode/) で使用することが推奨されます。デフォルト値: [FontMode.Auto](../aztecencodemode/)。 |
| [set_Location](./set_location/)(CodeLocation) | 表示される CodeText の位置を指定します。CodeText を非表示にするには [CodeLocation.None](../codelocation/) を設定します。デフォルト値は、1D バーコードの場合は [CodeLocation.Below](../codelocation/) で、2D バーコードの場合は [CodeLocation.None](../codelocation/) です。 |
| [set_NoWrap](./set_nowrap/)(bool) | テキスト内の改行（ワードラップ）を指定します。デフォルト値: false。 |
| [set_Space](./set_space/)(System::SharedPtr\<Unit\>) | CodeText と [BarCode](../../aspose.barcode/) の間のスペース（[Unit ](../unit/) 単位）。デフォルト値: 2pt。EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon では無視されます。 |
| [set_TwoDDisplayText](./set_twoddisplaytext/)(System::String) | 2D バーコードで codetext の代わりに表示されるテキスト。使用対象: Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode |
| [ToString](./tostring/)() const override | この [CodetextParameters](./) の人間が読める文字列表現を返します。 |
## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
