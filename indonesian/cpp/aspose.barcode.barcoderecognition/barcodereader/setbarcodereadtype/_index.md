---
title: "metode"
linktitle: "SetBarCodeReadType"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "metode. Menetapkan array tipe SingleDecodeType untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes() dalam C++."
type: docs
weight: 1600
url: /id/cpp/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader::SetBarCodeReadType method


Menetapkan array tipe [SingleDecodeType](../../singledecodetype/) untuk pengenalan. Harus dipanggil sebelum metode [ReadBarCodes()](../readbarcodes/).

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeReadType(const System::ArrayPtr<System::SharedPtr<SingleDecodeType>> &barcodeTypes)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| barcodeTypes | const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\& | Array tipe [SingleDecodeType](../../singledecodetype/) untuk dibaca. |
## Catatan



Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.
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

## Lihat Juga

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
