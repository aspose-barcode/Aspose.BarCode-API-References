---
title: "Metered"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode/metered/
---

## Metered class

メーターキーを設定するためのメソッドを提供します。

Metered 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| Metered() | Metered クラスの新しいインスタンスを初期化します |
## メソッド
| 名前 | 説明 |
| :- | :- |
| set_metered_key(public_key, private_key) | メーター制御の公開鍵と秘密鍵を設定します。<br/>            メーター制御ライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があります。通常、これだけで十分です。 <br/>            ただし、消費データのアップロードに常に失敗し、24 時間を超えると、ライセンスは評価状態に設定されます。 <br/>            このような事態を回避するために、定期的にライセンス状態を確認し、評価状態であれば再度この API を呼び出すべきです。 |
| get_consumption_quantity() | 消費ファイルサイズを取得します |
| get_consumption_credit() | 消費クレジットを取得します |
| get_product_name() | ライセンス製品の名前を取得します |
| is_metered_licensed() | メーター制御がライセンスされているか確認します |

### 関連項目

* namespace [aspose.barcode](/barcode/python-net/aspose.barcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

