---
title: "method"
linktitle: "set_Timeout"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Imposta il timeout del processo di riconoscimento in millisecondi in C++."
type: docs
weight: 400
url: /it/cpp/aspose.barcode.barcoderecognition/barcodereader/set_timeout/
---
## BarCodeReader::set_Timeout method


Imposta il timeout del processo di riconoscimento in millisecondi.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_Timeout(int32_t value)
```

## Osservazioni


Il timeout.

Questo esempio mostra come evitare blocchi di riconoscimento con timeout su immagini di grandi dimensioni
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

## Vedi anche

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
