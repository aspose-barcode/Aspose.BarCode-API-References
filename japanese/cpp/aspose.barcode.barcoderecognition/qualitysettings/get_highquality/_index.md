---
title: "メソッド"
linktitle: "get_HighQuality"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " method. HighQuality 認識品質プリセットです。このプリセットは低品質のバーコード用に開発されました。C++ で高度に損傷したバーコードの検出を可能にします。"
type: docs
weight: 300
url: /ja/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highquality/
---
## QualitySettings::get_HighQuality method


HighQuality 認識品質プリセット。このプリセットは低品質のバーコード向けに開発され、極度に損傷したバーコードの検出を可能にします。

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighQuality()
```

## 備考


このサンプルは HighQuality モードの使用方法を示しています
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighQuality 認識品質プリセット。
## 関連項目

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
