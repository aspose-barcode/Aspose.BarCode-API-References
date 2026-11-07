---
title: "Aspose::BarCode::BarCodeRecognition::LuminanceFrame クラス"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::LuminanceFrame クラス。8ビットのグレースケール画像フレームを表します。各ピクセルは、C++ における輝度値を含む 1 バイトで表されます。"
type: docs
weight: 2400
url: /ja/cpp/aspose.barcode.barcoderecognition/luminanceframe/
---
## LuminanceFrame class


8 ビットのグレースケール画像フレームを表します。各ピクセルは、輝度値を含む 1 バイトで表現されます。

```cpp
class LuminanceFrame : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Data](./get_data/)() const | 輝度データを取得します。 |
| [get_Height](./get_height/)() const | フレームの高さ（ピクセル単位）を取得します。 |
| [get_RotationDegrees](./get_rotationdegrees/)() const | 正しい向きになるようにフレームを時計回りに回転させる必要がある角度（度）を取得します。 |
| [get_RowStride](./get_rowstride/)() const | 隣接する 2 行の開始位置間のバイト数の距離を取得します。 |
| [get_Width](./get_width/)() const | フレームの幅（ピクセル単位）を取得します。 |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) | 行間にパディングなしで [LuminanceFrame](./) クラスの新しいインスタンスを初期化します。隣接する行間の距離は *width* と等しくなります。 |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) | 指定された行ストライドで [LuminanceFrame](./) クラスの新しいインスタンスを初期化します。 |
## 関連項目

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
