---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext kelas"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext kelas. Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC LIC yang menyimpan data utama dalam C++."
type: docs
weight: 900
url: /id/cpp/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class


Kelas untuk penyandian dan penguraian teks yang tertanam dalam kode HIBC LIC yang menyimpan data utama.

```cpp
class HIBCLICPrimaryDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [HIBCLICPrimaryDataCodetext](./) yang ditentukan. |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | Mendapatkan tipe barcode. Codetext HIBC LIC dapat dikodekan menggunakan tipe enkode HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC, dan HIBCQRLIC. Nilai default: HIBCCode39LIC. |
| [get_Data](./get_data/)() const | Mengidentifikasi data utama. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | Mendapatkan tipe barcode. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Menyusun codetext |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Menginisialisasi instance dari codetext yang disusun. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Mengatur tipe barcode. Codetext HIBC LIC dapat dikodekan menggunakan tipe enkode HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC, dan HIBCQRLIC. Nilai default: HIBCCode39LIC. |
| [set_Data](./set_data/)(System::SharedPtr\<PrimaryData\>) | Mengidentifikasi data utama. |
## Catatan


Contoh ini menunjukkan cara mengkodekan dan mendekode HIBC LIC menggunakan [HIBCLICPrimaryDataCodetext](./).
```cpp
[C#]
HIBCLICPrimaryDataCodetext complexCodetext  = new HIBCLICPrimaryDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.Data = new PrimaryData();
complexCodetext.Data.ProductOrCatalogNumber = "12345";
complexCodetext.Data.LabelerIdentificationCode = "A999";
complexCodetext.Data.UnitOfMeasureID = 1;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICPrimaryDataCodetext result = (HIBCLICPrimaryDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.Data.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.Data.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.Data.UnitOfMeasureID);
    }
}
```

## Lihat Juga

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
