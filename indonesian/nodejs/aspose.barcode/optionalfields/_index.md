---
title: "OptionalFields"
linktitle: "OptionalFields"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Elemen opsional (field) dari kartu."
type: docs
weight: 730
url: /id/nodejs/aspose.barcode/optionalfields/
---

## OptionalFields class

Elemen opsional (field) dari kartu.

```js
new OptionalFields()
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getAliasAKAFamilyName()](#getaliasakafamilyname) | DBN, Nama keluarga lain yang dikenal oleh pemegang kartu, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getaliasakagivenname) | DBG, Nama depan lain yang dikenal oleh pemegang kartu, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getaliasakasuffixname) | DBS, Akhiran lain yang dikenal oleh pemegang kartu, DL/ID, V5ANS |
| [getAuditInformation()](#getauditinformation) | DCJ, Sebuah string huruf dan/atau angka yang mengidentifikasi kapan, di mana, dan oleh siapa kartu SIM/ID dibuat. Jika a |
| [getCardRevisionDate()](#getcardrevisiondate) | DDB, field yang diperlukan oleh DHS yang menunjukkan tanggal perubahan versi terbaru atau modifikasi pada format yang terlihat dari t |
| [getComplianceType()](#getcompliancetype) | DDA, field yang diperlukan oleh DHS yang menunjukkan kepatuhan: “F” = patuh; dan, “N” = tidak patuh, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getendorsementcodedescription) | DCQ, Teks yang menjelaskan kode khusus yurisdiksi yang menunjukkan hak mengemudi tambahan yang diberikan kepada ca |
| [getHairColor()](#gethaircolor) | DAZ, Botak, hitam, pirang, coklat, abu-abu, merah/kastanye, berpasir, putih, tidak diketahui. Jika yurisdiksi penerbit ingin mempersingkat |
| [getHAZMATEndorsementExpDate()](#gethazmatendorsementexpdate) | DDC, Tanggal di mana endorsement bahan berbahaya yang diberikan oleh dokumen tidak lagi berlaku. (MMDDCCYY untuk AS, CC |
| [getInventoryControlNumber()](#getinventorycontrolnumber) | DCK, Sekumpulan huruf dan/atau angka yang ditempelkan pada bahan mentah (kertas karton, laminasi, dll.) yang digunakan dalam produksi |
| [getLimitedDurationDocIndicator()](#getlimiteddurationdocindicator) | DDD, field yang diperlukan oleh DHS yang menunjukkan bahwa pemegang kartu memiliki status hukum sementara = “1”, DL/ID, F1N |
| [getNameSuffix()](#getnamesuffix) | DCU, Akhiran Nama (Jika yurisdiksi berpartisipasi dalam sistem yang memerlukan akhiran nama (PDPS, CDLIS, dll.), akhiran harus |
| [getOrganDonorIndicator()](#getorgandonorindicator) | DDK, Field yang menunjukkan bahwa pemegang kartu adalah donor organ = “1”, DL/ID, F1N |
| [getPlaceOfBirth()](#getplaceofbirth) | DCI, Negara dan kota serta/atau negara bagian/provinsi, DL/ID, V33A |
| [getRaceEthnicity()](#getraceethnicity) | DCL, Kode untuk ras atau etnisitas pemegang kartu, sebagaimana didefinisikan dalam AAMVA D20, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getrestrictioncodedescription) | DCR, Teks yang menjelaskan kode pembatasan khusus yurisdiksi yang membatasi hak mengemudi, DL, V50ANS |
| [getStandardEndorsementCode()](#getstandardendorsementcode) | DCN, Kode endorsement standar untuk pemegang kartu. Lihat kode dalam D20. Elemen data ini adalah placeholder untuk upaya di masa depan |
| [getStandardRestrictionCode()](#getstandardrestrictioncode) | DCO, Kode pembatasan standar untuk pemegang kartu. Lihat kode dalam D20. Elemen data ini adalah placeholder untuk upaya di masa depan |
| [getStandardVehClassification()](#getstandardvehclassification) | DCM, Kode klasifikasi kendaraan standar untuk pemegang kartu. Elemen data ini adalah placeholder untuk upaya di masa depan untuk |
| [getUnder18Until()](#getunder18until) | DDH, Tanggal ketika pemegang kartu berusia 18 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N |
| [getUnder21Until()](#getunder21until) | DDJ, Tanggal ketika pemegang kartu berusia 21 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N |
| [getVehClassDescription()](#getvehclassdescription) | DCP, Teks yang menjelaskan kode khusus yurisdiksi untuk klasifikasi kendaraan yang diizinkan untuk dikendarai oleh pemegang kartu |
| [getVeteranIndicator()](#getveteranindicator) | DDL, Field yang menunjukkan bahwa pemegang kartu adalah veteran = “1”, DL/ID, F1N |
| [getWeightKilograms()](#getweightkilograms) | DAX, Berat pemegang kartu dalam kilogram, Contoh 84 kg = “084”, DL/ID, F3N |
| [getWeightPounds()](#getweightpounds) | DAW, Berat pemegang kartu dalam pon, Contoh 185 lb = “185”, DL/ID, F3N |
| [getWeightRange()](#getweightrange) | DCE, Menunjukkan perkiraan rentang berat pemegang kartu: 0 = hingga 31 kg (hingga 70 lbs), 1 = 32 – 45 kg (71 – 100 lb |
| [setAddressStreet2()](#setaddressstreet2) | DAH, Baris kedua dari bagian jalan pada alamat pemegang kartu, DL/ID, V35ANS |
| [setAliasAKAFamilyName()](#setaliasakafamilyname) | DBN, Nama keluarga lain yang dikenal oleh pemegang kartu, DL/ID, V10ANS |
| [setAliasAKAGivenName()](#setaliasakagivenname) | DBG, Nama depan lain yang dikenal oleh pemegang kartu, DL/ID, V15ANS |
| [setAliasAKASuffixName()](#setaliasakasuffixname) | DBS, Akhiran lain yang dikenal oleh pemegang kartu, DL/ID, V5ANS |
| [setAuditInformation()](#setauditinformation) | DCJ, Sebuah string huruf dan/atau angka yang mengidentifikasi kapan, di mana, dan oleh siapa kartu SIM/ID dibuat. Jika a |
| [setCardRevisionDate()](#setcardrevisiondate) | DDB, field yang diperlukan oleh DHS yang menunjukkan tanggal perubahan versi terbaru atau modifikasi pada format yang terlihat dari t |
| [setComplianceType()](#setcompliancetype) | DDA, field yang diperlukan oleh DHS yang menunjukkan kepatuhan: “F” = patuh; dan, “N” = tidak patuh, DL/ID, F1A |
| [setEndorsementCodeDescription()](#setendorsementcodedescription) | DCQ, Teks yang menjelaskan kode khusus yurisdiksi yang menunjukkan hak mengemudi tambahan yang diberikan kepada ca |
| [setHairColor()](#sethaircolor) | DAZ, Botak, hitam, pirang, coklat, abu-abu, merah/kastanye, berpasir, putih, tidak diketahui. Jika yurisdiksi penerbit ingin mempersingkat |
| [setInventoryControlNumber()](#setinventorycontrolnumber) | DCK, Sekumpulan huruf dan/atau angka yang ditempelkan pada bahan mentah (kertas karton, laminasi, dll.) yang digunakan dalam produksi |
| [setLimitedDurationDocIndicator()](#setlimiteddurationdocindicator) | DDD, field yang diperlukan oleh DHS yang menunjukkan bahwa pemegang kartu memiliki status hukum sementara = “1”, DL/ID, F1N |
| [setNameSuffix()](#setnamesuffix) | DCU, Akhiran Nama (Jika yurisdiksi berpartisipasi dalam sistem yang memerlukan akhiran nama (PDPS, CDLIS, dll.), akhiran harus |
| [setOrganDonorIndicator()](#setorgandonorindicator) | DDK, Field yang menunjukkan bahwa pemegang kartu adalah donor organ = “1”, DL/ID, F1N |
| [setPlaceOfBirth()](#setplaceofbirth) | DCI, Negara dan kota serta/atau negara bagian/provinsi, DL/ID, V33A |
| [setRaceEthnicity()](#setraceethnicity) | DCL, Kode untuk ras atau etnisitas pemegang kartu, sebagaimana didefinisikan dalam AAMVA D20, DL/ID, V3A |
| [setRestrictionCodeDescription()](#setrestrictioncodedescription) | DCR, Teks yang menjelaskan kode pembatasan khusus yurisdiksi yang membatasi hak mengemudi, DL, V50ANS |
| [setStandardEndorsementCode()](#setstandardendorsementcode) | DCN, Kode endorsement standar untuk pemegang kartu. Lihat kode dalam D20. Elemen data ini adalah placeholder untuk upaya di masa depan |
| [setStandardRestrictionCode()](#setstandardrestrictioncode) | DCO, Kode pembatasan standar untuk pemegang kartu. Lihat kode dalam D20. Elemen data ini adalah placeholder untuk upaya di masa depan |
| [setStandardVehClassification()](#setstandardvehclassification) | DCM, Kode klasifikasi kendaraan standar untuk pemegang kartu. Elemen data ini adalah placeholder untuk upaya di masa depan untuk |
| [setUnder18Until()](#setunder18until) | DDI, Tanggal ketika pemegang kartu berusia 19 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N |
| [setUnder19Until()](#setunder19until) | DDI, Tanggal ketika pemegang kartu berusia 19 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N |
| [setUnder21Until()](#setunder21until) | DDJ, Tanggal ketika pemegang kartu berusia 21 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N |
| [setVehClassDescription()](#setvehclassdescription) | DCP, Teks yang menjelaskan kode khusus yurisdiksi untuk klasifikasi kendaraan yang diizinkan untuk dikendarai oleh pemegang kartu |
| [setVeteranIndicator()](#setveteranindicator) | DDL, Field yang menunjukkan bahwa pemegang kartu adalah veteran = “1”, DL/ID, F1N |
| [setWeightKilograms()](#setweightkilograms) | DAX, Berat pemegang kartu dalam kilogram, Contoh 84 kg = “084”, DL/ID, F3N |
| [setWeightPounds()](#setweightpounds) | DAW, Berat pemegang kartu dalam pon, Contoh 185 lb = “185”, DL/ID, F3N |
| [setWeightRange()](#setweightrange) | DCE, Menunjukkan perkiraan rentang berat pemegang kartu: 0 = hingga 31 kg (hingga 70 lbs), 1 = 32 – 45 kg (71 – 100 lb |

### getAliasAKAFamilyName() {#getaliasakafamilyname}

DBN, Nama keluarga lain yang dikenal oleh pemegang kartu, DL/ID, V10ANS

### getAliasAKAGivenName() {#getaliasakagivenname}

DBG, Nama depan lain yang dikenal oleh pemegang kartu, DL/ID, V15ANS

### getAliasAKASuffixName() {#getaliasakasuffixname}

DBS, Akhiran lain yang dikenal oleh pemegang kartu, DL/ID, V5ANS

### getAuditInformation() {#getauditinformation}

DCJ, Sekumpulan huruf dan/atau angka yang mengidentifikasi kapan, di mana, dan oleh siapa kartu SIM/ID dibuat. Jika informasi audit tidak digunakan pada kartu atau MRT, harus dimasukkan ke dalam catatan pengemudi, DL/ID, V25ANS

### getCardRevisionDate() {#getcardrevisiondate}

DDB, bidang wajib DHS yang menunjukkan tanggal perubahan versi terbaru atau modifikasi pada format tampak DL/ID. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N

### getComplianceType() {#getcompliancetype}

DDA, field yang diperlukan oleh DHS yang menunjukkan kepatuhan: “F” = patuh; dan, “N” = tidak patuh, DL/ID, F1A

### getEndorsementCodeDescription() {#getendorsementcodedescription}

DCQ, Teks yang menjelaskan kode khusus yurisdiksi yang menunjukkan hak mengemudi tambahan yang diberikan kepada pemegang kartu di luar kelas kendaraan, DL, V50ANS

### getHairColor() {#gethaircolor}

DAZ, Botak, hitam, pirang, coklat, abu-abu, merah/kastanye, berpasir, putih, tidak diketahui. Jika yurisdiksi penerbit ingin menyingkat warna, kode tiga karakter yang disediakan dalam AAMVA D20 harus digunakan, DL/ID, V12A

### getHAZMATEndorsementExpDate() {#gethazmatendorsementexpdate}

DDC, Tanggal di mana endorsement bahan berbahaya yang diberikan oleh dokumen tidak lagi berlaku. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL, F8N

### getInventoryControlNumber() {#getinventorycontrolnumber}

DCK, Rangkaian huruf dan/atau angka yang ditempelkan pada bahan mentah (kertas kartu, laminasi, dll.) yang digunakan dalam pembuatan lisensi pengemudi dan kartu ID. (bidang yang direkomendasikan DHS), DL/ID, V25ANS

### getLimitedDurationDocIndicator() {#getlimiteddurationdocindicator}

DDD, field yang diperlukan oleh DHS yang menunjukkan bahwa pemegang kartu memiliki status hukum sementara = “1”, DL/ID, F1N

### getNameSuffix() {#getnamesuffix}

DCU, Akhiran Nama (Jika yurisdiksi berpartisipasi dalam sistem yang memerlukan akhiran nama (PDPS, CDLIS, dll.), akhiran harus dikumpulkan dan ditampilkan pada DL/ID dan di MRT). JR (Junior), SR (Senior), 1ST atau I (Pertama), hingga 9TH atau IX (Kesembilan), DL/ID, V5ANS

### getOrganDonorIndicator() {#getorgandonorindicator}

DDK, Field yang menunjukkan bahwa pemegang kartu adalah donor organ = “1”, DL/ID, F1N

### getPlaceOfBirth() {#getplaceofbirth}

DCI, Negara dan kota serta/atau negara bagian/provinsi, DL/ID, V33A

### getRaceEthnicity() {#getraceethnicity}

DCL, Kode untuk ras atau etnisitas pemegang kartu, sebagaimana didefinisikan dalam AAMVA D20, DL/ID, V3A

### getRestrictionCodeDescription() {#getrestrictioncodedescription}

DCR, Teks yang menjelaskan kode pembatasan khusus yurisdiksi yang membatasi hak mengemudi, DL, V50ANS

### getStandardEndorsementCode() {#getstandardendorsementcode}

DCN, Kode endorsement standar untuk pemegang kartu. Lihat kode dalam D20. Elemen data ini merupakan placeholder untuk upaya di masa mendatang dalam menstandarisasi kode endorsement, DL, F5AN

### getStandardRestrictionCode() {#getstandardrestrictioncode}

DCO, Kode pembatasan standar untuk pemegang kartu. Lihat kode dalam D20. Elemen data ini merupakan placeholder untuk upaya di masa mendatang dalam menstandarisasi kode pembatasan, DL, F12AN

### getStandardVehClassification() {#getstandardvehclassification}

DCM, Kode klasifikasi kendaraan standar untuk pemegang kartu. Elemen data ini merupakan placeholder untuk upaya di masa mendatang dalam menstandarisasi klasifikasi kendaraan, DL, F4AN

### getUnder18Until() {#getunder18until}

DDH, Tanggal ketika pemegang kartu berusia 18 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N

### getUnder21Until() {#getunder21until}

DDJ, Tanggal ketika pemegang kartu berusia 21 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N

### getVehClassDescription() {#getvehclassdescription}

DCP, Teks yang menjelaskan kode khusus yurisdiksi untuk klasifikasi kendaraan yang diizinkan untuk dikendarai oleh pemegang kartu, DL, V50ANS

### getVeteranIndicator() {#getveteranindicator}

DDL, Field yang menunjukkan bahwa pemegang kartu adalah veteran = “1”, DL/ID, F1N

### getWeightKilograms() {#getweightkilograms}

DAX, Berat pemegang kartu dalam kilogram, Contoh 84 kg = “084”, DL/ID, F3N

### getWeightPounds() {#getweightpounds}

DAW, Berat pemegang kartu dalam pon, Contoh 185 lb = “185”, DL/ID, F3N

### getWeightRange() {#getweightrange}

DCE, Menunjukkan rentang berat perkiraan pemegang kartu: 0 = hingga 31 kg (hingga 70 lbs), 1 = 32 – 45 kg (71 – 100 lbs), 2 = 46 - 59 kg (101 – 130 lbs), 3 = 60 - 70 kg (131 – 160 lbs), 4 = 71 - 86 kg (161 – 190 lbs), 5 = 87 - 100 kg (191 – 220 lbs), 6 = 101 - 113 kg (221 – 250 lbs), 7 = 114 - 127 kg (251 – 280 lbs), 8 = 128 – 145 kg (281 – 320 lbs), 9 = 146+ kg (321+ lbs), DL/ID, F1N

### setAddressStreet2() {#setaddressstreet2}

DAH, Baris kedua dari bagian jalan pada alamat pemegang kartu, DL/ID, V35ANS

### setAliasAKAFamilyName() {#setaliasakafamilyname}

DBN, Nama keluarga lain yang dikenal oleh pemegang kartu, DL/ID, V10ANS

### setAliasAKAGivenName() {#setaliasakagivenname}

DBG, Nama depan lain yang dikenal oleh pemegang kartu, DL/ID, V15ANS

### setAliasAKASuffixName() {#setaliasakasuffixname}

DBS, Akhiran lain yang dikenal oleh pemegang kartu, DL/ID, V5ANS

### setAuditInformation() {#setauditinformation}

DCJ, Sekumpulan huruf dan/atau angka yang mengidentifikasi kapan, di mana, dan oleh siapa kartu SIM/ID dibuat. Jika informasi audit tidak digunakan pada kartu atau MRT, harus dimasukkan ke dalam catatan pengemudi, DL/ID, V25ANS

### setCardRevisionDate() {#setcardrevisiondate}

DDB, bidang wajib DHS yang menunjukkan tanggal perubahan versi terbaru atau modifikasi pada format tampak DL/ID. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N

### setComplianceType() {#setcompliancetype}

DDA, field yang diperlukan oleh DHS yang menunjukkan kepatuhan: “F” = patuh; dan, “N” = tidak patuh, DL/ID, F1A

### setEndorsementCodeDescription() {#setendorsementcodedescription}

DCQ, Teks yang menjelaskan kode khusus yurisdiksi yang menunjukkan hak mengemudi tambahan yang diberikan kepada pemegang kartu di luar kelas kendaraan, DL, V50ANS

### setHairColor() {#sethaircolor}

DAZ, Botak, hitam, pirang, coklat, abu-abu, merah/kastanye, berpasir, putih, tidak diketahui. Jika yurisdiksi penerbit ingin menyingkat warna, kode tiga karakter yang disediakan dalam AAMVA D20 harus digunakan, DL/ID, V12A

### setInventoryControlNumber() {#setinventorycontrolnumber}

DCK, Rangkaian huruf dan/atau angka yang ditempelkan pada bahan mentah (kertas kartu, laminasi, dll.) yang digunakan dalam pembuatan lisensi pengemudi dan kartu ID. (bidang yang direkomendasikan DHS), DL/ID, V25ANS

### setLimitedDurationDocIndicator() {#setlimiteddurationdocindicator}

DDD, field yang diperlukan oleh DHS yang menunjukkan bahwa pemegang kartu memiliki status hukum sementara = “1”, DL/ID, F1N

### setNameSuffix() {#setnamesuffix}

DCU, Akhiran Nama (Jika yurisdiksi berpartisipasi dalam sistem yang memerlukan akhiran nama (PDPS, CDLIS, dll.), akhiran harus dikumpulkan dan ditampilkan pada DL/ID dan di MRT). JR (Junior), SR (Senior), 1ST atau I (Pertama), hingga 9TH atau IX (Kesembilan), DL/ID, V5ANS

### setOrganDonorIndicator() {#setorgandonorindicator}

DDK, Field yang menunjukkan bahwa pemegang kartu adalah donor organ = “1”, DL/ID, F1N

### setPlaceOfBirth() {#setplaceofbirth}

DCI, Negara dan kota serta/atau negara bagian/provinsi, DL/ID, V33A

### setRaceEthnicity() {#setraceethnicity}

DCL, Kode untuk ras atau etnisitas pemegang kartu, sebagaimana didefinisikan dalam AAMVA D20, DL/ID, V3A

### setRestrictionCodeDescription() {#setrestrictioncodedescription}

DCR, Teks yang menjelaskan kode pembatasan khusus yurisdiksi yang membatasi hak mengemudi, DL, V50ANS

### setStandardEndorsementCode() {#setstandardendorsementcode}

DCN, Kode endorsement standar untuk pemegang kartu. Lihat kode dalam D20. Elemen data ini merupakan placeholder untuk upaya di masa mendatang dalam menstandarisasi kode endorsement, DL, F5AN

### setStandardRestrictionCode() {#setstandardrestrictioncode}

DCO, Kode pembatasan standar untuk pemegang kartu. Lihat kode dalam D20. Elemen data ini merupakan placeholder untuk upaya di masa mendatang dalam menstandarisasi kode pembatasan, DL, F12AN

### setStandardVehClassification() {#setstandardvehclassification}

DCM, Kode klasifikasi kendaraan standar untuk pemegang kartu. Elemen data ini merupakan placeholder untuk upaya di masa mendatang dalam menstandarisasi klasifikasi kendaraan, DL, F4AN

### setUnder18Until() {#setunder18until}

DDI, Tanggal ketika pemegang kartu berusia 19 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N

### setUnder19Until() {#setunder19until}

DDI, Tanggal ketika pemegang kartu berusia 19 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N

### setUnder21Until() {#setunder21until}

DDJ, Tanggal ketika pemegang kartu berusia 21 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N

### setVehClassDescription() {#setvehclassdescription}

DCP, Teks yang menjelaskan kode khusus yurisdiksi untuk klasifikasi kendaraan yang diizinkan untuk dikendarai oleh pemegang kartu, DL, V50ANS

### setVeteranIndicator() {#setveteranindicator}

DDL, Field yang menunjukkan bahwa pemegang kartu adalah veteran = “1”, DL/ID, F1N

### setWeightKilograms() {#setweightkilograms}

DAX, Berat pemegang kartu dalam kilogram, Contoh 84 kg = “084”, DL/ID, F3N

### setWeightPounds() {#setweightpounds}

DAW, Berat pemegang kartu dalam pon, Contoh 185 lb = “185”, DL/ID, F3N

### setWeightRange() {#setweightrange}

DCE, Menunjukkan rentang berat perkiraan pemegang kartu: 0 = hingga 31 kg (hingga 70 lbs), 1 = 32 – 45 kg (71 – 100 lbs), 2 = 46 - 59 kg (101 – 130 lbs), 3 = 60 - 70 kg (131 – 160 lbs), 4 = 71 - 86 kg (161 – 190 lbs), 5 = 87 - 100 kg (191 – 220 lbs), 6 = 101 - 113 kg (221 – 250 lbs), 7 = 114 - 127 kg (251 – 280 lbs), 8 = 128 – 145 kg (281 – 320 lbs), 9 = 146+ kg (321+ lbs), DL/ID, F1N
