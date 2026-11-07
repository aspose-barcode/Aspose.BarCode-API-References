---
title: "methode"
linktitle: "Abort"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Functie vraagt beëindiging van de huidige herkenningssessie vanaf een andere thread. Abort is een onblokkeerbare methode en geeft de controle direct terug na het aanroepen. De methode moet worden gebruikt wanneer het herkenningsproces te lang duurt in C++."
type: docs
weight: 1200
url: /nl/cpp/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader::Abort method


Functie vraagt beëindiging van de huidige herkenningssessie vanaf een andere thread. Abort is een ononderbreekbare methode en geeft de controle terug direct na het aanroepen. De methode moet worden gebruikt wanneer het herkenningsproces te lang duurt.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::Abort()
```

## Opmerkingen


Dit voorbeeld toont hoe de Abort‑functie aan te roepen vanaf een andere thread
```cpp
[C#]
private static void ThreadRecognize(object readerObj)
{
    BarCodeReader reader = (BarCodeReader)readerObj;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeType);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}

BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128);
Thread thread1 = new Thread(ThreadRecognize);
thread1.Start(reader);
Thread.Sleep(100);
reader.Abort();
[VB.NET]
Private Shared Sub ThreadRecognize(readerObj As Object)
    Dim reader As BarCodeReader = readerObj
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Sub

Dim reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
Dim thread1 As New Thread(AddressOf ThreadRecognize)
thread1.Start(reader)
Thread.Sleep(100)
reader.Abort()
```

## Zie ook

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
