---
title: "methode"
linktitle: "SetBarCodeReadType"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Stelt een SingleDecodeType-type-array in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes() methode in C++."
type: docs
weight: 1600
url: /nl/cpp/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader::SetBarCodeReadType method


Stelt de [SingleDecodeType](../../singledecodetype/) type-array in voor herkenning. Moet worden aangeroepen vóór de [ReadBarCodes()](../readbarcodes/) methode.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeReadType(const System::ArrayPtr<System::SharedPtr<SingleDecodeType>> &barcodeTypes)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| barcodeTypes | const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\& | De [SingleDecodeType](../../singledecodetype/) type-array om te lezen. |
## Opmerkingen



Dit voorbeeld laat zien hoe Code39- en Code128-barcodes te detecteren.
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

## Zie ook

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
