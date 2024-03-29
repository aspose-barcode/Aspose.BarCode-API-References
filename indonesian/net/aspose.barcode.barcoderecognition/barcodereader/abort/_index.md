---
title: Abort
second_title: Aspose.BarCode untuk .NET API Referensi
description: Fungsi meminta penghentian sesi pengenalan saat ini dari utas lainnya. Batalkan adalah metode yang tidak dapat diblokir dan mengembalikan kontrol tepat setelah menelepon. Metode ini sebaiknya digunakan saat proses pengenalan terlalu lama.
type: docs
weight: 80
url: /id/net/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader.Abort method

Fungsi meminta penghentian sesi pengenalan saat ini dari utas lainnya. Batalkan adalah metode yang tidak dapat diblokir dan mengembalikan kontrol tepat setelah menelepon. Metode ini sebaiknya digunakan saat proses pengenalan terlalu lama.

```csharp
public void Abort()
```

### Contoh

Contoh ini menunjukkan cara memanggil fungsi Abort dari thread lain

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

### Lihat juga

* class [BarCodeReader](../)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* perakitan [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
