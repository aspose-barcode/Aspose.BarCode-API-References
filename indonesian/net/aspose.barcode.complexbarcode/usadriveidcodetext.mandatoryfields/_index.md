---
title: "Kelas USADriveIdCodetext.MandatoryFields"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Kelas Aspose.BarCode.ComplexBarcode.USADriveIdCodetextMandatoryFields. Elemen wajib kartu"
type: docs
weight: 820
url: /id/net/aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
## USADriveIdCodetext.MandatoryFields class

Elemen wajib (field) kartu

```csharp
public class MandatoryFields
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/.ctor)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AddressCity](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresscity) { get; set; } | DAI, bagian Kota dari alamat pemegang kartu, DL/ID, V20ANS |
| [AddressPostalCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresspostalcode) { get; set; } | DAK, bagian kode pos dari alamat pemegang kartu di AS dan Kanada. Jika bagian akhir kode pos di AS tidak diketahui, nol akan digunakan untuk mengisi bagian akhir angka hingga 9 digit, DL/ID, F11ANS |
| [AddressState](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstate) { get; set; } | DAJ, bagian Negara bagian dari alamat pemegang kartu, DL/ID, F2A |
| [AddressStreet1](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstreet1) { get; set; } | DAG, bagian Jalan dari alamat pemegang kartu, DL/ID, V35ANS |
| [CountryIdentification](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/countryidentification) { get; set; } | DCG, Negara tempat DL/ID diterbitkan. AS = USA, Kanada = CAN, DL/ID, F3A |
| [CustomerIDNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/customeridnumber) { get; set; } | DAQ, Nomor yang diberikan atau dihitung oleh otoritas penerbit, DL/ID, V25ANS |
| [DateOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/dateofbirth) { get; set; } | DBB, Tanggal dokumen diterbitkan, MMDDCCYY untuk AS, CCYYMMDD untuk Kanada, DL/ID, F8N |
| [DocumentDiscriminator](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/documentdiscriminator) { get; set; } | DCF, Nomor harus secara unik mengidentifikasi dokumen tertentu yang dikeluarkan untuk pelanggan tersebut dari dokumen lain yang mungkin telah dikeluarkan di masa lalu. Nomor ini dapat berfungsi untuk berbagai tujuan diskriminasi dokumen, nomor informasi audit, dan/atau kontrol inventaris, DL/ID, V25ANS |
| [EndorsementCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/endorsementcodes) { get; set; } | DCD, Kode endorsement spesifik yurisdiksi, DL, V5ANS |
| [ExpirationDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/expirationdate) { get; set; } | DBA, Tanggal Kedaluwarsa Dokumen, MMDDCCYY untuk AS, CCYYMMDD untuk Kanada, DL/ID, F8N |
| [EyeColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/eyecolor) { get; set; } | DAY, Warna mata pemegang kartu. (kode ANSI D-20). DL/ID, F3A |
| [FamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familyname) { get; set; } | DCS, Nama keluarga pemegang kartu, DL/ID, V40ANS |
| [FamilyNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familynametruncation) { get; set; } | DDE, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A |
| [FirstName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstname) { get; set; } | DAC, Nama depan pemegang kartu, DL/ID, V40ANS |
| [FirstNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstnametruncation) { get; set; } | DDF, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A |
| [Height](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/height) { get; set; } | DAU, Tinggi pemegang kartu. Inci (in): jumlah inci diikuti oleh " in" contoh 6'1'' = "073 in" Sentimeter (cm): jumlah sentimeter diikuti oleh " cm" contoh 181 sentimeter="181 cm" , DL/ID, F6ANS |
| [IssueDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/issuedate) { get; set; } | DBD, Tanggal dokumen dikeluarkan, MMDDCCYY untuk AS, CCYYMMDD untuk Kanada, DL/ID, F8N |
| [MiddleName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlename) { get; set; } | DAD, Nama tengah pemegang kartu. Jika ada beberapa nama tengah, mereka harus dipisahkan dengan koma ",". , DL/ID, V40ANS |
| [MiddleNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlenametruncation) { get; set; } | DDG, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A |
| [RestrictionCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/restrictioncodes) { get; set; } | DCB, Kode pembatasan spesifik yurisdiksi, DL, V12ANS |
| [Sex](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/sex) { get; set; } | DBC, Jenis kelamin pemegang kartu. 1 = pria, 2 = wanita, 9 = tidak ditentukan, DL/ID, F1N |
| [VehicleClass](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/vehicleclass) { get; set; } | DCA, Kode kelas / grup kendaraan spesifik yurisdiksi, DL, V6ANS |

### Lihat Juga

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


