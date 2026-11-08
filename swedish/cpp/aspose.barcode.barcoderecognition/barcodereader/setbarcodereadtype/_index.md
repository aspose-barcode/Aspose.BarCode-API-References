---
title: "metod"
linktitle: "SetBarCodeReadType"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Ställer in SingleDecodeType-typarray för igenkänning. Måste anropas före ReadBarCodes() metod i C++."
type: docs
weight: 1600
url: /sv/cpp/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader::SetBarCodeReadType method


Ställer in [SingleDecodeType](../../singledecodetype/) typarray för igenkänning. Måste anropas före [ReadBarCodes()](../readbarcodes/) metod.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeReadType(const System::ArrayPtr<System::SharedPtr<SingleDecodeType>> &barcodeTypes)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| barcodeTypes | const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\& | Den [SingleDecodeType](../../singledecodetype/) typarrayen att läsa. |
## Anmärkningar



Detta exempel visar hur man upptäcker Code39- och Code128-streckkoder.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## Se även

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
