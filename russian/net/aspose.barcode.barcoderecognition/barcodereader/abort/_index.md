---
title: Abort
second_title: Справочник по API Aspose.BarCode для .NET
description: Функция запрашивает завершение текущего сеанса распознавания из другого потока. Abort является неблокируемым методом и возвращает управление сразу после вызова. Метод следует использовать когда процесс распознавания слишком долгий.
type: docs
weight: 80
url: /ru/net/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader.Abort method

Функция запрашивает завершение текущего сеанса распознавания из другого потока. Abort является неблокируемым методом и возвращает управление сразу после вызова. Метод следует использовать, когда процесс распознавания слишком долгий.

```csharp
public void Abort()
```

### Примеры

В этом примере показано, как вызвать функцию Abort из другого потока

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

### Смотрите также

* class [BarCodeReader](../../barcodereader)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* сборка [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->