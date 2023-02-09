---
title: Abort
second_title: Aspose.BarCode für .NET-API-Referenz
description: Die Funktion fordert die Beendigung der aktuellen Erkennungssitzung von einem anderen Thread an. Abort ist eine nicht blockierbare Methode und gibt die Kontrolle unmittelbar nach dem Aufruf zurück. Die Methode sollte angewendet werden wenn der Erkennungsprozess zu lang ist.
type: docs
weight: 80
url: /de/net/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader.Abort method

Die Funktion fordert die Beendigung der aktuellen Erkennungssitzung von einem anderen Thread an. Abort ist eine nicht blockierbare Methode und gibt die Kontrolle unmittelbar nach dem Aufruf zurück. Die Methode sollte angewendet werden, wenn der Erkennungsprozess zu lang ist.

```csharp
public void Abort()
```

### Beispiele

Dieses Beispiel zeigt, wie die Abort-Funktion von einem anderen Thread aufgerufen wird

```csharp
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

BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128);
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

Dim reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
Dim thread1 As New Thread(AddressOf ThreadRecognize)
thread1.Start(reader)
Thread.Sleep(100)
reader.Abort()
```

### Siehe auch

* class [BarCodeReader](../../barcodereader)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Montage [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->