---
title: "列挙型 XDimensionMode"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.BarCodeRecognition.XDimensionMode 列挙型。バーコードの最小要素（マトリックスセルまたはバー）のサイズを 1 から無限大まで設定する認識モードです。"
type: docs
weight: 400
url: /ja/net/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enumeration

バーコードの最小要素（マトリックスセルまたはバー）のサイズを（1 から無限大まで）設定する認識モードです。

```csharp
public enum XDimensionMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Auto | `0` | XDimension の値は AI（SVM）によって検出されます。現在は Normal と同じです。 |
| Small | `1` | BarcodeQuality の品質で、1 ピクセル以上の小さな XDimension を持つバーコードを検出します。 |
| Normal | `2` | BarcodeQuality の品質、または高品質バーコードで、2 ピクセル以上の標準的な XDimension を持つバーコードを検出します。 |
| Large | `3` | 高解像度カメラで撮影された BarcodeQuality の品質で、大きな XDimension を持つバーコードを検出します。 |
| UseMinimalXDimension | `4` | MinimalXDimension に設定されたサイズで、BarcodeQuality の品質のバーコードを検出します。 |

## 例

このサンプルは XDimension モードの使用方法を示しています。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 関連項目

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


