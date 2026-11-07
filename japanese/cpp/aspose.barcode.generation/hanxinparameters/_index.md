---
title: "Aspose::BarCode::Generation::HanXinParameters クラス"
linktitle: "HanXinParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::HanXinParameters クラス。C++ の Han Xin パラメータ。"
type: docs
weight: 2900
url: /ja/cpp/aspose.barcode.generation/hanxinparameters/
---
## HanXinParameters class


Han Xin パラメータ。

```cpp
class HanXinParameters : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | 拡張チャネル解釈識別子。これは、シンボル内のデータをエンコードするために使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装には、すべてのよく知られた文字セットエンコーディングが含まれています。 |
| [get_EncodeMode](./get_encodemode/)() const | HanXin エンコーディングモード。デフォルト値: EncodeMode.Mixed。 |
| [get_ErrorLevel](./get_errorlevel/)() const | Han Xin バーコードの Reed-Solomon エラー訂正レベル。低から高へ: L1, L2, L3, L4。ErrorLevel を参照してください。 |
| [get_Version](./get_version/)() const | HanXin コードのバージョン。Version01 から Version84 までの Han Xin コードに対応しています。デフォルト値は [Version.Auto](../aztecencodemode/) です。 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | 拡張チャネル解釈識別子。これは、シンボル内のデータをエンコードするために使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装には、すべてのよく知られた文字セットエンコーディングが含まれています。 |
| [set_EncodeMode](./set_encodemode/)(HanXinEncodeMode) | HanXin エンコーディングモード。デフォルト値: EncodeMode.Mixed。 |
| [set_ErrorLevel](./set_errorlevel/)(HanXinErrorLevel) | Han Xin バーコードの Reed-Solomon エラー訂正レベル。低から高へ: L1, L2, L3, L4。ErrorLevel を参照してください。 |
| [set_Version](./set_version/)(HanXinVersion) | HanXin コードのバージョン。Version01 から Version84 までの Han Xin コードに対応しています。デフォルト値は [Version.Auto](../aztecencodemode/) です。 |
| [ToString](./tostring/)() const override | この [HanXinParameters](./) の人間が読める文字列表現を返します。 |
## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
