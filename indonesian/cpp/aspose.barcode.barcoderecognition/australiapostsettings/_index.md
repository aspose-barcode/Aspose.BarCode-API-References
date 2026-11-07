---
title: "Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings kelas"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings kelas. Parameter decoding AustraliaPost. Berisi parameter yang memengaruhi data yang dikenali dari simbol AustraliaPost dalam C++."
type: docs
weight: 200
url: /id/cpp/aspose.barcode.barcoderecognition/australiapostsettings/
---
## AustraliaPostSettings class


Parameter dekoding AustraliaPost. Berisi parameter yang memengaruhi data yang dikenali pada simbol AustraliaPost.

```cpp
class AustraliaPostSettings : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_CustomerInformationDecoder](./get_customerinformationdecoder/)() const | Antarmuka publik untuk decoding Customer Information Field yang digunakan dalam simbol AustraliaPost. |
| [get_CustomerInformationInterpretingType](./get_customerinformationinterpretingtype/)() const | Mendapatkan Interpreting Type untuk Customer Information dari AustralianPost [BarCode.Default](../checksumvalidation/) adalah [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/). |
| [get_IgnoreEndingFillingPatternsForCTable](./get_ignoreendingfillingpatternsforctable/)() const | Bendera yang memaksa decoder AustraliaPost mengabaikan pola pengisian terakhir dalam Customer Information Field selama decoding dengan metode CTable. Metode pengkodean CTable tidak memiliki celah dalam tabel pengkodean dan urutan "333" dari pola pengisian didekode sebagai huruf "z". |
| [set_CustomerInformationDecoder](./set_customerinformationdecoder/)(System::SharedPtr\<AustraliaPostCustomerInformationDecoder\>) | Antarmuka publik untuk decoding Customer Information Field yang digunakan dalam simbol AustraliaPost. |
| [set_CustomerInformationInterpretingType](./set_customerinformationinterpretingtype/)(Aspose::BarCode::CustomerInformationInterpretingType) | Mengatur Interpreting Type untuk Customer Information dari AustralianPost [BarCode.Default](../checksumvalidation/) adalah [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/). |
| [set_IgnoreEndingFillingPatternsForCTable](./set_ignoreendingfillingpatternsforctable/)(bool) | Bendera yang memaksa decoder AustraliaPost mengabaikan pola pengisian terakhir dalam Customer Information Field selama decoding dengan metode CTable. Metode pengkodean CTable tidak memiliki celah dalam tabel pengkodean dan urutan "333" dari pola pengisian didekode sebagai huruf "z". |
## Lihat Juga

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
