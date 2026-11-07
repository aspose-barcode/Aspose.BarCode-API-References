---
title: "method"
linktitle: "get_FoundCount"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Ottiene il conteggio dei codici a barre riconosciuti in C++."
type: docs
weight: 600
url: /it/cpp/aspose.barcode.barcoderecognition/barcodereader/get_foundcount/
---
## BarCodeReader::get_FoundCount method


Ottiene il conteggio dei codici a barre riconosciuti

```cpp
int32_t Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_FoundCount()
```

## Osservazioni


Il conteggio dei codici a barre riconosciuti

Questo esempio mostra come leggere i codici a barre con [BarCodeReader](../)
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

## Vedi anche

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
