---
title: "metode"
linktitle: "get_FoundBarCodes"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " method. Mendapatkan array BarCodeResults yang dikenali dalam C++."
type: docs
weight: 500
url: /id/cpp/aspose.barcode.barcoderecognition/barcodereader/get_foundbarcodes/
---
## BarCodeReader::get_FoundBarCodes method


Mendapatkan array [BarCodeResult](../../barcoderesult/) yang dikenali

```cpp
System::ArrayPtr<System::SharedPtr<BarCodeResult>> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_FoundBarCodes()
```

## Catatan


Array [BarCodeResult](../../barcoderesult/) yang dikenali

Contoh ini menunjukkan cara membaca kode batang dengan [BarCodeReader](../)
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

## Lihat Juga

* Class [BarCodeResult](../../barcoderesult/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
