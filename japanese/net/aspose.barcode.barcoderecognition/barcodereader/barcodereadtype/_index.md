---
title: "BarCodeReader.BarCodeReadType"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "BarCodeReader プロパティ。認識に使用されるバーコードデコードタイプを取得または設定します。ReadBarCodes を呼び出す前に設定する必要があります。"
type: docs
weight: 30
url: /ja/net/aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/
---
## BarCodeReader.BarCodeReadType property

認識に使用されるバーコードデコードタイプを取得または設定します。[`ReadBarCodes`](../readbarcodes/) を呼び出す前に設定する必要があります。

```csharp
public BaseDecodeType BarCodeReadType { get; set; }
```

## 例

このサンプルは Code39 と Code128 バーコードの検出方法を示しています。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.BarCodeReadType = new MultiDecodeType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString());
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.BarCodeReadType = New MultiDecodeType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString())
End Using
```

### 関連項目

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


