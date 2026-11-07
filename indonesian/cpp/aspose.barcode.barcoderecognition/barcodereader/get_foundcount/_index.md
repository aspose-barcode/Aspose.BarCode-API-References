---
title: "metode"
linktitle: "get_FoundCount"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "metode. Mendapatkan jumlah kode batang yang dikenali di C++."
type: docs
weight: 600
url: /id/cpp/aspose.barcode.barcoderecognition/barcodereader/get_foundcount/
---
## BarCodeReader::get_FoundCount method


Mendapatkan jumlah barcode yang dikenali

```cpp
int32_t Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_FoundCount()
```

## Catatan


Jumlah kode batang yang dikenali

Contoh ini menunjukkan cara membaca kode batang dengan [BarCodeReader](../)
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

## Lihat Juga

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
