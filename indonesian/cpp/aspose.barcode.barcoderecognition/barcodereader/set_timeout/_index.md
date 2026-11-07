---
title: "metode"
linktitle: "set_Timeout"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "metode. Mengatur batas waktu proses pengenalan dalam milidetik di C++."
type: docs
weight: 400
url: /id/cpp/aspose.barcode.barcoderecognition/barcodereader/set_timeout/
---
## BarCodeReader::set_Timeout method


Mengatur batas waktu proses pengenalan dalam milidetik.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_Timeout(int32_t value)
```

## Catatan


Batas waktu.

Contoh ini menunjukkan cara menghindari kegagalan pengenalan dengan timeout pada gambar besar.
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

## Lihat Juga

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
