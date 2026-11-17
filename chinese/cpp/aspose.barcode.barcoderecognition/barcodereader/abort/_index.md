---
title: "method"
linktitle: "Abort"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。该函数请求从其他线程终止当前识别会话。Abort 是不可阻塞的方法，调用后立即返回控制。该方法应在 C++ 中识别过程过长时使用。"
type: docs
weight: 1200
url: /zh/cpp/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader::Abort method


该函数请求从其他线程终止当前的识别会话。Abort 是不可阻塞的方法，调用后立即返回控制权。应在识别过程过长时使用此方法。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::Abort()
```

## 备注


此示例展示了如何从其他线程调用 Abort 函数
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

## 另见

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
