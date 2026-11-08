---
title: "metot"
linktitle: "get_BarCodeReadType"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " yöntem. Tanıma için kullanılan barkod çözümleme türünü alır. C++'da ReadBarCodes çağrılmadan önce ayarlanmalıdır."
type: docs
weight: 1000
url: /tr/cpp/aspose.barcode.barcoderecognition/barcodereader/get_barcodereadtype/
---
## BarCodeReader::get_BarCodeReadType method


Tanıma için kullanılan barkod çözümleme türünü alır. [ReadBarCodes](../readbarcodes/) çağrılmadan önce ayarlanmalıdır.

```cpp
System::SharedPtr<BaseDecodeType> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_BarCodeReadType()
```

## Açıklamalar


Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
```cpp
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

## Ayrıca Bakınız

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
