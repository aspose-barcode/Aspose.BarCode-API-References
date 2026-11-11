---
title: "BarCodeReader.SetBarCodeReadType"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "BarCodeReader yöntemi. Tanıma için SingleDecodeType tip dizisini ayarlar. ReadBarCodes yönteminden önce çağrılmalıdır"
type: docs
weight: 130
url: /tr/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader.SetBarCodeReadType method

[`SingleDecodeType`](../../singledecodetype/) tip dizisini tanıma için ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır.

```csharp
public void SetBarCodeReadType(params SingleDecodeType[] barcodeTypes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| barcodeTypes | SingleDecodeType[] | Okunacak [`SingleDecodeType`](../../singledecodetype/) tip dizisi. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Ayrıca Bakınız

* class [SingleDecodeType](../../singledecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


