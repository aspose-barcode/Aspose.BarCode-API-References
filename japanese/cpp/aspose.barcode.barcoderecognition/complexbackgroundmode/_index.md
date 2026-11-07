---
title: "enum"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "C++でenumを使用する方法。"
type: docs
weight: 3700
url: /ja/cpp/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enum




```cpp
enum class ComplexBackgroundMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| 自動 | 0 | 現在は Disabled と同じです。カラー画像上のカラーバーコードの追加認識を無効にします。 |
| 無効 | 1 | カラー画像上のカラーバーコードの追加認識を無効にします。 |
| 有効 | 2 | カラー画像上のカラーバーコードの追加認識を有効にします。 |

## 備考


カラー画像上のカラーバーコードの追加認識を有効または無効にするモードです。

このサンプルは ComplexBackground モードの使用方法を示しています
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 関連項目

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
