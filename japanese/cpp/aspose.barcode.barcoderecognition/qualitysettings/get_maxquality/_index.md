---
title: "メソッド"
linktitle: "get_MaxQuality"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " method. MaxQuality 認識品質プリセットです。このプリセットは、C++ で可能なすべてのバーコード、さらには誤ったバーコードも認識できるように開発されました。"
type: docs
weight: 400
url: /ja/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_maxquality/
---
## QualitySettings::get_MaxQuality method


MaxQuality 認識品質プリセット。このプリセットは、可能なすべてのバーコード、さらには誤ったバーコードまで認識できるように開発されています。

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_MaxQuality()
```

## 備考


このサンプルは MaxQuality モードの使用方法を示しています
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


MaxQuality 認識品質プリセット。
## 関連項目

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
