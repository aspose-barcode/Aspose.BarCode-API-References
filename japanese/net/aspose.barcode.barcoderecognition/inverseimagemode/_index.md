---
title: "列挙体 InverseImageMode"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.BarCodeRecognition.InverseImageMode 列挙体。 反転した色の輝度を持つ画像上でのバーコードの追加認識を有効または無効にするモード"
type: docs
weight: 270
url: /ja/net/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enumeration

反転した色（輝度）を持つ画像上でのバーコードの追加認識を有効または無効にするモード。

```csharp
public enum InverseImageMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Auto | `0` | QRコードを除くすべてのバーコードタイプに対して、逆画像上でのバーコードの追加認識を無効にします。 |
| Disabled | `1` | 逆画像上でのバーコードの追加認識を無効にします。 |
| Enabled | `2` | 逆画像上でのバーコードの追加認識を有効にします |

## 例

このサンプルは InverseImage モードの使用方法を示しています

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 関連項目

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


