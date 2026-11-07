---
title: "Methode"
linktitle: "get_Timeout"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. Ermittelt den Timeout des Erkennungsprozesses in Millisekunden in C++."
type: docs
weight: 300
url: /de/cpp/aspose.barcode.barcoderecognition/barcodereader/get_timeout/
---
## BarCodeReader::get_Timeout method


Ermittelt den Timeout des Erkennungsprozesses in Millisekunden.

```cpp
int32_t Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_Timeout()
```

## Hinweise


Das Timeout.

Dieses Beispiel zeigt, wie man Erkennungsblockaden mit einem Timeout bei großen Bildern vermeidet
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

## Siehe auch

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
