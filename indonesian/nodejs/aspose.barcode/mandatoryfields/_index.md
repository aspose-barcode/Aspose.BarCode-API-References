---
title: "MandatoryFields"
linktitle: "MandatoryFields"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Elemen (field) wajib dari kartu"
type: docs
weight: 590
url: /id/nodejs/aspose.barcode/mandatoryfields/
---

## MandatoryFields class

Elemen (field) wajib dari kartu

```js
new MandatoryFields()
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getAddressCity()](#getaddresscity) | DAI, bagian Kota dari alamat pemegang kartu, DL/ID, V20ANS |
| [getAddressPostalCode()](#getaddresspostalcode) | DAK, bagian kode pos dari alamat pemegang kartu di AS dan Kanada. Jika bagian akhir kode pos di |
| [getAddressState()](#getaddressstate) | DAJ, bagian Negara Bagian dari alamat pemegang kartu, DL/ID, F2A |
| [getAddressStreet1()](#getaddressstreet1) | DAG, bagian Jalan dari alamat pemegang kartu, DL/ID, V35ANS |
| [getCountryIdentification()](#getcountryidentification) | DCG, Negara tempat DL/ID diterbitkan. U.S. = USA, Canada = CAN, DL/ID, F3A |
| [getCustomerIDNumber()](#getcustomeridnumber) | DAQ, Nomor yang diberikan atau dihitung oleh otoritas penerbit, DL/ID, V25ANS |
| [getDateOfBirth()](#getdateofbirth) | DBB, Tanggal penerbitan dokumen, MMDDCCYY untuk U.S., CCYYMMDD untuk Canada, DL/ID, F8N |
| [getDocumentDiscriminator()](#getdocumentdiscriminator) | DCF, Nomor harus secara unik mengidentifikasi dokumen tertentu yang diterbitkan untuk pelanggan tersebut dari dokumen lain yang mungkin telah diterbitkan sebelumnya. |
| [getEndorsementCodes()](#getendorsementcodes) | DCD, Kode endorsement khusus yurisdiksi, DL, V5ANS |
| [getEyeColor()](#geteyecolor) | DAY, Warna mata pemegang kartu. (Kode ANSI D-20). DL/ID, F3A |
| [getFamilyName()](#getfamilyname) | DCS, Nama keluarga pemegang kartu, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getfamilynametruncation) | DDE, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong |
| [getFirstName()](#getfirstname) | DAC, Nama depan pemegang kartu, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getfirstnametruncation) | DDF, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong |
| [getHeight()](#getheight) | DAU, Tinggi pemegang kartu. Inci (in): jumlah inci diikuti oleh " in" contoh 6'1'' = "073 in" Sentimeter(cm) : number |
| [getMiddleName()](#getmiddlename) | DAD, Nama tengah pemegang kartu. Jika ada beberapa nama tengah, mereka harus dipisahkan dengan koma ",". , DL |
| [getMiddleNameTruncation()](#getmiddlenametruncation) | DDG, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong |
| [getRestrictionCodes()](#getrestrictioncodes) | DCB, Kode pembatasan khusus yurisdiksi, DL, V12ANS |
| [getSex()](#getsex) | DBC, Jenis kelamin pemegang kartu. 1 = pria, 2 = wanita, 9 = tidak ditentukan, DL/ID, F1N |
| [getVehicleClass()](#getvehicleclass) | DCA, Kode kelas / grup kendaraan khusus yurisdiksi, DL, V6ANS |
| [setAddressCity()](#setaddresscity) | DAI, bagian Kota dari alamat pemegang kartu, DL/ID, V20ANS |
| [setAddressPostalCode()](#setaddresspostalcode) | DAK, bagian kode pos dari alamat pemegang kartu di AS dan Kanada. Jika bagian akhir kode pos di |
| [setAddressState()](#setaddressstate) | DAJ, bagian Negara Bagian dari alamat pemegang kartu, DL/ID, F2A |
| [setAddressStreet1()](#setaddressstreet1) | DAG, bagian Jalan dari alamat pemegang kartu, DL/ID, V35ANS |
| [setCountryIdentification()](#setcountryidentification) | DCG, Negara tempat DL/ID diterbitkan. U.S. = USA, Canada = CAN, DL/ID, F3A |
| [setCustomerIDNumber()](#setcustomeridnumber) | DAQ, Nomor yang diberikan atau dihitung oleh otoritas penerbit, DL/ID, V25ANS |
| [setDateOfBirth()](#setdateofbirth) | DBB, Tanggal penerbitan dokumen, MMDDCCYY untuk U.S., CCYYMMDD untuk Canada, DL/ID, F8N |
| [setDocumentDiscriminator()](#setdocumentdiscriminator) | DCF, Nomor harus secara unik mengidentifikasi dokumen tertentu yang diterbitkan untuk pelanggan tersebut dari dokumen lain yang mungkin telah diterbitkan sebelumnya. |
| [setEndorsementCodes()](#setendorsementcodes) | DCD, Kode endorsement khusus yurisdiksi, DL, V5ANS |
| [setEyeColor()](#seteyecolor) | DAY, Warna mata pemegang kartu. (Kode ANSI D-20). DL/ID, F3A |
| [setFamilyName()](#setfamilyname) | DCS, Nama keluarga pemegang kartu, DL/ID, V40ANS |
| [setFamilyNameTruncation()](#setfamilynametruncation) | DDE, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong |
| [setFirstName()](#setfirstname) | DAC, Nama depan pemegang kartu, DL/ID, V40ANS |
| [setFirstNameTruncation()](#setfirstnametruncation) | DDF, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong |
| [setHeight()](#setheight) | DAU, Tinggi pemegang kartu. Inci (in): jumlah inci diikuti oleh " in" contoh 6'1'' = "073 in" Sentimeter(cm) : number |
| [setMiddleName()](#setmiddlename) | DAD, Nama tengah pemegang kartu. Jika ada beberapa nama tengah, mereka harus dipisahkan dengan koma ",". , DL |
| [setMiddleNameTruncation()](#setmiddlenametruncation) | DDG, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong |
| [setRestrictionCodes()](#setrestrictioncodes) | DCB, Kode pembatasan khusus yurisdiksi, DL, V12ANS |
| [setSex()](#setsex) | DBC, Jenis kelamin pemegang kartu. 1 = pria, 2 = wanita, 9 = tidak ditentukan, DL/ID, F1N |
| [setVehicleClass()](#setvehicleclass) | DCA, Kode kelas / grup kendaraan khusus yurisdiksi, DL, V6ANS |

### getAddressCity() {#getaddresscity}

DAI, bagian Kota dari alamat pemegang kartu, DL/ID, V20ANS

### getAddressPostalCode() {#getaddresspostalcode}

DAK, Bagian kode pos dari alamat pemegang kartu di AS dan Kanada. Jika bagian akhir kode pos di AS tidak diketahui, nol akan digunakan untuk mengisi bagian akhir angka hingga 9 digit, DL/ID, F11ANS

### getAddressState() {#getaddressstate}

DAJ, bagian Negara Bagian dari alamat pemegang kartu, DL/ID, F2A

### getAddressStreet1() {#getaddressstreet1}

DAG, bagian Jalan dari alamat pemegang kartu, DL/ID, V35ANS

### getCountryIdentification() {#getcountryidentification}

DCG, Negara tempat DL/ID diterbitkan. U.S. = USA, Canada = CAN, DL/ID, F3A

### getCustomerIDNumber() {#getcustomeridnumber}

DAQ, Nomor yang diberikan atau dihitung oleh otoritas penerbit, DL/ID, V25ANS

### getDateOfBirth() {#getdateofbirth}

DBB, Tanggal penerbitan dokumen, MMDDCCYY untuk U.S., CCYYMMDD untuk Canada, DL/ID, F8N

### getDocumentDiscriminator() {#getdocumentdiscriminator}

DCF, Nomor harus secara unik mengidentifikasi dokumen tertentu yang diterbitkan untuk pelanggan tersebut dari dokumen lain yang mungkin telah diterbitkan sebelumnya. Nomor ini dapat berfungsi untuk berbagai tujuan seperti diskriminasi dokumen, nomor informasi audit, dan/atau kontrol inventaris, DL/ID, V25ANS

### getEndorsementCodes() {#getendorsementcodes}

DCD, Kode endorsement khusus yurisdiksi, DL, V5ANS

### getEyeColor() {#geteyecolor}

DAY, Warna mata pemegang kartu. (Kode ANSI D-20). DL/ID, F3A

### getFamilyName() {#getfamilyname}

DCS, Nama keluarga pemegang kartu, DL/ID, V40ANS

### getFamilyNameTruncation() {#getfamilynametruncation}

DDE, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A

### getFirstName() {#getfirstname}

DAC, Nama depan pemegang kartu, DL/ID, V40ANS

### getFirstNameTruncation() {#getfirstnametruncation}

DDF, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A

### getHeight() {#getheight}

DAU, Tinggi pemegang kartu. Inci (in): jumlah inci diikuti oleh " in" contoh 6'1'' = "073 in" Sentimeter(cm): jumlah sentimeter diikuti oleh " cm" contoh 181 sentimeter="181 cm" , DL/ID, F6ANS

### getMiddleName() {#getmiddlename}

DAD, Nama tengah pemegang kartu. Jika ada beberapa nama tengah, mereka harus dipisahkan dengan koma ",". , DL/ID, V40ANS

### getMiddleNameTruncation() {#getmiddlenametruncation}

DDG, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A

### getRestrictionCodes() {#getrestrictioncodes}

DCB, Kode pembatasan khusus yurisdiksi, DL, V12ANS

### getSex() {#getsex}

DBC, Jenis kelamin pemegang kartu. 1 = pria, 2 = wanita, 9 = tidak ditentukan, DL/ID, F1N

### getVehicleClass() {#getvehicleclass}

DCA, Kode kelas / grup kendaraan khusus yurisdiksi, DL, V6ANS

### setAddressCity() {#setaddresscity}

DAI, bagian Kota dari alamat pemegang kartu, DL/ID, V20ANS

### setAddressPostalCode() {#setaddresspostalcode}

DAK, Bagian kode pos dari alamat pemegang kartu di AS dan Kanada. Jika bagian akhir kode pos di AS tidak diketahui, nol akan digunakan untuk mengisi bagian akhir angka hingga 9 digit, DL/ID, F11ANS

### setAddressState() {#setaddressstate}

DAJ, bagian Negara Bagian dari alamat pemegang kartu, DL/ID, F2A

### setAddressStreet1() {#setaddressstreet1}

DAG, bagian Jalan dari alamat pemegang kartu, DL/ID, V35ANS

### setCountryIdentification() {#setcountryidentification}

DCG, Negara tempat DL/ID diterbitkan. U.S. = USA, Canada = CAN, DL/ID, F3A

### setCustomerIDNumber() {#setcustomeridnumber}

DAQ, Nomor yang diberikan atau dihitung oleh otoritas penerbit, DL/ID, V25ANS

### setDateOfBirth() {#setdateofbirth}

DBB, Tanggal penerbitan dokumen, MMDDCCYY untuk U.S., CCYYMMDD untuk Canada, DL/ID, F8N

### setDocumentDiscriminator() {#setdocumentdiscriminator}

DCF, Nomor harus secara unik mengidentifikasi dokumen tertentu yang diterbitkan untuk pelanggan tersebut dari dokumen lain yang mungkin telah diterbitkan sebelumnya. Nomor ini dapat berfungsi untuk berbagai tujuan seperti diskriminasi dokumen, nomor informasi audit, dan/atau kontrol inventaris, DL/ID, V25ANS

### setEndorsementCodes() {#setendorsementcodes}

DCD, Kode endorsement khusus yurisdiksi, DL, V5ANS

### setEyeColor() {#seteyecolor}

DAY, Warna mata pemegang kartu. (Kode ANSI D-20). DL/ID, F3A

### setFamilyName() {#setfamilyname}

DCS, Nama keluarga pemegang kartu, DL/ID, V40ANS

### setFamilyNameTruncation() {#setfamilynametruncation}

DDE, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A

### setFirstName() {#setfirstname}

DAC, Nama depan pemegang kartu, DL/ID, V40ANS

### setFirstNameTruncation() {#setfirstnametruncation}

DDF, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A

### setHeight() {#setheight}

DAU, Tinggi pemegang kartu. Inci (in): jumlah inci diikuti oleh " in" contoh 6'1'' = "073 in" Sentimeter(cm): jumlah sentimeter diikuti oleh " cm" contoh 181 sentimeter="181 cm" , DL/ID, F6ANS

### setMiddleName() {#setmiddlename}

DAD, Nama tengah pemegang kartu. Jika ada beberapa nama tengah, mereka harus dipisahkan dengan koma ",". , DL/ID, V40ANS

### setMiddleNameTruncation() {#setmiddlenametruncation}

DDG, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A

### setRestrictionCodes() {#setrestrictioncodes}

DCB, Kode pembatasan khusus yurisdiksi, DL, V12ANS

### setSex() {#setsex}

DBC, Jenis kelamin pemegang kartu. 1 = pria, 2 = wanita, 9 = tidak ditentukan, DL/ID, F1N

### setVehicleClass() {#setvehicleclass}

DCA, Kode kelas / grup kendaraan khusus yurisdiksi, DL, V6ANS
