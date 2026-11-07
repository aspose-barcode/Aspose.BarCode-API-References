---
title: "Methode"
linktitle: "set_Timeout"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Legt das Timeout des Erkennungsprozesses in Millisekunden in C++ fest."
type: docs
weight: 400
url: /de/cpp/aspose.barcode.barcoderecognition/barcodereader/set_timeout/
---
## BarCodeReader::set_Timeout method


Legt den Timeout des Erkennungsprozesses in Millisekunden fest.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_Timeout(int32_t value)
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
