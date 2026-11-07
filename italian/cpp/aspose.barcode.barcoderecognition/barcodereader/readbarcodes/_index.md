---
title: "method"
linktitle: "ReadBarCodes"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Legge BarCodeResults dall'immagine in C++."
type: docs
weight: 1300
url: /it/cpp/aspose.barcode.barcoderecognition/barcodereader/readbarcodes/
---
## BarCodeReader::ReadBarCodes method


Legge [BarCodeResult](../../barcoderesult/)s dall'immagine.

```cpp
System::ArrayPtr<System::SharedPtr<BarCodeResult>> Aspose::BarCode::BarCodeRecognition::BarCodeReader::ReadBarCodes()
```


### ReturnValue

Restituisce un array di [BarCodeResult](../../barcoderesult/) riconosciuti sull'immagine. Se non viene riconosciuto nulla, viene restituito un array vuoto.
## Osservazioni


Questo esempio mostra come leggere i codici a barre con [BarCodeReader](../)
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
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

Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```


## Vedi anche

* Class [BarCodeResult](../../barcoderesult/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
