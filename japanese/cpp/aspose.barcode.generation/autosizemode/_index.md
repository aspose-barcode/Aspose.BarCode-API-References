---
title: "enum"
linktitle: "AutoSizeMode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " enum. C++ における自動サイズ設定モードのさまざまなタイプを指定します。"
type: docs
weight: 5200
url: /ja/cpp/aspose.barcode.generation/autosizemode/
---
## AutoSizeMode enum


自動サイズモードのさまざまなタイプを指定します。

```cpp
enum class AutoSizeMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| なし | 0 | 自動リサイズは無効です。 |
| Nearest | 1 | バーコードを ImageWidth と ImageHeight プロパティで指定された最も近い最小サイズにリサイズします。デフォルトのアスペクト比を保持します。 |
| 補間 | 2 | バーコードのサイズを指定されたサイズにリサイズします。サイズは ImageWidth と ImageHeight プロパティで指定できます。スケーリング後、生成されたバーコードは無効（読み取れない）になる可能性があります。 |

## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
