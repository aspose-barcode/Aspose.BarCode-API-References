---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext class"
linktitle: "USADriveIdCodetext"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext class. Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode PDF417 USA Driving License dalam C++."
type: docs
weight: 2900
url: /id/cpp/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class


Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode PDF417 USA Driving [License](../../aspose.barcode/license/).

```cpp
class USADriveIdCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_AAMVAVersionNumber](./get_aamvaversionnumber/)() const | Nomor Versi AAMVA 00-99 |
| [get_IssuerIdentificationNumber](./get_issueridentificationnumber/)() const | Nomor ini secara unik mengidentifikasi yurisdiksi penerbit dan dapat diperoleh dengan menghubungi Otoritas Penerbit ISO (AAMVA). IIN 6 digit lengkap harus dikodekan. |
| [get_JurisdictionSpecificSubfile](./get_jurisdictionspecificsubfile/)() const | Bidang Spesifik Yurisdiksi |
| [get_JurisdictionVersionNumber](./get_jurisdictionversionnumber/)() const | Nomor Versi Yurisdiksi 00-99 |
| [get_MandatoryElements](./get_mandatoryelements/)() const | Elemen wajib (field) dari kartu |
| [get_NumberOfEntries](./get_numberofentries/)() const | Nomor 00-99 subfile |
| [get_OptionalElements](./get_optionalelements/)() const | Elemen opsional (field) dari kartu |
| [get_SubfileDesignator](./get_subfiledesignator/)() const | Berisi informasi tentang subfile berikut, tipe, offset, dan panjang. Penting: hanya set tipe, offset dan panjang yang akan diatur secara otomatis. |
| [GetBarcodeType](./getbarcodetype/)() override | Mengembalikan tipe barcode USA DL (Pdf417) |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Membuat codetext dari data USA DL |
| [InitFromString](./initfromstring/)(System::String) override | Inisialisasi objek USA DL dari codetext |
| [SaveToXml](./savetoxml/)(System::SharedPtr\<System::IO::Stream\>) | Menyimpan ke XML |
| [set_AAMVAVersionNumber](./set_aamvaversionnumber/)(System::String) | Nomor Versi AAMVA 00-99 |
| [set_IssuerIdentificationNumber](./set_issueridentificationnumber/)(System::String) | Nomor ini secara unik mengidentifikasi yurisdiksi penerbit dan dapat diperoleh dengan menghubungi Otoritas Penerbit ISO (AAMVA). IIN 6 digit lengkap harus dikodekan. |
| [set_JurisdictionSpecificSubfile](./set_jurisdictionspecificsubfile/)(System::SharedPtr\<USADriveIdJurisdSubfile\>) | Bidang Spesifik Yurisdiksi |
| [set_JurisdictionVersionNumber](./set_jurisdictionversionnumber/)(System::String) | Nomor Versi Yurisdiksi 00-99 |
| [set_MandatoryElements](./set_mandatoryelements/)(System::SharedPtr\<USADriveIdCodetext::MandatoryFields\>) | Elemen wajib (field) dari kartu |
| [set_NumberOfEntries](./set_numberofentries/)(int32_t) | Nomor 00-99 subfile |
| [set_OptionalElements](./set_optionalelements/)(System::SharedPtr\<USADriveIdCodetext::OptionalFields\>) | Elemen opsional (field) dari kartu |
| [set_SubfileDesignator](./set_subfiledesignator/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<USADriveIdCodetext::SubfileProperties\>>>) | Berisi informasi tentang subfile berikut, tipe, offset, dan panjang. Penting: hanya set tipe, offset dan panjang yang akan diatur secara otomatis. |
| [USADriveIdCodetext](./usadriveidcodetext/)() | Konstruktor default |
## Lihat Juga

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
