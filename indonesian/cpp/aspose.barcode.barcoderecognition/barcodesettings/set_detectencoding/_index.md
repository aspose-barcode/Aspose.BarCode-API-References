---
title: "metode"
linktitle: "set_DetectEncoding"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " metode. Bendera yang memaksa mesin mendeteksi enkoding teks kode untuk set kode Unicode. Nilai default adalah true di C++."
type: docs
weight: 800
url: /id/cpp/aspose.barcode.barcoderecognition/barcodesettings/set_detectencoding/
---
## BarcodeSettings::set_DetectEncoding method


Bendera yang memaksa mesin mendeteksi pengkodean teks kode untuk set kode Unicode. Nilai default adalah true.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarcodeSettings::set_DetectEncoding(bool value)
```

## Catatan


Contoh ini menunjukkan cara mendeteksi enkoding teks secara langsung jika DetectEncoding diaktifkan
```cpp
[C#]
using (MemoryStream ms = new MemoryStream())
{
    using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
    {
        generator.SetCodeText("Слово", Encoding.UTF8);
        generator.Save(ms, BarCodeImageFormat.Png);
    }
    //deteksi enkoding untuk set kode Unicode diaktifkan
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    //deteksi enkoding dinonaktifkan
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = false;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using ms As New MemoryStream
    Using generator As New BarcodeGenerator(EncodeTypes.QR, "Слово")
        generator.SetCodeText("Слово", System.Text.Encoding.UTF8)
        generator.Save(ms, BarCodeImageFormat.Png)
    End Using
    'detects encoding for Unicode codesets is enabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = True
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
    'detect encoding is disabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = False
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```


Bendera yang memaksa mesin mendeteksi enkoding teks kode untuk set kode Unicode
## Lihat Juga

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
