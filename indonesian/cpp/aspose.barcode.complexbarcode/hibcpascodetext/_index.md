---
title: "Kelas Aspose::BarCode::ComplexBarcode::HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Kelas Aspose::BarCode::ComplexBarcode::HIBCPASCodetext. Kelas untuk mengenkode dan mendekode teks yang tertanam dalam kode HIBC PAS di C++."
type: docs
weight: 1100
url: /id/cpp/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class


Kelas untuk penyandian dan penguraian teks yang tertanam dalam kode HIBC PAS.

```cpp
class HIBCPASCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [AddRecord](./addrecord/)(HIBCPASDataType, System::String) | Menambahkan catatan baru |
| [AddRecord](./addrecord/)(System::SharedPtr\<HIBCPASRecord\>) | Menambahkan catatan baru |
| [Clear](./clear/)() | Menghapus daftar catatan |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [HIBCPASCodetext](./) yang ditentukan. |
| [get_BarcodeType](./get_barcodetype/)() const | Mendapatkan tipe barcode. Codetext HIBC PAS dapat dienkode menggunakan tipe HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS, dan HIBCQRPAS. Nilai default: HIBCCode39PAS. |
| [get_DataLocation](./get_datalocation/)() const | Mengidentifikasi lokasi data. |
| [GetBarcodeType](./getbarcodetype/)() override | Mendapatkan tipe barcode. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Menyusun codetext |
| [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk instance ini. |
| [GetRecords](./getrecords/)() | Mendapatkan daftar catatan |
| [HIBCPASCodetext](./hibcpascodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Menginisialisasi instance dari codetext yang disusun. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Mengatur tipe barcode. Codetext HIBC PAS dapat dienkode menggunakan tipe HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS, dan HIBCQRPAS. Nilai default: HIBCCode39PAS. |
| [set_DataLocation](./set_datalocation/)(HIBCPASDataLocation) | Mengidentifikasi lokasi data. |
## Catatan


Contoh ini menunjukkan cara mengenkode dan mendekode HIBC PAS menggunakan [HIBCPASCodetext](./).
```cpp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
            HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
        Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

## Lihat Juga

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
