---
title: "BarCodeReader.BarCodeReadType"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "BarCodeReader özelliği. Tanıma için kullanılan barkod kod çözme türünü alır veya ayarlar. ReadBarCodes çağrılmadan önce ayarlanmalıdır."
type: docs
weight: 30
url: /tr/net/aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/
---
## BarCodeReader.BarCodeReadType property

Tanıma için kullanılan barkod kod çözme türünü alır veya ayarlar. [`ReadBarCodes`](../readbarcodes/) çağrılmadan önce ayarlanmalıdır.

```csharp
public BaseDecodeType BarCodeReadType { get; set; }
```

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

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

### Ayrıca Bakınız

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


