---
title: "BarCodeReader.Timeout"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "BarCodeReader özelliği. Tanıma işleminin zaman aşımını milisaniye cinsinden alır veya ayarlar"
type: docs
weight: 80
url: /tr/net/aspose.barcode.barcoderecognition/barcodereader/timeout/
---
## BarCodeReader.Timeout property

Tanıma işleminin zaman aşımını milisaniye cinsinden alır veya ayarlar.

```csharp
public int Timeout { get; set; }
```

### Property Value

Zaman aşımı.

## Örnekler

Bu örnek, büyük görüntülerde zaman aşımıyla tanıma takılmalarını önlemenin yolunu gösterir.

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

### Ayrıca Bakınız

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


