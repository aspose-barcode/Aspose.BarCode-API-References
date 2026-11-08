---
title: "método"
linktitle: "set_Timeout"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Establece el tiempo de espera del proceso de reconocimiento en milisegundos en C++."
type: docs
weight: 400
url: /es/cpp/aspose.barcode.barcoderecognition/barcodereader/set_timeout/
---
## BarCodeReader::set_Timeout method


Establece el tiempo de espera del proceso de reconocimiento en milisegundos.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_Timeout(int32_t value)
```

## Observaciones


El tiempo de espera.

Este ejemplo muestra cómo evitar bloqueos de reconocimiento con tiempo de espera en imágenes grandes
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
{
    reader.Timeout = 5000;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png")
    reader.Timeout = 5000
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## Ver también

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
