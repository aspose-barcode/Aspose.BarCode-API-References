---
title: "método"
linktitle: "get_FoundBarCodes"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Obtiene la matriz de BarCodeResults reconocidos en C++."
type: docs
weight: 500
url: /es/cpp/aspose.barcode.barcoderecognition/barcodereader/get_foundbarcodes/
---
## BarCodeReader::get_FoundBarCodes method


Obtiene la matriz de [BarCodeResult](../../barcoderesult/)s reconocidos

```cpp
System::ArrayPtr<System::SharedPtr<BarCodeResult>> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_FoundBarCodes()
```

## Observaciones


La matriz de [BarCodeResult](../../barcoderesult/)s reconocidos

Este ejemplo muestra cómo leer códigos de barras con [BarCodeReader](../)
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    reader.ReadBarCodes();
    for(int i = 0; reader.FoundCount > i; ++i)
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes[i].CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    reader.ReadBarCodes()
    For i As Integer = 0 To reader.FoundCount - 1 Step 1
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes(i).CodeText)
    Next
End Using
```

## Ver también

* Class [BarCodeResult](../../barcoderesult/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
