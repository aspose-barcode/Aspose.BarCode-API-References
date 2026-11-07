---
title: "μέθοδος"
linktitle: "Abort"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " method. Η λειτουργία ζητά τερματισμό της τρέχουσας συνεδρίας αναγνώρισης από άλλο νήμα. Το Abort είναι μέθοδος που δεν μπορεί να μπλοκαριστεί και επιστρέφει τον έλεγχο αμέσως μετά την κλήση. Η μέθοδος πρέπει να χρησιμοποιείται όταν η διαδικασία αναγνώρισης διαρκεί πολύ σε C++."
type: docs
weight: 1200
url: /el/cpp/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader::Abort method


Η συνάρτηση ζητά τη λήξη της τρέχουσας συνεδρίας αναγνώρισης από άλλο νήμα. Η Abort είναι μέθοδος που δεν μπορεί να αποκλειστεί και επιστρέφει τον έλεγχο αμέσως μετά την κλήση. Η μέθοδος πρέπει να χρησιμοποιείται όταν η διαδικασία αναγνώρισης διαρκεί πολύ.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::Abort()
```

## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να καλέσετε τη λειτουργία Abort από άλλο νήμα
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

## Δείτε επίσης

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
