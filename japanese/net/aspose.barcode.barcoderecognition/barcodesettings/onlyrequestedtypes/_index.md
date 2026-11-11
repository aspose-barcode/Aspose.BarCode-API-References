---
title: "BarcodeSettings.OnlyRequestedTypes"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "BarcodeSettings プロパティ。認識のために明示的に指定されたバーコードタイプのみを返します。有効にすると、他の互換または同等のタイプの認識されたバーコードは除外されます。デフォルト値は false です。"
type: docs
weight: 50
url: /ja/net/aspose.barcode.barcoderecognition/barcodesettings/onlyrequestedtypes/
---
## BarcodeSettings.OnlyRequestedTypes property

認識のために明示的に指定されたバーコードタイプのみを返します。有効にすると、他の互換または同等のタイプの認識されたバーコードは除外されます。デフォルト値は false です。

```csharp
public bool OnlyRequestedTypes { get; set; }
```

### Property Value

認識のために明示的に指定されたバーコードタイプのみを返します。デフォルト値は false です。

## 例

このサンプルは、認識結果を要求されたバーコードタイプのみに制限する方法を示しています

```csharp
[C#]
//EAN13 バーコードを生成する
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//UPCA バーコードのみを認識する（結果なし、ソースが EAN13 のため）
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//互換タイプを認識: EAN13、UPCA、ISSN、ISMN、ISBN（EAN13 は UPCA 相当として返されます）
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```

### 関連項目

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


