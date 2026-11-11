---
title: "LuminanceFrame.LuminanceFrame"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "LuminanceFrame コンストラクタ。行間に余白を付けずに LuminanceFrame クラスの新しいインスタンスを初期化します。隣接する行間の距離は width と等しくなります。"
type: docs
weight: 10
url: /ja/net/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame(byte[], int, int, int) {#constructor}

行間に余白を付けずに [`LuminanceFrame`](../) クラスの新しいインスタンスを初期化します。隣接する行間の距離は *width* と等しくなります。

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rotationDegrees = 0)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| data | Byte[] | 各ピクセルにつき 1 バイトの輝度データです。 |
| width | Int32 | フレームの幅（ピクセル単位）。 |
| height | Int32 | フレームの高さ（ピクセル単位）。 |
| rotationDegrees | Int32 | フレームを正立させるために必要な時計回りの回転角度です。サポートされる値は 0、90、180、270 です。既定値は 0 です。 |

### 関連項目

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## LuminanceFrame(byte[], int, int, int, int) {#constructor_1}

指定された row stride を使用して [`LuminanceFrame`](../) クラスの新しいインスタンスを初期化します。

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rowStride, int rotationDegrees)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| data | Byte[] | 各ピクセルにつき 1 バイトの輝度データです。 |
| width | Int32 | フレームの幅（ピクセル単位）。 |
| height | Int32 | フレームの高さ（ピクセル単位）。 |
| rowStride | Int32 | 隣接する 2 行の開始位置間のバイト数です。値は *width* 未満にすることはできません。 |
| rotationDegrees | Int32 | フレームを正立させるために必要な時計回りの回転角度です。サポートされる値は 0、90、180、270 です。 |

### 関連項目

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


