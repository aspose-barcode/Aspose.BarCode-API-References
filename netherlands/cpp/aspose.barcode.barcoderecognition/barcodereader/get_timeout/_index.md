---
title: "methode"
linktitle: "get_Timeout"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Haalt de time-out van het herkenningsproces op in milliseconden in C++."
type: docs
weight: 300
url: /nl/cpp/aspose.barcode.barcoderecognition/barcodereader/get_timeout/
---
## BarCodeReader::get_Timeout method


Haalt de time-out van het herkenningsproces op in milliseconden.

```cpp
int32_t Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_Timeout()
```

## Opmerkingen


De time‑out.

Dit voorbeeld toont hoe recogntion hungs te vermijden met timeount op grote afbeeldingen
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

## Zie ook

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
