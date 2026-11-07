---
title: "methode"
linktitle: "get_FoundBarCodes"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Haalt de herkende BarCodeResults-array op in C++."
type: docs
weight: 500
url: /nl/cpp/aspose.barcode.barcoderecognition/barcodereader/get_foundbarcodes/
---
## BarCodeReader::get_FoundBarCodes method


Haalt de herkende [BarCodeResult](../../barcoderesult/)s-array op

```cpp
System::ArrayPtr<System::SharedPtr<BarCodeResult>> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_FoundBarCodes()
```

## Opmerkingen


De herkende [BarCodeResult](../../barcoderesult/)s-array

Dit voorbeeld toont hoe barcodes te lezen met [BarCodeReader](../)
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

## Zie ook

* Class [BarCodeResult](../../barcoderesult/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
