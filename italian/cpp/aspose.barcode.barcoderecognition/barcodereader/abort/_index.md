---
title: "method"
linktitle: "Abort"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. La funzione richiede la terminazione della sessione di riconoscimento corrente da un altro thread. Abort è un metodo non bloccabile e restituisce il controllo subito dopo la chiamata. Il metodo dovrebbe essere usato quando il processo di riconoscimento è troppo lungo in C++."
type: docs
weight: 1200
url: /it/cpp/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader::Abort method


La funzione richiede la terminazione della sessione di riconoscimento corrente da un altro thread. Abort è un metodo non bloccabile e restituisce il controllo subito dopo la chiamata. Il metodo dovrebbe essere utilizzato quando il processo di riconoscimento è troppo lungo.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::Abort()
```

## Osservazioni


Questo esempio mostra come chiamare la funzione Abort da un altro thread
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

## Vedi anche

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
