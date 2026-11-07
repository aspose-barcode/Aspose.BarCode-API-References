---
title: "constructor"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " コンストラクタ。行間にパディングなしで LuminanceFrame クラスの新しいインスタンスを初期化します。隣接する行間の距離は C++ で幅と等しくなります。"
type: docs
weight: 600
url: /ja/cpp/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) constructor


[LuminanceFrame](../) クラスの新しいインスタンスを、行間にパディングなしで初期化します。隣接する行間の距離は *width* と等しいです。

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rotationDegrees=0)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | 各ピクセルあたり1バイトの輝度データです。 |
| width | int32_t | フレームの幅（ピクセル単位）です。 |
| height | int32_t | フレームの高さ（ピクセル単位）です。 |
| rotationDegrees | int32_t | フレームを正立させて表示するために必要な時計回りの回転角度です。サポートされる値は 0、90、180、270 で、デフォルト値は 0 です。 |

## 関連項目

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) constructor


指定された row stride を使用して [LuminanceFrame](../) クラスの新しいインスタンスを初期化します。

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rowStride, int32_t rotationDegrees)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | 各ピクセルあたり1バイトの輝度データです。 |
| width | int32_t | フレームの幅（ピクセル単位）です。 |
| height | int32_t | フレームの高さ（ピクセル単位）です。 |
| rowStride | int32_t | 隣接する 2 行の開始位置間のバイト単位の距離です。値は *width* 未満にすることはできません。 |
| rotationDegrees | int32_t | フレームを正立させて表示するために必要な時計回りの回転です。サポートされている値は 0、90、180、270 です。 |

## 関連項目

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
