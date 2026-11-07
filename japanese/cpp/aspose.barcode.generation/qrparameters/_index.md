---
title: "Aspose::BarCode::Generation::QrParameters クラス"
linktitle: "QrParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::QrParameters クラス。C++ における QR パラメーター。"
type: docs
weight: 4400
url: /ja/cpp/aspose.barcode.generation/qrparameters/
---
## QrParameters class


QR パラメータ。

```cpp
class QrParameters : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) モジュールの高さ/幅比率。 |
| [get_ECIEncoding](./get_eciencoding/)() const | 拡張チャネル解釈識別子です。シンボル内のデータをエンコードするために使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装はすべての既知の文字セットエンコーディングで構成されています。MicroQR ではサポートされていません。 |
| [get_EncodeGS1SeparatorInByteMode](./get_encodegs1separatorinbytemode/)() const |  |
| [get_EncodeMode](./get_encodemode/)() const | [BarCode](../../aspose.barcode/) のエンコードモードの QR シンボルタイプです。デフォルト値: [QREncodeMode.Auto](../aztecencodemode/). |
| [get_ErrorLevel](./get_errorlevel/)() const | QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベルです。低から高へ: LevelL、LevelM、LevelQ、LevelH。QRErrorLevel を参照してください。 |
| [get_MicroQRVersion](./get_microqrversion/)() const | MicroQR コードのバージョンです。バージョン M1 から M4 まで。デフォルト値は [MicroQRVersion.Auto](../aztecencodemode/)です。 |
| [get_RectMicroQrVersion](./get_rectmicroqrversion/)() const | RectMicroQR コードのバージョンです。バージョン R7x59 から R17x139 まで。デフォルト値は [RectMicroQRVersion.Auto](../aztecencodemode/)です。 |
| [get_StructuredAppend](./get_structuredappend/)() const | QR の構造化付加パラメータです。構造化付加モードは MicroQR および RectMicroQR バーコードではサポートされていません。 |
| [get_Version](./get_version/)() const | QR コードのバージョンです。Version1 から Version40 まで。デフォルト値は [QRVersion.Auto](../aztecencodemode/)です。 |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) モジュールの高さ/幅比率。 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | 拡張チャネル解釈識別子です。シンボル内のデータをエンコードするために使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装はすべての既知の文字セットエンコーディングで構成されています。MicroQR ではサポートされていません。 |
| [set_EncodeGS1SeparatorInByteMode](./set_encodegs1separatorinbytemode/)(bool) |  |
| [set_EncodeMode](./set_encodemode/)(QREncodeMode) | [BarCode](../../aspose.barcode/) のエンコードモードの QR シンボルタイプです。デフォルト値: [QREncodeMode.Auto](../aztecencodemode/). |
| [set_ErrorLevel](./set_errorlevel/)(QRErrorLevel) | QR、MicroQR、RectMicroQR バーコードの Reed-Solomon 誤り訂正レベルです。低から高へ: LevelL、LevelM、LevelQ、LevelH。QRErrorLevel を参照してください。 |
| [set_MicroQRVersion](./set_microqrversion/)(Aspose::BarCode::Generation::MicroQRVersion) | MicroQR コードのバージョンです。バージョン M1 から M4 まで。デフォルト値は [MicroQRVersion.Auto](../aztecencodemode/)です。 |
| [set_RectMicroQrVersion](./set_rectmicroqrversion/)(RectMicroQRVersion) | RectMicroQR コードのバージョンです。バージョン R7x59 から R17x139 まで。デフォルト値は [RectMicroQRVersion.Auto](../aztecencodemode/)です。 |
| [set_StructuredAppend](./set_structuredappend/)(System::SharedPtr\<QrStructuredAppendParameters\>) | QR の構造化付加パラメータです。構造化付加モードは MicroQR および RectMicroQR バーコードではサポートされていません。 |
| [set_Version](./set_version/)(QRVersion) | QR コードのバージョンです。Version1 から Version40 まで。デフォルト値は [QRVersion.Auto](../aztecencodemode/)です。 |
| [ToString](./tostring/)() const override | この [QrParameters](./) の人間が読みやすい文字列表現を返します。 |
## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
