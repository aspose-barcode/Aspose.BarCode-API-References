---
title: "methode"
linktitle: "set_Timeout"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Stelt de time‑out van het herkenningsproces in milliseconden in C++."
type: docs
weight: 400
url: /nl/cpp/aspose.barcode.barcoderecognition/barcodereader/set_timeout/
---
## BarCodeReader::set_Timeout method


Stelt de time-out van het herkenningsproces in milliseconden in.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_Timeout(int32_t value)
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
