---
title: "طريقة"
linktitle: "Abort"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. تطلب الدالة إنهاء جلسة التعرف الحالية من خيط آخر. Abort هي طريقة لا يمكن إيقافها وتعيد التحكم مباشرة بعد الاستدعاء. يجب استخدام الطريقة عندما تكون عملية التعرف طويلة جدًا في C++."
type: docs
weight: 1200
url: /ar/cpp/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader::Abort method


تطلب الدالة إنهاء جلسة التعرف الحالية من خيط آخر. Abort هي طريقة لا يمكن إلغاء حظرها وتعيد التحكم فور استدعائها. يجب استخدام هذه الطريقة عندما تكون عملية التعرف طويلة جدًا.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::Abort()
```

## ملاحظات


يعرض هذا المثال كيفية استدعاء دالة Abort من خيط آخر
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

## انظر أيضًا

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
