---
title: "Kelas USADriveIdCodetext.OptionalFields"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Kelas Aspose.BarCode.ComplexBarcode.USADriveIdCodetextOptionalFields. Bidang elemen opsional dari kartu"
type: docs
weight: 830
url: /id/net/aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
## USADriveIdCodetext.OptionalFields class

Elemen (bidang) opsional dari kartu

```csharp
public class OptionalFields
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/.ctor)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AddressStreet2](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/addressstreet2) { get; set; } | DAH, Baris kedua dari bagian jalan alamat pemegang kartu, DL/ID, V35ANS |
| [AliasAKAFamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakafamilyname) { get; set; } | DBN, Nama keluarga lain yang dikenal oleh pemegang kartu, DL/ID, V10ANS |
| [AliasAKAGivenName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakagivenname) { get; set; } | DBG, Nama depan lain yang dikenal oleh pemegang kartu, DL/ID, V15ANS |
| [AliasAKASuffixName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakasuffixname) { get; set; } | DBS, Akhiran lain yang dikenal oleh pemegang kartu, DL/ID, V5ANS |
| [AuditInformation](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/auditinformation) { get; set; } | DCJ, Sebuah rangkaian huruf dan/atau angka yang mengidentifikasi kapan, dimana, dan oleh siapa lisensi mengemudi/kartu ID dibuat. Jika informasi audit tidak digunakan pada kartu atau MRT, harus disertakan dalam catatan pengemudi, DL/ID, V25ANS |
| [CardRevisionDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/cardrevisiondate) { get; set; } | DDB, bidang wajib DHS yang menunjukkan tanggal perubahan versi terbaru atau modifikasi format tampilan DL/ID. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N |
| [ComplianceType](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/compliancetype) { get; set; } | DDA, bidang wajib DHS yang menunjukkan kepatuhan: “F” = patuh; dan, “N” = tidak patuh, DL/ID, F1A |
| [EndorsementCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/endorsementcodedescription) { get; set; } | DCQ, Teks yang menjelaskan kode khusus yurisdiksi yang menunjukkan hak mengemudi tambahan yang diberikan kepada pemegang kartu di luar kelas kendaraan, DL, V50ANS |
| [HairColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/haircolor) { get; set; } | DAZ, Botak, hitam, pirang, coklat, abu-abu, merah/kastanye, berpasir, putih, tidak diketahui. Jika yurisdiksi penerbit ingin menyingkat warna, gunakan kode tiga karakter yang disediakan dalam AAMVA D20, DL/ID, V12A |
| [HAZMATEndorsementExpDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/hazmatendorsementexpdate) { get; set; } | DDC, Tanggal di mana endorsement bahan berbahaya yang diberikan oleh dokumen tidak lagi berlaku. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL, F8N |
| [InventoryControlNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/inventorycontrolnumber) { get; set; } | DCK, Rangkaian huruf dan/atau angka yang ditempelkan pada bahan mentah (kertas kartu, laminasi, dll.) yang digunakan dalam pembuatan lisensi mengemudi dan kartu ID. (bidang yang direkomendasikan DHS), DL/ID, V25ANS |
| [LimitedDurationDocIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/limiteddurationdocindicator) { get; set; } | DDD, bidang wajib DHS yang menunjukkan bahwa pemegang kartu memiliki status hukum sementara = “1”, DL/ID, F1N |
| [NameSuffix](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/namesuffix) { get; set; } | DCU, Akhiran Nama (Jika yurisdiksi berpartisipasi dalam sistem yang memerlukan akhiran nama (PDPS, CDLIS, dll.), akhiran harus dikumpulkan dan ditampilkan pada DL/ID dan dalam MRT). JR (Junior), SR (Senior), 1ST atau I (Pertama), hingga 9TH atau IX (Kesembilan), DL/ID, V5ANS |
| [OrganDonorIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/organdonorindicator) { get; set; } | DDK, Bidang yang menunjukkan bahwa pemegang kartu adalah donor organ = “1”, DL/ID, F1N |
| [PlaceOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/placeofbirth) { get; set; } | DCI, Negara dan kota serta/atau provinsi, DL/ID, V33A |
| [RaceEthnicity](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/raceethnicity) { get; set; } | DCL, Kode untuk ras atau etnisitas pemegang kartu, sebagaimana didefinisikan dalam AAMVA D20, DL/ID, V3A |
| [RestrictionCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/restrictioncodedescription) { get; set; } | DCR, Teks yang menggambarkan kode pembatasan khusus yurisdiksi yang membatasi hak mengemudi, DL, V50ANS |
| [StandardEndorsementCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardendorsementcode) { get; set; } | DCN, Kode endorsement standar untuk pemegang kartu. Lihat kode dalam D20. Elemen data ini adalah placeholder untuk upaya mendatang menstandarisasi kode endorsement, DL, F5AN |
| [StandardRestrictionCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardrestrictioncode) { get; set; } | DCO, Kode pembatasan standar untuk pemegang kartu. Lihat kode dalam D20. Elemen data ini adalah placeholder untuk upaya mendatang menstandarisasi kode pembatasan, DL, F12AN |
| [StandardVehClassification](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardvehclassification) { get; set; } | DCM, Kode klasifikasi kendaraan standar untuk pemegang kartu. Elemen data ini adalah placeholder untuk upaya mendatang menstandarisasi klasifikasi kendaraan, DL, F4AN |
| [Under18Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under18until) { get; set; } | DDH, Tanggal di mana pemegang kartu berusia 18 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N |
| [Under19Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under19until) { get; set; } | DDI, Tanggal di mana pemegang kartu berusia 19 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N |
| [Under21Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under21until) { get; set; } | DDJ, Tanggal di mana pemegang kartu berusia 21 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N |
| [VehClassDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/vehclassdescription) { get; set; } | DCP, Teks yang menjelaskan kode khusus yurisdiksi untuk klasifikasi kendaraan yang diizinkan untuk dikendarai pemegang kartu, DL, V50ANS |
| [VeteranIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/veteranindicator) { get; set; } | DDL, Bidang yang menunjukkan bahwa pemegang kartu adalah veteran = “1”, DL/ID, F1N |
| [WeightKilograms](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightkilograms) { get; set; } | DAX, Berat pemegang kartu dalam kilogram, Contoh 84 kg = “084”, DL/ID, F3N |
| [WeightPounds](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightpounds) { get; set; } | DAW, Berat pemegang kartu dalam pon, Contoh 185 lb = “185”, DL/ID, F3N |
| [WeightRange](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightrange) { get; set; } | DCE, Menunjukkan rentang berat perkiraan pemegang kartu: 0 = hingga 31 kg (hingga 70 lbs), 1 = 32 – 45 kg (71 – 100 lbs), 2 = 46 - 59 kg (101 – 130 lbs), 3 = 60 - 70 kg (131 – 160 lbs), 4 = 71 - 86 kg (161 – 190 lbs), 5 = 87 - 100 kg (191 – 220 lbs), 6 = 101 - 113 kg (221 – 250 lbs), 7 = 114 - 127 kg (251 – 280 lbs), 8 = 128 – 145 kg (281 – 320 lbs), 9 = 146+ kg (321+ lbs), DL/ID, F1N |

### Lihat Juga

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


