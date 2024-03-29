---
title: Abort
second_title: Aspose.BarCode for .NET API Referansı
description: İşlev diğer iş parçacığından geçerli tanıma oturumunun sonlandırılmasını istiyor. Abort engellenemez bir yöntemdir ve çağrıdan hemen sonra kontrolü döndürür. Tanıma işlemi çok uzun olduğunda yöntem kullanılmalıdır.
type: docs
weight: 80
url: /tr/net/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader.Abort method

İşlev, diğer iş parçacığından geçerli tanıma oturumunun sonlandırılmasını istiyor. Abort, engellenemez bir yöntemdir ve çağrıdan hemen sonra kontrolü döndürür. Tanıma işlemi çok uzun olduğunda yöntem kullanılmalıdır.

```csharp
public void Abort()
```

### Örnekler

Bu örnek, diğer thread öğesinden Durdurma işlevinin nasıl çağrılacağını gösterir.

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

### Ayrıca bakınız

* class [BarCodeReader](../../barcodereader)
* ad alanı [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* toplantı [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
