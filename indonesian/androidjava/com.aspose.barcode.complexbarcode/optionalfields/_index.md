---
title: USADriveIdCodetext.OptionalFields
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Bidang elemen opsional kartu
type: docs
weight: 11
url: /id/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.OptionalFields
```

Elemen opsional (field) kartu
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [OptionalFields()](#OptionalFields--) |  |
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressStreet2()](#getAddressStreet2--) | DAH, Baris kedua bagian jalan dari alamat pemegang kartu, DL/ID, V35ANS |
| [getAliasAKAFamilyName()](#getAliasAKAFamilyName--) | DBN, Nama keluarga lain yang dikenal untuk pemegang kartu, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getAliasAKAGivenName--) | DBG, Nama depan lain yang dikenal untuk pemegang kartu, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getAliasAKASuffixName--) | DBS, Akhiran lain yang dikenal untuk pemegang kartu, DL/ID, V5ANS |
| [getAuditInformation()](#getAuditInformation--) | DCJ, Sebuah rangkaian huruf dan/atau angka yang mengidentifikasi kapan, di mana, dan oleh siapa SIM/kartu identitas dibuat. |
| [getCardRevisionDate()](#getCardRevisionDate--) | DDB, bidang yang diwajibkan DHS yang menunjukkan tanggal perubahan versi terbaru atau modifikasi pada format terlihat DL/ID. |
| [getClass()](#getClass--) |  |
| [getComplianceType()](#getComplianceType--) | DDA, bidang yang diwajibkan DHS yang menunjukkan kepatuhan: \u201cF\u201d = patuh; dan, \u201cN\u201d = tidak patuh, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getEndorsementCodeDescription--) | DCQ, Teks yang menjelaskan kode khusus yurisdiksi yang menunjukkan hak mengemudi tambahan yang diberikan kepada pemegang kartu di luar kelas kendaraan, DL, V50ANS |
| [getHAZMATEndorsementExpDate()](#getHAZMATEndorsementExpDate--) | DDC, Tanggal di mana endorsement bahan berbahaya yang diberikan oleh dokumen tidak lagi berlaku. |
| [getHairColor()](#getHairColor--) | DAZ, Botak, hitam, pirang, coklat, abu-abu, merah/kastanye, berpasir, putih, tidak diketahui. |
| [getInventoryControlNumber()](#getInventoryControlNumber--) | DCK, Sebuah rangkaian huruf dan/atau angka yang ditempelkan pada bahan mentah (kertas kartu, laminasi, dll.) yang digunakan dalam pembuatan SIM dan kartu identitas. |
| [getLimitedDurationDocIndicator()](#getLimitedDurationDocIndicator--) | DDD, bidang yang diwajibkan DHS yang menunjukkan bahwa pemegang kartu memiliki status sah sementara = \u201c1\u201d, DL/ID, F1N |
| [getNameSuffix()](#getNameSuffix--) | DCU, Akhiran Nama (Jika yurisdiksi berpartisipasi dalam sistem yang memerlukan akhiran nama (PDPS, CDLIS, dll.), akhiran harus dikumpulkan dan ditampilkan pada DL/ID serta di MRT). |
| [getOrganDonorIndicator()](#getOrganDonorIndicator--) | DDK, Bidang yang menunjukkan bahwa pemegang kartu adalah donor organ = \u201c1\u201d, DL/ID, F1N |
| [getPlaceOfBirth()](#getPlaceOfBirth--) | DCI, Negara dan kota serta/atau provinsi, DL/ID, V33A |
| [getRaceEthnicity()](#getRaceEthnicity--) | DCL, Kode untuk ras atau etnisitas pemegang kartu, sebagaimana didefinisikan dalam AAMVA D20, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getRestrictionCodeDescription--) | DCR, Teks yang menjelaskan kode pembatasan khusus yurisdiksi yang membatasi hak mengemudi, DL, V50ANS |
| [getStandardEndorsementCode()](#getStandardEndorsementCode--) | DCN, Kode endorsement standar untuk pemegang kartu. |
| [getStandardRestrictionCode()](#getStandardRestrictionCode--) | DCO, Kode pembatasan standar untuk pemegang kartu. |
| [getStandardVehClassification()](#getStandardVehClassification--) | DCM, Kode klasifikasi kendaraan standar untuk pemegang kartu. |
| [getUnder18Until()](#getUnder18Until--) | DDH, Tanggal ketika pemegang kartu berusia 18 tahun. |
| [getUnder19Until()](#getUnder19Until--) | DDI, Tanggal ketika pemegang kartu berusia 19 tahun. |
| [getUnder21Until()](#getUnder21Until--) | DDJ, Tanggal ketika pemegang kartu berusia 21 tahun. |
| [getVehClassDescription()](#getVehClassDescription--) | DCP, Teks yang menjelaskan kode khusus yurisdiksi untuk klasifikasi kendaraan yang diizinkan untuk dikendarai oleh pemegang kartu, DL, V50ANS |
| [getVeteranIndicator()](#getVeteranIndicator--) | DDL, Kolom yang menunjukkan bahwa pemegang kartu adalah veteran = \\u201c1\\u201d, DL/ID, F1N |
| [getWeightKilograms()](#getWeightKilograms--) | DAX, Berat pemegang kartu dalam kilogram, Contoh. |
| [getWeightPounds()](#getWeightPounds--) | DAW, Berat pemegang kartu dalam pon, Contoh. |
| [getWeightRange()](#getWeightRange--) | DCE, Menunjukkan kisaran berat perkiraan pemegang kartu: 0 = hingga 31 kg(up to 70 lbs), 1 = 32 \\u2013 45 kg(71 \\u2013 100 lbs), 2 = 46 - 59 kg(101 \\u2013 130 lbs), 3 = 60 - 70 kg(131 \\u2013 160 lbs), 4 = 71 - 86 kg(161 \\u2013 190 lbs), 5 = 87 - 100 kg(191 \\u2013 220 lbs), 6 = 101 - 113 kg(221 \\u2013 250 lbs), 7 = 114 - 127 kg(251 \\u2013 280 lbs), 8 = 128 \\u2013 145 kg(281 \\u2013 320 lbs), 9 = 146+ kg(321+ lbs), DL/ID, F1N |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressStreet2(String value)](#setAddressStreet2-java.lang.String-) | DAH, Baris kedua bagian jalan dari alamat pemegang kartu, DL/ID, V35ANS |
| [setAliasAKAFamilyName(String value)](#setAliasAKAFamilyName-java.lang.String-) | DBN, Nama keluarga lain yang dikenal untuk pemegang kartu, DL/ID, V10ANS |
| [setAliasAKAGivenName(String value)](#setAliasAKAGivenName-java.lang.String-) | DBG, Nama depan lain yang dikenal untuk pemegang kartu, DL/ID, V15ANS |
| [setAliasAKASuffixName(String value)](#setAliasAKASuffixName-java.lang.String-) | DBS, Akhiran lain yang dikenal untuk pemegang kartu, DL/ID, V5ANS |
| [setAuditInformation(String value)](#setAuditInformation-java.lang.String-) | DCJ, Sebuah rangkaian huruf dan/atau angka yang mengidentifikasi kapan, di mana, dan oleh siapa SIM/kartu identitas dibuat. |
| [setCardRevisionDate(LocalDate value)](#setCardRevisionDate-java.time.LocalDate-) | DDB, bidang yang diwajibkan DHS yang menunjukkan tanggal perubahan versi terbaru atau modifikasi pada format terlihat DL/ID. |
| [setComplianceType(String value)](#setComplianceType-java.lang.String-) | DDA, bidang yang diwajibkan DHS yang menunjukkan kepatuhan: \u201cF\u201d = patuh; dan, \u201cN\u201d = tidak patuh, DL/ID, F1A |
| [setEndorsementCodeDescription(String value)](#setEndorsementCodeDescription-java.lang.String-) | DCQ, Teks yang menjelaskan kode khusus yurisdiksi yang menunjukkan hak mengemudi tambahan yang diberikan kepada pemegang kartu di luar kelas kendaraan, DL, V50ANS |
| [setHairColor(USADriveIdHairColor value)](#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-) | DAZ, Botak, hitam, pirang, coklat, abu-abu, merah/kastanye, berpasir, putih, tidak diketahui. |
| [setInventoryControlNumber(String value)](#setInventoryControlNumber-java.lang.String-) | DCK, Sebuah rangkaian huruf dan/atau angka yang ditempelkan pada bahan mentah (kertas kartu, laminasi, dll.) yang digunakan dalam pembuatan SIM dan kartu identitas. |
| [setLimitedDurationDocIndicator(String value)](#setLimitedDurationDocIndicator-java.lang.String-) | DDD, bidang yang diwajibkan DHS yang menunjukkan bahwa pemegang kartu memiliki status sah sementara = \u201c1\u201d, DL/ID, F1N |
| [setNameSuffix(String value)](#setNameSuffix-java.lang.String-) | DCU, Akhiran Nama (Jika yurisdiksi berpartisipasi dalam sistem yang memerlukan akhiran nama (PDPS, CDLIS, dll.), akhiran harus dikumpulkan dan ditampilkan pada DL/ID serta di MRT). |
| [setOrganDonorIndicator(String value)](#setOrganDonorIndicator-java.lang.String-) | DDK, Bidang yang menunjukkan bahwa pemegang kartu adalah donor organ = \u201c1\u201d, DL/ID, F1N |
| [setPlaceOfBirth(String value)](#setPlaceOfBirth-java.lang.String-) | DCI, Negara dan kota serta/atau provinsi, DL/ID, V33A |
| [setRaceEthnicity(String value)](#setRaceEthnicity-java.lang.String-) | DCL, Kode untuk ras atau etnisitas pemegang kartu, sebagaimana didefinisikan dalam AAMVA D20, DL/ID, V3A |
| [setRestrictionCodeDescription(String value)](#setRestrictionCodeDescription-java.lang.String-) | DCR, Teks yang menjelaskan kode pembatasan khusus yurisdiksi yang membatasi hak mengemudi, DL, V50ANS |
| [setStandardEndorsementCode(String value)](#setStandardEndorsementCode-java.lang.String-) | DCN, Kode endorsement standar untuk pemegang kartu. |
| [setStandardRestrictionCode(String value)](#setStandardRestrictionCode-java.lang.String-) | DCO, Kode pembatasan standar untuk pemegang kartu. |
| [setStandardVehClassification(String value)](#setStandardVehClassification-java.lang.String-) | DCM, Kode klasifikasi kendaraan standar untuk pemegang kartu. |
| [setUnder18Until(LocalDate value)](#setUnder18Until-java.time.LocalDate-) | DDH, Tanggal ketika pemegang kartu berusia 18 tahun. |
| [setUnder19Until(LocalDate value)](#setUnder19Until-java.time.LocalDate-) | DDI, Tanggal ketika pemegang kartu berusia 19 tahun. |
| [setUnder21Until(LocalDate value)](#setUnder21Until-java.time.LocalDate-) | DDJ, Tanggal ketika pemegang kartu berusia 21 tahun. |
| [setVehClassDescription(String value)](#setVehClassDescription-java.lang.String-) | DCP, Teks yang menjelaskan kode khusus yurisdiksi untuk klasifikasi kendaraan yang diizinkan untuk dikendarai oleh pemegang kartu, DL, V50ANS |
| [setVeteranIndicator(String value)](#setVeteranIndicator-java.lang.String-) | DDL, Kolom yang menunjukkan bahwa pemegang kartu adalah veteran = \\u201c1\\u201d, DL/ID, F1N |
| [setWeightKilograms(int value)](#setWeightKilograms-int-) | DAX, Berat pemegang kartu dalam kilogram, Contoh. |
| [setWeightPounds(int value)](#setWeightPounds-int-) | DAW, Berat pemegang kartu dalam pon, Contoh. |
| [setWeightRange(String value)](#setWeightRange-java.lang.String-) | DCE, Menunjukkan kisaran berat perkiraan pemegang kartu: 0 = hingga 31 kg(up to 70 lbs), 1 = 32 \\u2013 45 kg(71 \\u2013 100 lbs), 2 = 46 - 59 kg(101 \\u2013 130 lbs), 3 = 60 - 70 kg(131 \\u2013 160 lbs), 4 = 71 - 86 kg(161 \\u2013 190 lbs), 5 = 87 - 100 kg(191 \\u2013 220 lbs), 6 = 101 - 113 kg(221 \\u2013 250 lbs), 7 = 114 - 127 kg(251 \\u2013 280 lbs), 8 = 128 \\u2013 145 kg(281 \\u2013 320 lbs), 9 = 146+ kg(321+ lbs), DL/ID, F1N |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OptionalFields() {#OptionalFields--}
```
public OptionalFields()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressStreet2() {#getAddressStreet2--}
```
public final String getAddressStreet2()
```


DAH, Baris kedua bagian jalan dari alamat pemegang kartu, DL/ID, V35ANS

**Returns:**
java.lang.String
### getAliasAKAFamilyName() {#getAliasAKAFamilyName--}
```
public final String getAliasAKAFamilyName()
```


DBN, Nama keluarga lain yang dikenal untuk pemegang kartu, DL/ID, V10ANS

**Returns:**
java.lang.String
### getAliasAKAGivenName() {#getAliasAKAGivenName--}
```
public final String getAliasAKAGivenName()
```


DBG, Nama depan lain yang dikenal untuk pemegang kartu, DL/ID, V15ANS

**Returns:**
java.lang.String
### getAliasAKASuffixName() {#getAliasAKASuffixName--}
```
public final String getAliasAKASuffixName()
```


DBS, Akhiran lain yang dikenal untuk pemegang kartu, DL/ID, V5ANS

**Returns:**
java.lang.String
### getAuditInformation() {#getAuditInformation--}
```
public final String getAuditInformation()
```


DCJ, Sekumpulan huruf dan/atau angka yang mengidentifikasi kapan, di mana, dan oleh siapa surat izin mengemudi/KTP dibuat. Jika informasi audit tidak digunakan pada kartu atau MRT, informasi tersebut harus dimasukkan ke dalam catatan pengemudi, DL/ID, V25ANS

**Returns:**
java.lang.String
### getCardRevisionDate() {#getCardRevisionDate--}
```
public final LocalDate getCardRevisionDate()
```


DDB, Kolom yang diwajibkan DHS yang menunjukkan tanggal perubahan versi terbaru atau modifikasi format tampilan DL/ID. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplianceType() {#getComplianceType--}
```
public final String getComplianceType()
```


DDA, bidang yang diwajibkan DHS yang menunjukkan kepatuhan: \u201cF\u201d = patuh; dan, \u201cN\u201d = tidak patuh, DL/ID, F1A

**Returns:**
java.lang.String
### getEndorsementCodeDescription() {#getEndorsementCodeDescription--}
```
public final String getEndorsementCodeDescription()
```


DCQ, Teks yang menjelaskan kode khusus yurisdiksi yang menunjukkan hak mengemudi tambahan yang diberikan kepada pemegang kartu di luar kelas kendaraan, DL, V50ANS

**Returns:**
java.lang.String
### getHAZMATEndorsementExpDate() {#getHAZMATEndorsementExpDate--}
```
public final LocalDate getHAZMATEndorsementExpDate()
```


DDC, Tanggal ketika endorsement bahan berbahaya yang diberikan oleh dokumen tidak lagi berlaku. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL, F8N

**Returns:**
java.time.LocalDate
### getHairColor() {#getHairColor--}
```
public final USADriveIdHairColor getHairColor()
```


DAZ, Botak, hitam, pirang, coklat, abu-abu, merah/kastanye, pasir, putih, tidak diketahui. Jika yurisdiksi penerbit ingin menyingkat warna, kode tiga karakter yang disediakan dalam AAMVA D20 harus digunakan, DL/ID, V12A

**Returns:**
[USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor)
### getInventoryControlNumber() {#getInventoryControlNumber--}
```
public final String getInventoryControlNumber()
```


DCK, Sekumpulan huruf dan/atau angka yang ditempelkan pada bahan mentah (kertas karton, laminasi, dll.) yang digunakan dalam pembuatan surat izin mengemudi dan kartu ID. (Kolom yang direkomendasikan DHS), DL/ID, V25ANS

**Returns:**
java.lang.String
### getLimitedDurationDocIndicator() {#getLimitedDurationDocIndicator--}
```
public final String getLimitedDurationDocIndicator()
```


DDD, bidang yang diwajibkan DHS yang menunjukkan bahwa pemegang kartu memiliki status sah sementara = \u201c1\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getNameSuffix() {#getNameSuffix--}
```
public final String getNameSuffix()
```


DCU, Akhiran Nama (Jika yurisdiksi berpartisipasi dalam sistem yang memerlukan akhiran nama (PDPS, CDLIS, dll.), akhiran harus dikumpulkan dan ditampilkan pada DL/ID dan dalam MRT). JR (Junior), SR (Senior), 1ST atau I (Pertama), hingga 9TH atau IX (Kesembilan), DL/ID, V5ANS

**Returns:**
java.lang.String
### getOrganDonorIndicator() {#getOrganDonorIndicator--}
```
public final String getOrganDonorIndicator()
```


DDK, Bidang yang menunjukkan bahwa pemegang kartu adalah donor organ = \u201c1\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getPlaceOfBirth() {#getPlaceOfBirth--}
```
public final String getPlaceOfBirth()
```


DCI, Negara dan kota serta/atau provinsi, DL/ID, V33A

**Returns:**
java.lang.String
### getRaceEthnicity() {#getRaceEthnicity--}
```
public final String getRaceEthnicity()
```


DCL, Kode untuk ras atau etnisitas pemegang kartu, sebagaimana didefinisikan dalam AAMVA D20, DL/ID, V3A

**Returns:**
java.lang.String
### getRestrictionCodeDescription() {#getRestrictionCodeDescription--}
```
public final String getRestrictionCodeDescription()
```


DCR, Teks yang menjelaskan kode pembatasan khusus yurisdiksi yang membatasi hak mengemudi, DL, V50ANS

**Returns:**
java.lang.String
### getStandardEndorsementCode() {#getStandardEndorsementCode--}
```
public final String getStandardEndorsementCode()
```


DCN, Kode endorsement standar untuk pemegang kartu. Lihat kode dalam D20. Elemen data ini merupakan placeholder untuk upaya di masa depan dalam menstandarisasi kode endorsement, DL, F5AN

**Returns:**
java.lang.String
### getStandardRestrictionCode() {#getStandardRestrictionCode--}
```
public final String getStandardRestrictionCode()
```


DCO, Kode pembatasan standar untuk pemegang kartu. Lihat kode dalam D20. Elemen data ini merupakan placeholder untuk upaya di masa depan dalam menstandarisasi kode pembatasan, DL, F12AN

**Returns:**
java.lang.String
### getStandardVehClassification() {#getStandardVehClassification--}
```
public final String getStandardVehClassification()
```


DCM, Kode klasifikasi kendaraan standar untuk pemegang kartu. Elemen data ini merupakan placeholder untuk upaya di masa depan dalam menstandarisasi klasifikasi kendaraan, DL, F4AN

**Returns:**
java.lang.String
### getUnder18Until() {#getUnder18Until--}
```
public final LocalDate getUnder18Until()
```


DDH, Tanggal ketika pemegang kartu berusia 18 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder19Until() {#getUnder19Until--}
```
public final LocalDate getUnder19Until()
```


DDI, Tanggal ketika pemegang kartu berusia 19 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder21Until() {#getUnder21Until--}
```
public final LocalDate getUnder21Until()
```


DDJ, Tanggal ketika pemegang kartu berusia 21 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getVehClassDescription() {#getVehClassDescription--}
```
public final String getVehClassDescription()
```


DCP, Teks yang menjelaskan kode khusus yurisdiksi untuk klasifikasi kendaraan yang diizinkan untuk dikendarai oleh pemegang kartu, DL, V50ANS

**Returns:**
java.lang.String
### getVeteranIndicator() {#getVeteranIndicator--}
```
public final String getVeteranIndicator()
```


DDL, Kolom yang menunjukkan bahwa pemegang kartu adalah veteran = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getWeightKilograms() {#getWeightKilograms--}
```
public final int getWeightKilograms()
```


DAX, Berat pemegang kartu dalam kilogram, Contoh 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightPounds() {#getWeightPounds--}
```
public final int getWeightPounds()
```


DAW, Berat pemegang kartu dalam pon, Contoh 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightRange() {#getWeightRange--}
```
public final String getWeightRange()
```


DCE, Menunjukkan kisaran berat perkiraan pemegang kartu: 0 = hingga 31 kg(up to 70 lbs), 1 = 32 \\u2013 45 kg(71 \\u2013 100 lbs), 2 = 46 - 59 kg(101 \\u2013 130 lbs), 3 = 60 - 70 kg(131 \\u2013 160 lbs), 4 = 71 - 86 kg(161 \\u2013 190 lbs), 5 = 87 - 100 kg(191 \\u2013 220 lbs), 6 = 101 - 113 kg(221 \\u2013 250 lbs), 7 = 114 - 127 kg(251 \\u2013 280 lbs), 8 = 128 \\u2013 145 kg(281 \\u2013 320 lbs), 9 = 146+ kg(321+ lbs), DL/ID, F1N

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressStreet2(String value) {#setAddressStreet2-java.lang.String-}
```
public final void setAddressStreet2(String value)
```


DAH, Baris kedua bagian jalan dari alamat pemegang kartu, DL/ID, V35ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setAliasAKAFamilyName(String value) {#setAliasAKAFamilyName-java.lang.String-}
```
public final void setAliasAKAFamilyName(String value)
```


DBN, Nama keluarga lain yang dikenal untuk pemegang kartu, DL/ID, V10ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setAliasAKAGivenName(String value) {#setAliasAKAGivenName-java.lang.String-}
```
public final void setAliasAKAGivenName(String value)
```


DBG, Nama depan lain yang dikenal untuk pemegang kartu, DL/ID, V15ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setAliasAKASuffixName(String value) {#setAliasAKASuffixName-java.lang.String-}
```
public final void setAliasAKASuffixName(String value)
```


DBS, Akhiran lain yang dikenal untuk pemegang kartu, DL/ID, V5ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setAuditInformation(String value) {#setAuditInformation-java.lang.String-}
```
public final void setAuditInformation(String value)
```


DCJ, Sekumpulan huruf dan/atau angka yang mengidentifikasi kapan, di mana, dan oleh siapa surat izin mengemudi/KTP dibuat. Jika informasi audit tidak digunakan pada kartu atau MRT, informasi tersebut harus dimasukkan ke dalam catatan pengemudi, DL/ID, V25ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setCardRevisionDate(LocalDate value) {#setCardRevisionDate-java.time.LocalDate-}
```
public final void setCardRevisionDate(LocalDate value)
```


DDB, Kolom yang diwajibkan DHS yang menunjukkan tanggal perubahan versi terbaru atau modifikasi format tampilan DL/ID. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.time.LocalDate |  |

### setComplianceType(String value) {#setComplianceType-java.lang.String-}
```
public final void setComplianceType(String value)
```


DDA, bidang yang diwajibkan DHS yang menunjukkan kepatuhan: \u201cF\u201d = patuh; dan, \u201cN\u201d = tidak patuh, DL/ID, F1A

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setEndorsementCodeDescription(String value) {#setEndorsementCodeDescription-java.lang.String-}
```
public final void setEndorsementCodeDescription(String value)
```


DCQ, Teks yang menjelaskan kode khusus yurisdiksi yang menunjukkan hak mengemudi tambahan yang diberikan kepada pemegang kartu di luar kelas kendaraan, DL, V50ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setHairColor(USADriveIdHairColor value) {#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-}
```
public final void setHairColor(USADriveIdHairColor value)
```


DAZ, Botak, hitam, pirang, coklat, abu-abu, merah/kastanye, pasir, putih, tidak diketahui. Jika yurisdiksi penerbit ingin menyingkat warna, kode tiga karakter yang disediakan dalam AAMVA D20 harus digunakan, DL/ID, V12A

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor) |  |

### setInventoryControlNumber(String value) {#setInventoryControlNumber-java.lang.String-}
```
public final void setInventoryControlNumber(String value)
```


DCK, Sekumpulan huruf dan/atau angka yang ditempelkan pada bahan mentah (kertas karton, laminasi, dll.) yang digunakan dalam pembuatan surat izin mengemudi dan kartu ID. (Kolom yang direkomendasikan DHS), DL/ID, V25ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setLimitedDurationDocIndicator(String value) {#setLimitedDurationDocIndicator-java.lang.String-}
```
public final void setLimitedDurationDocIndicator(String value)
```


DDD, bidang yang diwajibkan DHS yang menunjukkan bahwa pemegang kartu memiliki status sah sementara = \u201c1\u201d, DL/ID, F1N

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setNameSuffix(String value) {#setNameSuffix-java.lang.String-}
```
public final void setNameSuffix(String value)
```


DCU, Akhiran Nama (Jika yurisdiksi berpartisipasi dalam sistem yang memerlukan akhiran nama (PDPS, CDLIS, dll.), akhiran harus dikumpulkan dan ditampilkan pada DL/ID dan dalam MRT). JR (Junior), SR (Senior), 1ST atau I (Pertama), hingga 9TH atau IX (Kesembilan), DL/ID, V5ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setOrganDonorIndicator(String value) {#setOrganDonorIndicator-java.lang.String-}
```
public final void setOrganDonorIndicator(String value)
```


DDK, Bidang yang menunjukkan bahwa pemegang kartu adalah donor organ = \u201c1\u201d, DL/ID, F1N

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setPlaceOfBirth(String value) {#setPlaceOfBirth-java.lang.String-}
```
public final void setPlaceOfBirth(String value)
```


DCI, Negara dan kota serta/atau provinsi, DL/ID, V33A

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setRaceEthnicity(String value) {#setRaceEthnicity-java.lang.String-}
```
public final void setRaceEthnicity(String value)
```


DCL, Kode untuk ras atau etnisitas pemegang kartu, sebagaimana didefinisikan dalam AAMVA D20, DL/ID, V3A

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setRestrictionCodeDescription(String value) {#setRestrictionCodeDescription-java.lang.String-}
```
public final void setRestrictionCodeDescription(String value)
```


DCR, Teks yang menjelaskan kode pembatasan khusus yurisdiksi yang membatasi hak mengemudi, DL, V50ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setStandardEndorsementCode(String value) {#setStandardEndorsementCode-java.lang.String-}
```
public final void setStandardEndorsementCode(String value)
```


DCN, Kode endorsement standar untuk pemegang kartu. Lihat kode dalam D20. Elemen data ini merupakan placeholder untuk upaya di masa depan dalam menstandarisasi kode endorsement, DL, F5AN

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setStandardRestrictionCode(String value) {#setStandardRestrictionCode-java.lang.String-}
```
public final void setStandardRestrictionCode(String value)
```


DCO, Kode pembatasan standar untuk pemegang kartu. Lihat kode dalam D20. Elemen data ini merupakan placeholder untuk upaya di masa depan dalam menstandarisasi kode pembatasan, DL, F12AN

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setStandardVehClassification(String value) {#setStandardVehClassification-java.lang.String-}
```
public final void setStandardVehClassification(String value)
```


DCM, Kode klasifikasi kendaraan standar untuk pemegang kartu. Elemen data ini merupakan placeholder untuk upaya di masa depan dalam menstandarisasi klasifikasi kendaraan, DL, F4AN

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setUnder18Until(LocalDate value) {#setUnder18Until-java.time.LocalDate-}
```
public final void setUnder18Until(LocalDate value)
```


DDH, Tanggal ketika pemegang kartu berusia 18 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.time.LocalDate |  |

### setUnder19Until(LocalDate value) {#setUnder19Until-java.time.LocalDate-}
```
public final void setUnder19Until(LocalDate value)
```


DDI, Tanggal ketika pemegang kartu berusia 19 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.time.LocalDate |  |

### setUnder21Until(LocalDate value) {#setUnder21Until-java.time.LocalDate-}
```
public final void setUnder21Until(LocalDate value)
```


DDJ, Tanggal ketika pemegang kartu berusia 21 tahun. (MMDDCCYY untuk AS, CCYYMMDD untuk Kanada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.time.LocalDate |  |

### setVehClassDescription(String value) {#setVehClassDescription-java.lang.String-}
```
public final void setVehClassDescription(String value)
```


DCP, Teks yang menjelaskan kode khusus yurisdiksi untuk klasifikasi kendaraan yang diizinkan untuk dikendarai oleh pemegang kartu, DL, V50ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setVeteranIndicator(String value) {#setVeteranIndicator-java.lang.String-}
```
public final void setVeteranIndicator(String value)
```


DDL, Kolom yang menunjukkan bahwa pemegang kartu adalah veteran = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setWeightKilograms(int value) {#setWeightKilograms-int-}
```
public final void setWeightKilograms(int value)
```


DAX, Berat pemegang kartu dalam kilogram, Contoh 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setWeightPounds(int value) {#setWeightPounds-int-}
```
public final void setWeightPounds(int value)
```


DAW, Berat pemegang kartu dalam pon, Contoh 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setWeightRange(String value) {#setWeightRange-java.lang.String-}
```
public final void setWeightRange(String value)
```


DCE, Menunjukkan kisaran berat perkiraan pemegang kartu: 0 = hingga 31 kg(up to 70 lbs), 1 = 32 \\u2013 45 kg(71 \\u2013 100 lbs), 2 = 46 - 59 kg(101 \\u2013 130 lbs), 3 = 60 - 70 kg(131 \\u2013 160 lbs), 4 = 71 - 86 kg(161 \\u2013 190 lbs), 5 = 87 - 100 kg(191 \\u2013 220 lbs), 6 = 101 - 113 kg(221 \\u2013 250 lbs), 7 = 114 - 127 kg(251 \\u2013 280 lbs), 8 = 128 \\u2013 145 kg(281 \\u2013 320 lbs), 9 = 146+ kg(321+ lbs), DL/ID, F1N

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

