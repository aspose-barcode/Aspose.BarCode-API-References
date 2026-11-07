---
title: "μέθοδος"
linktitle: "get_FoundCount"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " μέθοδος. Επιστρέφει τον αριθμό των αναγνωρισμένων γραμμωτών κωδίκων σε C++."
type: docs
weight: 600
url: /el/cpp/aspose.barcode.barcoderecognition/barcodereader/get_foundcount/
---
## BarCodeReader::get_FoundCount method


Λαμβάνει τον αριθμό των αναγνωρισμένων barcode

```cpp
int32_t Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_FoundCount()
```

## Σχόλια


Ο αριθμός των αναγνωρισμένων γραμμωτών κωδίκων

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

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
