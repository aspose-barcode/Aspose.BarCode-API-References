---
title: Abort
second_title: Referencia de API de Aspose.BarCode para .NET
description: La función solicita la finalización de la sesión de reconocimiento actual de otro subproceso. Abortar es un método desbloqueable y devuelve el control justo después de llamar. El método debe usarse cuando el proceso de reconocimiento es demasiado largo.
type: docs
weight: 80
url: /es/net/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader.Abort method

La función solicita la finalización de la sesión de reconocimiento actual de otro subproceso. Abortar es un método desbloqueable y devuelve el control justo después de llamar. El método debe usarse cuando el proceso de reconocimiento es demasiado largo.

```csharp
public void Abort()
```

### Ejemplos

Este ejemplo muestra cómo llamar a la función Abortar desde otro subproceso

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

### Ver también

* class [BarCodeReader](../../barcodereader)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* asamblea [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->