---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICCombinedCodetext kelas"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICCombinedCodetext class. Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC LIC yang menyimpan data utama dan sekunder dalam C++."
type: docs
weight: 700
url: /id/cpp/aspose.barcode.complexbarcode/hibcliccombinedcodetext/
---
## HIBCLICCombinedCodetext class


Kelas untuk penyandian dan penguraian teks yang tertanam dalam kode HIBC LIC yang menyimpan data utama dan sekunder.

```cpp
class HIBCLICCombinedCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [HIBCLICCombinedCodetext](./) yang ditentukan. |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | Mendapatkan tipe barcode. Codetext HIBC LIC dapat dikodekan menggunakan tipe enkode HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC, dan HIBCQRLIC. Nilai default: HIBCCode39LIC. |
| [get_PrimaryData](./get_primarydata/)() const | Mengidentifikasi data utama. |
| [get_SecondaryAndAdditionalData](./get_secondaryandadditionaldata/)() const | Mengidentifikasi data sekunder dan data tambahan suplemental. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | Mendapatkan tipe barcode. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Menyusun codetext |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Menginisialisasi instance dari codetext yang disusun. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Mengatur tipe barcode. Codetext HIBC LIC dapat dikodekan menggunakan tipe enkode HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC, dan HIBCQRLIC. Nilai default: HIBCCode39LIC. |
| [set_PrimaryData](./set_primarydata/)(System::SharedPtr\<Aspose::BarCode::ComplexBarcode::PrimaryData\>) | Mengidentifikasi data utama. |
| [set_SecondaryAndAdditionalData](./set_secondaryandadditionaldata/)(System::SharedPtr\<Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData\>) | Mengidentifikasi data sekunder dan data tambahan suplemental. |
## Catatan


Contoh ini menunjukkan cara mengkodekan dan mendekode HIBC LIC menggunakan [HIBCLICCombinedCodetext](./).
```cpp
[C#]
HIBCLICCombinedCodetext combinedCodetext = new HIBCLICCombinedCodetext();
combinedCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
combinedCodetext.PrimaryData = new PrimaryData();
combinedCodetext.PrimaryData.ProductOrCatalogNumber = "12345";
combinedCodetext.PrimaryData.LabelerIdentificationCode = "A999";
combinedCodetext.PrimaryData.UnitOfMeasureID = 1;
combinedCodetext.SecondaryAndAdditionalData = new SecondaryAndAdditionalData();
combinedCodetext.SecondaryAndAdditionalData.ExpiryDate = DateTime.Now;
combinedCodetext.SecondaryAndAdditionalData.ExpiryDateFormat = HIBCLICDateFormat.MMDDYY;
combinedCodetext.SecondaryAndAdditionalData.Quantity = 30;
combinedCodetext.SecondaryAndAdditionalData.LotNumber = "LOT123";
combinedCodetext.SecondaryAndAdditionalData.SerialNumber = "SERIAL123";
combinedCodetext.SecondaryAndAdditionalData.DateOfManufacture = DateTime.Now;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICCombinedCodetext result = (HIBCLICCombinedCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.PrimaryData.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.PrimaryData.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.PrimaryData.UnitOfMeasureID);
        Console.WriteLine("Expiry date: " + result.SecondaryAndAdditionalData.ExpiryDate);
        Console.WriteLine("Quantity: " + result.SecondaryAndAdditionalData.Quantity);
        Console.WriteLine("Lot number: " + result.SecondaryAndAdditionalData.LotNumber);
        Console.WriteLine("Serial number: " + result.SecondaryAndAdditionalData.SerialNumber);
        Console.WriteLine("Date of manufacture: " + result.SecondaryAndAdditionalData.DateOfManufacture);
    }
}
```

## Lihat Juga

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
