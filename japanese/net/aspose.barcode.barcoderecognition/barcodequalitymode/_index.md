---
title: "列挙体 BarcodeQualityMode"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.BarCodeRecognition.BarcodeQualityMode 列挙体。選択された品質でバーコード要素を認識するメソッドを有効にするモードです。品質が低いバーコード要素は、より多くの高度なメソッドを必要とし、認識が遅くなります。"
type: docs
weight: 110
url: /ja/net/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enumeration

選択された品質でバーコード要素を認識するメソッドを有効にするモードです。品質が低いバーコード要素は、より多くの高度なメソッドを必要とし、認識が遅くなります。

```csharp
public enum BarcodeQualityMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| High | `0` | 高品質バーコードの認識メソッドを有効にします。 |
| Normal | `1` | 一般（標準）品質バーコードの認識メソッドを有効にします。 |
| Low | `2` | 低品質バーコードの認識メソッドを有効にします。 |

## 例

このサンプルは BarcodeQuality モードの使用方法を示しています

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 関連項目

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


