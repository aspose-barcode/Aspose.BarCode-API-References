---
title: "metod"
linktitle: "set_Timeout"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Ställer in timeout för igenkänningsprocessen i millisekunder i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.barcode.barcoderecognition/barcodereader/set_timeout/
---
## BarCodeReader::set_Timeout method


Ställer in tidsgränsen för igenkänningsprocessen i millisekunder.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_Timeout(int32_t value)
```

## Anmärkningar


Timeouten.

Detta exempel visar hur man undviker igenkänningshängningar med timeout på stora bilder.
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

## Se även

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
