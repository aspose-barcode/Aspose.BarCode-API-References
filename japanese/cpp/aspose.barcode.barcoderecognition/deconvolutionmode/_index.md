---
title: "enum"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "C++でenumを使用する方法。"
type: docs
weight: 3800
url: /ja/cpp/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enum




```cpp
enum class DeconvolutionMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| 高速 | 0 | 高品質画像向けに高速デコンボリューション手法を有効にします。 |
| Normal | 1 | 一般的な画像向けに標準デコンボリューション手法を有効にします。 |
| 低速 | 2 | 低品質画像向けに低速デコンボリューション手法を有効にします。 |

## 備考


画像劣化のレベルを定義するデコンボリューション（画像復元）モードです。デコンボリューションは、カメラで画像を取得する際にぼかしなどの自然な関数によって劣化（畳み込み）した画像を復元できる機能です。画像を劣化させる関数を検出できないため、シャープや数学的形態学など、よく知られた関数をチェックする必要があります。

このサンプルは Deconvolution モードの使用方法を示しています
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 関連項目

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
