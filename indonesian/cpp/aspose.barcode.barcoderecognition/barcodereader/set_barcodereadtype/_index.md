---
title: "metode"
linktitle: "set_BarCodeReadType"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " metode. Mengatur tipe dekode kode batang yang digunakan untuk pengenalan. Harus diatur sebelum memanggil ReadBarCodes dalam C++."
type: docs
weight: 1100
url: /id/cpp/aspose.barcode.barcoderecognition/barcodereader/set_barcodereadtype/
---
## BarCodeReader::set_BarCodeReadType method


Mengatur tipe dekode kode batang yang digunakan untuk pengenalan. Harus diatur sebelum memanggil [ReadBarCodes](../readbarcodes/).

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_BarCodeReadType(System::SharedPtr<BaseDecodeType> value)
```

## Catatan


Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.BarCodeReadType = new MultiDecodeType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString());
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.BarCodeReadType = New MultiDecodeType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString())
End Using
```

## Lihat Juga

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
