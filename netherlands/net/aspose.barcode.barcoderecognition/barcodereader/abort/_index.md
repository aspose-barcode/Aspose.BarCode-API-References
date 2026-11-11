---
title: "BarCodeReader.Abort"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "BarCodeReader methode. Functie vraagt beëindiging van de huidige herkenningssessie vanuit een andere thread. Abort is een ononderbreekbare methode en geeft de controle direct terug na aanroep. De methode moet worden gebruikt wanneer het herkenningsproces te lang duurt."
type: docs
weight: 90
url: /nl/net/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader.Abort method

Functie vraagt beëindiging van de huidige herkenningssessie vanaf een andere thread. Abort is een onblokkeerbare methode en geeft de controle terug direct na het aanroepen. De methode moet worden gebruikt wanneer het herkenningsproces te lang duurt.

```csharp
public void Abort()
```

## Voorbeelden

Dit voorbeeld toont hoe de Abort-functie vanuit een andere thread aan te roepen.

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

### Zie ook

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


