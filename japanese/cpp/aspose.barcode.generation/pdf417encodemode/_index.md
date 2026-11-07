---
title: "enum"
linktitle: "Pdf417EncodeMode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " 列挙型。C++ の Pdf417 バーコードエンコードモードです。"
type: docs
weight: 7900
url: /ja/cpp/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enum


Pdf417 バーコードのエンコードモード

```cpp
enum class Pdf417EncodeMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| 自動 | 0 | Auto モードでは、CodeText が最大限のデータ圧縮でエンコードされます。Unicode 文字は、指定された ECIEncoding で再エンコードされ、ECI 識別子が挿入されます。選択された ECI エンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。 |
| バイナリ | 1 | バイナリモードでは、CodeText が最大限のデータ圧縮でエンコードされます。Unicode 文字が見つかった場合、例外がスローされます。 |
| ECI | 2 | ECI モードでは、メッセージ全体が指定された ECIEncoding で再エンコードされ、ECI 識別子が挿入されます。選択された ECI エンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。なお、一部の古い（2006 年以前の）スキャナーはこのモードをサポートしていない可能性があります。 |
| 拡張 | 3 |  |

## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
