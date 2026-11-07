---
title: "method"
linktitle: "set_BarCodeReadType"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Imposta il tipo di decodifica del codice a barre utilizzato per il riconoscimento. Deve essere impostato prima di chiamare ReadBarCodes in C++."
type: docs
weight: 1100
url: /it/cpp/aspose.barcode.barcoderecognition/barcodereader/set_barcodereadtype/
---
## BarCodeReader::set_BarCodeReadType method


Imposta il tipo di decodifica del codice a barre utilizzato per il riconoscimento. Deve essere impostato prima di chiamare [ReadBarCodes](../readbarcodes/).

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_BarCodeReadType(System::SharedPtr<BaseDecodeType> value)
```

## Osservazioni


Questo esempio mostra come rilevare i codici a barre Code39 e Code128.
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

## Vedi anche

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
