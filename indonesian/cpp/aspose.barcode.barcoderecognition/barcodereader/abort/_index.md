---
title: "metode"
linktitle: "Abort"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " metode. Fungsi meminta penghentian sesi pengenalan saat ini dari thread lain. Abort adalah metode yang tidak dapat diblokir dan mengembalikan kontrol segera setelah dipanggil. Metode ini harus digunakan ketika proses pengenalan terlalu lama dalam C++."
type: docs
weight: 1200
url: /id/cpp/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader::Abort method


Fungsi meminta penghentian sesi pengenalan saat ini dari thread lain. Abort adalah metode yang tidak dapat diblokir dan mengembalikan kontrol segera setelah dipanggil. Metode ini harus digunakan ketika proses pengenalan terlalu lama.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::Abort()
```

## Catatan


Contoh ini menunjukkan cara memanggil fungsi Abort dari thread lain
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

## Lihat Juga

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
