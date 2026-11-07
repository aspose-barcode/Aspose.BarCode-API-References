---
title: "μέθοδος"
linktitle: "get_FoundBarCodes"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " μέθοδος. Λαμβάνει τον πίνακα των αναγνωρισμένων BarCodeResults σε C++."
type: docs
weight: 500
url: /el/cpp/aspose.barcode.barcoderecognition/barcodereader/get_foundbarcodes/
---
## BarCodeReader::get_FoundBarCodes method


Λαμβάνει τον πίνακα των αναγνωρισμένων [BarCodeResult](../../barcoderesult/)s

```cpp
System::ArrayPtr<System::SharedPtr<BarCodeResult>> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_FoundBarCodes()
```

## Σχόλια


Ο πίνακας των αναγνωρισμένων [BarCodeResult](../../barcoderesult/)s

Αυτό το παράδειγμα δείχνει πώς να διαβάσετε γραμμωτούς κώδικες με το [BarCodeReader](../)
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

## Δείτε επίσης

* Class [BarCodeResult](../../barcoderesult/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
