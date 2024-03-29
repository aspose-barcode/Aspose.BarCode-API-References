---
title: Abort
second_title: Aspose.BarCode για Αναφορά API .NET
description: Η συνάρτηση ζητά τερματισμό της τρέχουσας περιόδου σύνδεσης αναγνώρισης από άλλο νήμα. Το Abort είναι μέθοδος με δυνατότητα απεμπλοκής και επιστρέφει τον έλεγχο αμέσως μετά την κλήση. Η μέθοδος θα πρέπει να χρησιμοποιείται όταν η διαδικασία αναγνώρισης είναι πολύ μεγάλη.
type: docs
weight: 80
url: /el/net/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader.Abort method

Η συνάρτηση ζητά τερματισμό της τρέχουσας περιόδου σύνδεσης αναγνώρισης από άλλο νήμα. Το Abort είναι μέθοδος με δυνατότητα απεμπλοκής και επιστρέφει τον έλεγχο αμέσως μετά την κλήση. Η μέθοδος θα πρέπει να χρησιμοποιείται όταν η διαδικασία αναγνώρισης είναι πολύ μεγάλη.

```csharp
public void Abort()
```

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να καλέσετε τη συνάρτηση Abort από άλλο νήμα

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

### Δείτε επίσης

* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
