---
title: "enum"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "C++でenumを使用する方法。"
type: docs
weight: 3600
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enum




```cpp
enum class BarcodeQualityMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| High | 0 | 高品質バーコードの認識メソッドを有効にします。 |
| Normal | 1 | 一般（Normal）品質のバーコード認識メソッドを有効にします。 |
| Low | 2 | 低品質バーコードの認識メソッドを有効にします。 |

## 備考


選択された品質でバーコード要素を認識するメソッドを有効にするモードです。品質が低いバーコード要素は、より多くの高度なメソッドを必要とし、認識が遅くなります。

このサンプルは BarcodeQuality モードの使用方法を示しています
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 関連項目

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
