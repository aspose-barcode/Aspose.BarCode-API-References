---
title: "Aspose::BarCode::Metered クラス"
linktitle: "メータード"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Metered クラス。C++ でメータードキーを設定するためのメソッドを提供します。"
type: docs
weight: 500
url: /ja/cpp/aspose.barcode/metered/
---
## Metered class


メーターキーを設定するメソッドを提供します。

```cpp
class Metered : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | 消費クレジットを取得します |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | 消費ファイルサイズを取得します |
| [GetProductName](./getproductname/)() | ライセンス製品の名前を取得します |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | メータードがライセンスされているか確認します |
| [Metered](./metered/)() | このクラスの新しいインスタンスを初期化します。 |
| [SetMeteredKey](./setmeteredkey/)(System::String, System::String) | メータードの公開キーと秘密キーを設定します。メータードライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があります。通常、これだけで十分です。ただし、消費データのアップロードが常に失敗し、24 時間を超えると、ライセンスが評価ステータスに設定されます。そのような事態を防ぐために、ライセンスステータスを定期的に確認し、評価ステータスの場合は再度この API を呼び出してください。 |
## 備考


この例では、メータードの公開キーと秘密キーを設定しようとします

<ms>
```cpp
[C#]
@verbatim
Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
@endverbatim
```
</ms>

<java> コンポーネントの jar ファイル:
```cpp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```
</java>
## 関連項目

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
