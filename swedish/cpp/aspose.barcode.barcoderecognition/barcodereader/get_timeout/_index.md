---
title: "metod"
linktitle: "get_Timeout"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Hämtar timeout för igenkänningsprocessen i millisekunder i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.barcode.barcoderecognition/barcodereader/get_timeout/
---
## BarCodeReader::get_Timeout method


Hämtar tidsgränsen för igenkänningsprocessen i millisekunder.

```cpp
int32_t Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_Timeout()
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
