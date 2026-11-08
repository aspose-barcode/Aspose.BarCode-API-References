---
title: "metot"
linktitle: "get_FoundBarCodes"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " metod. C++'da tanınan BarCodeResults dizisini alır."
type: docs
weight: 500
url: /tr/cpp/aspose.barcode.barcoderecognition/barcodereader/get_foundbarcodes/
---
## BarCodeReader::get_FoundBarCodes method


Tanınan [BarCodeResult](../../barcoderesult/)s dizisini alır

```cpp
System::ArrayPtr<System::SharedPtr<BarCodeResult>> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_FoundBarCodes()
```

## Açıklamalar


Tanınan [BarCodeResult](../../barcoderesult/)s dizisi

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

* Class [BarCodeResult](../../barcoderesult/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
