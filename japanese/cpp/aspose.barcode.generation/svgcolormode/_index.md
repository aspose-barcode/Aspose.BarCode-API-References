---
title: "enum"
linktitle: "SvgColorMode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " enum. SVG ファイルで色を塗りつぶす際の可能なモードです。RGB がデフォルトで、SVG 1.1 でサポートされています。RGBA、HSL、HSLA は SVG 2.0 標準で許可されています。RGB の場合でも、不透明度は C++ の \"fill-opacity\" パラメータで設定されます。"
type: docs
weight: 8500
url: /ja/cpp/aspose.barcode.generation/svgcolormode/
---
## SvgColorMode enum


svg ファイルでの塗りつぶし色の可能なモード。RGB がデフォルトで SVG 1.1 でサポートされています。RGBA、HSL、HSLA は SVG 2.0 標準で許可されています。RGB でも不透明度は "fill-opacity" パラメータで設定されます。

```cpp
enum class SvgColorMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| RGB | 0 | RGB モード、例: fill=\"#ff5511\" fill-opacity=\"0.73\"。 デフォルトモード。 |
| RGBA | 1 | RGBA モード、例: fill=\"rgba(255, 85, 17, 0.73)\" |
| HSL | 2 | HSL モード、例: fill=\"hsl(17, 100%, 53%)\" fill-opacity=\"0.73\" |
| HSLA | 3 | HSLA モード、例: fill=\"hsla(30, 50%, 70%, 0.8)\" |

## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
