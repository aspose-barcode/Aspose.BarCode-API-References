---
title: "metode"
linktitle: "GetCodeText"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " method. Mendapatkan teks kode dengan enkoding dalam C++."
type: docs
weight: 1000
url: /id/cpp/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult::GetCodeText method


Mendapatkan teks kode dengan enkoding.

```cpp
System::String Aspose::BarCode::BarCodeRecognition::BarCodeResult::GetCodeText(System::SharedPtr<System::Text::Encoding> encoding)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| enkoding | System::SharedPtr\<System::Text::Encoding\> | Enkoding untuk teks kode. |

### ReturnValue

String yang berisi teks kode yang dikenali.
## Catatan



Contoh ini menunjukkan cara menggunakan **GetCodeText**:


```cpp
[C#]
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## Lihat Juga

* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
