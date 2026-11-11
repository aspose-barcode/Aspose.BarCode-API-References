---
title: "列挙体 ComplexBackgroundMode"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.BarCodeRecognition.ComplexBackgroundMode 列挙体。カラー画像上のカラーバーコードの追加認識を有効または無効にするモード"
type: docs
weight: 200
url: /ja/net/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enumeration

カラー画像上のカラーバーコードの追加認識を有効または無効にするモード。

```csharp
public enum ComplexBackgroundMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Auto | `0` | 現在は Disabled と同じです。カラー画像上のカラーバーコードの追加認識を無効にします。 |
| Disabled | `1` | カラー画像上のカラーバーコードの追加認識を無効にします。 |
| Enabled | `2` | カラー画像上のカラーバーコードの追加認識を有効にします。 |

## 例

このサンプルは ComplexBackground モードの使用方法を示しています

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 関連項目

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


