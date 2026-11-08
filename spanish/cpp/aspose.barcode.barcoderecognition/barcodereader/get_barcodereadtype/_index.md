---
title: "método"
linktitle: "get_BarCodeReadType"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Obtiene el tipo de decodificación de código de barras utilizado para el reconocimiento. Debe establecerse antes de llamar a ReadBarCodes en C++."
type: docs
weight: 1000
url: /es/cpp/aspose.barcode.barcoderecognition/barcodereader/get_barcodereadtype/
---
## BarCodeReader::get_BarCodeReadType method


Obtiene el tipo de decodificación de código de barras utilizado para el reconocimiento. Debe establecerse antes de llamar a [ReadBarCodes](../readbarcodes/).

```cpp
System::SharedPtr<BaseDecodeType> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_BarCodeReadType()
```

## Observaciones


Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.BarCodeReadType = new MultiDecodeType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString());
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.BarCodeReadType = New MultiDecodeType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString())
End Using
```

## Ver también

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
