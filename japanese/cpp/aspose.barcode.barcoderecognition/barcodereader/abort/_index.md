---
title: "メソッド"
linktitle: "Abort"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " method. 他のスレッドから現在の認識セッションの終了を要求する関数です。Abort はブロックできないメソッドで、呼び出し直後に制御が返ります。認識処理が長すぎる場合に C++ で使用すべきメソッドです。"
type: docs
weight: 1200
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader::Abort method


この関数は、別スレッドから現在の認識セッションの終了を要求します。Abort はブロック解除できないメソッドで、呼び出し直後に制御を返します。認識プロセスが長すぎる場合にこのメソッドを使用すべきです。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::Abort()
```

## 備考


このサンプルは他のスレッドから Abort 関数を呼び出す方法を示しています。
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

## 関連項目

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
