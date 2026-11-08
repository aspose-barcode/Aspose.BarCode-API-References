---
title: "metot"
linktitle: "get_DetectEncoding"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " metodu. Motorun Unicode kod setleri için kod metni kodlamasını tespit etmesini zorlayan bayrak. Varsayılan değer C++'da true."
type: docs
weight: 700
url: /tr/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_detectencoding/
---
## BarcodeSettings::get_DetectEncoding method


Unicode kod kümeleri için kod metni kodlamasını algılamaya zorlayan bayrak. Varsayılan değer doğrudur.

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_DetectEncoding() const
```

## Açıklamalar


Bu örnek, DetectEncoding etkinse metin kodlamasını anında nasıl tespit edeceğinizi gösterir
```cpp
[C#]
using (MemoryStream ms = new MemoryStream())
{
    using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
    {
        generator.SetCodeText("Слово", Encoding.UTF8);
        generator.Save(ms, BarCodeImageFormat.Png);
    }
    //Unicode kod setleri için kodlama tespiti etkin
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    //kodlama tespiti devre dışı
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = false;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using ms As New MemoryStream
    Using generator As New BarcodeGenerator(EncodeTypes.QR, "Слово")
        generator.SetCodeText("Слово", System.Text.Encoding.UTF8)
        generator.Save(ms, BarCodeImageFormat.Png)
    End Using
    'detects encoding for Unicode codesets is enabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = True
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
    'detect encoding is disabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = False
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```


Motorun Unicode kod setleri için kod metni kodlamasını tespit etmesini zorlayan bayrak
## Ayrıca Bakınız

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
