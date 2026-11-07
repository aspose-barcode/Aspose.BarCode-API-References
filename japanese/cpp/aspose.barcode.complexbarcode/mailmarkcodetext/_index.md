---
title: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext クラス"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext クラス。C++ で 4 状態の Royal Mailmark コードに埋め込まれたテキストのエンコードとデコードを行うクラスです。"
type: docs
weight: 1500
url: /ja/cpp/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class


4状態のRoyal Mailmarkコードに埋め込まれたテキストをエンコードおよびデコードするクラスです。

```cpp
class MailmarkCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Class](./get_class/)() const | \"0\" - NULL またはテスト \"1\" - 1C（小売） \"2\" - 2C（小売） \"3\" - 3C（小売） \"4\" - プレミアム（RetailPublishing Mail、将来の使用のための予備） \"5\" - デファード（小売） \"6\" - エア（小売、将来の使用のための予備） \"7\" - サーフェス（小売、将来の使用のための予備） \"8\" - プレミアム（ネットワークアクセス） \"9\" - スタンダード（ネットワークアクセス） |
| [get_DestinationPostCodePlusDPS](./get_destinationpostcodeplusdps/)() const | PC と DP は PAF 形式に準拠する必要があります。国際的な \"XY11     \"（末尾のスペース5つに注意）を示す9文字の文字列、または国内の仕分けコードを示す文字パターンです。国内の仕分けコードは、外向き郵便番号、内向き郵便番号、そして配達ポイントサフィックスで構成されます。 |
| [get_Format](./get_format/)() const | \"0\" – NULL またはテスト \"1\" – 手紙 \"2\" – 大型手紙 |
| [get_ItemID](./get_itemid/)() const | 最大値は 99999999 です。 |
| [get_SupplychainID](./get_supplychainid/)() const | バーコード C の最大値は 99、バーコード L の最大値は 999999 です。 |
| [get_VersionID](./get_versionid/)() const | 現在 \"1\" – Mailmark バーコード用（0 と 2〜9 および A〜Z は将来の使用のために予備） |
| [GetBarcodeType](./getbarcodetype/)() override | バーコードの種類を取得します。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Mailmark データからコードテキストを構築します。 |
| [InitFromString](./initfromstring/)(System::String) override | 構築されたコードテキストから Mailmark データを初期化します。 |
| [MailmarkCodetext](./mailmarkcodetext/)() | 新しい [MailmarkCodetext](./) クラスのインスタンスを初期化します。 |
| [set_Class](./set_class/)(System::String) | \"0\" - NULL またはテスト \"1\" - 1C（小売） \"2\" - 2C（小売） \"3\" - 3C（小売） \"4\" - プレミアム（RetailPublishing Mail、将来の使用のための予備） \"5\" - デファード（小売） \"6\" - エア（小売、将来の使用のための予備） \"7\" - サーフェス（小売、将来の使用のための予備） \"8\" - プレミアム（ネットワークアクセス） \"9\" - スタンダード（ネットワークアクセス） |
| [set_DestinationPostCodePlusDPS](./set_destinationpostcodeplusdps/)(System::String) | PC と DP は PAF 形式に準拠する必要があります。国際的な \"XY11     \"（末尾のスペース5つに注意）を示す9文字の文字列、または国内の仕分けコードを示す文字パターンです。国内の仕分けコードは、外向き郵便番号、内向き郵便番号、そして配達ポイントサフィックスで構成されます。 |
| [set_Format](./set_format/)(int32_t) | \"0\" – NULL またはテスト \"1\" – 手紙 \"2\" – 大型手紙 |
| [set_ItemID](./set_itemid/)(int32_t) | 最大値は 99999999 です。 |
| [set_SupplychainID](./set_supplychainid/)(int32_t) | バーコード C の最大値は 99、バーコード L の最大値は 999999 です。 |
| [set_VersionID](./set_versionid/)(int32_t) | 現在 \"1\" – Mailmark バーコード用（0 と 2〜9 および A〜Z は将来の使用のために予備） |
## 関連項目

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
