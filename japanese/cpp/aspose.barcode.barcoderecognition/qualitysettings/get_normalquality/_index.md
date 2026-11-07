---
title: "メソッド"
linktitle: "get_NormalQuality"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。NormalQuality 認識品質プリセットです。C++ でほとんどのバーコードに適しています。"
type: docs
weight: 200
url: /ja/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_normalquality/
---
## QualitySettings::get_NormalQuality method


NormalQuality 認識品質プリセット。ほとんどのバーコードに適しています。

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_NormalQuality()
```

## 備考


このサンプルは NormalQuality モードの使用方法を示しています。
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


NormalQuality 認識品質プリセット。
## 関連項目

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
