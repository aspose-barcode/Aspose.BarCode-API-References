---
title: "QualitySettings.MaxQuality"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "QualitySettings プロパティ。MaxQuality 認識品質プリセット。このプリセットは、誤ったバーコードも含め、可能なすべてのバーコードを認識できるように開発されています。"
type: docs
weight: 30
url: /ja/net/aspose.barcode.barcoderecognition/qualitysettings/maxquality/
---
## QualitySettings.MaxQuality property

MaxQuality 認識品質プリセット。このプリセットは、すべての可能なバーコード、たとえ誤ったバーコードでも認識できるように開発されています。

```csharp
public static QualitySettings MaxQuality { get; }
```

### Property Value

MaxQuality 認識品質プリセット。

## 例

このサンプルは MaxQuality モードの使用方法を示しています

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 関連項目

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


