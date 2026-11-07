---
title: "メソッド"
linktitle: "SetMeteredKey"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "メソッド。メーター制御の公開鍵と秘密鍵を設定します。メーターライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があります。通常、これだけで十分です。ただし、消費データのアップロードが常に失敗し、24 時間を超えると、ライセンスは評価ステータスに設定されます。そのような事態を回避するために、ライセンスステータスを定期的に確認し、評価ステータスの場合は C++ でこの API を再度呼び出してください。"
type: docs
weight: 200
url: /ja/cpp/aspose.barcode/metered/setmeteredkey/
---
## Metered::SetMeteredKey method


メータードの公開キーと秘密キーを設定します。メータードライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があります。通常、これだけで十分です。ただし、消費データのアップロードが常に失敗し、24 時間を超えると、ライセンスが評価ステータスに設定されます。そのような事態を防ぐために、ライセンスステータスを定期的に確認し、評価ステータスの場合は再度この API を呼び出してください。

```cpp
void Aspose::BarCode::Metered::SetMeteredKey(System::String publicKey, System::String privateKey)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| publicKey | System::String | 公開鍵 |
| privateKey | System::String | 秘密鍵 |

## 関連項目

* Class [Metered](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
