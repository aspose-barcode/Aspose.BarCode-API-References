---
title: "método"
linktitle: "Abort"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. La función solicita la terminación de la sesión de reconocimiento actual desde otro hilo. Abort es un método no bloqueable y devuelve el control justo después de llamarse. El método debe usarse cuando el proceso de reconocimiento es demasiado largo en C++."
type: docs
weight: 1200
url: /es/cpp/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader::Abort method


La función solicita la terminación de la sesión de reconocimiento actual desde otro hilo. Abort es un método no bloqueable y devuelve el control justo después de llamarse. El método debe usarse cuando el proceso de reconocimiento es demasiado largo.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::Abort()
```

## Observaciones


Este ejemplo muestra cómo llamar a la función Abort desde otro hilo
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

## Ver también

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
