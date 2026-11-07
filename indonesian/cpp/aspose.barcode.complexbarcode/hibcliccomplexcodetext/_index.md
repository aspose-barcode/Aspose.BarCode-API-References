---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext kelas"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext kelas. Kelas dasar untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC LIC di C++."
type: docs
weight: 800
url: /id/cpp/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class


Kelas dasar untuk penyandian dan penguraian teks yang tertanam dalam kode HIBC LIC.

```cpp
class HIBCLICComplexCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_BarcodeType](./get_barcodetype/)() const | Mendapatkan tipe barcode. Codetext HIBC LIC dapat dikodekan menggunakan tipe enkode HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC, dan HIBCQRLIC. Nilai default: HIBCCode39LIC. |
| [GetBarcodeType](./getbarcodetype/)() override | Mendapatkan tipe barcode. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | Menyusun codetext |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/)() |  |
| virtual [InitFromString](./initfromstring/)(System::String) | Menginisialisasi instance dari codetext yang disusun. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Mengatur tipe barcode. Codetext HIBC LIC dapat dikodekan menggunakan tipe enkode HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC, dan HIBCQRLIC. Nilai default: HIBCCode39LIC. |
## Catatan


Contoh ini menunjukkan cara mendekode kode teks HIBC LIC mentah menjadi instance [HIBCLICComplexCodetext](./).
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.HIBCAztecLIC))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.TryDecodeHIBCLIC(result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## Lihat Juga

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
