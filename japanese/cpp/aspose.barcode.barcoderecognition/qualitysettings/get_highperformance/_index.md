---
title: "メソッド"
linktitle: "get_HighPerformance"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " method. HighPerformance 認識品質プリセット。このモードでは高品質のバーコードがうまく認識されます（C++）。"
type: docs
weight: 100
url: /ja/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highperformance/
---
## QualitySettings::get_HighPerformance method


HighPerformance 認識品質プリセット。このモードでは高品質のバーコードが適切に認識されます。

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighPerformance()
```

## 備考


このサンプルは HighPerformance モードの使用方法を示しています。
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighPerformance 認識品質プリセット。
## 関連項目

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
