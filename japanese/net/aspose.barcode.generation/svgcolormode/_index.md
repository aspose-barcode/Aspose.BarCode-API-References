---
title: "列挙型 SvgColorMode"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.Generation.SvgColorMode 列挙型。SVG ファイルで色を塗りつぶす際の可能なモードです。RGB がデフォルトで、SVG 1.1 でサポートされています。RGBA、HSL、HSLA は SVG 2.0 標準で許可されています。RGB の場合でも、透明度は fillopacity パラメータで設定されます。"
type: docs
weight: 1690
url: /ja/net/aspose.barcode.generation/svgcolormode/
---
## SvgColorMode enumeration

SVG ファイルで色を塗りつぶす際の可能なモード。RGB がデフォルトであり SVG 1.1 でサポートされています。RGBA、HSL、HSLA は SVG 2.0 標準で許可されています。RGB の場合でも不透明度は \"fill-opacity\" パラメータで設定されます。

```csharp
public enum SvgColorMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| RGB | `0` | RGB モード、例: fill=\"#ff5511\" fill-opacity=\"0.73\"。デフォルトモードです。 |
| RGBA | `1` | RGBA モード、例: fill=\"rgba(255, 85, 17, 0.73)\" |
| HSL | `2` | HSL モード、例: fill=\"hsl(17, 100%, 53%)\" fill-opacity=\"0.73\" |
| HSLA | `3` | HSLA モード、例: fill=\"hsla(30, 50%, 70%, 0.8)\" |

### 関連項目

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


