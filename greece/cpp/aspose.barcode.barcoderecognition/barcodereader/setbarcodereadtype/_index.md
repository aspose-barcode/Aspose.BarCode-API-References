---
title: "μέθοδος"
linktitle: "SetBarCodeReadType"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "μέθοδος. Ορίζει τον πίνακα τύπων SingleDecodeType για αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes() σε C++."
type: docs
weight: 1600
url: /el/cpp/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader::SetBarCodeReadType method


Ορίζει τον πίνακα τύπων [SingleDecodeType](../../singledecodetype/) για αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [ReadBarCodes()](../readbarcodes/).

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeReadType(const System::ArrayPtr<System::SharedPtr<SingleDecodeType>> &barcodeTypes)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| barcodeTypes | const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\& | Ο πίνακας τύπων [SingleDecodeType](../../singledecodetype/) για ανάγνωση. |
## Σχόλια



Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε τα barcodes Code39 και Code128.
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

## Δείτε επίσης

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
