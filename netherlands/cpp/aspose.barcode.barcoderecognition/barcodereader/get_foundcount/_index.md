---
title: "methode"
linktitle: "get_FoundCount"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Haalt het aantal herkende barcodes op in C++."
type: docs
weight: 600
url: /nl/cpp/aspose.barcode.barcoderecognition/barcodereader/get_foundcount/
---
## BarCodeReader::get_FoundCount method


Haalt het aantal herkende barcodes op

```cpp
int32_t Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_FoundCount()
```

## Opmerkingen


Het aantal herkende barcodes

Dit voorbeeld toont hoe barcodes te lezen met [BarCodeReader](../)
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

## Zie ook

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
