---
title: Timeout
second_title: Aspose.BarCode for.NETAPIリファレンス
description: ミリ秒単位で認識プロセスのタイムアウトを取得または設定します
type: docs
weight: 70
url: /ja/net/aspose.barcode.barcoderecognition/barcodereader/timeout/
---
## BarCodeReader.Timeout property

ミリ秒単位で認識プロセスのタイムアウトを取得または設定します。

```csharp
public int Timeout { get; set; }
```

### プロパティ値

タイムアウト.

### 例

このサンプルは、大きな画像でのタイムアウトによる認識のハングを回避する方法を示しています

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
{
    reader.Timeout = 5000;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png")
    reader.Timeout = 5000
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 関連項目

* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
