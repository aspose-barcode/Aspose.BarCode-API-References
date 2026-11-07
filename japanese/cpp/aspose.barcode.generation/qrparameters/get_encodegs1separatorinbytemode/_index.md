---
title: "メソッド"
linktitle: "get_EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "C++ で Aspose::BarCode::Generation::QrParameters クラスの get_EncodeGS1SeparatorInByteMode メソッドを使用する方法。"
type: docs
weight: 1700
url: /ja/cpp/aspose.barcode.generation/qrparameters/get_encodegs1separatorinbytemode/
---
## QrParameters::get_EncodeGS1SeparatorInByteMode method




```cpp
bool Aspose::BarCode::Generation::QrParameters::get_EncodeGS1SeparatorInByteMode() const
```

## 備考


QR および RectMicroQR バーコードで GS1 の特殊文字をバイトモードでエンコードすべきかを示す値を取得します。

false の場合、QR 仕様に従い、GS1 区切り文字は英数字モードで '' としてエンコードされる可能性があります。

true の場合、GS1 グループ区切り文字はバイトモードで 0x1D 文字としてエンコードされ、'' 文字もデータとして保持するためにバイトモードでエンコードされます。

このオプションは、バイトレベルの GS1 グループ区切り文字を期待するデコーダとの互換性を向上させ、'' データ文字が GS1 区切り文字として解釈されるのを防止します。
## 関連項目

* Class [QrParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
