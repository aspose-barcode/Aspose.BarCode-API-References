---
title: "Aspose::BarCode::Generation::BaseGenerationParameters クラス"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::BaseGenerationParameters クラス。C++ におけるバーコード画像生成パラメータです。"
type: docs
weight: 700
url: /ja/cpp/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class


バーコード画像生成パラメーター。

```cpp
class BaseGenerationParameters : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_AutoSizeMode](./get_autosizemode/)() const | 自動サイズモードのさまざまなタイプを指定します。デフォルト値: [AutoSizeMode.None](../autosizemode/)。 |
| [get_BackColor](./get_backcolor/)() const | バーコード画像の背景色。デフォルト値: Color.White。詳しくは [Color](../) を参照してください。 |
| [get_Barcode](./get_barcode/)() const | すべてのバーコードプロパティを含む [BarcodeParameters](../barcodeparameters/) を取得します。 |
| [get_Border](./get_border/)() const | バーコード境界のすべての構成プロパティを含む [BorderParameters](../borderparameters/) を取得します。 |
| [get_CaptionAbove](./get_captionabove/)() const | 画像の上にある [BarCode](../../aspose.barcode/) のキャプション。参照: [CaptionParameters](../captionparameters/)。 |
| [get_CaptionBelow](./get_captionbelow/)() const | 画像の下にある [BarCode](../../aspose.barcode/) のキャプション。参照: [CaptionParameters](../captionparameters/)。 |
| [get_Image](./get_image/)() const | 画像パラメータ。参照: [ImageParameters](../imageparameters/)。 |
| [get_ImageHeight](./get_imageheight/)() const | [AutoSizeMode](../autosizemode/) プロパティが [AutoSizeMode.Nearest](../autosizemode/) または [AutoSizeMode.Interpolation](../autosizemode/) に設定されている場合の [BarCode](../../aspose.barcode/) 画像の高さ。 |
| [get_ImageWidth](./get_imagewidth/)() const | [AutoSizeMode](../autosizemode/) プロパティが [AutoSizeMode.Nearest](../autosizemode/) または [AutoSizeMode.Interpolation](../autosizemode/) に設定されている場合の [BarCode](../../aspose.barcode/) 画像の幅。 |
| [get_Resolution](./get_resolution/)() const | [BarCode](../../aspose.barcode/) 画像の解像度を取得します。両方の次元に対して同じ値です。デフォルト値: 96 dpi。 |
| [get_RotationAngle](./get_rotationangle/)() const | [BarCode](../../aspose.barcode/) 画像の回転角度（度単位）。例: RotationAngle = 0 または RotationAngle = 360 は回転なしを意味します。RotationAngle が 90、180、270、または 0 以外の場合、スキャナが画像を読み取る難易度が上がる可能性があります。デフォルト値: 0。 |
| [get_UseAntiAlias](./get_useantialias/)() const | 画像をレンダリングする際にアンチエイリアスモードが使用されているかどうかの値を取得します |
| [set_AutoSizeMode](./set_autosizemode/)(Aspose::BarCode::Generation::AutoSizeMode) | 自動サイズモードのさまざまなタイプを指定します。デフォルト値: [AutoSizeMode.None](../autosizemode/)。 |
| [set_BackColor](./set_backcolor/)(System::Drawing::Color) | バーコード画像の背景色。デフォルト値: Color.White。詳しくは [Color](../) を参照してください。 |
| [set_ImageHeight](./set_imageheight/)(System::SharedPtr\<Unit\>) | [AutoSizeMode](../autosizemode/) プロパティが [AutoSizeMode.Nearest](../autosizemode/) または [AutoSizeMode.Interpolation](../autosizemode/) に設定されている場合の [BarCode](../../aspose.barcode/) 画像の高さ。 |
| [set_ImageWidth](./set_imagewidth/)(System::SharedPtr\<Unit\>) | [AutoSizeMode](../autosizemode/) プロパティが [AutoSizeMode.Nearest](../autosizemode/) または [AutoSizeMode.Interpolation](../autosizemode/) に設定されている場合の [BarCode](../../aspose.barcode/) 画像の幅。 |
| [set_Resolution](./set_resolution/)(float) | [BarCode](../../aspose.barcode/) 画像の解像度を設定します。両方の次元に対して同じ値です。デフォルト値: 96 dpi。 |
| [set_RotationAngle](./set_rotationangle/)(float) | [BarCode](../../aspose.barcode/) 画像の回転角度（度単位）。例: RotationAngle = 0 または RotationAngle = 360 は回転なしを意味します。RotationAngle が 90、180、270、または 0 以外の場合、スキャナが画像を読み取る難易度が上がる可能性があります。デフォルト値: 0。 |
| [set_UseAntiAlias](./set_useantialias/)(bool) | 画像をレンダリングする際にアンチエイリアスモードが使用されているかどうかの値を設定します |
## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
