---
title: "enum"
linktitle: "XDimensionMode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "C++でenumを使用する方法。"
type: docs
weight: 4000
url: /ja/cpp/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enum




```cpp
enum class XDimensionMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| 自動 | 0 | XDimensionの値はAI（SVM）によって検出されます。現在はNormalと同じです |
| Small | 1 | BarcodeQualityの品質で、1ピクセル以上の小さなXDimensionを持つバーコードを検出します |
| Normal | 2 | BarcodeQualityの品質、または高品質バーコードで、2ピクセル以上の標準的なXDimensionを持つバーコードを検出します |
| Large | 3 | 高解像度カメラで撮影されたBarcodeQualityの品質で、大きなXDimensionを持つバーコードを検出します |
| UseMinimalXDimension | 4 | MinimalXDimensionで設定されたサイズからバーコードを検出し、BarcodeQualityの品質で評価します |

## 備考


[Recognition](../../aspose.barcode.barcoderecognition.recognition/) mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. 

このサンプルはXDimensionモードの使用方法を示しています
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 関連項目

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
