---
title: "metot"
linktitle: "get_FoundCount"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " yöntemi. Tanınan barkod sayısını C++'ta alır."
type: docs
weight: 600
url: /tr/cpp/aspose.barcode.barcoderecognition/barcodereader/get_foundcount/
---
## BarCodeReader::get_FoundCount method


Tanınan barkod sayısını alır

```cpp
int32_t Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_FoundCount()
```

## Açıklamalar


Tanımlanan barkod sayısı

Bu örnek, [BarCodeReader](../) ile barkodları nasıl okuyacağınızı gösterir.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    reader.ReadBarCodes();
    for(int i = 0; reader.FoundCount > i; ++i)
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes[i].CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    reader.ReadBarCodes()
    For i As Integer = 0 To reader.FoundCount - 1 Step 1
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes(i).CodeText)
    Next
End Using
```

## Ayrıca Bakınız

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
