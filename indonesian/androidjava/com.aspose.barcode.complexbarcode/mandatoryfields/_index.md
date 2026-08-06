---
title: USADriveIdCodetext.MandatoryFields
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Bidang elemen wajib kartu
type: docs
weight: 10
url: /id/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.MandatoryFields
```

Elemen (field) wajib pada kartu
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [MandatoryFields()](#MandatoryFields--) |  |
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressCity()](#getAddressCity--) | DAI, Bagian kota dari alamat pemegang kartu, DL/ID, V20ANS |
| [getAddressPostalCode()](#getAddressPostalCode--) | DAK, Bagian kode pos dari alamat pemegang kartu di AS dan Kanada. |
| [getAddressState()](#getAddressState--) | DAJ, Bagian negara bagian dari alamat pemegang kartu, DL/ID, F2A |
| [getAddressStreet1()](#getAddressStreet1--) | DAG, Bagian jalan dari alamat pemegang kartu, DL/ID, V35ANS |
| [getClass()](#getClass--) |  |
| [getCountryIdentification()](#getCountryIdentification--) | DCG, Negara tempat DL/ID diterbitkan. |
| [getCustomerIDNumber()](#getCustomerIDNumber--) | DAQ, Nomor yang diberikan atau dihitung oleh otoritas penerbit, DL/ID, V25ANS |
| [getDateOfBirth()](#getDateOfBirth--) | DBB, Tanggal dokumen diterbitkan, MMDDCCYY untuk AS, CCYYMMDD untuk Kanada, DL/ID, F8N |
| [getDocumentDiscriminator()](#getDocumentDiscriminator--) | DCF, Nomor harus secara unik mengidentifikasi dokumen tertentu yang diterbitkan kepada pelanggan tersebut dari dokumen lain yang mungkin telah diterbitkan sebelumnya. |
| [getEndorsementCodes()](#getEndorsementCodes--) | DCD, Kode endorsement khusus yurisdiksi, DL, V5ANS |
| [getEyeColor()](#getEyeColor--) | DAY, Warna mata pemegang kartu. |
| [getFamilyName()](#getFamilyName--) | DCS, Nama keluarga pemegang kartu, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getFamilyNameTruncation--) | DDE, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A |
| [getFirstName()](#getFirstName--) | DAC, Nama depan pemegang kartu, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getFirstNameTruncation--) | DDF, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A |
| [getHeight()](#getHeight--) | DAU, Tinggi pemegang kartu. |
| [getMiddleName()](#getMiddleName--) | DAD, Nama tengah pemegang kartu. |
| [getMiddleNameTruncation()](#getMiddleNameTruncation--) | DDG, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A |
| [getRestrictionCodes()](#getRestrictionCodes--) | DCB, Kode pembatasan khusus yurisdiksi, DL, V12ANS |
| [getSex()](#getSex--) | DBC, Jenis kelamin pemegang kartu. |
| [getVehicleClass()](#getVehicleClass--) | DCA, Kode kelas / grup kendaraan khusus yurisdiksi, DL, V6ANS |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressCity(String value)](#setAddressCity-java.lang.String-) | DAI, Bagian kota dari alamat pemegang kartu, DL/ID, V20ANS |
| [setAddressPostalCode(String value)](#setAddressPostalCode-java.lang.String-) | DAK, Bagian kode pos dari alamat pemegang kartu di AS dan Kanada. |
| [setAddressState(String value)](#setAddressState-java.lang.String-) | DAJ, Bagian negara bagian dari alamat pemegang kartu, DL/ID, F2A |
| [setAddressStreet1(String value)](#setAddressStreet1-java.lang.String-) | DAG, Bagian jalan dari alamat pemegang kartu, DL/ID, V35ANS |
| [setCountryIdentification(USADriveIdCountry value)](#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-) | DCG, Negara tempat DL/ID diterbitkan. |
| [setCustomerIDNumber(String value)](#setCustomerIDNumber-java.lang.String-) | DAQ, Nomor yang diberikan atau dihitung oleh otoritas penerbit, DL/ID, V25ANS |
| [setDateOfBirth(LocalDate value)](#setDateOfBirth-java.time.LocalDate-) | DBB, Tanggal dokumen diterbitkan, MMDDCCYY untuk AS, CCYYMMDD untuk Kanada, DL/ID, F8N |
| [setDocumentDiscriminator(String value)](#setDocumentDiscriminator-java.lang.String-) | DCF, Nomor harus secara unik mengidentifikasi dokumen tertentu yang diterbitkan kepada pelanggan tersebut dari dokumen lain yang mungkin telah diterbitkan sebelumnya. |
| [setEndorsementCodes(String value)](#setEndorsementCodes-java.lang.String-) | DCD, Kode endorsement khusus yurisdiksi, DL, V5ANS |
| [setEyeColor(USADriveIdEyeColor value)](#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-) | DAY, Warna mata pemegang kartu. |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | DCS, Nama keluarga pemegang kartu, DL/ID, V40ANS |
| [setFamilyNameTruncation(String value)](#setFamilyNameTruncation-java.lang.String-) | DDE, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A |
| [setFirstName(String value)](#setFirstName-java.lang.String-) | DAC, Nama depan pemegang kartu, DL/ID, V40ANS |
| [setFirstNameTruncation(String value)](#setFirstNameTruncation-java.lang.String-) | DDF, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A |
| [setHeight(String value)](#setHeight-java.lang.String-) | DAU, Tinggi pemegang kartu. |
| [setMiddleName(String value)](#setMiddleName-java.lang.String-) | DAD, Nama tengah pemegang kartu. |
| [setMiddleNameTruncation(String value)](#setMiddleNameTruncation-java.lang.String-) | DDG, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A |
| [setRestrictionCodes(String value)](#setRestrictionCodes-java.lang.String-) | DCB, Kode pembatasan khusus yurisdiksi, DL, V12ANS |
| [setSex(USADriveIdSex value)](#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-) | DBC, Jenis kelamin pemegang kartu. |
| [setVehicleClass(String value)](#setVehicleClass-java.lang.String-) | DCA, Kode kelas / grup kendaraan khusus yurisdiksi, DL, V6ANS |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MandatoryFields() {#MandatoryFields--}
```
public MandatoryFields()
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
### getAddressCity() {#getAddressCity--}
```
public final String getAddressCity()
```


DAI, Bagian kota dari alamat pemegang kartu, DL/ID, V20ANS

**Returns:**
java.lang.String
### getAddressPostalCode() {#getAddressPostalCode--}
```
public final String getAddressPostalCode()
```


DAK, Bagian kode pos dari alamat pemegang kartu di AS dan Kanada. Jika bagian akhir kode pos di AS tidak diketahui, nol akan digunakan untuk mengisi bagian akhir angka hingga 9 digit, DL/ID, F11ANS

**Returns:**
java.lang.String
### getAddressState() {#getAddressState--}
```
public final String getAddressState()
```


DAJ, Bagian negara bagian dari alamat pemegang kartu, DL/ID, F2A

**Returns:**
java.lang.String
### getAddressStreet1() {#getAddressStreet1--}
```
public final String getAddressStreet1()
```


DAG, Bagian jalan dari alamat pemegang kartu, DL/ID, V35ANS

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryIdentification() {#getCountryIdentification--}
```
public final USADriveIdCountry getCountryIdentification()
```


DCG, Negara tempat DL/ID diterbitkan. U.S. = USA, Canada = CAN, DL/ID, F3A

**Returns:**
[USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry)
### getCustomerIDNumber() {#getCustomerIDNumber--}
```
public final String getCustomerIDNumber()
```


DAQ, Nomor yang diberikan atau dihitung oleh otoritas penerbit, DL/ID, V25ANS

**Returns:**
java.lang.String
### getDateOfBirth() {#getDateOfBirth--}
```
public final LocalDate getDateOfBirth()
```


DBB, Tanggal dokumen diterbitkan, MMDDCCYY untuk AS, CCYYMMDD untuk Kanada, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getDocumentDiscriminator() {#getDocumentDiscriminator--}
```
public final String getDocumentDiscriminator()
```


DCF, Nomor harus secara unik mengidentifikasi dokumen tertentu yang diterbitkan untuk pelanggan tersebut dari dokumen lain yang mungkin telah diterbitkan di masa lalu. Nomor ini dapat berfungsi untuk berbagai tujuan diskriminasi dokumen, nomor informasi audit, dan/atau kontrol inventaris, DL/ID, V25ANS

**Returns:**
java.lang.String
### getEndorsementCodes() {#getEndorsementCodes--}
```
public final String getEndorsementCodes()
```


DCD, Kode endorsement khusus yurisdiksi, DL, V5ANS

**Returns:**
java.lang.String
### getEyeColor() {#getEyeColor--}
```
public final USADriveIdEyeColor getEyeColor()
```


DAY, Warna mata pemegang kartu. (kode ANSI D-20). DL/ID, F3A

**Returns:**
[USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor)
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


DCS, Nama keluarga pemegang kartu, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFamilyNameTruncation() {#getFamilyNameTruncation--}
```
public final String getFamilyNameTruncation()
```


DDE, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A

**Returns:**
java.lang.String
### getFirstName() {#getFirstName--}
```
public final String getFirstName()
```


DAC, Nama depan pemegang kartu, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFirstNameTruncation() {#getFirstNameTruncation--}
```
public final String getFirstNameTruncation()
```


DDF, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A

**Returns:**
java.lang.String
### getHeight() {#getHeight--}
```
public final String getHeight()
```


DAU, Tinggi pemegang kartu. Inches (in): jumlah inci diikuti dengan " in" contoh 6'1'' = "073 in" Centimeters(cm) : jumlah sentimeter diikuti dengan " cm" contoh 181 sentimeter="181 cm" , DL/ID, F6ANS

**Returns:**
java.lang.String
### getMiddleName() {#getMiddleName--}
```
public final String getMiddleName()
```


DAD, Nama tengah pemegang kartu. Jika ada beberapa nama tengah, mereka harus dipisahkan dengan koma ",". , DL/ID, V40ANS

**Returns:**
java.lang.String
### getMiddleNameTruncation() {#getMiddleNameTruncation--}
```
public final String getMiddleNameTruncation()
```


DDG, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A

**Returns:**
java.lang.String
### getRestrictionCodes() {#getRestrictionCodes--}
```
public final String getRestrictionCodes()
```


DCB, Kode pembatasan khusus yurisdiksi, DL, V12ANS

**Returns:**
java.lang.String
### getSex() {#getSex--}
```
public final USADriveIdSex getSex()
```


DBC, Jenis kelamin pemegang kartu. 1 = laki-laki, 2 = perempuan, 9 = tidak ditentukan, DL/ID, F1N

**Returns:**
[USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex)
### getVehicleClass() {#getVehicleClass--}
```
public final String getVehicleClass()
```


DCA, Kode kelas / grup kendaraan khusus yurisdiksi, DL, V6ANS

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




### setAddressCity(String value) {#setAddressCity-java.lang.String-}
```
public final void setAddressCity(String value)
```


DAI, Bagian kota dari alamat pemegang kartu, DL/ID, V20ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setAddressPostalCode(String value) {#setAddressPostalCode-java.lang.String-}
```
public final void setAddressPostalCode(String value)
```


DAK, Bagian kode pos dari alamat pemegang kartu di AS dan Kanada. Jika bagian akhir kode pos di AS tidak diketahui, nol akan digunakan untuk mengisi bagian akhir angka hingga 9 digit, DL/ID, F11ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setAddressState(String value) {#setAddressState-java.lang.String-}
```
public final void setAddressState(String value)
```


DAJ, Bagian negara bagian dari alamat pemegang kartu, DL/ID, F2A

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setAddressStreet1(String value) {#setAddressStreet1-java.lang.String-}
```
public final void setAddressStreet1(String value)
```


DAG, Bagian jalan dari alamat pemegang kartu, DL/ID, V35ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setCountryIdentification(USADriveIdCountry value) {#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-}
```
public final void setCountryIdentification(USADriveIdCountry value)
```


DCG, Negara tempat DL/ID diterbitkan. U.S. = USA, Canada = CAN, DL/ID, F3A

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry) |  |

### setCustomerIDNumber(String value) {#setCustomerIDNumber-java.lang.String-}
```
public final void setCustomerIDNumber(String value)
```


DAQ, Nomor yang diberikan atau dihitung oleh otoritas penerbit, DL/ID, V25ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setDateOfBirth(LocalDate value) {#setDateOfBirth-java.time.LocalDate-}
```
public final void setDateOfBirth(LocalDate value)
```


DBB, Tanggal dokumen diterbitkan, MMDDCCYY untuk AS, CCYYMMDD untuk Kanada, DL/ID, F8N

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.time.LocalDate |  |

### setDocumentDiscriminator(String value) {#setDocumentDiscriminator-java.lang.String-}
```
public final void setDocumentDiscriminator(String value)
```


DCF, Nomor harus secara unik mengidentifikasi dokumen tertentu yang diterbitkan untuk pelanggan tersebut dari dokumen lain yang mungkin telah diterbitkan di masa lalu. Nomor ini dapat berfungsi untuk berbagai tujuan diskriminasi dokumen, nomor informasi audit, dan/atau kontrol inventaris, DL/ID, V25ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setEndorsementCodes(String value) {#setEndorsementCodes-java.lang.String-}
```
public final void setEndorsementCodes(String value)
```


DCD, Kode endorsement khusus yurisdiksi, DL, V5ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setEyeColor(USADriveIdEyeColor value) {#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-}
```
public final void setEyeColor(USADriveIdEyeColor value)
```


DAY, Warna mata pemegang kartu. (kode ANSI D-20). DL/ID, F3A

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor) |  |

### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public final void setFamilyName(String value)
```


DCS, Nama keluarga pemegang kartu, DL/ID, V40ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setFamilyNameTruncation(String value) {#setFamilyNameTruncation-java.lang.String-}
```
public final void setFamilyNameTruncation(String value)
```


DDE, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setFirstName(String value) {#setFirstName-java.lang.String-}
```
public final void setFirstName(String value)
```


DAC, Nama depan pemegang kartu, DL/ID, V40ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setFirstNameTruncation(String value) {#setFirstNameTruncation-java.lang.String-}
```
public final void setFirstNameTruncation(String value)
```


DDF, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setHeight(String value) {#setHeight-java.lang.String-}
```
public final void setHeight(String value)
```


DAU, Tinggi pemegang kartu. Inches (in): jumlah inci diikuti dengan " in" contoh 6'1'' = "073 in" Centimeters(cm) : jumlah sentimeter diikuti dengan " cm" contoh 181 sentimeter="181 cm" , DL/ID, F6ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setMiddleName(String value) {#setMiddleName-java.lang.String-}
```
public final void setMiddleName(String value)
```


DAD, Nama tengah pemegang kartu. Jika ada beberapa nama tengah, mereka harus dipisahkan dengan koma ",". , DL/ID, V40ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setMiddleNameTruncation(String value) {#setMiddleNameTruncation-java.lang.String-}
```
public final void setMiddleNameTruncation(String value)
```


DDG, Kode yang menunjukkan apakah sebuah bidang telah dipotong (T), tidak dipotong (N), atau tidak diketahui apakah dipotong (U), DL/ID, F1A

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setRestrictionCodes(String value) {#setRestrictionCodes-java.lang.String-}
```
public final void setRestrictionCodes(String value)
```


DCB, Kode pembatasan khusus yurisdiksi, DL, V12ANS

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setSex(USADriveIdSex value) {#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-}
```
public final void setSex(USADriveIdSex value)
```


DBC, Jenis kelamin pemegang kartu. 1 = laki-laki, 2 = perempuan, 9 = tidak ditentukan, DL/ID, F1N

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex) |  |

### setVehicleClass(String value) {#setVehicleClass-java.lang.String-}
```
public final void setVehicleClass(String value)
```


DCA, Kode kelas / grup kendaraan khusus yurisdiksi, DL, V6ANS

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

