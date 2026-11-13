---
title: "BaseGenerationParameters"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

バーコード画像生成パラメータ。

BaseGenerationParameters 型は次のメンバーを公開します:
## プロパティ
| 名前 | 説明 |
| :- | :- |
| use_anti_alias | 画像をレンダリングする際に anti-aliasing モードが使用されているかどうかを示す値を取得または設定します |
| back_color | バーコード画像の背景色。<br/>            デフォルト値: Color.White。<br/>            詳細は [Color](/barcode/python-net/aspose.drawing/color/) を参照してください。 |
| 解像度 | BarCode 画像の解像度を取得または設定します。<br/>            2 つの次元に対して同じ値を使用します。<br/>            デフォルト値: 96 dpi。 |
| rotation_angle | BarCode 画像の回転角度（度単位）。例: RotationAngle = 0 または RotationAngle = 360 は回転なしを意味します。<br/>            RotationAngle が 90、180、270、または 0 以外の場合、スキャナが画像を読み取る難易度が上がる可能性があります。<br/>            デフォルト値: 0。 |
| caption_above | バーコード画像の上部キャプション。詳細は [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/) を参照してください。 |
| caption_below | バーコード画像の下部キャプション。詳細は [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/) を参照してください。 |
| image | 画像パラメータ。詳細は [ImageParameters](/barcode/python-net/aspose.barcode.generation/imageparameters/) を参照してください。 |
| auto_size_mode | 自動サイズモードのさまざまなタイプを指定します。<br/>            デフォルト値: AutoSizeMode.None。 |
| image_height | BarCode 画像の高さは、[auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) プロパティが AutoSizeMode.Nearest または AutoSizeMode.Interpolation に設定されている場合です。 |
| image_width | BarCode 画像の幅は、[auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) プロパティが AutoSizeMode.Nearest または AutoSizeMode.Interpolation に設定されている場合です。 |
| barcode | すべてのバーコードプロパティを含む [BarcodeParameters](/barcode/python-net/aspose.barcode.generation/barcodeparameters/) を取得します。 |
| border | バーコード境界のすべての構成プロパティを含む [BorderParameters](/barcode/python-net/aspose.barcode.generation/borderparameters/) を取得します。 |

### 関連項目

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

