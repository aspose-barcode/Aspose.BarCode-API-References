---
title: "enum"
linktitle: "PatchFormat"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " 列挙型。PatchCode のフォーマット。単一の PatchCode を生成するには PatchOnly を選択します。C++ で PatchCode を境界として Patch ページを生成するにはページフォーマットを使用します。"
type: docs
weight: 7800
url: /ja/cpp/aspose.barcode.generation/patchformat/
---
## PatchFormat enum


PatchCode フォーマット。PatchOnly を選択すると単一の PatchCode が生成されます。ページ形式を使用すると、PatchCode を境界として持つ Patch ページが生成されます。

```cpp
enum class PatchFormat
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| PatchOnly | 0 | PatchCode のみを生成します |
| A4 | 1 | PatchCodes を枠として、中央にオプションの QR を配置した A4 フォーマットのページを生成します |
| A4_LANDSCAPE | 2 | PatchCodes を枠として、中央にオプションの QR を配置した A4 ランドスケープ形式のページを生成します |
| US_Letter | 3 | PatchCodes を枠として、中央にオプションの QR を配置した US レター形式のページを生成します |
| US_Letter_LANDSCAPE | 4 | PatchCodes を枠として、中央にオプションの QR を配置した US レター ランドスケープ形式のページを生成します |

## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
