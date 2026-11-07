---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICSecondaryAndAdditionalDataCodetext class"
linktitle: "HIBCLICSecondaryAndAdditionalDataCodetext"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICSecondaryAndAdditionalDataCodetext class. Kelas untuk mengkodekan dan mendekode teks yang disematkan dalam kode HIBC LIC yang menyimpan data sekunder dalam C++."
type: docs
weight: 1000
url: /id/cpp/aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
## HIBCLICSecondaryAndAdditionalDataCodetext class


Kelas untuk penyandian dan penguraian teks yang tertanam dalam kode HIBC LIC yang menyimpan data sekunder.

```cpp
class HIBCLICSecondaryAndAdditionalDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [HIBCLICSecondaryAndAdditionalDataCodetext](./) yang ditentukan. |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | Mendapatkan tipe barcode. Codetext HIBC LIC dapat dikodekan menggunakan tipe enkode HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC, dan HIBCQRLIC. Nilai default: HIBCCode39LIC. |
| [get_Data](./get_data/)() const | Mengidentifikasi data sekunder dan tambahan. |
| [get_LinkCharacter](./get_linkcharacter/)() const | Mengidentifikasi karakter tautan. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | Mendapatkan tipe barcode. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Menyusun codetext |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Menginisialisasi instance dari codetext yang disusun. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Mengatur tipe barcode. Codetext HIBC LIC dapat dikodekan menggunakan tipe enkode HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC, dan HIBCQRLIC. Nilai default: HIBCCode39LIC. |
| [set_Data](./set_data/)(System::SharedPtr\<SecondaryAndAdditionalData\>) | Mengidentifikasi data sekunder dan tambahan. |
| [set_LinkCharacter](./set_linkcharacter/)(char16_t) | Mengidentifikasi karakter tautan. |
## Catatan


///

Contoh ini menunjukkan cara mengkodekan dan mendekode HIBC LIC menggunakan [HIBCLICSecondaryAndAdditionalDataCodetext](./).
```cpp
[C#]
HIBCLICSecondaryAndAdditionalDataCodetext complexCodetext = new HIBCLICSecondaryAndAdditionalDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.LinkCharacter = 'L';
complexCodetext.Data = new SecondaryAndAdditionalData();
complexCodetext.Data.ExpiryDate = DateTime.Now;
complexCodetext.Data.ExpiryDateFormat = HIBCLICDateFormat.MMDDYY;
complexCodetext.Data.Quantity = 30;
complexCodetext.Data.LotNumber = "LOT123";
complexCodetext.Data.SerialNumber = "SERIAL123";
complexCodetext.Data.DateOfManufacture = DateTime.Now;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICSecondaryAndAdditionalDataCodetext result = (HIBCLICSecondaryAndAdditionalDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Expiry date: " + result.Data.ExpiryDate);
        Console.WriteLine("Quantity: " + result.Data.Quantity);
        Console.WriteLine("Lot number: " + result.Data.LotNumber);
        Console.WriteLine("Serial number: " + result.Data.SerialNumber);
        Console.WriteLine("Date of manufacture: " + result.Data.DateOfManufacture);
    }
}
```

## Lihat Juga

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
