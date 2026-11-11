---
title: "列挙体 DeconvolutionMode"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.BarCodeRecognition.DeconvolutionMode 列挙体。 画像劣化のレベルを定義するデコンボリューション画像復元モード。もともとデコンボリューションは、カメラで画像を取得する際のぼかしなどの自然な関数によって劣化（畳み込み）した画像を復元できる機能です。画像を劣化させる関数を検出できないため、シャープや数学的形態学など、最もよく知られた関数をチェックする必要があります。"
type: docs
weight: 240
url: /ja/net/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enumeration

デコンボリューション（画像復元）モードは、画像劣化のレベルを定義します。もともとデコンボリューションは、カメラで画像を取得する際のぼかしなどの自然な関数によって劣化（畳み込み）した画像を復元できる機能です。画像を劣化させる関数を検出できないため、シャープや数学的形態学など、最もよく知られた関数をチェックする必要があります。

```csharp
public enum DeconvolutionMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Fast | `0` | 高品質画像向けに高速デコンボリューション手法を有効にします。 |
| Normal | `1` | 一般的な画像向けに標準デコンボリューション手法を有効にします。 |
| Slow | `2` | 低品質画像向けに低速デコンボリューション手法を有効にします。 |

## 例

このサンプルは Deconvolution モードの使用方法を示しています

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 関連項目

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


