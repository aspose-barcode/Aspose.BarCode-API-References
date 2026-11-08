---
title: "metot"
linktitle: "set_Timeout"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " yöntemi. Tanıma sürecinin zaman aşımını milisaniye cinsinden C++'ta ayarlar."
type: docs
weight: 400
url: /tr/cpp/aspose.barcode.barcoderecognition/barcodereader/set_timeout/
---
## BarCodeReader::set_Timeout method


Tanıma işleminin zaman aşımını milisaniye cinsinden ayarlar.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_Timeout(int32_t value)
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
