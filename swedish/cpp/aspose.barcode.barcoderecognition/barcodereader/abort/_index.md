---
title: "metod"
linktitle: "Abort"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Funktionen begär avslutning av den aktuella igenkänningssessionen från en annan tråd. Abort är en oblockerbar metod och återgår kontrollen omedelbart efter anropet. Metoden bör användas när igenkänningsprocessen är för lång i C++."
type: docs
weight: 1200
url: /sv/cpp/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader::Abort method


Funktionen begär avslutning av den aktuella igenkänningssessionen från en annan tråd. Abort är en odelbar metod och återgår kontrollen omedelbart efter anropet. Metoden bör användas när igenkänningsprocessen är för lång.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::Abort()
```

## Anmärkningar


Detta exempel visar hur man anropar Abort‑funktionen från en annan tråd
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

## Se även

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
