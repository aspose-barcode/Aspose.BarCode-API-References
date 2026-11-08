---
title: "metot"
linktitle: "Abort"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " yöntem. Fonksiyon, başka bir iş parçacığından mevcut tanıma oturumunun sonlandırılmasını talep eder. Abort, engellenemeyen bir yöntemdir ve çağrıldıktan hemen sonra kontrolü geri verir. Yöntem, tanıma süreci C++ içinde çok uzun olduğunda kullanılmalıdır."
type: docs
weight: 1200
url: /tr/cpp/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader::Abort method


Fonksiyon, mevcut tanıma oturumunun diğer bir iş parçacığından sonlandırılmasını talep eder. Abort, engellenemeyen bir yöntemdir ve çağrıldıktan hemen sonra kontrolü geri verir. Tanıma süreci çok uzun olduğunda bu yöntem kullanılmalıdır.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::Abort()
```

## Açıklamalar


Bu örnek, Abort işlevinin başka bir iş parçacığından nasıl çağrılacağını gösterir.
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

## Ayrıca Bakınız

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
