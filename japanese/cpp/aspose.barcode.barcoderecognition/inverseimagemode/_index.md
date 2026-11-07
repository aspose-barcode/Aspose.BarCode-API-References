---
title: "enum"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "C++でenumを使用する方法。"
type: docs
weight: 3900
url: /ja/cpp/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enum




```cpp
enum class InverseImageMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Auto | 0 | すべてのバーコードタイプで、[QR](../../aspose.barcode.barcoderecognition.qr/) コードを除く逆画像上のバーコードの追加認識を無効にします。 |
| 無効 | 1 | 逆画像上のバーコードの追加認識を無効にします。 |
| 有効 | 2 | 逆画像上のバーコードの追加認識を有効にします |

## 備考


色が反転した（輝度）画像上のバーコードの追加認識を有効または無効にするモードです。

このサンプルは InverseImage モードの使用方法を示しています
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 関連項目

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
