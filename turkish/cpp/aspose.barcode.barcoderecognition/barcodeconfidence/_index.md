---
title: "enum"
linktitle: "BarCodeConfidence"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " enum. C++'da tanıma güven düzeyini içerir."
type: docs
weight: 3500
url: /tr/cpp/aspose.barcode.barcoderecognition/barcodeconfidence/
---
## BarCodeConfidence enum


Tanıma güven düzeyini içerir

```cpp
enum class BarCodeConfidence : int32_t
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | 0 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) güveni, kod metni doğru tanınmadığında veya barkod olası sahte olarak tespit edildiğinde. |
|  | Moderate | 80 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) güveni, zayıf kontrol toplamına (çoğunlukla 1D barkodlar) sahip barkodlar için veya hiç kontrol toplamı yoksa. Kod metninde bazı yanlış tanımlamalar veya hatta sahte tanımlamalar içerebilir. |

düşük |
| Strong | 100 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) güveni, Reed–Solomon gibi BCH kodlarıyla doğrulanmıştır. Okunan kod metninde hata veya sahte tanımlama olmamalıdır. |

## Açıklamalar


Bu örnek, barkod tipine bağlı olarak BarCodeConfidence'ın nasıl değiştiğini gösterir.
```cpp
[C#]
//Orta düzey güven
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}

//Yüksek güven
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}
[VB.NET]
'Moderate confidence
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using

'Strong confidence
Using generator As New BarcodeGenerator(EncodeTypes.QR, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
