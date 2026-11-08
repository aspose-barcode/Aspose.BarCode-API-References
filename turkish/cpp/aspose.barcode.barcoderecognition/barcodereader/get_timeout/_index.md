---
title: "metot"
linktitle: "get_Timeout"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " metod. Tanıma işleminin zaman aşımını milisaniye cinsinden C++'da alır."
type: docs
weight: 300
url: /tr/cpp/aspose.barcode.barcoderecognition/barcodereader/get_timeout/
---
## BarCodeReader::get_Timeout method


Tanıma işleminin zaman aşımını milisaniye cinsinden alır.

```cpp
int32_t Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_Timeout()
```

## Açıklamalar


Zaman aşımı.

Bu örnek, büyük görüntülerde zaman aşımıyla oluşan tanıma takılmalarını nasıl önleyeceğinizi gösterir.
```cpp
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

## Ayrıca Bakınız

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
