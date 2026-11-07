---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext kelas"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext kelas. Kelas untuk mengenkode dan mendekode teks kode MaxiCode untuk mode 4, 5, dan 6 dalam C++."
type: docs
weight: 2000
url: /id/cpp/aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
## MaxiCodeStandardCodetext class


Kelas untuk mengkodekan dan mendekode kode teks MaxiCode untuk mode 4, 5, dan 6.

```cpp
class MaxiCodeStandardCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [MaxiCodeStandardCodetext](./) yang ditentukan. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Mendapatkan enkoding ECI. Digunakan ketika MaxiCodeEncodeMode adalah Auto. Nilai default: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Mendapatkan mode enkoding MaxiCode. Nilai default: Auto. |
| [get_Message](./get_message/)() const | Mendapatkan pesan. |
| [get_Mode](./get_mode/)() | Mendapatkan mode MaxiCode. Teks kode standar hanya dapat digunakan dengan mode 4, 5, dan 6. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Mendapatkan tipe barcode. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Menyusun codetext |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [GetMode](./getmode/)() const override | Mendapatkan mode MaxiCode. |
| [InitFromString](./initfromstring/)(System::String) override | Menginisialisasi instance dari codetext yang disusun. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/)() |  |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Mengatur enkoding ECI. Digunakan ketika MaxiCodeEncodeMode adalah Auto. Nilai default: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Mengatur mode enkoding MaxiCode. Nilai default: Auto. |
| [set_Message](./set_message/)(System::String) | Mengatur pesan. |
| [set_Mode](./set_mode/)(Generation::MaxiCodeMode) | Mengatur mode MaxiCode. Teks kode standar hanya dapat digunakan dengan mode 4, 5, dan 6. |
## Catatan


//Mode 4 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode4; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Mode 5 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode5; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Mode 6 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode6; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); }
## Lihat Juga

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
